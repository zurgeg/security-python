# Security-python
A basic security module

## Using it
To generate a user:
```security.genuser("Hello", "password")```
Doing this will return a dictionary with the following:
```{"User": "passwordhash"}```

To attempt to logon
```security.checkpswd("hash", "password")```

