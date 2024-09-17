## Building a Hypermedia-Driven RESTful Web Service

We will build a hypermedia-driven REST service with 
Spring HATEOAS: a library of APIs that you can use to 
create links that point to Spring MVC controllers, 
build up resource representations, and control how 
they are rendered into supported hypermedia formats (such as HAL).

Hypermedia is an important aspect of REST. It lets you 
build services that decouple client and server to a large 
extent and let them evolve independently. The representations 
returned for REST resources contain not only data but also 
links to related resources. Thus, the design of the representations 
is crucial to the design of the overall service.

### Dependencies

* Spring HATEOAS