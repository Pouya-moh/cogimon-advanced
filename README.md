## INSTALL THESE PACKAGES FIRST

mercurial

libeigen3-dev

libmatio-dev

ros-kinetic-desktop-full


# distro and project files have to be included inside citk/dist/...

# Notes:
### RBDL:
	1. ros include in addon should be commented
	2. rbdl should be built seperately, using jenkins typical flags
	3. in the build folder, before calling cmake with above flags, run /opt/ros/dist/setup
	4. /opt/ros/dist should be appended to cmake_prefix_path when calling 3