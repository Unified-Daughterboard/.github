# The Unified Daughterboard Project
![banner](https://github.com/Unified-Daughterboard/.github/raw/main/banner.jpg)

## Introduction
The Unified Daughterboard Project is an open standard to unify the USB daughterboards used in custom mechanical keyboard projects.  
The USB-to-internal-cable daughterboards allows designers to easily implement electrical protection via a tested proven PCB, and allows users to maintain and repair their keyboards in the future via an open-source standard.  
  
The Unified Daughterboard integrates USB Type C connector and the needed circuitry for USB2.0 operation in a small PCB that can be screwed into a keyboard chassis; this allows for greater case design freedom and simplifies the main circuit board.

## Features

In its latest versions, the daughterboards of this project feature:

* ESD (Electrostatic Discharge) protection on the data lines of the USB connector through a specialized chip;
* Overcurrent protection through a PTC fuse;
* Overvoltage protection through a bidirectional TVS diode;
* Shielding noise decoupling capabilities through a ferrite bead;
* Single-path grounding of the metallic chassis to which the daughterboard is attached.

Adittionally, same-letter series (C1, C2, C3, etc.) are backwards compatible, allowing for upgrading daughterboards used in past projects to newer revisions.  

## Read further
Please visit our [website](https://unified-daughterboard.github.io/) for further information such as announcements, detailed information on designing around and implementing the Unified Daughterboard into a project, and production details.
