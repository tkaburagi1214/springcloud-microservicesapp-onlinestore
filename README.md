# springcloud-microservicesapp-onlinestore

This is a Microservice application for Pivotal Cloud Foundry. Microsevices and 12 Factor Application elements are implemented. This is a very good an application for demonstration.

# Pre-requisite
This application requires four services. Refer to Pivotal Documents.
* MySQL for PCF (Datastore)
** http://docs.pivotal.io/p-mysql/index.html
* Redis for PCF (HTTP Session Store)
* * http://docs.pivotal.io/redis/index.html
* Spring Cloud Services
* * Config Server (Config Server)
* * Circuit Breaker (Netflix Hystrix and Turbine)
* * Registry Server (Netflix Eureka and Feign)
* * http://docs.pivotal.io/spring-cloud-services/index.html

