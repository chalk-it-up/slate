## Searching for Events
This endpoint is used to search for events across all charities and schools.

```shell
http GET example.com/api/events
```

```javascript
TODO
```

### HTTP Request

`GET example.com/api/events`

### Parameters

Parameter | Description
--------- | -----------
org_id | Filters events to a single organisation (used when listing for charities or schools) 
province_id | Filters events to a single province (should always be used)
tag | Only return events matching the given tag
day | Filter events to a specified day of the week (E.g. "fri")
month | Only return events available in a given month (Numeric values from 1 - 12)
year | Will default to current year if not specified (E.g. 2021)
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
total_rows | The number of events on all pages 

> The above command returns JSON structured like this:

```json
{
    "success": true,
    "message": "Ok",
    "data": {
      "page": 0,
      "page_size": 4,
      "pages": 2,
      "next_page": 1,
      "total_rows": 7,
      "events": [
        {
          "event_id": 174015022755890,
          "name": "Animal Care",
          "description": "Come and spend an afternoon with our animals, feed the puppies and help to clean their living quarters",
          "org_id": 174015022247960,
          "org_name": "Ark Animal Centre ? Puppy Shelter",
          "org_type": "C",
          "recurrence": "Weekly",
          "start_date": "2021-06-01",
          "end_date": "2022-12-31",
          "days_of_week": [
            "Wednesday",
            "Thursday",
            "Friday"
          ],
          "start_time": "14:00:00",
          "end_time": "16:00:00",
          "booking_closes": 60,
          "capacity": 50,
          "event_date": "2021-07-15",
          "slots_booked": 0,
          "slots_available": 50,
          "street": "17 Howard Avenue",
          "suburb": "Chartwell",
          "city": "Johannesburg",
          "province": "Gauteng",
          "email": "info@arkanimalcentre.co.za",
          "telephone": "087 742 2211",
          "website": "http://www.arkanimalcentre.co.za/",
          "registration_number": "930053318",
          "gps_coords": "2W8W+5J",
          "tags": [
            "Animals"
          ],
          "images": [
            {
              "image_id": 174015022772276,
              "image_type": "thumbnail",
              "image_size": 60
            }
          ]
        }
      ]
    }
}
```


