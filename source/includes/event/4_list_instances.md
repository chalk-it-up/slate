## List Event Entries
This endpoint allows for event entries to be listed.
 
```shell
http GET example.com/api/events/816546547/instances
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/events/{id}/instances

### Parameters

Parameter | Description
--------- | -----------
date_from | Used to restrict events to a date range (E.g. "2021-12-01")
date_to | Used to restrict events to a date range (E.g. "2021-12-31")
page | The required page number (starting at zero)
page_size | The number of rows to return per page

### Response Parameters

Parameter | Description
--------- | -----------
page | The required page number (starting at zero)
page_size | The number of rows to return per page
pages | The total number of pages
previous_page | The number of the previous page or null if page is the first page
next_page | The number of the next page or null if page is the last page
total_rows | The number of event entries on all pages

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": {
      "page": 0,
      "page_size": 5,
      "pages": 83,
      "next_page": 1,
      "total_rows": 415,
      "event_entries": [
        {
          "event_date": "2020-06-01",
          "slots_booked": 0,
          "slots_available": 100
        },
        {
          "event_date": "2020-06-02",
          "slots_booked": 0,
          "slots_available": 100
        }
      ]
    }
}
```
