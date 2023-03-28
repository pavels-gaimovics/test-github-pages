# HTTP and how portals work

Hello, friend! I see what you want to become a real website developer rockstar! You even have some knowledge about HTML and CSS. But to be real tough developer you need to know a lot of things too, like how work browsers, how they make requests and what kind of request they can do.

## How portals work
When you open a webpage bunch of things are happening what you not see. You can open your favorite browser and look at Networking tab.

![Web page requests](/assets/images/webpage-work.png)

Browser could make a tons of requests to get html, images, javascripts and css. After that it will parse them to working webpage.

## What you should know?

Each browser have their own Javascript and HTML interpreter and features what they support. For Web developer you need to know, what things what looks good in one browser can look different in other or even not work at all.

Check this links:
- https://caniuse.com/?search=flexbox
- https://caniuse.com/?search=nullish
- https://caniuse.com/?search=ruby

## What is HTTP?

I hope you understand now what each browser is separate program and everyone need the common way to make requests to web server, because it could be overheating to support each browser requests types. Here comes time for HTTP to shine.

HTTP (Hypertext Transfer Protocol) is the set of rules for transferring files - such as text, images, sound, video and other multimedia files over the web. That runs on top of the TCP/IP suite of protocols, which forms the foundation of the internet.

You can check it in your browser.
![Request body](/assets/images/request-explained.png)

## HTTP Methods

When browser make request, he even can say web server what he planing to do.

- GET - is used to request data from a specified resource
- POST - is used to send data to a server to create/update a resource
- PUT - is used to send data to a server to create/update a resource
- PATCH - is used to apply partial modifications to a resource
- HEAD -  is almost identical to GET, but without the response body
- DELETE - deletes the specified resource
- OPTIONS - describes the communication options for the target resource
- CONNECT - is used to start a two-way communications (a tunnel) with the requested resource
-TRACE - is used to perform a message loop-back test that tests the path for the target resource (useful for debugging purposes)

But most popular what use Rails are: GET, POST, PUT/PATCH and DELETE