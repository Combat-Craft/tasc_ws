# tasc_ws
Workspace setup and vcs repos file

```
git clone https://github.com/Combat-Craft/tasc_ws.git

sudo apt update
sudo apt install python3-vcstool

mkdir -p asimov_ws/src
cd asimov_ws
vcs import src < ~/tasc_ws/tasc.repos
colcon build --symlink-install
source install/setup.bash
```
