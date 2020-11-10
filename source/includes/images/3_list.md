## List Images for an Entity
This endpoint can be used to list the image details for the given entity.

```shell
http GET example.com/api/images?entity_id=23863428
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/images?entity_id=23863428

> The above command returns JSON structured like below.

```json
{
    "success": true,
    "data": [
      {
          "id": 88646878580765,
          "entity_id": 62816468781029,
          "image_type": "thumbnail",
          "image_size": 2761
      },
      {
          "id": 88646878580789,
          "entity_id": 62816468781029,
          "image_type": "mugshot",
          "image_size": 78820
      }
    ]
}
```



