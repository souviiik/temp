# temp

```
users/index.php
objects/user.php
```

forget password
```http://localhost/api/users/forgetpassword/pal.goutam@gmail.com```   GET
```http://localhost/api/users/forgetpassword/{username}```

reset password
```http://localhost/api/users/resetpassword```      PUT

payload
---------------------------
```javascript
{
    "username":"pal.goutam@gmail.com",
    "password":"admin"                
}
```
