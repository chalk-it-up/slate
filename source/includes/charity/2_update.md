## Update Charity Details
This endpoint can be used to update the details of a charity.

```shell
http PUT example.com/api/charities/:id
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/charities/2327833979673121796`

### Parameters

Parameter | Description
--------- | -----------
id  | The id of the charity to change
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
