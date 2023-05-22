# Ecommerce-JHipster-Full-Microservice-stack

Source: 

https://medium.com/jhipster/create-full-microservice-stack-using-jhipster-domain-language-under-30-minutes-ecc6e7fc3f77

https://medium.com/@barryvredevoort/deploying-jhipster-microservices-on-aws-eks-elastic-container-service-for-kubernetes-d8ec77f5a9

![image](https://github.com/juano47/Ecommerce-JHipster-Full-Microservice-stack/assets/22141158/ae587ed1-e41a-4261-8ac4-cbd6a090f308)

The stack includes:

 - Service discovery using JHipster Registry, a Spring boot application that packs Eureka server and Spring cloud config server.

 - API management and Gateway using Spring Boot, Netflix Zuul, ReactJS, and Swagger.

 - Microservices using Spring Boot.

 - Monitoring using JHipster Console which is made of the Elastic stack(ELK) and Zipkin.

The Gateway routes incoming requests to two microservices, Invoice application, and Notification application.
