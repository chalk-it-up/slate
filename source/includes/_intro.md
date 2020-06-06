# Chalky API

## Introduction
All shell commands use `HTTPie` instead of curl but you could use curl if you choose. Syntax will vary slightly.

## Authentication
Upon successful logon an authentication token will be returned.

Chalky API expects this authentication token to be present in the header of each request: 

`Authorization:Bearer $AUTH_TOKEN`

<aside class="notice">
You must replace <code>$AUTH_TOKEN</code> with the token returned in the logon response message.
</aside>

The exceptions to this are the Health, Logon and Register endpoints which require no header.
 
## Health
This endpoint returns the health of the system. Two methods are supported HEAD (preferred) and GET.

No authorization is required for this endpoint.

```shell
http HEAD <%= config[:endpoint] %>/health "Authorization:Bearer $AUTH_TOKEN"
```

### HTTP Request

`HEAD <%= config[:endpoint] %>/health`

Returns HTTP status code 200 and no content

`GET <%= config[:endpoint] %>/health`

Returns HTTP status code 200 and content `OK`

# System
This endpoint returns useful information pertaining to the system itself.
 
```shell
http GET <%= config[:endpoint] %>/system
```

```javascript
TODO
```

### HTTP Request

`GET <%= config[:endpoint] %>/system`

> The above command returns JSON structured like this:

```json
{
    "chalky_version": "1.1.10",
    "java_version": "11.0.6",
    "process_start_time": "2020-05-31T12:01:09.146Z"
}
```

## Invalid Requests
If a request fails then the most common response would be something like the following:

HTTP status code 400 - Bad Request

```json
{
    "error_message": "Last name was not specified"
}
```
