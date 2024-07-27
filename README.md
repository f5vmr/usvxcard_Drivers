# usvxcard Drivers

### Install usvxcard
Get the usvxcard source code. and install all linux kernel drivers
```bash
git clone https://github.com/f5vmr/usvxcard_Drivers
cd usvxcard_Drivers
sudo ./install.sh
sudo reboot
```
It may probably happen that the driver won't compile with the latest kernel when raspbian rolls out new patches to the kernel. If so, please try `sudo ./install.sh --compat-kernel` which uses an older kernel but ensures that the driver can work. 

