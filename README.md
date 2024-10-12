# Envoy Proxy Practices

Studies based in day 31-32 of 100 Days System Design for DevOps and Cloud Engineers.

https://deoshankar.medium.com/100-days-system-design-for-devops-and-cloud-engineers-18af7a80bc6f

Days 31–40: Scalability and Performance Optimization

Day 31–32: Implement advanced load balancing techniques using Envoy Proxy.

## Project Overview

There are two project folders.

### ```envoy-load-balancing```

Run:
```
docker-compose up --build
```
Open another terminal side by side with docker-compose and do ```curl http://localhost:8080``` to see the load balancer working.

### ```envoy-replica-load-balacing```

Run:
```
docker-compose up --build --scale app=3
```
Open another terminal side by side with docker-compose and do ```curl http://localhost:8080``` to see the load balancer working.

## Author
This project was implemented by [Lucas de Queiroz dos Reis][2]. It is based on the Day 23–24: Automate multi-environment setups using Terraform and Ansible dynamic inventories from the [100 Days System Design for DevOps and Cloud Engineers][1].

[1]: https://deoshankar.medium.com/100-days-system-design-for-devops-and-cloud-engineers-18af7a80bc6f "Medium - Deo Shankar 100 Days"
[2]: https://www.linkedin.com/in/lucas-de-queiroz/ "LinkedIn - Lucas de Queiroz"