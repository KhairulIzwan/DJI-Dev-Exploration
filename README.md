# DJI-Dev-Exploration

- DJI Developer
	- MOBILE SDK
	- UX SDK
	- [ONBOARD SDK](https://developer.dji.com/onboard-sdk/)
	- PAYLOAD SDK
	- WINDOWS SDK

# ONBOARD SDK

- Development Platform
	- LINUX
	- **[ROS](https://developer.dji.com/onboard-sdk/documentation/quickstart/development-environment.html#configure-ros-development-environment)**
	- Embedded Systems

## Configure ROS Development Environment

1. Install Development Tools
	1. [ROS](https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/#pc-setup)
	2. [DJI Onboard-SDK-ROS](https://github.com/dji-sdk/Onboard-SDK-ROS)
	
2. Install Dependent Software
	1. [DJI Onboard SDK](https://github.com/dji-sdk/Onboard-SDK)
	```
	 $ git clone https://github.com/dji-sdk/Onboard-SDK.git
	 $ cd Onboard-SDK
	 $ mkdir build
	 $ cd build
	 $ cmake ..
	 $ sudo make -j4 install
	```
	
	2. Install nema-comms
	```
	 $ sudo apt install ros-{release}-nmea-comms
	```
	
	3. [Install ACM Driver](https://github.com/jetsonhacks/installACMModule)**
	
	4. Install FFmpeg
	```
	 $ sudo apt-get install libavcodec-dev libswresample-dev
	```
	
	5. Install OpenCV 3.x
<!--- echo "# DJI-Dev-Exploration" >> README.md-->
<!--- git init-->
<!--- git add README.md-->
<!--- git commit -m "first commit"-->
<!--- git branch -M main-->
<!--- git remote add origin https://github.com/KhairulIzwan/DJI-Dev-Exploration.git-->
<!--- git push -u origin main-->
