# tasc_ws
Workspace setup and vcs repos file

```
sudo apt update
sudo apt install python3-vcstool

mkdir -p asimov_ws/src
cd asimov_ws
vcs import src < /path/to/tasc_ws/tasc.repos
colcon build --symlink-install
source install/setup.bash
```
