# Latest Ionic
### based on cypress/browsers (with all Cypress dependencies and a pre-installed browser)
----
### Pull from Docker Hub
```
docker pull francoisduchemin/docker-cypress-ionic:latest
```

### Build from GitHub
```
docker build -t francoisduchemin/docker-cypress-ionic github.com/francoisduchemin/docker-cypress-ionic
```

### Run image
```
docker run -it francoisduchemin/docker-cypress-ionic bash
```

### Use as base image
```Dockerfile
FROM francoisduchemin/docker-cypress-ionic:latest
```


----

![One does not simply use latest](https://i.imgflip.com/1fgwxr.jpg)