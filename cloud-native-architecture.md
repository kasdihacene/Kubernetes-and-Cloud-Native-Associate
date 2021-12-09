## CLOUD NATIVE ARCHITECTURE CHAPTER

- The idea of cloud native architecture is to optimize the software for cost efficiency, 
reliability and faster time-to-market by using a combination of cultural, technological and architectural design patterns.

- The basic idea is to break down your application in smaller pieces which makes them more manageable. Instead of providing all functionality in a single application, 
you have multiple decoupled applications that communicate with each other in a network.

### Characteristics of Cloud Native Architecture

1. High level of automation (using CD/CD tools)
2. Self healing (includes health check and restart the services when the are down)
3. Scaling (starting multiple instances of the solution is recommended, automating the process based on CPU or memory to ensure the high availability of the service)
4. Cost Efficient (To optimize your infrastructure usage, after a scale up if no resource is no more needed we can scale down, ensure the automatic scaling)
5. Easy to maintain (Using small pieces, microservices)
6. Secure by default (systems were divided in different security zones that denied access from different networks or people.)

A good baseline and starting point for your cloud native journey is the twelve-factor app. The twelve factor app is a guideline for developing cloud native applications, 
which starts with simple things like version control of your codebase, 
environment-aware configuration and more sophisticated patterns like statelessness and concurrency of your application.
