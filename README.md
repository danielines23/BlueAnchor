# Autonomous Docking for BlueROV Heavy

## Project Overview

This repository contains the final poster for the summer internship project completed at the Applied Physics Laboratory, University of Washington. The project focused on developing and implementing a reliable solution for autonomous docking of the BlueROV Heavy, an underwater remotely operated vehicle (ROV). The poster details the approaches used for mapping, localization, and navigation of the ROV, specifically addressing the challenges of wireless charging and data transfer in subsea environments.

## Introduction

Autonomous docking is crucial for subsea systems such as wireless charging and data transfer for ROVs. The ability to control the ROV without human intervention opens up new possibilities for underwater operations, from monitoring tidal turbines to surveying telecommunication cables. This project aimed to address one aspect of this challenge: achieving autonomous docking for the BlueROV Heavy.

## Key Components

- **Mapping and Localization Algorithms**: Developed algorithms for mapping and localization using GTSAM and trilateration techniques. 
- **SLAM Implementation**: Applied GTSAM for Simultaneous Localization and Mapping (SLAM) and used fiducial markers to enhance localization accuracy.
- **ROS Pipelines**: Built robust ROS pipelines and RViz renderings with custom launch files to support ROV spatial awareness and navigation.

## Technical Approach

The BlueROV Heavy, constrained by the compute power of a Raspberry Pi 4, required a lightweight solution for localization. The approach involved:

1. **Mapping with AprilTag Markers**: Utilized AprilTag markers to map the environment.
2. **Localization with Trilateration**: Implemented trilateration based on camera input and fiducial markers for precise localization of the ROV.

## Poster

The final poster summarizing the project and its outcomes can be found [here](BlueAnchorPoster.pdf). 

## Acknowledgments

Special thanks to the Applied Physics Laboratory at the University of Washington for the opportunity to work on this project. 

## Contact

For any questions or further information, please contact:

- **Your Name**: dal337@cornell.edu


