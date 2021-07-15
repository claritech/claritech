- 👋 Hi, I’m @claritech
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
claritech/claritech is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

Highlights

1. Improve speed/performance steps on IIS
 - Application pools - start mode: always running
 - Application pools - recycling: regular time interval - 0, virtual memory limit - 0
 - Application pools - process model: idle-time (mins) - 0
 
2. Website advanced settings
 - Limit connection timeout: 0


Setting up a digital wall through raspberry pi

1. pishop.co.za
2. PI4 with mini HDMI, wifi and bluetooth
3. Load PI with already loaded rasbian desktop
4. Configure PI on initial load 
5. terminal --> sudo raspi-config --> setup 1. system options --> boot login --> desktop GUI logged in as PI user
6. terminal --> sudi raspi-config --> setup 8. update
7. sudo apt-get install xdotool unclutter sed
8. sudo nano /etc/xdg/lxsession/LXDE-pi/autostart
9. sed -i 's/"exited_cleanly":false/"exited_cleanly":true/' /home/pi/.config/chromium/Default/Preferences
10. sed -i 's/"exit_type":"Crashed"/"exit_type":"Normal"/' /home/pi/.config/chromium/Default/Preferences
11. /usr/bin/chromium-browser --noerrdialogs --disable-infobars --kiosk https://www.google.com
12. sudo nano /boot/config.txt --> disable overscan
13. sudo nano /boot/config.txt --> add disable_splash=1 at the bottom
14. sudo nano /boot/cmdline.txt --> silent quiet splash loglevel=0 logo.nologo vt.global_cursor_default=0, replace console=tty1 with console=tty3 at end of line
15. Remove waste paper basket from desktop
16. Hide banner --> panel settings
17. Load background image --> right click background
18. 
