## Get All Schools
This endpoint returns a list of all schools.

```shell
http GET example.com/api/schools
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/schools`

> The above command returns JSON structured like this:

```json
{
  "success": true,
  "message": "Ok",
  "data": [
    {
      "id": 164064441593927,
      "name": "Random School Name",
      "images": [
        {
          "image_id": 164064444493896,
          "image_type": "thumbnail",
          "image_size": 60
        }
      ]
    },
    {
      "id": 164064421441553,
      "name": "St Stithians Boys' College",
      "images": []
    }
  ]
}
```


