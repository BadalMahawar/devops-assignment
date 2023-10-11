
# Dockerizing WordPress With Dockerfile, Docker Compose, and Database Optimization

Create a Dockerizing WordPress Withe Dock is and compose file with MySQL then Optimization of the Database



## Author :- Badal Mahawar


## Installation

Downlode and Install Docker Desktop on your System from

https://www.docker.com/products/docker-desktop/

    
## Roadmap

- Create a Directory for the project

- Open Code Editor and Create docker-compose.yaml file

```bash
$ touch docker-compose.yaml
```
- File docker-compose.yaml sets up a multi-container application consisting of a MySql database, phpMyAdmin and WordPress and connect to the network

- Create compose file
```bash
$ docker-compose up -d
```

## Optimize The DataBase For performance 
#### phpMyAdmin

- login phpMyAdmin with username - wordpress and password - wordpress
- Select database and generate SQL query for Optimize the database

#### WordPress plugins
- login into WordPress 
- Install data Optimize plugins that WordPress Provide like 
##### Caching plugins
```bash
W3 total Cache
WP Super Cache
```
##### Database Optimize plugins
```bash
WP-Optimize – Cache, Clean, Compress
WP-Sweep
```
- Lazy Loading Enable
- Disable unused plugins
- Enable Gzip Compression


## Demo
- db at http://localhost:8080
- WordPress at http://localhost:8000
Link:- https://youtu.be/1N0OzvbF_60?si=ysB0lg8exsFg9azG

## Challenges
I was working on DevOps for 4 months and as per my learning path I just worked on AWS CLI and Google Cloud Firebase and Firestore and with Docker and WordPress i Don't have any experience but through the docker documentation and Youtube Videos I learn Docker and Complet the assignment during the project I faced some problems:. 
1. Setting up Docker:  I understand that setting up Docker can be challenging, especially if you are new to containerization. You may have faced difficulties installing Docker Desktop on your system or configuring it correctly.
2. Configuring the Docker Compose file: Writing the Docker Compose file can be complex, I am not familiar with the syntax and configuration options. I struggled with properly defining the services, volumes, and networks in the file.
3. Troubleshooting container connectivity: Connecting the containers together and ensuring they can communicate with each other can be a challenge. I faced issues with container networking, such as containers not being able to reach each other or ports not being properly exposed.
4. Database optimization: Optimizing the database for performance can be a complex task. I have encountered challenges in identifying and implementing the right optimization techniques, such as caching, cleaning, compressing, and enabling Gzip compression.
5. Plugin installation and configuration: Installing and configuring WordPress plugins can sometimes be tricky. I have faced challenges in finding and installing the right plugins for database optimization, caching, and lazy loading. Additionally, configuring the plugins to work correctly with  WordPress installation may have posed difficulties.
