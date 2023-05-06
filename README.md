# jenkins-docker

Sample jenkins apps ran with docker

Access `http://localhost:6850`

Run the following command to start the Jenkins container:
```
docker-compose up -d
```

You'll need to enter an initial admin password, which you can retrieve by running the following command:

```
docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword
```

clear container:

```
docker-compose down

# volumes + network
docker-compose down -v
```