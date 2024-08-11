### Arducam, and libcamera setup scripts

**Download bash scripts**
`wget -O install_pivariety_pkgs.sh https://github.com/ArduCAM/Arducam-Pivariety-V4L2-Driver/releases/download/install_script/install_pivariety_pkgs.sh`
`chmod +x install_pivariety_pkgs.sh`
**Install libcam**
`./install_pivariety_pkgs.sh -p libcamera_dev`
**Install libcam apps**
`./install_pivariety_pkgs.sh -p libcamera_apps`

### 5s preview

`libcamera-still -t 5000`

### 5s image (no preview) save as test.jpg

`libcamera-still -t 5000 -n -o test.jpg`

### Modify config file

`sudo nano /boot/firmware/config.txt`

[arducam quicstart](https://docs.arducam.com/Raspberry-Pi-Camera/Pivariety-Camera/Quick-Start-Guide/)
