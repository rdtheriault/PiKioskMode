# PiKioskMode
Simple script to setup Raspberry Pi to boot into Kiosk mode on the chosen site

----Instructions for Install----

1. Drop Script on pi desktop.
2. Open Terminal.
3. Enter 
```
cd Desktop
sudo chmod install.sh 777
./install.sh
```
6. When asked what site to link to you can enter the URL of any site you choose to start at.
7. The script will then create necessary files in order to have pi automatically boot to selected page.


--OR--

```
sudo git clone https://github.com/JOrdanLiebe/PiKioskMode.git
cd PiKioskMode
sudo chmod +x install.sh
./install.sh
```
and steps 6 and 7 above
