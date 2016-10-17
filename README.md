# About this Repo

This is the Git repo to follow along with [Building Microservices with Docker blog](http://www.3pillarglobal.com/insights/building-microservice-architecture-spring-boot-docker-part-iv)

Each Part will be represented by a branch folder, with substeps included:
Part 1 - master (since there's no code)
Part 2- part2/start, part2/step1, part2/step3, etc...
Part 3- part3/start, part3/step1, etc...
 
# About this project

![3Pillar Global] (http://www.3pillarglobal.com/wp-content/themes/base/library/images/logo_3pg.png) 

This project is developed and maintained by [3Pillar Global](http://www.3pillarglobal.com/).

# To run the example:
* start the services with:
  `docker-compose up -d`
* to add an employee:
  `curl -X POST -H "Content-Type: application/json" -d '{\
  "id": "66fb2f1930e07c6c844b02aa",\
  "email": "tim.schmelmer@gmail.com",\
  "fullName": "Tim Schmelmer",\
  "managerEmail": null\
}' http://localhost:8080/employee

* to list all employees:
  `curl -H "Content-Type: application/json" http://localhost:8080/employee`



