# ros2_python_skeleton
A skeleton ROS2 python package generator. This is an alternative to using
`ros2 pkg create`, which uses an outdated version of the flake8 test. This
is only suitable for Python packages. For packages declaring messages,
you are better off using `ros2 pkg create` and using CMakeLists.txt to
define how to compile and install the messages.

## How to use

1. Clone this repository.

2. Create or clone the repository for the new Python ROS2 package.

3. Run ./create-package with two arguments: the new package name, and the
directory containing the new package.

4. Edit README.md, package.xml, and setup.py in the new package.
