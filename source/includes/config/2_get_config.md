## Get Configuration Entries
This endpoint can be used to retrieve configuration details.

```shell
http GET example.com/api/configs?name=email_settings
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/configs?name=email_settings`

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": [
        {
            "id": 105625159897122,
            "name": "email_settings",
            "key": "subject",
            "value": "Password Reset"
        },
        {
            "id": 105625159897122,
            "name": "email_settings",
            "key": "from",
            "value": "chalky@mail.org"
        }
    ]
}
```
