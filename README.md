# Wordpress-On-Docker-"using Docker Compose" 🐳 📦
-------------------

![kisspng-docker-application-software-software-deployment-mi-docker-5ba331e62a2ce0 4850087515374217981728-removebg-preview](https://github.com/WaseemCloud/Dynamic-web-page---Docker/assets/157589909/7ad105da-5471-499e-9e21-e8bd93247787)


In this tutorial, I will be demonstrating how to build two containers. One for Wordpress, and the second is mysql, as Wordpress needs to have a Database as a dependency. Instead of building these containers individually, we will be deploying them using Docker Compose. Docker Compose files are used to run several containers with all their necessary configurations at once. You can also, specify the docker network that you wish to run your containers in.

-------------------

-------------------
# 1) Creating Docker Compose file:
-------------------

![image](https://github.com/WaseemCloud/MongoDB-On-Docker/assets/157589909/1eefab69-1b94-4743-a44e-479ddaa5fb12)

- This file can be found in the repository "wordpress-services.yaml".

-------------------
# 2) Running the Docker Compose File:
-------------------

- let's also pull the image of MongoDB-Express from DockerHub:

      docker-compose -f  wordpress-services.yaml up


-------------------
# 3) Verify containers:
-------------------

- Verify that both container "Wordpress" and "MySQL" have been successfully deployed and running perfectly fine:

      docker ps


![image](https://github.com/WaseemCloud/MongoDB-On-Docker/assets/157589909/095a1607-79b1-4020-bbd3-144c3969cd16)

