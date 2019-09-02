## Scenario

your company is working on Microservice Architecture. Scenario is, User can create a a Task. when use create a task, it should be stored in the Database and should be updated in all other Users dashboard on real time.  User is a Separate Service and Task is a Separate Service. Communication between Services will be through Kafka/RabbitMQ or any other Message Queue.

<!-- PubSub.png comes here -->
![Reference](https://github.com/ganeshmani/solve_scenarios/blob/master/Image_References/PubSub.png)


## Problem

Build a App to solve the above problem scenario