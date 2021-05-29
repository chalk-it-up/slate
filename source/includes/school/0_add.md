# Schools

## Add New School
This endpoint can be used to add a new school.


```shell
http POST example.com/api/schools
```

```javascript
TODO
```

### HTTP Request

`POST example.com/api/schools`

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
gps_coords | Used for exact location

> The above command returns JSON structured like below where id is the identity of the event added.

```json
{
    "success": true,
    "message": "Ok",
    "data": {
        "id": 164064441593927,
        "name": "Random School Name",
        "description": "Blurb about the school Changed",
        "street": "Some Road",
        "suburb": "Douglasdale",
        "city": "Bryanston",
        "province_id": 3,
        "email": "new_email@school.org",
        "telephone": "0113334405",
        "website": "http://www.school.org",
        "gps_coords": "-26.871 27.006",
        "enabled": true,
        "time_created": "2021-05-29T10:40:15.512424Z",
        "images": [
            {
                "image_id": 164064444493896,
                "image_type": "thumbnail",
                "image_size": 60
            }
        ]
    }
}```
