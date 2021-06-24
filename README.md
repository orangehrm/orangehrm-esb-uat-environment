# orangehrm-esb-uat-environment

**Introduction**

Orangehrm-esb-uat-environment  is a dockerized RabbitMQ service for OrangeHRM.
 
**Prerequisites**

1. Docker engine installed.(Get docker)
2. Minimum docker version 17.3
3. Minimum docker-compose version 1.12. (Get docker compose)

**How to use  ?**

The Centralized RabbitMQ service  has been configured to use 15671,5671 ports as the default ports. So make sure that the 15671,5671 ports of your host machine is been used by none of the other services 

**Installation:**

```
git clone https://github.com/orangehrm/orangehrm-esb-uat-environment.git
cd orangehrm-esb-uat-environment
docker-compose up -d
```


