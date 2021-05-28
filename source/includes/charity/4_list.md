## Get All Charities
This endpoint returns a list of all charities.
 
```shell
http GET example.com/api/charities
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/charities?province_id=3&tag=Animals&offset=0&limit=10`

### Request Parameters

Parameter | Description
--------- | -----------
id_province | The province to filter by
tag | The tag/category to filter by
offset | The starting record (for pagination)
limit | The number of records to return

> The above command returns JSON structured like this:

```json
[
  {
    "id": 163699236958234,
    "name": "Ann Harding Cheshire Home",
    "suburb": "Northwold",
    "city": "Randburg",
    "tags": [
      "Disability"
    ],
    "images": [],
  },
  {
    "id": 163699236950038,
    "name": "Ark Animal Centre ? Puppy Shelter",
    "suburb": "Chartwell",
    "city": "Johannesburg",
    "tags": [
      "Animals"
    ],
    "images": [],
  }
]
```


