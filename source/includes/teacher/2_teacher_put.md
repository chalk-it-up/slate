## Update Teacher Details
This endpoint can be used to update all details of a teacher.

On successful completion teacher details will be included in the JSON response.

```shell
http PUT example.com/api/teachers/{id}
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/teachers/2327833979673121796`

### Parameters

Parameter | Description
--------- | -----------
email | "teacher@school.org"
first_name | "Joe"
last_name | "Soap"
mobile | "0802223333"
date_of_birth | "2010-01-01"
gender | "M"
id_type | "P"
id_number | "456789"
school_id | 444444
