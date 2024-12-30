## Useful commands 


- colcon build --symlink install : to build the package (more option available)
- ros2 launch "pkg name" "lanch_file name" : To use a launch file 

- Rviz2 : start Rviz
- gz sim : start an empty gazebo world (it is better to use a launch file)

### urdf info

Distance between wheels= 18.5

### Debug
- rqt_graph : to see topics,actions...
- to see the tf tree : "ros2 run rqt_tf_tree rqt_tf_tree --force-discover"
- ros2 ... list : view list of action, topics... (replace the "..." by it)
- ros2 topic echo "name of the topic" : to view what is sent by the topic