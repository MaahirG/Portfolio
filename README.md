# Project Portfolio 
#### [You can also click here for my Github homepage to browse outside the portfolio 😊](https://github.com/MaahirG)

## Project 1: Software stack from scratch for my autonomous mini car
### Project demo showing various software modules coming together for my autonomous mini car.
<img src='./AutonomousMiniCar.gif'>

### Keep scrolling for more projects!

#### [Click me for the code repo](https://github.com/MaahirG/SmartCar)

#### Behind the scenes

- [x] Python & C++
- [x] Physical car built + wired
- [x] Controlled it with an analog joystick + arduino over the internet
- [x] Linux + interfaced a camera + built out a ROS network for video streaming
- [x] Controlled the car from my laptop over the internet with a PS3 controller
- [x] Upgraded from a RPi to a Jetson Nano
- [x] Packages, environment setup PAIN, Linux
- [x] Built out an obstacle detection pipeline with the RPi camera
- [x] Pipeline too choppy, so used TensorRT for ~20fps
- [x] Switched from following car with a cord plugged into the wall to a LiPo battery
- [x] Started playing with occupancy maps + visualizations
- [x] Brainstormed and banged head to make the occupancy grid work properly
- [x] Motor interfacing difficulties
- [x] A* route planning within the occupancy map
- [x] SD card not booting up, new OS and dev environment from scratch (ty Github) but PAIN.
- [x] Mapped real world obstacles into the occupancy map frame
- [x] Realtime movement in the occupancy map: arrow keys to actual car movements
- [x] Built out spline generation for smooth path planning
- [x] Implemented realtime route change based on obstacles
- [x] Implemented multiprocessing for path planning and camera streaming separation and concurrency
- [x] Made the occupancy map prettier
- [x] tested, debugged, tested x7, debugged x4
- [x] Must've missed a few things! :)
I seriously thank you for reading through that, the journey becomes 1000x better when somebody else takes the time to walk through it too!

## Project 2: Machine Learning Application, Backend Workflow (Machine Learning + SWE Intern)
### Codebase design for a deep learning based auto-annotating scientist aid within the realm of Mass Spectrometry.
#### Private code repo, but here is my censored flowchart:

<p float="left">
  <img src='./MLAppBackend.png' width=70%>
</p>

#### Behind the scenes

- [x] Research papers
- [x] Learning about different model types and DL models/architectures
- [x] Built tool for data ingestion and ML related tasks
- [x] Model implementation in PyTorch
- [x] ML model train,test,eval,tune etc (lifecycle)
- [x] Built application backend
- [x] Modularized and made scalable
- [x] Compatibility with front end webapp
- [x] Learnt fundamentals of ML deployment
- [x] Preparing for ML deployment

## Project 3: High Lvl Software - Path Planning + Environment Modeling for Chevy Bolt EV
### Showcasing one usecase of my code contribution towards real-road autonomous driving.
<p float="left">
  <img src='./AutonomousPathPlanning.gif' width='54%' height='320'>
  <img src='./AutoWatoBolt.PNG' width='45%' height='320'>
</p>

#### Behind the scenes
- [x] C++
- [x] Co-authored a research paper based on this environment model idea. Candidate in iROS and RAL conferences.
- [x] Algorithm: Dijkstra search + iterative max depth BFS + Embed the meaning of perceived signs in RoutingGraph
- [x] SWE Fundamentals - big codebase - CI
- [x] Entire AV software stack chugging away (ROS + Docker)
- [x] Local planning module (pink line)
- [x] Environment modeling module (main focus of demo) 
- [x] Mock perception data publisher (Carla Simulation)
- [x] Simulation(rviz) & more! :)
- [x] Unfortunately private Github repo
