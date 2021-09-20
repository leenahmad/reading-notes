#  APIs

### API Design Best Practices

What does REST stand for?

REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP. However, most common REST API implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP.



REST APIs are designed around a __resources__.

What is an identifer of a resource? Give an example.

which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:

HTTP

`https://adventure-works.com/orders/1`


What are the most common HTTP verbs?

GET, POST, PUT, PATCH, and DELETE.


What should the URIs be based on?
 nouns (the resource) and not verbs (the operations on the resource).

Give an example of a good URI.?

/customers is the path to the customers collection, and /customers/5 is the path to the customer with ID equal to 5. This approach helps to keep the web API intuitive. Also, many web API frameworks can route requests based on parameterized URI paths, so you could define a route for the path /customers/{id}.


What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires. Instead, you might want to denormalize the data and combine related information into bigger resources that can be retrieved with a single request. However, you need to balance this approach against the overhead of fetching data that the client doesn't need. Retrieving large objects can increase the latency of a request and incur additional bandwidth costs. For more information about these performance antipatterns, see Chatty I/O and Extraneous Fetching.


What status code does a successful GET request return?

 returns HTTP status code 200 (OK).

What status code does an unsuccessful GET request return?

return 404 (Not Found). 

What status code does a successful POST request return?

 returns HTTP status code 201 (Created)

What status code does a successful DELETE request return?

should respond with HTTP status code 204 (No Content),