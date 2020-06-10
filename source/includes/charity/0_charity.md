# Charity

## Get All Charities
This endpoint returns a list of all charities.
 
```shell
http GET example.com/api/charities
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/charities`

> The above command returns JSON structured like this:

```json
[
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
    },
    {
        "category": "Children and Youth",
        "category_id": 2,
        "charity_id": 2327833979631178753,
        "city": "Sandton",
        "contact": null,
        "email": "info@heartsofhope.org.za",
        "gps_latitude": null,
        "gps_longitude": null,
        "mobile": "082 458 2677",
        "name": "Hearts of Hope",
        "province": "Gauteng",
        "province_id": 3,
        "registration_number": null,
        "street": null,
        "suburb": null,
        "telephone": null,
        "website": "https://heartsofhope.org.za/"
    }
]
```


