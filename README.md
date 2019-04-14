# RoboticsHardware
Amazing Hardware for robotics

## Table of Contents
- [CPUs + (GPUs)](#cpus)
  - [ARM based computers](#armcpus)
  - [x86 computers](#x86cpus)
- [Sensors](#sensors)
  - [Cameras](#cameras)
    - [Imaging Cameras](#imagcameras)
    - [Event cameras](#eventcameras)
  - [Distance Sensors](#dist)
  - [LIDAR](#lidar)
  - [IMUs](#imu)

## CPUs + (GPUs)
<a name="cpus"/>

#### ARM based computers
<a name="armcpus"/>

###### [OrangePi Zero Plus](http://www.orangepi.org/OrangePiZeroPlus/) <br>
[<img src="Images/OrangePi.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: H5 Quad-core 64-bit Cortex-A53 <br>
**GPU**: Hexa-core Mali450 <br>
**RAM**: 512MB DDR3 (shared with GPU) <br>
**ROM**: NA <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**: Micro SD Card (Max. 32GB) <br>
**Ports**: 1 USB 2.0 Host, 1 USB OTG, Ethernet, 13 GPIOs <br>
**Power**: 5 W <br>
**OS**: Ubuntu, Android <br>
**Dimensions**: 45 mm x 48 mm <br>
**Weight**: 26 g <br> 
**Supported Libraries**: <br>
TensorFlow: &#9745; <br>
OpenCV 3.3: &#9745; <br>
ROS: &#9745; <br>
Webcam Support: &#9745; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: <br>

###### [Raspberry Pi 3B+](https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/) <br>
[<img src="Images/RaspberryPi3B+.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: Broadcom BCM2837B0, Cortex-A53 (ARMv8) 64-bit SoC at 1.4GHz <br>
**GPU**: NA <br>
**RAM**: 1GB <br>
**ROM**: NA <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**: Micro SD Card (Max. 32GB) <br>
**Ports**: 4 USB 2.0, Ethernet, HDMI, CSI, DSI, 40 GPIOs <br>
**Power**: 12.5 W <br>
**OS**: Ubuntu, Android <br>
**Dimensions**: 85 mm x 49 mm <br>
**Weight**: 42 g <br> 
**Supported Libraries**: <br>
TensorFlow: &#9744; <br>
OpenCV 3.3: &#9744; <br>
ROS: &#9744; <br>
Webcam Support: &#9744; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: <br>

###### [NVIDIA Jetson TX2](https://developer.nvidia.com/embedded/buy/jetson-tx2) <br>
[<img src="Images/RaspberryPi3B+.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: Dual-core Denver 2 64-bit CPU and quad-core ARM A57 complex <br>
**GPU**: 256 NVIDIA Pascal Cuda Cores <br>
**RAM**: 8GB <br>
**ROM**: 32GB <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**: Micro SD Card (Max. 32GB) <br>
**Ports**: 4 USB 2.0, Ethernet, HDMI, CSI, 40 GPIOs <br>
**Power**: 15 W <br>
**OS**: Ubuntu <br>
**Dimensions**: 87 mm x 50 mm <br>
**Weight**: 120 g? <br> 
**Supported Libraries**: <br>
TensorFlow: &#9745; <br>
OpenCV 3.3: &#9745; <br>
ROS: &#9745; <br>
Webcam Support: &#9745; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: Use [this Connect Tech carrier board](http://connecttech.com/product/sprocket-carrier-nvidia-jetson-tx2-jetson-tx1/) <br>

###### [NVIDIA Jetson Xavier](https://developer.nvidia.com/embedded/buy/jetson-tx2) <br>
[<img src="Images/RaspberryPi3B+.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: Dual-core Denver 2 64-bit CPU and quad-core ARM A57 complex <br>
**GPU**: 256 NVIDIA Pascal Cuda Cores <br>
**RAM**: 8GB <br>
**ROM**: 32GB <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**: Micro SD Card (Max. 32GB) <br>
**Ports**: 4 USB 2.0, Ethernet, HDMI, CSI, 40 GPIOs <br>
**Power**: 15 W <br>
**OS**: Ubuntu <br>
**Dimensions**: 87 mm x 50 mm <br>
**Weight**: 120 g? <br> 
**Supported Libraries**: <br>
TensorFlow: &#9745; <br>
OpenCV 3.3: &#9745; <br>
ROS: &#9745; <br>
Webcam Support: &#9745; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: Use [this Connect Tech carrier board](http://connecttech.com/product/sprocket-carrier-nvidia-jetson-tx2-jetson-tx1/) <br>

###### [NVIDIA Jetson Nano](https://developer.nvidia.com/embedded/buy/jetson-tx2) <br>
[<img src="Images/RaspberryPi3B+.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: Dual-core Denver 2 64-bit CPU and quad-core ARM A57 complex <br>
**GPU**: 256 NVIDIA Pascal Cuda Cores <br>
**RAM**: 8GB <br>
**ROM**: 32GB <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**: Micro SD Card (Max. 32GB) <br>
**Ports**: 4 USB 2.0, Ethernet, HDMI, CSI, 40 GPIOs <br>
**Power**: 15 W <br>
**OS**: Ubuntu <br>
**Dimensions**: 87 mm x 50 mm <br>
**Weight**: 120 g? <br> 
**Supported Libraries**: <br>
TensorFlow: &#9745; <br>
OpenCV 3.3: &#9745; <br>
ROS: &#9745; <br>
Webcam Support: &#9745; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: Use [this Connect Tech carrier board](http://connecttech.com/product/sprocket-carrier-nvidia-jetson-tx2-jetson-tx1/) <br>

#### x86 computers <br>
<a name="x86cpus"/>
###### [Intel NUC](https://developer.nvidia.com/embedded/buy/jetson-tx2) <br>
[<img src="Images/RaspberryPi3B+.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: Dual-core Denver 2 64-bit CPU and quad-core ARM A57 complex <br>
**GPU**: 256 NVIDIA Pascal Cuda Cores <br>
**RAM**: 8GB <br>
**ROM**: 32GB <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**: Micro SD Card (Max. 32GB) <br>
**Ports**: 4 USB 2.0, Ethernet, HDMI, CSI, 40 GPIOs <br>
**Power**: 15 W <br>
**OS**: Ubuntu <br>
**Dimensions**: 87 mm x 50 mm <br>
**Weight**: 120 g? <br> 
**Supported Libraries**: <br>
TensorFlow: &#9745; <br>
OpenCV 3.3: &#9745; <br>
ROS: &#9745; <br>
Webcam Support: &#9745; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: Use [this Connect Tech carrier board](http://connecttech.com/product/sprocket-carrier-nvidia-jetson-tx2-jetson-tx1/) <br>

###### [Intel Up Squared](https://developer.nvidia.com/embedded/buy/jetson-tx2) <br>
[<img src="Images/RaspberryPi3B+.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: Dual-core Denver 2 64-bit CPU and quad-core ARM A57 complex <br>
**GPU**: 256 NVIDIA Pascal Cuda Cores <br>
**RAM**: 8GB <br>
**ROM**: 32GB <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**: Micro SD Card (Max. 32GB) <br>
**Ports**: 4 USB 2.0, Ethernet, HDMI, CSI, 40 GPIOs <br>
**Power**: 15 W <br>
**OS**: Ubuntu <br>
**Dimensions**: 87 mm x 50 mm <br>
**Weight**: 120 g? <br> 
**Supported Libraries**: <br>
TensorFlow: &#9745; <br>
OpenCV 3.3: &#9745; <br>
ROS: &#9745; <br>
Webcam Support: &#9745; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: Use [this Connect Tech carrier board](http://connecttech.com/product/sprocket-carrier-nvidia-jetson-tx2-jetson-tx1/) <br>

## Sensors
<a name="sensors"/>

#### Cameras
<a name="cameras"/>

##### Imaging Cameras 
<a name="imagcameras"/>

##### Event Cameras 
<a name="eventcameras"/>


#### Distance Sensors
<a name="dist"/>

#### LIDAR
<a name="lidar"/>

#### IMUs
<a name="imu"/>
 
