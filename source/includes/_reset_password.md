## Reset Password
The second stage is invoked when the password reset link is clicked and the new details have been submitted.
 
### HTTP Request

`POST example.com/reset_password`

### Parameters

Parameter | Description
--------- | -----------
token | The token provided by the password reset request  
new_password | The new password requested by the user 
 
```shell
http POST example.com/reset_password token=joe@soap.com new_password=Secret44
```

```javascript
TODO
```

> The above command returns JSON structured like this:

```json
{
  "success": true,
  "messaage": "The password has been reset"
}
```
