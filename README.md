
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


