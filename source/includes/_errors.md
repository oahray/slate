# Errors

<aside class="notice">This is a list of the status codes you might see when you encounter an error</aside>

The Postit API uses the following error codes:

Error Code | Meaning
---------- | -------
400 | Bad Request -- You did not quite structure your request as you should have.
401 | Unauthorized -- Your `x-auth` access token is invalid.
403 | Forbidden -- You cannot access this routes, because you have insufficient permissions although authenticated.
404 | Not Found -- The specified group or user, or even route, could not be found.
500 | Internal Server Error -- We had a problem with our server. Try again later.
