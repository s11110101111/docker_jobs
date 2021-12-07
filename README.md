# docker_jobs
проект для сборки образов docker 

#1. jenkins

``` 
create dir 
mkdir ~/jenkins

```
Firs Log in

View the generated administrator password to log in the first time.
```
docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword
```
#2. rabbutMQ
```
cd rabbitmq-compose
docker-compose up
```
## Play

Open [http://localhost:15672/] (or what ever IP you get when you run docker-machine ip)
```
open http://$(docker-machine ip default):15672/
```
and use the login
```
username: guest
password: guest
```
