## Get One Charity
This endpoint returns the details for a single charity.
 
```shell
http GET example.com/api/charities/:id
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/charities/2327833979673121796`

> The above command returns JSON structured like this:

```json
{
  "success": true,
  "message": "Ok",
  "data": {
    "id": 163697218900039,
    "name": "Test Charity",
    "description": "Charity Description",
    "about_us": "Something about us",
    "street": "1 The Lane",
    "suburb": "Suburbia",
    "city": "Johannesburg",
    "province_id": 3,
    "email": "charity@mail.org",
    "telephone": "0112223333",
    "website": "www.oursite.com",
    "registration_number": "12345",
    "gps_coords": "-26.012, 27.994",
    "enabled": true,
    "time_created": "2021-05-28T09:46:01.531721Z",
    "tags": [
      "Animals",
      "Community"
    ],
    "images": []
  }
}
```
