## Get an Image
This endpoint can be used to get an image.

**Note**
There could be two variants to this. The first is to simply retrieve the image data using the image id.

The second could be to use the entity_id, and the image_type. 

```shell
http GET example.com/api/images/:id
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/images/87946494654`

### Parameters
The path parameter (:id) is the image id

Returns the image data as  binary stream . In this case not JSON.
