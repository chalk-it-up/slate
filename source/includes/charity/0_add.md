# Charity

## Add New Charity
This endpoint can be used to add a new charity organisation.


```shell
http POST example.com/api/charities
```

```javascript
TODO
```

### HTTP Request

`POST example.com/api/charities`

### Parameters

Parameter | Description
--------- | -----------
name | The name of the charity
description | A longer description of the charity
about_us | An extra field to explain the purpose of the charity
street | The street number and name
suburb | The name of the suburb
city | The name of the city
province_id | The id from the list of provinces
email | The general email
telephone | The main telephone number
website | The website of the charity
registration_number | the NGO or similar (needs verification)
gps_coords | Used for exact location
tags | A list of tag names used to categorise charities (fixed list)

> The above command returns JSON structured like below where id is the identity of the event added.

```json
{
    "success": true,
    "message": "Ok",
    "data": {
        "id": 163680840699975
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
        "tags": [
            "Animals",
            "Community"
        ],
    }
}```
