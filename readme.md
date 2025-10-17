### Spawn go1 in dockerfile 

```sh
rosrun gazebo_ros spawn_model -urdf \
  -file /root/muse_ws/muse_ws/src/go1/go1_description/urdf/go1.urdf \
  -model go1 -x 0 -y 0 -z 0.3
```