# DevOpsDesignTask

- Kubernetes will be used

- There will be 5 namespaces;  3 dev's, 1 staging and 1 prod

- Whole infrastructure will be on same VPC

- FE will be on public Subnet, back-end will be on private

- All deployments will have different IP Blocks, developers can access

- Kubernetes deployments:
  * C# microservices communicating wiht FE 
  * C# microservices which are running background tasks
  * Python microservices communicating wiht FE
  * Python microservices which are running background tasks
  * Front-end server (Angular)
  * SQL working with C# microservices
  * SQL working with Python microservices
  * MongoDB working with Python microservices
  * RabbitMQ message broker
  * Prometheus / Graphana
  * Jenkins
 
 - Persistent Volumes will be used to store log files
 
 - ELB will be used in front of Angular
 
 - CI/CD pipeline on Jenkins Server
 
 - Repository
 
 # Questions:
 - What is the intention of using S3 service?
