
Follow these steps to upload your project to GitHub:
1)Start working with Git 
Install git
git init
git add .
git commit -m "Add all my files"
git remote add origin https://github.com/yourusername/your-repo-name.git

Upload of the project from scratch requires git pull origin master.
git pull origin master
git push origin master
If any problem occurs in pushing, use git push --force origin master.

2)Work on Spring and Microservices
Microservices
Spring
Department-Service - Spring Web, Spring data JPA, Lombok, Eureka discovery Client, config-server
User-Servicer - - Spring Web, Spring data JPA, Lombok, Eureka discovery Client,config-server
Hystrix maintenance Library - For circuit breaker and fallback mechanism in API cloud gateway service
Hystrix Dashboard - new microservices with Eureka discovery Client and hystrix dashboard lib and config server
Visit to http://localhost:9295/hystrix and put http://localhost:9191/actuator/hystrix.stream/ to monitor stream
Zipkin server
Slueth
Config server - create microser as config server dependency it i will need git hub to keep config
API Gateway -- Front microservices , will handle all requests and traverse from here- Eureka discovery Client to register it with eureka service
                Gateway for spring cloud route, spring boot actuator for restpoint monitoring and config server  dependency
Config server - microservices to handle configuration for all microservice using git config file or others
Service registry  -- work as load balancer and Maintain all restpoints of all microservices which are registered under this - Spring-cloud-netflix Eureka server (Spring cloud discovery)
Added bootstrap yml - to add all config details

3)Work with IntelliJIdea
Open java project using idea .
Set environment variable of C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2021.2\bin
If not starting getting lock error delete unwanted folder from C:\Users\Chandrabhan Pal\AppData\Local\JetBrains
