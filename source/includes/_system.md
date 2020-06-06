## System
This endpoint returns useful information pertaining to the system itself.
 
```shell
http GET <%= config[:endpoint] %>/system
```

```javascript
TODO
```

### HTTP Request

`GET <%= config[:endpoint] %>/system`

> The above command returns JSON structured like this:

```json
{
    "chalky_version": "1.1.10",
    "java_version": "11.0.6",
    "process_start_time": "2020-05-31T12:01:09.146Z"
}
```
