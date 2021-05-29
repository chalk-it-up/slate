## Patch School Details
This endpoint can be used to update specific attributes of a school.
 
```shell
http PATCH example.com/api/schools/{id}
```

```javascript
TODO
```

### HTTP Request

`PATCH example.com/api/schools/164064441593927`

### Parameters
Parameters can be any of the following:

Parameter | Description
--------- | -----------
name | The name of the school
description | A longer description of the school
about_us | An extra field to explain the purpose of the school
street | The street number and name
suburb | The name of the suburb
city | The name of the city
province_id | The id from the list of provinces
email | The general email
telephone | The main telephone number
website | The website of the school
gps_coords | Used for exact location
