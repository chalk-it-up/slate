## Login
This endpoint is used to login to the Chalky API system
 
```shell
http POST example.com/login email=joe@soap.com password=secret
```

```javascript
TODO
```

### HTTP Request

`POST example.com/login`

### Parameters

Parameter | Description
--------- | -----------
email | The email address of the user 
password | The password for the user
 
> The above command returns JSON structured like this:

```json
{
  "success": true,
  "data": {
      "user_id": 272466682903204,
      "token": "eyJ0eXAi.....7sjnwj",
      "user_type": "S",
      "permissions": [
        "charity-view",
        "event-view"
      ]
  }
}
```
