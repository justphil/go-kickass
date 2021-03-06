# Go Kickass
Go Kickass is an integration of de facto standard Go packages that allows you to rapidly bootstrap a rock solid web app.

## Background
The idea is that you can fork this repository every time you need to start a new web project. I've done a thorough research to find all these packages when I started to learn Go back in late 2014. I studied their source code and wanted to make sure that they are of high quality, in particular focusing on aspects like:

* Are they written in an idiomatic way?
* Do they take into account performance considerations?
* Do they solve one particular problem in a concise way without being to bloated?
* Do they provide a satisfying test coverage?
* Are they still maintained?
* Do they complement Go's standard lib without reinventing the wheel?

## Integrations

Middleware: [Negroni](https://github.com/codegangsta/negroni)
Routing: [HttpRouter](https://github.com/julienschmidt/httprouter)
Rendering: [Render](https://github.com/unrolled/render)
Authentication: [Goth](https://github.com/markbates/goth)
Authorization: TBD
CORS Middleware: [cors](https://github.com/fasterness/cors)
Live Reload: [Gin](https://github.com/codegangsta/gin) (not to be confused with the [Gin](https://github.com/gin-gonic/gin) web framework!)
