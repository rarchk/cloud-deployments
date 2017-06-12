# Cloud Deployments

> Journey of application from development box to production... 


In this repo, I explore a random application running on a software developer machine, and try to run it in production using tools like 

0. Build an application (Java)
1. Containerize your application  (Docker) 
2. Scheduling and Fault Tolerant Deployment (Docker Swarm and Kubernetes)
3. Orchestrate the development enviroment using tools (Ansible, Terraform)
4. Adding Software Processes to update application (CI/CD Pipeline)


## Build an application
In our study, we do not write application itself. Our concern is to build an environment in which this application can run while resolving all dependencies. 
However it is important to run and understand the behaviour of application, like what ports or what interfaces are open. Furthermore, how do you run such an application.

After a careful study, we came to know that   