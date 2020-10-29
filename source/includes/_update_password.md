## Update Password
Here a user can reset their own password assuming they are already authenticated.
 
### HTTP Request

`PUT example.com/api/users/:id/password`

### Parameters

Parameter | Description
--------- | -----------
current_password | The user's current password  
new_password | The new password requested by the user 

The frontend UI should have two fields to confirm that new password matches in both.

```shell
http PUT example.com/api/users/:id/password current_password=OldSecret new_password=NewSecret
```

```javascript
TODO
```

> The above command returns JSON structured like this:

```json
{
  "success": true,
  "message": "Successful"
}
```
