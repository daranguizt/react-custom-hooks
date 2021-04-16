#useForm

Example:

```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    };

    const [formValues, handleInputChange, reset] = useForm(initialForm);
```

It uses the structure sent, and manages the state within the hook. 