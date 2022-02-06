# **Docker From Scratch**

### **Building a First Utility Container**
    1. Create a directory for your utility container
    2. Copy the Dockerfile into the directory
    3. docker build -t node-util .
    4. docker run -it -v /Users/virus/Desktop/Backend/Docker/docker-from-scratch:/app node-util npm init
    
### **Utilizing ENTRYPOINT**
    1. docker build -t mynpm .
    2. docker run -it -v /Users/virus/Desktop/Backend/Docker/docker-from-scratch:/app mynpm i express --save

### **Using Docker Compose**
    1. Create a directory for your docker-compose file
    2. docker-compose run --rm npm init

