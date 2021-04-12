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
        // this name must be to equal the value of desclared in initial state (object)
            name="example"
        //Receive the form value desclared in initial state for wait changes
            value={example}
            onChange={handleInputChange}
        />
    </form>

```
