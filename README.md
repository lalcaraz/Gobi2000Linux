# Gobi2000Linux
Gobi2000 drivers by Lenovo

---
## Instructions
* sudo apt-get install gobi-loader
* sudo mkdir /lib/firmware/gobi
* sudo cp ./*.mbn /lib/firmware/gobi
* sudo pkill modem-manager; sudo rmmod qcserial; sudo modprobe qcserial

