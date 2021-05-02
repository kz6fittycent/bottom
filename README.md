[![bottom](https://snapcraft.io//bottom/badge.svg)](https://snapcraft.io/bottom)

# bottom
A snap for bottom

##  A cross-platform graphical process/system monitor with a customizable interface and a multitude of features. Supports Linux, macOS, and Windows. Inspired by both gtop and gotop.
  
### Install the snap:

`sudo snap install bottom`

### After installation, run the following commands so the program will run as intended:
```
- sudo snap connect bottom:mount-observe
- sudo snap connect bottom:hardware-observe
- sudo snap connect bottom:system-observe
- sudo snap connect bottom:process-control
```
  
### Check out the developer's site for more usage hints: https://github.com/ClementTsang/bottom#usage
