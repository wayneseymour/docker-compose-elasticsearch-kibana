# Docker Notes  
## docker  
### Copy a dir out of a running/stopped container  
`docker cp 343643cbeb3e:/usr/share/elasticsearch/config usr/share/elasticsearch/config`  
_I had to run mkdir -p on the target destination first_  
## docker-compose  
### Launch a bash shell in a running docker-compose "service"
`docker-compose exec elasticsearch /bin/bash`

### 
``
