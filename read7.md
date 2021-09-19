#  REST

1- Who is Roy Fielding?
Some guy. He's smart.
He helped write the first web 
servers, that sent documents across 
the internet… and then he did a ton 
of research explaining why the web 
works the way it does. His name is on 
the specification for the protocol 
that is used to get pages from 
servers to your browser.

2- Why don’t the techniques that we 
use today work well when we need to 
be able to talk to all of the 
machines in the world?

Because they weren't designed to be 
used like that. When Fielding and his 
colleagues started building the web, 
being able to talk to any machine 
anywhere in the world was a primary 
concern. But most of the techniques 
developers later used to get 
computers to talk to each other 
didn't have those requirements. You 
just needed to talk to a small group 
of machines.


3- What is the HTTP protocol that 
Fielding and his friends created?

For instance, when you go to a web 
page, the browser does an HTTP GET on 
the URL you typed in and back comes a 
web page.
Web pages usually have images, right? 
Those are separate resources. The web 
page just specifies the URLs to the 
images and the browser goes and does 
more GETs using the HTTP protocol on 
them until all the resources are 
obtained and the web page is 
displayed. But the important thing 
here is that very different kinds of 
nouns can be treated the same. 
Whether the noun is an image, text, 
video, an mp3, a slideshow, whatever. 
I can GET all of those things the 
same way given a URL.


4- What does a `GET` do?

 request data from a specified 
 resource.

5- What does a `POST` do?

send data to a server to create/
update a resource.

6- What does `PUT` do?

end data to a server to create/update 
a resource.

The difference between POST and PUT 
is that PUT requests are idempotent. 
That is, calling the same PUT request 
multiple times will always produce 
the same result. In contrast, calling 
a POST request repeatedly have side 
effects of creating the same resource 
multiple times.

7- What does `PATCH` do?

request method applies partial modifications to a resource.




# API Keys

Request a personal API key from the following APIs. You should 
receive these in your email within a few hours, often within minutes. 
Please request these keys prior to lecture to allow adequate time 
because you will need them in order to complete your lab assignment. 
Note: do not post your API keys in the Canvas discussion or on 
GitHub. Save them in a secure place.

1- Geocoding API

-  Did you get your API key? YES 

2- Weather Bit API

- Did you get your API key? YES

3- Yelp API Docs

- Did you get your API key? NO

4- The Movie DB API Docs

- Did you get your API key? NO