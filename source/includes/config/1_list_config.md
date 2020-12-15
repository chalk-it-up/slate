## List Configuration Entries
This endpoint can be used to list configuration entries.

```shell
http GET example.com/api/configs
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/configs

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
