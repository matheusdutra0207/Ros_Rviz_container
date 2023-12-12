# Ros Rviz container

####  To get into a docker container:
```
xhost + local:docker
export DISPLAY=:1
docker exec -it <container_name> /bash
```

#### Inside the container:

```
apt-get update
source /opt/ros/humble/setup.bash
rviz2
```
