# Configuration
Configuration entries are stored in the database as strings using a key/value pair with an 
additional name used to group entries together.
  
## Add Configuration Entry
This endpoint can be used to add or update a configuration entry.

```shell
http PATCH example.com/api/configs
```

```javascript
TODO
```

### HTTP Request

`POST example.com/api/configs`

### Parameters

Parameter | Description
--------- | -----------
name | The name used for grouping configuration entries
key | The configuration entry key
value | The configuration entry value

{
    "name": "email_settings",
    "key": "subject",
    "value": "Password Reset"
}

> The above command returns JSON structured like below where id is the identity of the configuration group.

```json
{
    "success": true,
    "message": "Ok",
    "data": {
        "id": 105625159897122,
        "name": "email_settings",
        "key": "subject",
        "value": "Password Reset"
    }
}
```
