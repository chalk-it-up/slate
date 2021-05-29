## Update Student Details
This endpoint can be used to update all details of a student.

On successful completion student details will be included in the JSON response.

```shell
http PUT example.com/api/students/{id}
```

```javascript
TODO
```

### HTTP Request

`PUT example.com/api/students/2327833979673121796`

### Parameters

Parameter | Description
--------- | -----------
email | "student2@mail.org"
first_name | "Joe"
last_name | "Soap"
mobile | "0802223333"
date_of_birth | "2010-01-01"
gender | "M"
grade | "6"
id_type | "P"
id_number | "456789"
school_id | 444444
