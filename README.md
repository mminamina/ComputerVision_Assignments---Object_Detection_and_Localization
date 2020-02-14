## ComputerVision Assignments: Object Detection and Localization
Object Detection and Localization Assignments
### Overview
This repository contains my work for Udacity Computer Vision Object Detection+Localization(SLAM) assignments, which allow me to learn, test and implement various object motion and localization methods. 

For assignment instructions and required software packages, please refer to https://github.com/udacity/CVND_Localization_Exercises

### Assignment Details
1. Robot Localization
2. 2D Histogram Filter
3. Kalman Filters
4. State and Motion
5. Matrices and Transformation of State
6. SLAM
7. Vehicle Motion and Calculus

### Robot Localization
1. Explore robot world
2. Compute probabilities after Sense
3. Build and implement **Sense Function**
4. Build and implement **Normalized Sense Function**
5. Apply multiple measurements
6. Incorporate **Move Function** (**Motion**) into sensor measurements
7. Inject Uncertainty into move function to introduce randomness+generalization
8. Test robot's multiple movements
9. Implement the cycle of Sense & Move

### 2D Histogram Filter
- Explore, understand and run pre-existing codebase
- Implement and test 2D Sense Function
- Incorporate Sense Function with Localization
- Identify and reproduce bug
- Implement debugger

### Kalman Filters
1. Apply **Gaussians** for **uncertainty**
2. Add new **Mean+Variance** for updated Gaussian (adding new info/measurement)
3. Incorporate Motion into Gaussian & write **Predict Function** with motion update
4. Implement Kalman Filter code to loop through the process cycle (**sense, measure, move**)

### State and Motion
- Learn how to move and turn the car
- Create and play around with car object (**movement**+**turning**)
- Setup and move around multiple colorful cars
- Define color object
- Modify predict-state function to use matrix multiplication

### Matrices and Transformation of State
- Vector Coding
- Matrices in Python
- Different Matrix calculations (**Addition**, **Multiplication**, **Transpose**, **Inverse**, **Identity**)

### SLAM
1. Construct **Omega** and **Xi**
2. Update constraint matrices with **Landmark sensor measurements**+**motion**
3. Adjust to test different confidence levels of measurements

### Vehicle Motion and Calculus
1. Approach **Instantaneous Speed**
2. Implement an **Accelerometer**
3. Plotting **Position** vs **Time**
4. Speed from Position Data
5. Understanding the Derivative
6. data generator

#### Packages 
Python, Pytorch

LICENSE: This project is licensed under the terms of the MIT license.
