## Update Charity Details
This endpoint can be used to update the details of a charity.

### TODO
- Normalise charity contacts
- Add extra fields for social media (which ones? facebook, instagram, twitter? other?) 
 
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
category_id | The category_id of the charity
street | The street number and name
suburb | The name of the suburb
city | The name of the city
province_id | The id from the list of suburbs 
contact | The primary contact (should normalise contacts here too)
email | The general email
mobile | The mobile number of contact (should normalise contacts here too)
telephone | The main telephone number
website | The website of the charity 
registration_number | the NGO or similar (need verification)
gps_latitude | Used for exact location
gps_longitude | Used for exact location (do we combine to one field?)
