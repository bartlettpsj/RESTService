# RESTService
Sample Grails 2.4.3 RESTService

Introduction
------------

Very simple example of how to do a Grails REST Service using Domain classes.

I have two domain objects and two Controllers.  

- One (City) was created by grails/intellij and there is a lot of scaffolding added for the Controller.  
- The second I created manually and as minimal as possible to prove a point.

In future I will create a REST controller that doesn't use domain objects.  I will try to return another class/structure as JSON/XML.

Using
-----

You can test the service either by clicking the controller in the sample Grails page or via:

curl -X GET -H "Accept:application/xml" http://localhost:8080/RESTService/person
curl -X GET -H "Accept:application/json" http://localhost:8080/RESTService/person

or even, which defaults to JSON.

curl -X GET http://localhost:8080/RESTService/person


Testing
-------

There are test cases generated by Grails but I have not yet checked them.

