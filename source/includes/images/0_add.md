# Images

## Add an Image
This endpoint can be used to add an image for an entity.
 
```shell
http POST example.com/api/images
```

```javascript
TODO
```

### HTTP Request

`POST example.com/api/images`

### Parameters

Parameter | Description
--------- | -----------
entity_id | 88646876442651
image_type | "thumbnail_400x400"
image_data | "_base64_encoded_content_"

> Entity id be any user or organisation such as student, parent, school, charity.

> Image type is flexible but can be used to add multiple images per entity.

> The above command returns JSON structured like below where id is the identity of the image added.

```json
{
    "success": true,
    "data": {
        "id": 88646878580765
    }
}
```
