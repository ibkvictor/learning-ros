# ROS (ROBOT OPERATING SYSTEM)

## TUTORIALS
- Catkin tools
An interesting substiute from the famous cmake build tool and  dependency manager for package creation especially with c++ and python.

### Core Components
- package.xml
Contains package information and dependecy packages used in creating a package. The file is structure using Markup language and details such as:
 - Author
 - Package name, details, etc
 - License
 - build tools
 - build packages
 - executable packages - packages required at runtime of build

- CMakeLists.txt
A regular Cmake file that helps manage dependencies at different folder levels. Common commands include:
 - find_package()
 - link_target_libraries()
 - add_libraries()
 - add_directories()

### Advantages
- Proper and easy documentation of package and its dependencies
- Shorter code lines for development of package
- Automatic addition of package in package.xml and CMakeLists.txt once included
- A more cross platform build tool.

### Disadvantages
- Tries to call cmake and make in the same command, so lower flexibility 


## References
- [ROS | Tutorials](http://wiki.ros.org/iOS/Tutorials)
- [Catkin | ROS](http://wiki.ros.org/catkin)
