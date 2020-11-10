## Get an Image
This endpoint can be used to get an image using the unique image id.

```shell
http GET example.com/api/images/:id
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/images/87946494654`

### Parameters
The path parameter (:id) is the image id

> The above command returns JSON structured like below where id is the identity of the image.

```json
{
    "success": true,
    "data": {
        "id": 88646878580765,
        "entity_id": 62816468781029,
        "image_type": "thumbnail",
        "image_size": 78261,
        "image_data": "__base64 encoded data__"
    }
}
```



