# udacity-project1
### Udacity's nano degree program: Robotics Software Engineering  
**Project Title**: Build My World  
By Navjot Kaur
## Overview  
In this project a simulation world in Gazebo is created. The following steps have been done:
1. Build a single floor wall structure using the **Building Editor** tool in Gazebo. 
2. Model any object of your choice using the **Model Editor** tool in Gazebo. Your model links should be connected with joints.  
3. Import your structure and two instances of your model inside an empty **Gazebo World**.  
4. Import at least one model from the **Gazebo online library** and implement it in your existing Gazebo world.  
5. Write a C++ **World Plugin** to interact with your world. Your code should display “Welcome to ’s World!” message as soon as you launch the Gazebo world file.  

## Prerequisites/Dependencies  
* Gazebo >= 7.0  
* ROS Kinetic  
* make >= 4.1(linux)
* gcc/g++ >= 5.4

## Setup Instructions (abbreviated)  
1. Meet the `Prerequisites/Dependencies`  
2. Open Ubuntu Bash and clone the project repository  
3. On the command line execute  
```bash
sudo apt-get update && sudo apt-get upgrade -y
```
4. Build and run your code.  
## Project Description  
Directory Structure  
```
.p1-gazebo-build-my-world                    # Build My World Project 
├── model                          # Model files 
│   ├── building
│   │   ├── model.config
│   │   ├── model.sdf
│   ├── robot-one
│   │   ├── model.config
│   │   ├── model.sdf
│   ├── robot-two
│   │   ├── model.config
│   │   ├── model.sdf
│   ├── table
│   │   ├── model.config
│   │   ├── model.sdf
├── script                         # Gazebo World plugin C++ script      
│   ├── welcome_message.cpp
├── world                          # Gazebo main World containing models 
│   ├── myoffice.world
├── CMakeLists.txt                 # Link libraries 
└── README.md
```


## Project Rubric  
### 1. Basic Requirements  
#### 1.1 Does the project include a world directory containing the Gazebo world file, a model directory containing a structure and an object model files, a script directory containing the C++ plugin code, and a CMakeLists.txt file?  
Yes, it does.  
### 2. Building  
#### 2.1 Does the project include a house with walls?  
Yes, it does.  
### 3. Modeling  
#### 3.1 Does the project include an object built using the Model Editor?  
Yes, it does.  
### 4. Gazebo World  
#### 4.1 Does the project contain a Gazebo world with multiple models?  
Yes, it does.  
### 5. World Plugin  
#### 5.1 Does the project contain a C++ world plugin?  
Yes, it does.  