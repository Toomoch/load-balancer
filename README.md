## **Load Balancer with NGINX and Docker**

**How to run:**
 1. Generate an SSL certificate and key and place them in `./cert.pem` and  `./key.pem` respectively (a self-signed certificate and key is already present for demonstration purposes).
 2. Execute `docker-compose up -d` to run the containers in the background.
 3. Access the load balancer by the `https://localhost/` address or the IP of the host `https://<host-ip>/`
 4. Accept the self-signed certificate warning if prompted.
 5. Refresh the page multiple times to see how the *pod ID* changes between the two containers.