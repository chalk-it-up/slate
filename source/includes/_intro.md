# Chalky API Introduction

## Introduction
All shell commands use `HTTPie` instead of curl but you could use curl if you choose. Syntax will vary slightly.

## Authentication
Upon successful login an authentication token will be returned.

Chalky API expects this authentication token to be present in the header of each request: 

`Authorization: Bearer $AUTH_TOKEN`

<aside class="notice">
You must replace <code>$AUTH_TOKEN</code> with the token returned in the logon response message.
</aside>

The exceptions to this are the Health, Logon and Register endpoints which require no authentication header.

## Invalid Requests
If a request fails then the most common response would be something like the following:

HTTP status code 400 - Bad Request

```json
{
  "success": false,
  "message": "Last name was not specified"
}
```

A full list of the status codes used can be found under `Status Codes`
