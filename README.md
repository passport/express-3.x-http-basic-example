This example demonstrates how to use [Express](http://expressjs.com/) 3.x and
[Passport](http://passportjs.org/) to authenticate users via the HTTP Basic
scheme.  Use this example as a starting point for your own web applications.

## Instructions

To install this example on your computer, clone the repository and install
dependencies.

```bash
$ git clone git@github.com:passport/express-3.x-http-digest-example.git
$ cd express-3.x-http-digest-example
$ npm install
```

Start the server.

```bash
$ node server.js
```

Use `curl` to send an authenticated request.

```bash
$ curl -v --user jack:secret http://127.0.0.1:3000/
```
