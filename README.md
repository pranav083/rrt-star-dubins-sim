# RRT Simulator

## Dependencies
* Qt5
* Eigen

## Compiling
```bash
$ git clone https://github.com/pranav083/rrt-dubins-sim
$ cd rrt-dubins-sim/
$ chmod +x build.sh
$ ./build.sh
```
Run the exectuable as
```
$ ./bin/motion-planning-demo
```
## Interface

![RRT with Dubins steering function Simulator](imgs/rrt.png)    
Path planning by RRT can also address the vehicle dynamic constraints (eg, turn radius)    
Thus, the above is an example of a dynamically feasible RRT motion plan for Nonholonomic Robot following Dubins motion model.    
![RRT* Simulator](imgs/rrtstar-sim.png)   
Example of an RRT* motion plan    



Thanks to:    
RRT simulator: https://github.com/sourishg/rrt-simulator   
Dubins Curves: https://github.com/AndrewWalker/Dubins-Curves    

*Note: Draw obstacles by clicking and dragging on the field.*
