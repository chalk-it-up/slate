## Patch Charity Details
This endpoint can be used to update specific attributes of a charity.
 
```shell
http PATCH example.com/api/charities/{id}
```

```javascript
TODO
```

### HTTP Request

`PATCH example.com/api/charities/2327833979673121796`

### Parameters
Parameters can be any of the following:

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
tags | A list of tag names use to categorise charities (fixed list)
