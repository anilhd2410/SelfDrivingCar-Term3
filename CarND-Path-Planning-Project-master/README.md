# CarND-Path-Planning-Project
Self-Driving Car Engineer Nanodegree Program
   
### Goals
In this project your goal is to safely navigate around a virtual highway with other traffic that is driving +-10 MPH of the 50 MPH speed limit. You will be provided the car's localization and sensor fusion data, there is also a sparse map list of waypoints around the highway. The car should try to go as close as possible to the 50 MPH speed limit, which means passing slower traffic when possible, note that other cars will try to change lanes too. The car should avoid hitting other cars at all cost as well as driving inside of the marked road lanes at all times, unless going from one lane to another. The car should be able to make one complete loop around the 6946m highway. Since the car is trying to go 50 MPH, it should take a little over 5 minutes to complete 1 loop. Also the car should not experience total acceleration over 10 m/s^2 and jerk that is greater than 10 m/s^3.

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./path_planning`.

---

## Dependencies

* cmake >= 3.5
 * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools]((https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)
* [uWebSockets](https://github.com/uWebSockets/uWebSockets)
  * Run either `install-mac.sh` or `install-ubuntu.sh`.
  * If you install from source, checkout to commit `e94b6e1`, i.e.
    ```
    git clone https://github.com/uWebSockets/uWebSockets 
    cd uWebSockets
    git checkout e94b6e1
    ```

---
## Result 
* The car is able to drive at least 4.32 miles without incident
<img src="https://github.com/anilhd2410/SelfDrivingCar-Term3/blob/master/CarND-Path-Planning-Project-master/images/PathPlanningSnapshot1.png" width=500 height=300/>

* The car is able to change lane when necessary to pass the vehicle and to come back to the middle lane 
<img src="https://github.com/anilhd2410/SelfDrivingCar-Term3/blob/master/CarND-Path-Planning-Project-master/images/PlathPlanningSnapshot2.png" width=500 height=300/>

It also fulfills other requirements of the project 
•	The car drive according to below speed limit and doesn’t exceed the 50MPH
•	The Car does not exceed the total acceleration of 10 10 m/s^2 and a jerk of 10 m/s^3.
•	Car does not come into contact with any other cars on the road
•	The car does not spend more than a 3-second length outside the lane lanes during changing lanes, and every other time the car stays inside one of the 3 lanes on the right hand side of the road.

Please find more information about the implemenation in ModelDocumentation.pdf
<a href="https://github.com/anilhd2410/SelfDrivingCar-Term3/blob/master/CarND-Path-Planning-Project-master/Model Documentation.pdf">Read More </a>
