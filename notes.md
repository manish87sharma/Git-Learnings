## Git basics
- Distributed Version Control system.
- Git is like a key value store.
- Value =data and key = hash of the data.
- Hashing algorithm is SHA1.
- Key is 40 digit hexadecimal number.
- This system is called a content addressable storage system.
- Git store data in blob along with meta data.
- It uses null string delimiter \0.
### Both command generate same hash output
```console
echo 'Hello' | git hash-object --stdin
echo 'blob 5\0Hello' | openssl sha1
```



