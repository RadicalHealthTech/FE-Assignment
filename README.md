# Front End Engineer Assignment Task

In this task, you will be building a mobile smart home controller dashboard.The dashboard is demonstrated in this [video](https://github.com/RadicalHealthTech/FE-Assignment/blob/master/smart_home_controller.mp4?raw=true).

There are two screens in this UI, detailed below.

## Main Screen

This screen lets the user monitor and control four categories of devices:

1. Thermostat
2. Electrical Outlets
3. Security Cameras
4. CO<sub>2</sub> Sensors

It also shows a graph demonstrating a statistic.
Data for the graph can be obtained from [here](https://raw.githubusercontent.com/RadicalHealthTech/FE-Assignment/master/db.json?token=ACAELVMWOPXECAU3RC27T5C6Q33BM).

This document has three fields:

1. index: int - The index of the data point
2. label: str - Entity that the data is for
3. data: float - The value of the data at an index

As demonstrated in the video, we would like you to build the second screen only for the CO<sub>2</sub> Sensor.

## CO<sub>2</sub> Sensor Page

The CO<sub>2</sub> Sensor Page provides access to CO<sub>2</sub> sensors on three different floors. The speedometer-like display displays the CO<sub>2</sub> measurement as a PPM from each sensor. This can be taken as an arbitrary value for each sensor.

Any element shown in the video that has no demonstrated interaction can be put in as a placeholder.

Attached you will also find a Figma file with the appropriate color palette and font styles.

You will be judged on the following:

1. Similarity of the submitted UI with the UI in the video.
2. Fluid interactivity.
3. Smooth animations.
4. Pixel-perfect alignments and placements.
5. Development and use of modular components.

## Language for Development

Use of ReactJS is mandated for development of this assignment.

## Submission

To submit, fork this repository, finish and push your notebook on the forked repository then perform a pull request to this repository.
Deadline for the submission is Monday, 27 March 2020 11:59 PM.
