# LitmusWithAuthentication

Created using this process: https://docs.google.com/document/d/14_6vvGjWSiykagsP8bRfXZ0NX43KalJidEKIF2aZXyQ/edit, except on File > New Project I used Windows Authentication.

Uses Windows Authentication

`// LitmusWithAuthentication - breaks
// private _cardUrl = 'http://localhost:25466/api/card';`

http://localhost:3000/list:
`XMLHttpRequest cannot load http://localhost:25466/api/card. No 'Access-Control-Allow-Origin' header is present on the requested resource. Origin 'http://localhost:3000' is therefore not allowed access. The response had HTTP status code 401.`
