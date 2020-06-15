# CodingMind-
TECHNICAL QUESTIONS

1. What is API
	- Application program interface contains set of tools, protocols for building softwares.
	-Define interations between multiple intermediates.
	-Advantage of an API is the applications can be made to work across different devices. 

2. What is REST and which methods are there in REST ?
	-Representational state transfer.
	-Software Architectural style used for creating web services.
	-Methods are POST, GET, PUT, PATCH and DELETE.

3. Which REST method will be cached in browser unless otherwise explicitly mentioned by
server ?
	-Cache is the ability to store copies of frequently accessed data.
	-Browsers treat all GET requests cacheable.
	-GET is cacheable by default while POST is not cacheable. 

4.Which REST method is idempotent and which method is not idempotent ? Explain with a
small example.
	-PUT is idempotent.
	-Idempotent means the result for the request performed is independent of the number of times it is executed.
	-Produce same result when it is called multiple times.
	-POST is idempotent.

5.Which REST method should be used to deal with user sensitive data like credit card
information etc.
	-POST is more secure than GET.
	-In GET parameters are passed via url.
	-Where parameters are stored in server logs and history so it is insecure.
	-POST carry request parameter in message body which makes it more secure.

6. What is the difference between http and https ? Explain shortly how https works.
	-HTTPS is secured while HTTP is unsecured.
	-HTTPS uses port 443 for data transfer while HTTP sends data over port 80.
	-HTTPS operates at transport layer while HTTP operate at application layer.

7.What is caching ? How does it help an application ?
	-Cache is the content stored on local hard drive to make it faster for user to access it.
	-Improves the efficiency and the overall performance.
	-Contents includes HTML pages, images, files.

8.What is the main difference between traditional relational databases and nosql databases ?
	-NoSQL database have dynamic schema and allows us to work more freely with unstructured data.
	- Relational database are  scalable, but usually more expensive.
	-NoSQL databases is more efficient in cost wise.

9.Explain shortly MVC pattern in developing backend applications.
	-Model-View-Controller.
	-Application design model.
	-Commonly used for developing modern user interfaces.

10.What is event loop in javascript ? Explain with an example
	-JavaScript has a model based on an event loop, which is responsible for executing code.
	-Collects and process events and execute sub tasks.

11.What is the difference between git pull and git fetch ?
	-Git fetch retrieve the latest meta-data from the original.
	-Git fetch is a primary command used to download contents from a remote repository.
	-Git pull brings changes from the remote repository.
	-Git pull used to update the local version of  a repository from a remote.
