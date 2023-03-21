# ORANGE PI 4 LTS KLIPPER BUILD NOTES

## NOTE: Initially tried installing using debian - Klipper worked fine, but setting up the4 pi to be a secondary MCU failed as I counldnt get the gpio visible.

1. Downloaded UBUNTO (Server) Orangepi4-lts_3.0.6_ubuntu_jammy_server_linux5.18.5.img from Orange PI download page (https://drive.google.com/drive/folders/1t6n1XnacRC2HCqAAzv6CXl5UxZ0F2Gsx) 

2. Used raspberry-pi-imager to image the iso onto sd-card

- sudo apt update

3. Change hostname

- sudo vi /etc/hostname
- sudo vi /etc/hosts

4. Enable wireless

Follow instructions here https://www.linuxbabe.com/ubuntu/connect-to-wi-fi-from-terminal-on-ubuntu-18-04-19-04-with-wpa-supplicant

5. Install klipper using https://github.com/th33xitus/kiauh
 
 - sudo su
 - apt-get update
 - apt-get install git -y
 - exit (from root)
 - cd ~ && git clone https://github.com/th33xitus/kiauh.git
 
6. Run kiauh
 
 - ./kiauh/kiauh.sh
 
 Install klipper (python3) / 
 Install moonraker
 
7. Install pi secondary mcu 

as per https://www.klipper3d.org/RPi_microcontroller.html
 
**gpio pinout on orangepi - https://uthings.uniud.it/control-gpio-pins-of-orange-pi-boards**
 