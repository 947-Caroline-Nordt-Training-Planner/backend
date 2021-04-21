# Perfect Personnel Placement (P^3)

## Project Description

Perfectly Placed Personnel is a web app that Revature managers can use to look at important information regarding clientele demands and batch output for the company. This service will visualize all current batches that are planned along with any associated information, as well as visualize that batch output alongside the client demand for associates. Managers will be able to input information for clients, and their demands, as well as input Batches which consist of a curriculum composed of skills, a number of associates, a trainer, and the duration of when the batch is planned. This web service will help ease the management of supply and demand for the company and will be an organizational aid.

## Technologies Used

### Backend
*  Java - version 1.8
*  Maven - version 3.6.3
*  Spring Boot - version 2.4.4
*  Spring Data - version 2.4.6
*  Sprint WebMVC - version 5.3.5
*  Spring Framework Cloud - version 3.0.2
*  Eureka - version 1.10.11
*  Spring Cloud Gateway Server - version 3.0.2
*  Mockito - version 3.2.4
*  JUnit4
*  PostgreSQL

## Features
* Create Read Update and Delete a trainer(s).
* Create Read Update and Delete a skill(s).
* Create Read Update and Delete a curriculum(s).
* Create Read Update and Delete a batches(s).
* Create Read Update and Delete a client(s).
* Create Read Update and Delete a client demand(s).

## Getting Started
### Prerequisites 
1. Must have Java 8 installed
2. Must have Spring Tool Suite
3. Must have Git/Git Bash tool installed


If you have all 3 prerequisites installed you can now cloned the repository.

1. Choose the folder you would like to install the project to. 
2. In the Git Bash terminal type `git clone https://github.com/947-Caroline-Nordt-Training-Planner/backend.git`
3. Hit enter and the project files will be downloaded to your machine.
4. After they have finished downloading the project you may now load the project into Spring Tool Suite.
5. Once you are in Spring Tool Suite you can go to File --> Import Projects from File System or Archive and import each project folder located in the repository. (CurriculaMicroService, TrainingMicroService, TrainerPlannerGateway, TrainerPlannerEureka)
7. Within Training Micro Service and Curricula Micro Service you'll need to go to the folder src/main/resources/data right click the file trainingdb (if you are in Training Micro Service) or curriculadb (if you are in Curricula Micro Service), go to properties, copy the location of the file.
8.  Then right click on the project folder name click Run As --> Run Configuration
9.  Choose Environment Tab, click Add...
10.  Name it TRAINING_URL or CURRICULA_URL,  and paste the location of the the data file in the value.
11.  You should now be ready to start the application.

## Usage

* In Spring Tool Suite you'll need to open the Boot Dashboard and run the services there in order.
* Please start in the following order:
   1. TrainingPlannerEureka
   2. TrainingPlannerGateway
   3. TrainingMicroService and CurriculaMicroService
* To monitor your services you can go to http://localhost:8761/

## Other Documentation and Guides
### Code Style Guide:
https://docs.google.com/document/d/1ROXci8yD7_vqiubZCvnr-OY-wmepg2skpEVXdiRvhR0/edit?usp=sharing

### Swagger DOCS:

https://app.swaggerhub.com/apis/Caroline-0947/Training-Planner/1.0.0

## Contributors

* Team Lead - Ethan McGill
* Team Lead - Kelly Brown
* Mathew Kestner 
* Joshua Freeman
* Dominick Wiley
* Enrique Mendoza
* Lindsay Read
* Rogelio Victorio
* Connor Smith
