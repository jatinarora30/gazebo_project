git # gazebo_project
-A 4 wheeled vehicle in a environment with a two walled house

How to use:
1. Clone the repositary
2. Got to repository
3. mkdir build
4. cd build && cmake .. && make
5. export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:[path to build]
6. cd ../world
7. gazebo myworld
