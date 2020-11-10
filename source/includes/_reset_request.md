## Reset Password Link Request
The reset password functionality comprises two stages. The first stage is the requesting of the password reset link.
 The link is emailed to the user if the provided email address is valid.
 
A status of success true will be returned irrespective of whether the email is valid or not. 

```shell
http GET example.com/reset_password_request email=joe@soap.com
```

```javascript
TODO
```

### HTTP Request

`POST example.com/reset_password_request`

### Parameters

Parameter | Description
--------- | -----------
email | The email address of the user 
 
> The above command returns JSON structured like this:

```json
{
  "success": true
}
```
