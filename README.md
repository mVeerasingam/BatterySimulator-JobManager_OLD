# BatterySimulator_JobManager 🔋🔄
## Authors: Mark Veerasingam and Lucas Jeanes
### Description: 
ATU 3rd Year CICD 1 Project

Job Manager manages all Java based operations for the battery simulator. Job Manager looks at the message queues sent from  microservice 1. 
If a message says if a job is already running, it waits before pulling from message queue. If a job is not running it tells microservice 3 to execute the next job (generate a new battery). 
Job manager updates the database if and when the simulation is succesfully complete with details of the simulation/id/jobs.




