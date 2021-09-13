# CRUD
## [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

## In your own words, describe what each group of status code represents:
### 100’s =Informational responses 
### 200’s =Successful responses
### 300’s =Redirects
### 400’s =Client errors 
#### 500’s = Server errors
## What is a status code 202?
- The HyperText Transfer Protocol (HTTP) 202 Accepted response status code indicates that the request has been accepted for processing, but the processing has not been completed; in fact, processing may not have started yet.
## What is a status code 308?
- The HyperText Transfer Protocol (HTTP) 308 Permanent Redirect redirect status response code indicates that the resource requested has been definitively moved to the URL given by the Location headers.Note: Some Web applications may use the 308 Permanent Redirect in a non-standard way and for other purposes.
## What code would you use if an update didn’t return data to a client?
- The values of the numeric status code to HTTP requests are as follows.
## What code would you use if a resource used to exist but no longer does?
- However, the "409 Conflict" is the best existing answer code (as pointed by @Wrikken), maybe including a Location header pointing to the existing resource. IMHO, "307 Temporary Redirect" is the real temporary redirect.
## What is the ‘Forbidden’ status code?
- The HTTP 403 Forbidden client error status response code indicates that the server understood the request but refuses to authorize it. This status is similar to 401 , but in this case, re-authenticating will make no difference

## [Build A REST API With Node.js, Express, & MongoDB - Quick ](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)


## Why do we need to pull our MongoDB database string out of our server and put it into our .env?
- Let Us Handle the Provisioning, Scaling, Back Ups, and Security of Your MongoDB Cluster. Focus More on Building Apps, and Less on Maintaining Database. Try Today for Free.
## What is middleware?
- Middleware is software that provides common services and capabilities to applications outside of what's offered by the operating system.
## What does app.use(express.json()) do?
- express. json() is a method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application using the code: app.
## What does the /:id mean in a route?
- params object, with the name of the route parameter specified in the path as their respective keys. and. app.
## What is the difference beween PUT and PATCH?
- The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.
## How do you make a defalut value in a schema?
- You can specify a default value for an item using the default keyword. When a data doesn't have a corresponding value
## What does a 500 error status code mean?
- The HyperText Transfer Protocol (HTTP) 500 Internal Server Error server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request. This error response is a generic "catch-all" response.
## What is the difference between a status 200 and a status 201?
- The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page).


## Things I want to know more about
[mongoose api](https://mongoosejs.com/docs/api.html#Model)
[React Router](https://reactrouter.com/web/api/BrowserRouter)