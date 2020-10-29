## Update an Image
This endpoint can be used to add an image for an entity.
 
```shell
http PUT example.com/api/images/:id
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/images/87946494654`

### Parameters
The path parameter (:id) is the image id

Parameter | Description
--------- | -----------
image_data | "_base64_encoded_content_"

Entity id be any user or organisation such as student, parent, school, charity.
Image type is flexible but can be used to add multiple images per entity.
