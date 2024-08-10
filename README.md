# time-lapse-exp

 This repository contains all the code that i will be utilizing in timelapse, and hyperlapse photography projects

## Computer
Rasberry pi 4 8gb

## OS

I went with Rasberry pi os (64-bit) w/desktop config to start with

## Camera
Arducam 5mp OV5647 Sensor Adjustable and Interchangeable Lens M12 Board, Focus and Angle Enhancement for Raspberry Pi 5/4/3/3 B+.

### Arducam, and libcamera setup scripts
**Download bash scripts**
`wget -O install_pivariety_pkgs.sh https://github.com/ArduCAM/Arducam-Pivariety-V4L2-Driver/releases/download/install_script/install_pivariety_pkgs.sh`
`chmod +x install_pivariety_pkgs.sh`
**Install libcam**
`./install_pivariety_pkgs.sh -p libcamera_dev`
**Install libcam apps**
`./install_pivariety_pkgs.sh -p libcamera_apps`


