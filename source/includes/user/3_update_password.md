## Update Password
When a user wishes to change their password.

Can only be called for the authenticated user.
 
### HTTP Request

`POST example.com/api/users/:id/password`

### Parameters

Parameter | Description
--------- | -----------
current_password | The current password used by the user  
new_password | The new password to set for the user 
 
```shell
http POST example.com/api/users/123456 current_password=test1234 new_password=test2345
```

```javascript
TODO
```

> The above command returns JSON structured like this:

```json
{
  "success": true,
  "message": "The password has been updated"
}
```
