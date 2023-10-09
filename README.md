# Ros Rviz container

##  To get into a docker container:
```
xhost + local:docker
```
```
export DISPLAY=:1
```
```
docker exec -it <container_name> /bash
```

## Inside the container:

```
apt-get update
```
```
source /opt/ros/noetic/setup.bash
```
```
ROS_IP=10.20.0.14
```
```
ROS_MASTER_URI="http://10.20.5.2:30015"
```
```
rviz
```
