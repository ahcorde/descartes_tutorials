# Descartes Tutorials

For a full description of the tutorials please see [the wiki](http://wiki.ros.org/descartes/Tutorials).

## Installation

Install the following:

```
sudo apt-get install ros-kinetic-moveit-simple-controller-manager
```

Clone the following repos:

```
git clone https://github.com/ros-industrial-consortium/descartes_tutorials.git
git clone https://github.com/ros-industrial/abb.git
```

Install dependencies:

```
rosdep install --from-paths src --ignore-src --rosdistro=kinetic -y
```

Then build.
