

### run
docker build -t test:dev .   
docker run -v ~/code/test:/test -p 3001:3000 --rm test:dev     


### open link 
http://localhost:3001/


### docker 
```
docker stop $(docker ps -aq)    
docker rm $(docker ps -aq)    
docker rmi $(docker images -q)   
```

#### accesss container
```
docker exec -ti cc55da85b915 /bin/sh    
docker exec -ti cc55da85b915 bash
```

### referene
https://nodejs.org/de/docs/guides/nodejs-docker-webapp/    
https://mherman.org/blog/dockerizing-a-react-app/


