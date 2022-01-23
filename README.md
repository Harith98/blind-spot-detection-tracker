## Blind Spot Detection Tracker for E-hailing Riders (BSTeRs)
# A. DEFINING THE PROJECT

Project Name : Blind Spot Detection Tracker for E-hailing Riders (BSTeRs)
<p align="center">
  <img width="400" height="200" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/logobster.png">
  <br>
  Product's logo
</p>

Lecturer : Prof. Dr. Goh Ong Sing

<table>
    <thead>
        <tr>
            <th></th>
            <th>Name</th>
            <th>Matric Num.</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Project Manager</td>
            <td>Badrul Amin bin Nasarudin </td>
            <td>(B031910475)</td>
        </tr>
        <tr>
            <td rowspan=3>Project Member</td>
            <td>Muhammad Luqman bin Mohd Azman</td>
            <td>B031910487</td>
        </tr>
        <tr>
            <td>Syed Muhammad Harith</td>
            <td>B031910496</td>
        </tr>
    </tbody>
</table>

### INTRODUCTION
A blind spot is a part of the road that cannot be noticed by looking forward through your rear-view and side-view mirrors. Blind spots can be large enough to block the vision of another automobile, motorcycle, bicycle, or pedestrian. Blind spots exist in all cars, including the front, back,and both sides of the vehicle. Bigger vehicles, such as trucks, trailers, and buses, have significantly larger blind spot area or zones.
Blind spot incidents happened when one or more drivers change lanes while driving and fail to detect another car in their blind area, resulting in a collision with the other vehicle on the road. When changing lanes, car accidents like these are often occur. Currently, there is no system that can give notice or alert to riders when they are in a blind spot of another vehicle. To solve this, we proposed a project which is blind spot detection and tracker. We believe that this project is able to help to reduce accident rate involving motorcycles. 
Our aim is that by doing this project, the rider society will be able to identify each vehicles blind spot around them and might be able to create an environment for them to be more careful and aware of their surroundings.

### OBJECTIVE
1.To design a blind spot detection algorithm based on vehicle image.

2.To develop a blind spot tracker for e-hailing riders(BSTeRs) to detect blind spot area.

3.To implement BSTeRs on e-hailing for motorcycles.


# B. PLANNING THE PROJECT

<p align="center">
    <img width="1200" height="500" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/wbs.PNG">
    <br>
    <em>Figure 1: Work Breakdown Structure</em>
</p>

Tree Structure

<p align="center">
    <img width="500" height="800" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/treestructure.PNG">
    <br>
    <em>Figure 2: Tree Structure of WBS</em>
</p>

### Responsibility Assignment Matrices (RAM)

<p align="center">
    <img width="520" height="648" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/ram.PNG">
    <br>
    <em>Figure B.3: Responsibility Assignment Matrices</em>
</p>

### Team Responsibility

Team Members | Role | Resposibilities
--- | --- | --- 
Badrul | Project Manager | Allocate the tasks to all the members.
Luqman | Implementation Manager | Hardware installation and the system modules.
Harith | System Analyst | Ensuring that the requirements of the project are captured and documented correctly. 

<p align="center">
  <em>  Team Responsibility</em>
</p>

# C.IMPLEMENTATION

## Costing
<p align="center">
  <img width="800" height="500" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/budget.png">
  <br>
  <em>Figure : Budget estimation</em>
</p>

## Time management

<p align="center">
  <img width="800" height="500" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/timemanagement.PNG">
  <br>
  <em>Figure :Time management</em>
</p>

## D. EXECUTING THE PROJECT
### Design & Model

<p align="center">
  <img width="598" height="251" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/circuit%20built.png">
  <br>
  <em>Figure : CIRCUIT PROTOTYPE</em>
</p>
<p align="center">
  <img width="598" height="251" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/circuit.png">
  <br>
  <em>Figure : CIRCUIT CONNECTION</em>
</p>

Module 1
The module one is to identify the vehicle in front of the rider’s vehicle based on the vehicle detection algorithm that was inspired from YOLOV3 object detection algorithm. The architecture of the algorithm can be seen at figure below and the implementation of the architecture can be seen at figure below also

<p align="center">
  <img width="500" height="800" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/module%201.png">
  <br>
  <em>Figure : MODULE 1 PROCESS FLOW</em>
</p>

<p align="center">
  <img width="602" height="339" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/googlecolab.png">
  <br>
  <em>Figure :IMPLEMENTATION GOOGLE COLAB</em>
</p>


Module 2 <br>
The second module is to calculate the distance between the rider's motorcycle and the  vehicle in front. After it has got the value from the output of the algorithm, the LiDaR sensor will be used to calculate whether riders are in blind spot area or not. This module architecture can be seen in the figure 4.11 and 4.12.
<p align="center">
  <img width="500" height="800" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/module%202.png">
  <br>
  <em>Figure : MODULE 2 PROCESS FLOW</em>
</p><br>

<p align="center">
  <img width="800" height="500" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/arduino%20code.png">
  <br>
  <em>Figure :ARDUINO CODE</em>
</p>



Module 3 <br>
In module 3, this can be considered the easiest module compared to those 2 modules. This module will notify riders if riders are in blind spots range using the Light Emitting Diode (LED). The led will be blinking as alert to riders in their corresponding location. If rider in the infront vehicle blindspot range, both led right and left will be blinking, otherwise it would be blinking based on the detection location as shown in figure 4.13



### Project Result
<p align="center">
  <img width="478" height="233" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/right%20detection.png">
  <br>
  <em>Figure :RIGHT DETECTION</em>
</p>
<br>
<p align="center">
  <img width="478" height="233" src="https://github.com/Harith98/blind-spot-detection-tracker/blob/main/image/left%20detection.png">
  <br>
  <em>Figure :LEFT DETECTION</em>
</p>
<br><br>

### Project Demonstration

[![https://www.youtube.com/watch?v=yWrd-FL-Q_U](https://raw.githubusercontent.com/Harith98/blind-spot-detection-tracker/main/image/videopicture.PNG
)](https://www.youtube.com/watch?v=yWrd-FL-Q_U "https://www.youtube.com/watch?v=yWrd-FL-Q_U")


