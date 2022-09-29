# APIs with Go

## Web APIs with gin-gonic

### Introduction to the gin framework

The following video is a very **basic** introduction to gin. It just the first step into gin.

[https://www.youtube.com/watch?v=RkmvVFZJJvs](https://www.youtube.com/watch?v=RkmvVFZJJvs)

### Gin + GORM

This article takes you through the basics of creating a REST API with gin and GORM

[How to build a REST API with Golang using Gin and Gorm](https://blog.logrocket.com/how-to-build-a-rest-api-with-golang-using-gin-and-gorm/)

### Gin Authentication

This [article](https://medium.com/@dandua98/gin-authentication-middleware-e659965877b6) introduces you to auth middleware with gin.

### Data problem: Web API version

#### Part 1: Data Loader
Copy the data loader from the previous (GORM) version of the Data project here. Put it in a separate folder from the Gin code you will write in the following section. **DO NOT** copy the JSON generation code, you will not generate JSON files.

#### Part 2: Web API
In the previous version, you had generated a JSON file. And used that JSON file to render the plot on the browser. In this project, you will generate the data required, on the fly using GORM in the gin "handler" functions.

#### Part 3: HTML

Copy the HTML/CSS/JS from your previous assignment to this project. The only change is all your HTML/CSS/JS must be **served** from your gin application.

[Gin Static Middleware](https://github.com/gin-contrib/static) is a good way to do that. But, you can choose whatever way to achieve the same result.

## REST API with Gin

### A more detailed tutorial into Gin

[https://www.youtube.com/watch?v=qR0WnWL2o1Q](https://www.youtube.com/watch?v=qR0WnWL2o1Q)

### Mini Project: TODO app

#### Part 1: REST API with Gin
- Create a REST API for the TODO model
- The todos should be stored in Postgres
- Add swagger to your project with [swaggo](https://github.com/swaggo/swag)
- Generate swagger documentation for your TODO API

#### Part 2: Frontend with JS
Please modify the frontend example from w3schools to work with the API given above.
Also, make changes to the Gin code to host the HTML/CSS/JS code

Reference: [w3schools js todo app](https://www.w3schools.com/howto/howto_js_todolist.asp)
