## Get One Charity
This endpoint returns the details for a single charity.
 
```shell
http GET chalky.com/api/charities/:id
```

```javascript
TODO
```

### HTTP Request

`GET chalky.com/api/charities/2327833979673121796`

> The above command returns JSON structured like this:

```json
{
    "category": "Animals",
    "category_id": 1,
    "charity_id": 2327833979673121796,
    "city": "Johannesburg",
    "contact": null,
    "email": "info@arkanimalcentre.co.za",
    "gps_latitude": "S25° 59’03.3",
    "gps_longitude": "E027°56’45.5",
    "mobile": null,
    "name": "Ark Animal Centre – Puppy Shelter",
    "province": "Gauteng",
    "province_id": 3,
    "registration_number": "930053318",
    "street": "17 Howard Avenue",
    "suburb": "Chartwell",
    "telephone": "087 742 2211",
    "website": "http://www.arkanimalcentre.co.za/"
}
```
