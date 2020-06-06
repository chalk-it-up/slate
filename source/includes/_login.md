## Login
This endpoint is used to login to the Chalky API system
 
```shell
http POST chalky.com/login email=joe@soap.com password=secret
```

```javascript
TODO
```

### HTTP Request

`POST chalky.com/login`

### Parameters

Parameter | Description
--------- | -----------
email | The email address of the user 
password | The password for the user
 
> The above command returns JSON structured like this:

```json
{
  "user_id": 272466682903204,
  "first_name": "Joe",
  "last_name": "Soap",
  "user_type": "V",
  "permissions": [
    "charity-view",
    "event-view"
  ]
}
```
