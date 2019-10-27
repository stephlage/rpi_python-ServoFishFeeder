## rpi_python-ServoFishFeeder
3D Printed automatic fish feeder  + servo + Raspberry Pi

### Parts List

 - Servo Motor
 - Raspberry Pi 3 B+
 - 1k &ohm; resistor
 - 3D Printed Automated Fish Feeder from [https://www.thingiverse.com/thing:497637/files](https://www.thingiverse.com/thing:497637/files)
 
 

### Setup
1. Get your raspberry pi running with your preferred OS.  I use [https://www.raspbian.org/](https://www.raspbian.org/)
2. SSH or open the terminal to your pi.
3. `sudo apt-get updates` (updates the list of available packages and their versions)
4. `sudo apt-get upgrade` (installs the newer versions of the packages you have)
5. 

### Wiring
![raspberry pi wiring](/images/rpi_fish_feeder_bb.png)

**Common Servo Pin-out Wire Colors**

| Signal | + | - |
| :---: | :---: | :---: |
| Yellow | Red | Black |
| White| Red | Black |
| Yellow | Red | Brown |


### Want to run this at startup?

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE2ODk3MDg1MjIsLTE5NDk4MjY0NjgsMz
E2MzM3NzA0LC0xMTkwMTAyOTYxLC0yMTA4MTcwODQ3LDIxMjU1
MzkzNzksLTUyNzYzODE5NCwtMTE1NTY5NDkxOCwtODI0Nzk5OT
QwLDMzMjQ1NTkxLDE0NDM3OTU4NTIsLTE1MzYxOTM5NTUsMTI0
MDUzMzIyNF19
-->