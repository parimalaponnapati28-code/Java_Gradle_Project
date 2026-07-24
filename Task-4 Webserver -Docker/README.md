# Web Server using Docker

## CodeAlpha DevOps Internship - Task 4

### Objective
Deploy a web server using Docker and Nginx.

### Tools Used
- Docker Desktop
- Nginx
- Windows 11

### Commands Used
```bash
docker pull nginx
docker run -d -p 8080:80 --name mynginx nginx
docker ps
docker images
docker exec -it mynginx bash
```

### Output
Successfully deployed the Nginx web server using Docker and customized the default web page to display:

**Hello from Parimala - CodeAlpha DevOps Internship**

### Author
Parimala
