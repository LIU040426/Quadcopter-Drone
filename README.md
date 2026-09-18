# Quadcoater Drone

## Introduction

This is a Quadcoater Drone project.

## Hardware equipment

- F450 Framework
- Turnigy Liop Battery 3S
- SKYRC LiPro Balance Charger
- AMP 2.8.0 Fly Controller
- FS-i6 Fly remote controller
- DJI 2212/920KV brushless motor and ESC *4

## Soldering the Battery and ESC

Before we start this project, we need soldering the the battery line and the
ESC line to the bottom board of the F450 frame. The after soldering picture is shown below:

![1789746957483](images/README/1789746957483.png)

Be Careful soldering each line in a correct pad. This F450 board has the + and - label to make sure it. After that, use the multimeter to test them.

After that, connect the battery to battery line and connect the ESC and brushless motor. It is shown below:

![1789747183708](images/README/1789747183708.png)

At this moment, the Motor will have some noise. BBBBBB...

It is normal, since the noise means the power is okay and we PWM signal input. We make sure the battery connectiong is finished well.

We can use the hot glue gun to cover the exposed solder joint we make sure it is safe and enhance the connection. This step may not essential. The picture is shown below:

![1789747581715](images/README/1789747581715.png)

After that, we can test it with multimeter again and contribute the frame.

![1789747628484](images/README/1789747628484.png)






## Mission Planner


The software download link is: [Mission Planner](https://ardupilot.org/planner/docs/mission-planner-installation.html)
