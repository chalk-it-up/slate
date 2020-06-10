## Update Volunteer Details
This endpoint is used to update the details of a volunteer.

### TODO
- Do we flatten details between user and volunteer
 
```shell
http PUT chalky.com/api/volunteers/:id
```

```javascript
TODO
```

### HTTP Request

`PUT chalky.com/api/volunteers/2327833979673121796`

### Parameters

Parameter | Description
--------- | -----------
volunteer_id | The id of the volunteer to change   
mobile | The mobile number 
gender | M or F (no binary here)
date_of_birth | YYYYMMDD
school_id | The id of the school from the provided list of schools 
