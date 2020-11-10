## Confirm Email
This is a simple endpoint that allows a user's email address to be confirmed.
 
### HTTP Request

`POST example.com/confirm_email`

### Parameters

Parameter | Description
--------- | -----------
email | The email address that is to be confirmed  
 
```shell
http POST example.com/confirm_email email=joe@soap.com
```

```javascript
TODO
```

> The above command returns JSON structured like this:

```json
{
  "success": true,
  "message": "The email address has been confirmed"
}
```
