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
[<img src="Images/TX2.PNG" width="480" />]() <br>
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

###### [NVIDIA Jetson Xavier](https://developer.nvidia.com/embedded/buy/jetson-agx-xavier-devkit) <br>
[<img src="Images/Xavier.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: 8-core ARM v8.2 64-bit CPU, 8MB L2 + 4MB L3 <br>
**GPU**: 512-core Volta GPU and 64 Tensor Cores <br>
**RAM**: 16GB <br>
**ROM**: 32GB <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**: Micro SD Card (Max. 32GB) <br>
**Ports**: 4 USB 2.0, Ethernet, HDMI, CSI, 40 GPIOs <br>
**Power**: 15 W <br>
**OS**: Ubuntu <br>
**Dimensions**: 105 mm x 105 mm <br>
**Weight**: 670 g? <br> 
**Supported Libraries**: <br>
TensorFlow: &#9744; <br>
OpenCV 3.3: &#9744; <br>
ROS: &#9744; <br>
Webcam Support: &#9744; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: Use [this Connect Tech carrier board](http://connecttech.com/product-category/form-factors/nvidia-jetson-agx-xavier/) <br>

###### [NVIDIA Jetson Nano](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/jetson-nano/) <br>
[<img src="Images/JetsonNano.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: Quad-core ARM A57 at 1.43 GHz <br>
**GPU**: 128 NVIDIA Maxwell Cuda Cores <br>
**RAM**: 4GB <br>
**ROM**: NA <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**: Micro SD Card (Max. 32GB) <br>
**Ports**: 4 USB 3.0, USB 2.0 Micro-B, Ethernet, HDMI, CSI, 40 GPIOs <br>
**Power**: 15 W <br>
**OS**: Ubuntu <br>
**Dimensions**: 87 mm x 59 mm <br>
**Weight**: 50 g <br> 
**Supported Libraries**: <br>
TensorFlow: &#9744; <br>
OpenCV 3.3: &#9744; <br>
ROS: &#9744; <br>
Webcam Support: &#9744; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: <br>

###### [iMX7](https://www.e-consystems.com/iMX7-som-system-on-module.asp) <br>
[<img src="Images/iMX7.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: NXP ARM Cortex A7 iMX7 at 1 GHz <br>
**GPU**: NA <br>
**RAM**: 2GB <br>
**ROM**: 4GB <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**: Micro SD Card (Max. 64GB) <br>
**Ports**: 2 USB 2.0, Ethernet, HDMI, CSI, some GPIOs <br>
**Power**: NA <br>
**OS**: Yocto Linux <br>
**Dimensions**: 105 mm x 80 mm <br>
**Weight**: NA <br> 
**Supported Libraries**: <br>
TensorFlow: &#9744; <br>
OpenCV 3.3: &#9744; <br>
ROS: &#9744; <br>
Webcam Support: &#9744; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: <br>


###### [iMX6PLUS](https://www.e-consystems.com/iMX6-quad-plus-dual-plus-core-som-system-on-module.asp) <br>
[<img src="Images/iMX6.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: NXP ARM Cortex A9 iMX6 at 1.2 GHz <br>
**GPU**: NA <br>
**RAM**: 2GB <br>
**ROM**: 8GB <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**: Micro SD Card (Max. 64GB) <br>
**Ports**: 2 USB 2.0, Ethernet, HDMI, CSI, some GPIOs <br>
**Power**: NA <br>
**OS**: Yocto Linux <br>
**Dimensions**: 70 mm x 45 mm <br>
**Weight**: NA <br> 
**Supported Libraries**: <br>
TensorFlow: &#9744; <br>
OpenCV 3.3: &#9744; <br>
ROS: &#9744; <br>
Webcam Support: &#9744; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: <br>

#### x86 computers <br>
<a name="x86cpus"/>

###### [Intel NUC 7I7DNBE](https://www.intel.in/content/www/in/en/products/boards-kits/nuc/boards/nuc7i7dnbe.html) <br>
[<img src="Images/NUC.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: Intel Core i7 <br>
**GPU**: Intel HD Graphics <br>
**RAM**: 32GB (Max.) <br>
**ROM**: M2 Slot (Max. 1 TB) <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**:  M2 Slot (Max. 1 TB) <br>
**Ports**: 4 USB 3.0, 1 USB 3.0 and 1 USB 2.0 via internal headers, Ethernet, HDMI, CSI, 40 GPIOs <br>
**Power**: 15 W <br>
**OS**: Ubuntu, Windows <br>
**Dimensions**: 101 mm x 101 mm <br>
**Weight**: 120 g? <br> 
**Supported Libraries**: <br>
TensorFlow: &#9744; <br>
OpenCV 3.3: &#9744; <br>
ROS: &#9744; <br>
Webcam Support: &#9744; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: <br>

###### [Intel Up Squared AI Vision X](https://software.intel.com/en-us/iot/hardware/up-squared-ai-vision-dev-kit) <br>
[<img src="Images/UpSquared.png" width="480" />]() <br>
**Specifications**<br>
**CPU**: Intel Atom x7-E3950 processor (1.6 GHz quad core, burst up to 2.0 GHz) <br>
**GPU**: Integrated Intel HD Graphics 505 and Movidius Myriad X <br>
**RAM**: 8GB <br>
**ROM**: 64GB <br>
**WiFi**: With [WiFi card](https://up-shop.org/up-peripherals/153-m2-2230-wifi-kit-for-up-squared-metal-chassis.html) <br>
**Memory Expansion**: Micro SD Card (Max. 32GB) <br>
**Ports**: 4 USB 2.0, Ethernet, HDMI, CSI, 40 GPIOs <br>
**Power**: 15 W <br>
**OS**: Ubuntu, Windows <br>
**Dimensions**: 101 mm x 101 mm <br>
**Weight**: 120 g? <br> 
**Supported Libraries**: <br>
TensorFlow: &#9744; <br>
OpenCV 3.3: &#9744; <br>
ROS: &#9744; <br>
Webcam Support: &#9744; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: <br>

## Sensors
<a name="sensors"/>

#### Cameras
<a name="cameras"/>

##### Imaging Cameras 
<a name="imagcameras"/>

###### [OpenMV Cam H7](https://openmv.io/products/openmv-cam-h7) <br>
[<img src="Images/OpenMVH7.PNG" width="480" />]() <br>
**Specifications**<br>
**Sensor**: ON Semiconductor MT9V034 with optional [Global Shutter upgrade](https://openmv.io/collections/cams/products/global-shutter-camera-module) <br>
**Shutter Type**: Global with upgrade <br> 
**Resolution and Frame rate**: 752 x 480 at 60 fps (Max.)  <br>
**Sensor Size**: 1/3" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: M12 <br>
**Dimensions**: 45 mm x 36 mm x 30 mm<br>
**Weight**: 19 g <br> 
**Additional Notes**: Comes with a Cortex M7 processor on-board at 400MHz, 256KB RAM and Micro SD Card support. Also supports MicroPython programming interface.<br>

###### [See3CAM_11CUG](https://www.e-consystems.com/industrial-digital-camera.asp) <br>
[<img src="Images/See3Cam11CUG.PNG" width="480" />]() <br>
**Specifications**<br>
**Sensor**: ON Semiconductor AR0134CS <br>
**Shutter Type**: Global with upgrade <br> 
**Resolution and Frame rate**: 1280 x 960 at 20 fps (Max.) Sensor supports upto 60 fps at Max. resolution. <br>
**Sensor Size**: 1/3" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: C/CS <br>
**Dimensions**: 40 mm x 44 mm <br>
**Weight**: 25 g (without lens and without enclosure) <br> 
**Additional Notes**: <br>


###### [mvBlueFox-MLC200wC](https://www.matrix-vision.com/USB3-vision-camera-mvbluefox3.html) <br>
[<img src="Images/mvBlueFox.PNG" width="480" />]() <br>
**Specifications**<br>
**Sensor**: ON Semiconductor MT9V <br>
**Shutter Type**: Global <br> 
**Resolution and Frame rate**: 752 x 480 at 93 fps (Max.) <br>
**Sensor Size**: 1/3" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: C/CS <br>
**Dimensions**: 35 mm x 33 mm xx 25 mm <br>
**Weight**: 10 g (without lens and without enclosure) <br> 
**Additional Notes**: <br>

- Global Shutter Camera
  - Point Grey
  - mvBlueFOX
- Rolling Shutter Camera
- Stereo Cameras
- RGBD cameras

##### Event Cameras 
<a name="eventcameras"/>

- IniLabs
- Professee
- Insightness


#### Distance Sensors
<a name="dist"/>

#### LIDAR
<a name="lidar"/>

- Velodyne Puck
- RP Lidar

#### IMUs
<a name="imu"/>

- Variense
- VectorNav
- InvenSense
 
