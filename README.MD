# Awesome Golang App Generators

The goal of this list is to compile the best app generators availabel for Go-lang as well as tutorials on how to use then. Pros and Cons etc. My goal being to find the best way to generate monolithic application composed of services. 

Definitions:
An App Generator is any Go project that helps to rapidly scaffold a monolithic or microservice application


## Microservice Generators

### Go Micro
- an awesome project which has a big vision and dedicated team building it out. Create a microservice quickly using protobuf files to generate a service. Run it locally using their micro CLI too. Deploy it to their hosted platform M3O. Once you get through the initial set up its quick and easy to use. 
cons: - difficult/ impossible to use to build a monolith
best feature: community built existing services, you can easily use existing services for generic purposes such as a geocoder or user service without writing your own from scratch.

### Goa
Goa is a framework that uses a DSL that you write to generate GRPC and HTTP api for you. Its focused on microservices


### Lile
A cool project from the UK that keeps things nice and simple. Uses protobuf to generate services using GRPC.
https://github.com/lileio/lile


### Heavy duty frameworks
I believe these frameworks are more geared towards building large applications.



