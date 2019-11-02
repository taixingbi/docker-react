

### run
docker exec -it container ID bash      
docker run -v ~/code/sample:/app -p 3001:3000         
docker run -v ~/code/sample:/app -p 3001:3000 --rm sample:dev     
docker run -v ~/code/sample:/app -v /app/node_modules -p 3001:3000 --rm sample:dev


### open link 
http://localhost:3001/


### docker 
docker stop $(docker ps -aq)    
docker rm $(docker ps -aq)    
docker rmi $(docker images -q)   



### referene
https://mherman.org/blog/dockerizing-a-react-app/


