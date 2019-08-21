
##### Removing a container
```
docker rm -v -f <container>
```
rm - remove
-v - any associated volumes
-f - force

##### Removing an image
```
docker rmi -f <image>
```

##### Seraching for container
```
docker ps -a | egrep '<search1>|<>search2'
```

##### Seraching for images 
```
docker images | egrep '<search1>|<>search2'
```