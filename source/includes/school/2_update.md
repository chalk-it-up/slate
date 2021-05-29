## Update School Details
This endpoint can be used to update the details of a school.

```shell
http PUT example.com/api/schools/:id
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/charities/2327833979673121796`

### Parameters

Parameter | Description
--------- | -----------
id  | The id of the school to change
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
