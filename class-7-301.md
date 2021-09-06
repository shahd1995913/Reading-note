#  How I explained REST 

- [x]  Who is Roy Fielding?
## helped write the first web servers, that sent documents across the internet… and then he did a ton of research explaining why the web works the way it does. His name is on the specification for the protocol that is used to get pages from servers to your browser.



- [x]  Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?
## most of the techniques developers later used to get computers to talk to each other didn't have those requirements. You just needed to talk to a small group of machines.
## We need to be able to talk to all machines about all the stuff that's on all the other machines. So we need some way of having one machine tell another machine about a resource that might be on yet another machine.


- [x]  What is the HTTP protocol that Fielding and his friends created?
## That first part tells the browser what protocol to use. 
## Because it is capable of describing the location of something anywhere in the world from anywhere in the world. It's the foundation of the web. You can think of it like GPS coordinates for knowledge and information.

## HTTP request methods are the assets that indicate the specific desired action to be performed on a given resource. Each method implements a distinct semantic, but there are some standard features shared by the various HTTP request methods.


- [x]  What does a GET do?
## GET is used to retrieve and request data from a specified resource in a server. GET is one of the most popular HTTP request techniques. In simple words, the GET method is used to retrieve whatever information is identified by the Request-URL.
- [x]  What does a POST do?
## POST requests are utilized to send data to a server to create or update a resource.  The information submitted to the server with POST request method is archived in the request body of the HTTP request. The HTTP POST method is often used to send user-generated data to a server. One example is when a user uploads a profile photo.
- [x]  What does PUT do?
## PUT is similar to POST as it is used to send data to the server to create or update a resource. The difference between the two is that PUT requests are idempotent. This means that if you call the same PUT requests multiple times, the results will always be the same.
- [x]  What does PATCH do?
## A PATCH request is similar to POST and PUT. However, its primary purpose is to apply partial modifications to the resource. And just like a POST request, the PATCH request is also non-idempotent. Additionally, unlike POST and PUT which require a full user entity, with PATCH requests, you may only send the updated username.