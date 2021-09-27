# CRUD

1- In your own words, describe what each group of status code
represents:

100’s = tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.  

200’s = tell the client that its request was accepted.
 
300’s = tell the client that the resource they are requesting isn’t available at the expected location anymore.

400’s = They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, 

500’s = they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.


2- What is a status code 202?
  
sed for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available. 


3- What is a status code 308?

Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.

4- What code would you use if an update didn’t return data to a client?  

204 No Content 

5- What code would you use if a resource used to exist but no longer
does?

414 Request-URI Too Long

6- What is the ‘Forbidden’ status code?

The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.
