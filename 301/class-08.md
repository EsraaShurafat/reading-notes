#  APIs
## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## What does REST stand for?
- REST over HTTP is that it uses open standards, and does not bind the implementation of the API or the client applications to any specific implementation. For example, a REST web service could be written in ASP.NET, and client applications can use any language or toolset that can generate HTTP requests and parse HTTP responses.

## REST APIs are designed around a protocol 
## What is an identifer of a resource? Give an example.
- Uniform Resource Identifier Components
Any portion of the Uniform Resource Identifier (URI) can be manipulated for XSS. Directory names, file names, and parameter name/value pairs will all be interpreted by the Web server in some manner. 
## What are the most common HTTP verbs?
- The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively. There are a number of other verbs, too, but are utilized less frequently.
## What should the URIs be based on?
- The purpose of URIs is to uniquely and reliably name resources on the Web. According to Cool URIs for the Semantic Web (W3C IG Note), URIs should be designed with simplicity, stability and manageability in mind, thinking about them as identifiers rather than as names for Web resources
## Give an example of a good URI.
- Stability over time,Short,Give the user an idea what is linked,Easy to type

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
- 
An API is bad when it is badly documented. An API is good when it is well documented and follows a coding standard. Commenting code, writing an well explained manual for the API is Mandatory.

## What status code does a successful GET request return?
-2XXsucssfully Generally, this means that the server provided the requested page. ... This means the server successfully processed the request, but is not returning any content. Unlike a 204 response, this response requires that the requester reset the document view.

## What status code does an unsuccessful GET request return?
- If not valid, 400 Bad Request is returned. Order is processed. If the order is successful, a 201 Created is returned for the order. If an unexpected error is encountered, a 500 Server Error is returned.
## What status code does a successful POST request return?
- 2xx Successful This means the request was successful and the server created a new resource. This means the server successfully processed the request, but is not returning any content. Unlike a 204 response, this response requires that the requester reset the document view.
## What status code does a successful DELETE request return?
- A successful response of DELETE requests SHOULD be HTTP response code 200 (OK) if the response includes an entity describing the status, 202 (Accepted) if the action has been queued, or 204 (No Content) if the action has been performed but the response does not include an entity.


## Things I want to know more about
- [RegExr](https://regexr.com/)
- [Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
- [Regex 101](https://regex101.com/)
