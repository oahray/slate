---
title: Postit API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - javascript

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/tripit/slate'>Documentation Powered by Slate</a>

includes:
  - users
  - groups
  - errors

search: true
---

# Introduction

Welcome to the Postit API! You can use our API to access Postit API endpoints, with which you can create and access user and group data in our database.

The API is implemented in Javascript(Nodejs). You can view code examples in the dark area to the right.

This API documentation page was created with [Slate](https://github.com/tripit/slate).

# Authentication

Some endpoints (routes) in this API are protected. They require a token which you can get when you signup as a new user or login as existing user.

> To authorize requests to protected endpoints, set the x-auth token in the request header like this::

```javascript
{
  "x-auth": "YOUR_AUTH_TOKEN"
}
```

<aside class="notice">
You must replace <code>YOUR_AUTH_TOKEN</code> with your personal API key.
</aside>

