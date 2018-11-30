---
layout: single
title: Thesis
permalink: "/thesis/"

---

In this thesis a vision feedback control system is designed for the control of a micro-robot in a 2-D environment via the manipulation of a magnetic field. The magnetic field is provided by a Helmholtz coil system.

The micro-robot’s movement is tracked by a USB Webcam connected to a computer. The computer reads the position of the robot, calculates the errors made and sends the data to the Arduino which implements a PID controller and a PI controller to minimize the errors.

The system was could not be fully integrated to the existing physical coil system due to the provided contraints being mileading, and could not therefore be tested as a whole. However individual subsystems were proven to be working through various testing methods.

The full document can be viewed [here](/uploads/Thesis.pdf).

![thesis2](/uploads/thesis2.jpg)

C++ and OpenCV was utilizied to detect the motion of the micro-bot from the video obtained from the camera. This live tracking provides "path corection vector" for the micro-bot (controlled via an Arduino Mega2560 which controls the magnetic field that drives the robot).

![thesis1](/uploads/thesis.jpg)