# The Task
Your task is to develop a small RESTFull service in java. You need you to build your application in your own GitHub repository. Once you are done, send us a link to your repository.

Please allow yourself at least 2 hours of uninterrupted time for this task, but feel free to spend as much time on the task as you like and make the solution and the code as perfect as you like.

# The Application

Your application needs to read the list of locations.

Rest APIs are needed to answer  following questions:

* Retrieve a store by id
* Retrieve all stores in order. Cities can be ordered by  name or open date
* A store object returned by the APIs  must include an attribute indicating  how many days the store was opened for
* Create a store . API signature is enough for this method. You can leave the implementation empty .  API should only return 201 Created with empty body.
* API should return JSON
* Use meaningful HTTP response codes. Follow the best REST API practices. 

Bonus : 
* We realize that source of data may respond slowly during peak times  . Cache the source guaranteed not to exceed 10mb and 10000 stores.
* It is acceptable return a stale data up to max 1 hour.


# What we are  looking for (and what we are not):


* Feel free to use any dependency management and build tools eg maven. gradle
* Make sure your design and implementation is simple. It should only the things speficied in the requirements section,  Not more, not less.
* Make sure your code includes unit . ( acceptance tests are bonus )
* Feel free to use any java libraries you feel appropriate. spring-boot, resteasy, jersey eg
* Please do not use database, we are more interested in your Java skills 
* Feel free to commit as often as you'd like. The more commits the better! 
* We will be looking at how you approach the task (e.g. how you break it into sub-tasks) and how you structure your code to answer the questions
* Include instructions about how to start the REST server.
