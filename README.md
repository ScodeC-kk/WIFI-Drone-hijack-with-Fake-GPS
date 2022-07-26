# WIFI-Drone-hijack-with-Fake-GPS
WPA2/WPA WIFI Drone hijack control by ROS with hackrf one fake GPS


### Step 

<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/step.png" width="80%"></img> 



## Getting Started
These instructions will provide you with a copy of the project running and running on your local computer for development and testing. For notes on how to deploy the project on a real-time system, see deployment.

### Set up environment 

Hardware
``` 
1. a Ubuntu 16.04 desktop (We set up in virtual machine)
2. two Wifi antenna (for the aircrack-ng)
3. a hackrf one(fakegps)
4. Drone (for testing e set up (Parrot Bebop 2,DJI Tello)
4. a server with powerful gpu (Used : pc with GTX1080 x 4 )
```


Software 
``` 
1. Ubuntu 16.04 desktop
2. Aircrack-ng (tried verison 1.5.2)
3. ROS ROS Kinetic (need to set up for each model of drone)
4. a hackrf one
5. Drone (for testing e set up (Parrot Bebop 2,DJI Tello)
6. Python3 with tkinter , ttk , threading , os , time , subprocess ,
                csv , datetime , pyautogui , string , sys , requests,
                re
7. nmap    (Parrot Bebop 2 control)
8. Mplayer (DJI tello control)
9. xdotool (DJI tello control)
10.hackrf (hackrf on drive)
11.hashcat (for the server)
```

The ros of the drone:
* Parrot Bebop 2 (https://github.com/gsilano/BebopS)
* DJI Tello      (https://github.com/hanyazou/TelloPy)

The set up will follow "/DroneControlCMD/sample.json"


The set up environment will like this


<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/setup.png" width="90%"></img> 


Please keep the server (for crack password) and the pc can communication with each other 
For the api work please keep the pc connect to the internet 

before launch software set up the "SystemInformation.txt"

```
rootPassword <Root_Password>
SSHIp <SSH_IP>
SSHUser <SSH_USER>
SSHPassword <SSH_Password>
```
## Launch the software

Launch the software:
```
python3 FYP_GUI_NoRoot.py
```

## GUI image
### Page 1
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/1.png" width="80%"></img> 
### Page 2
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/2.jpg" width="80%"></img>
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/2.1.jpg" width="80%"></img> 
### Page 3
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/3.jpg" width="80%"></img>
### Page 4
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/4.png" width="80%"></img>
### Page 5 
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/5.jpg" width="80%"></img>
### Page 6 
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/6.jpg" width="80%"></img>
### Page 7
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/7.jpg" width="80%"></img>
### Page 8 
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/8.jpg" width="80%"></img>
### Page 9 
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/9.jpg" width="80%"></img> 
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/9.1.jpg" width="80%"></img>
### Page 10 
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/10.jpg" width="80%"></img> 
<img src="https://raw.githubusercontent.com/SunnyChan-code/WIFI-Drone-hijack-with-Fake-GPS/main/README_IMAGE/page/10.1.jpg" width="80%"></img> 


## License

Distributed under the GPL-3.0 License. See `LICENSE` for more information.

## Code reference:

* "/CrackPasswdTools/hashcat-utils-master/":     https://github.com/hashcat/hashcat-utils


