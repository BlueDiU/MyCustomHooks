# How to use this Hook

```

    const [values, handleInputChange, reset] = useForm({
        example: '',
    });

    const handleSearch = (e) => {
        e.preventDefault();
        // Receive any children values to submit form
        console.log(values.search);
    };

    <form onSubmit={handleSubmit}>
        <input
        // this name must be to equal the value of sentences initial state (object)
            name="example"
            //Receive form the value sentence in initial state from weight changes
            value={example}
            onChange={handleInputChange}
        />
    </form>

```
