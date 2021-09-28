#

## Installation
Make sure you have all the repositories from sim.rosinstall
```
wget https://raw.githubusercontent.com/PilzDE/neo_simulation/melodic/sim.rosinstall
wstool init src sim.rosinstall
```

Install dependencies
```
rosdep install --from-path src --ignore-src
```