# python-docker

To start the web server:
```bash
docker run -d -p 5000:5000 python-docker
```

Access using web browser:
http://localhost:5000/

Check running dockers:
```bash
docker ps
```

Stop the web server:
```bash
docker stop CONTAINER_ID
```

Change CONTAINER_ID from ID output of docker ps
