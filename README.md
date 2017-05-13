# slam_backend
iSAM2-based backend interface for 2D Pose Graph SLAM

Build by cloning this into the src directory of your catkin workspace and then doing catkin_make.

Requires GTSAM.
To install GTSAM, follow the instructions (https://bitbucket.org/gtborg/gtsam), cloning into a folder outside your catkin workspace.

$ mkdir build

$ cd build

$ cmake ..

$ ccmake .. (set GTSAM_WITH_EIGEN_MKL and GTSAM_WITH_EIGEN_MKL_OPENMP to OFF)

$ make check (optional, runs unit tests)

$ make install
