[![Udacity - Robotics NanoDegree Program](https://s3-us-west-1.amazonaws.com/udacity-robotics/Extra+Images/RoboND_flag.png)](https://www.udacity.com/robotics)

# Introduction
This repository has reference to the project **Map My World** of the [Robotics Software Engineer Nanodegree](https://www.udacity.com/course/robotics-software-engineer--nd209) program offered by [Udacity](https://www.udacity.com/).
This branch [map_alg](https://github.com/Ekanshh/rse_p5_udacity.git) contains the algorithm used for [Occupancy Grid Mapping](https://en.wikipedia.org/wiki/Occupancy_grid_mapping), _written in [C++](https://en.wikipedia.org/wiki/C%2B%2B)_.  

## Steps to Launch the Algorithm Visualization 

### Clone this repository
```
$ cd /home/workspace/src
$ git clone <this repo>
```
### Compile the program
```
$ cd rse_p5_udacity/map_alg
$ rm -rf Images/* //Deletes the folder content, not the folder itself.
$ g++ OCM.cpp -o app -std=c++11 -I/usr/include/python2.7 -lpython2.7
```
### Run the program
```
$ ./app
```
Now, wait for the program to generate the map and store it in the `/home/workspace/rse_p5_udacity/map_alg/Images` directory

## Output Image

<img src="/map_alg/Images/Image.png" height=500 >

-----------------------------------------------------------------------------------------------------------------------------

#### Commit c7edeb5: 
Added **Multiple Sensor Fusion** algorithm _written in C++_. To run the program, _Compile_ it using : ` $ g++ OCM.cpp -o app -std=c++11` and then _run_ it using: `./app`. 

The output will display a matrix:
```
0.93 0.76 
0.46 0.65 
```

