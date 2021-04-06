# Project Portfolio
# Project 1: Path Planning + Environment Modeling for a Chevy Bolt EV
### Small snippet of my code contribution towards autonomous driving on real roads.
<img src='./AutonomousPathPlanning.gif'>

### Behind the scenes
* Algorithm: Dijkstra search + iterative max depth BFS + Embed the meaning of perceived signs RoutingGraph
* SWE Fundamentals - big codebase - CI
* Entire AV software stack chugging away (ROS + Docker)
* Local planning module (pink line)
* Environment modeling module (main focus of demo) 
* Mock perception data publisher (Carla Simulation)
* Simulation(rviz)
* & moreee :)
* Private Github repo :(

# Project 2: Software stack from scratch for my autonomous mini car
### Project demo showing various software modules coming together for my autonomous mini car.
<img src='./AutonomousMiniCar.gif'>

[Click me for the code repo](https://github.com/MaahirG/SmartCar)
### Behind the scenes & Progression
* Physical car built + wired
* Controlled it with an analog joystick + arduino over the internet
* Linux + interfaced a camera + built out a ROS network for video streaming
* Controlled the car from my laptop over the internet with a PS3 controller
* Upgraded from a RPi to a Jetson Nano
* Packages, environment setup PAIN, Linux PAIN
* Built out an obstacle detection pipeline with the RPi camera
* Started playing with occupancy maps + visualizations
* A lot of brainstorming and head banging to make the occupancy map work properly
* Motor interfacing head banging
* A* Path planning within the occupancy map
* SD card not booting up, new OS and dev environment from scratch (ty Github) but PAIN.
* Mapped real world obstacles into the occupancy map frame
* Realtime movement in the occupancy map: arrow keys to actual car movements
* Spline generation for smooth path planning
* Implemented realtime route change based on obstacles
* Made the occupancy map prettier
* tested
* debugged
* tested x7
* debugged x4
* Must've missed a few things! :)

I seriously thank you for reading through that, the journey becomes 1000x better when somebody else takes the time to walk through it too!
