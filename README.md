***#Node-App#***

**1. Build the Docker image**

   ```
   docker build -t node-docker-app .
   ```
   
**2. Run the container**

```
docker run -p 3000:3000 node-docker-app
```

**can visit http://external_ip:3000 in your browser, and you’ll see the message "Hello from Dockerized Node.js app!"**


