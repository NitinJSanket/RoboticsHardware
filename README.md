# RoboticsHardware
Amazing Hardware for robotics

## Table of Contents
- [CPUs + (GPUs)](#cpus)
  - [ARM based computers](#armcpus)
  - [x86 computers](#x86cpus)
- [Sensors](#sensors)
  - [Cameras](#cameras)
    - [Imaging Cameras](#imagcameras)
      - [Global Shutter Cameras](#globimagcameras)
      - [Rolling Shutter Cameras](#rollingimagcameras)
      - [RGB Cameras](#rgbd)
    - [Event cameras](#eventcameras)
  - [Distance Sensors](#dist)
  - [LIDAR](#lidar)
  - [IMUs](#imu)

 ## TODO:
 - Add Prices
 - Common Imaging Sensors


<a name="cpus"/>

## CPUs + (GPUs)

<a name="armcpus"/>

### ARM based computers

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
**Additional Notes**: [Ubuntu on iMX6 Boards](https://community.nxp.com/docs/DOC-330147). <br>



<a name="x86cpus"/>

### x86 computers <br>

###### [Intel NUC 7I7DNBE](https://www.intel.in/content/www/in/en/products/boards-kits/nuc/boards/nuc7i7dnbe.html) <br>
[<img src="Images/NUC.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: Intel Core i7 <br>
**GPU**: Intel HD Graphics <br>
**RAM**: 32GB (Max.) <br>
**ROM**: M2 Slot (Max. 1 TB) <br>
**WiFi**: On-board with antenna <br>
**Memory Expansion**: M2 Slot (Max. 1 TB) <br>
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
**Memory Expansion**: NA <br>
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

###### [AAeon Up Board](https://store.intelrealsense.com/buy-aaeon-up-board.html) <br>
[<img src="Images/AaeonUpBoard.PNG" width="480" />]() <br>
**Specifications**<br>
**CPU**: Intel Atom x5-Z8350 Processor (1.44 GHz quad core, burst up to 1.92 GHz) <br>
**GPU**: Integrated Intel HD Graphics 400 <br>
**RAM**: 4GB <br>
**ROM**: 32GB <br>
**WiFi**: With [WiFi card](https://up-shop.org/up-peripherals/153-m2-2230-wifi-kit-for-up-squared-metal-chassis.html) <br>
**Memory Expansion**: NA <br>
**Ports**: 1 USB 3.0 OTG, 4 USB 2.0, 2 USB 2.0 header, Ethernet, HDMI, CSI, DSI, 40 GPIOs <br>
**Power**: 15 W <br>
**OS**: Ubuntu 14.04, 16.04 <br>
**Dimensions**: 85.60 mm x 56.5 mm <br>
**Weight**: 120 g? <br> 
**Supported Libraries**: <br>
TensorFlow: &#9744; <br>
OpenCV 3.3: &#9744; <br>
ROS: &#9744; <br>
Webcam Support: &#9744; <br>
**Benchmarks if available**: NA <br>
**Additional Notes**: <br>

<a name="sensors"/>

## Sensors

<a name="cameras"/>

### Cameras

<a name="imagcameras"/>

#### Imaging Cameras 

<a name="globimagcameras"/>

##### Global Shutter Cameras 


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


###### [Matrix Vision mvBlueFox-MLC200wC](https://www.matrix-vision.com/USB3-vision-camera-mvbluefox3.html) <br>
[<img src="Images/mvBlueFox.PNG" width="480" />]() <br>
**Specifications**<br>
**Sensor**: ON Semiconductor MT9V <br>
**Shutter Type**: Global <br> 
**Resolution and Frame rate**: 752 x 480 at 93 fps (Max.) <br>
**Sensor Size**: 1/3" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: C/CS <br>
**Dimensions**: 35 mm x 33 mm x 25 mm <br>
**Weight**: 10 g (without lens and without enclosure) <br> 
**Additional Notes**: <br>

###### [Point Grey Flea3 e2v EV76C560](https://www.ptgrey.com/flea3-13-mp-color-usb3-vision-e2v-ev76c560-camera) <br>
[<img src="Images/Flea3.jpg" width="480" />]() <br>
**Specifications**<br>
**Sensor**: e2v EV76C560
 <br>
**Shutter Type**: Global <br> 
**Resolution and Frame rate**: 1280 x 1024 at 60 fps (Max.) <br>
**Sensor Size**: 1/1.8" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: C <br>
**Dimensions**: 29 mm x 29 mm x 30 mm <br>
**Weight**: 41 g (without lens and without enclosure) <br> 
**Additional Notes**: <br>

<a name="rollingimagcameras"/>

##### Rolling Shutter Cameras 


###### [ELP USB Camera](https://www.amazon.com/dp/B012CH5F58/ref=sspa_dk_detail_0?psc=1&pd_rd_i=B012CH5F58&pd_rd_w=C08fx&pf_rd_p=8a8f3917-7900-4ce8-ad90-adf0d53c0985&pd_rd_wg=wmekN&pf_rd_r=9BRH4KPT0RXJG111XN4V&pd_rd_r=bd919c96-6379-11e9-afd4-2da01f345a74) <br>
[<img src="Images/ELPCamera.PNG" width="480" />]() <br>
**Specifications**<br>
**Sensor**: Aptina MI5100  <br>
**Shutter Type**: Rolling <br> 
**Resolution and Frame rate**: 2592 x 1944 at 15 fps (Max.) <br>
**Sensor Size**: 1/2.5" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: M12 <br>
**Dimensions**: 38 mm x 38 mm <br>
**Weight**: 10 g (with lens) <br> 
**Additional Notes**: <br>

###### [Raspberry Pi Camera Module V2](https://www.raspberrypi.org/products/camera-module-v2/) <br>
[<img src="Images/RaspberryPiCam2.PNG" width="480" />]() <br>
**Specifications**<br>
**Sensor**: Sony IMX219  <br>
**Shutter Type**: Rolling <br> 
**Resolution and Frame rate**: 1920 x 1080 at 30 fps (Max.) <br>
**Sensor Size**: 1/4" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: M12 <br>
**Dimensions**: 25 mm x 24 mm x 9 mm <br>
**Weight**: 3 g (with lens) <br> 
**Additional Notes**: Similar Modules can be found at [ArduCam](http://www.arducam.com/). [Rolling Shutter Problems](https://www.raspberrypi.org/forums/viewtopic.php?t=177046).<br>


###### [CaliCam Fisheye Mono](https://astar.ai/collections/astar-products/products/calicam-mono) <br>
[<img src="Images/CaliCamMono.png" width="480" />]() <br>
**Specifications**<br>
**Sensor**: NA  <br>
**Shutter Type**: Rolling <br> 
**Resolution and Frame rate**: 1280 x 960 at 30 fps (Max.) <br>
**Sensor Size**: NA <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: M12 <br>
**Dimensions**: 38 mm x 38 mm <br>
**Weight**: NA (with lens) <br> 
**Additional Notes**: Pre-calibrated to less than 0.3 px RMSE. <br>


###### [CaliCam Fisheye Stereo](https://astar.ai/collections/astar-products/products/stereo-camera) <br>
[<img src="Images/CaliCamStereo.png" width="480" />]() <br>
**Specifications**<br>
**Sensor**: NA  <br>
**Shutter Type**: Rolling <br> 
**Resolution and Frame rate**: 2560 x 960 at 30 fps (Max.) <br>
**Baseline**: 120 mm <br>
**Sensor Size**: NA <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: M12 <br>
**Dimensions**: 150 mm x 30 mm <br>
**Weight**: NA (with lens) <br> 
**Additional Notes**: Pre-calibrated to less than 0.3 px RMSE. <br>

###### [Mynt Eye D](https://www.mynteye.com/pages/mynt-eye-d) <br>
[<img src="Images/MyntEyeD.PNG" width="480" />]() <br>
**Specifications**<br>
**Sensor**: NA  <br>
**Shutter Type**: Global <br> 
**Resolution and Frame rate**: 2560 x 720 at 60 fps (Max.) and Depth at 1280 x 720 at 60 fps (Max.) <br>
**Baseline**: NA <br>
**Sensor Size**: NA <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: M12 <br>
**Dimensions**: 145 mm x 20 mm x 28.6 mm<br>
**Weight**: 190 (with casing), 80 g (without casing) <br> 
**Additional Notes**: Includes an IMU as well. <br>

###### [Tara](https://www.e-consystems.com/3D-USB-stereo-camera.asp) <br>
[<img src="Images/Tara.PNG" width="480" />]() <br>
**Specifications**<br>
**Sensor**: MT9V024 <br>
**Shutter Type**: Global <br> 
**Resolution and Frame rate**: 1504 x 480 at 60 fps (Max.) <br>
**Baseline**: 60 mm <br>
**Sensor Size**: 1/3" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: M12 <br>
**Dimensions**: 145 mm x 20 mm x 28.6 mm<br>
**Weight**: 80.5 (with casing), 28.5 g (without casing) <br> 
**Additional Notes**: Includes an IMU as well. <br>

###### [Duo MLX](https://duo3d.com/product/duo-minilx-lv1) <br>
[<img src="Images/DuoMLX.PNG" width="480" />]() <br>
**Specifications**<br>
**Sensor**: NA <br>
**Shutter Type**: Global <br> 
**Resolution and Frame rate**: 1504 x 480 at 45 fps (Max.) <br>
**Baseline**: 30 mm <br>
**Sensor Size**: 1/3" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: M8 <br>
**Dimensions**: 52 mm x 25 mm x 13 mm<br>
**Weight**: 12.5 g <br> 
**Additional Notes**: Includes an IMU as well. <br>


<a name="rgbd"/>

##### RGBD Cameras 

###### [Asus Xtion Pro Live](https://www.asus.com/us/3D-Sensor/Xtion_PRO_LIVE/) <br>
[<img src="Images/Xtion.PNG" width="480" />]() <br>
**Specifications**<br>
**Depth Range**: 800 mm to 3500 mm <br>
**Resolution and Frame rate**: Images at 1280 x 1024 at 30 fps (Max.), Depth at 640 x 480 at 30 fps (Max.) <br>
**Color/Monochrome**: RGB Color <br>
**Dimensions**: 457 mm x 89 mm x 127 mm<br>
**Weight**: 540 g <br> 
**Additional Notes**: Includes microphones as well. <br>

###### [Intel RealSense D435i](https://www.intelrealsense.com/depth-camera-d435i/) <br>
[<img src="Images/RealSense.png" width="480" />]() <br>
**Specifications**<br>
**Depth Range**: 105 mm to 10000 mm <br>
**Resolution and Frame rate**: Images at 1920 x 1080 at 30 fps (Max.), Depth at 1280 x 720 at 90 fps (Max.) <br>
**Color/Monochrome**: RGB Color <br>
**Dimensions**: 99 mm x 25 mm x 25 mm<br>
**Weight**: 540 g <br> 
**Additional Notes**: Includes IMU as well. More versions available [here](https://store.intelrealsense.com/).<br>

<a name="eventcameras"/>

##### Event Cameras 

###### [DAVIS 240C](https://inivation.com/buy/) <br>
[<img src="Images/DAVIS240C.PNG" width="480" />]() <br>
**Specifications**<br>
**Imaging Shutter Type**: Global <br> 
**Resolution and Event Rate**: 240 x 180 at 12 MEPS (Max.) <br>
**Sensor Size**: 1/3" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: CS <br>
**Dimensions**: 56 mm x 62 mm x 28 mm <br>
**Weight**: 75 g (without lens) <br> 
**Additional Notes**: <br>

###### [DAVIS 346](https://inivation.com/buy/) <br>
[<img src="Images/DAVIS346.PNG" width="480" />]() <br>
**Specifications**<br>
**Imaging Shutter Type**: Global <br> 
**Resolution and Event Rate**: 346 x 260 at 12 MEPS (Max.) <br>
**Sensor Size**: 1/3.33" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: CS <br>
**Dimensions**: 40 mm x 60 mm x 25 mm <br>
**Weight**: 100 g (without lens) <br> 
**Additional Notes**: <br>

###### [Silicon Eye Rino 3.0](http://www.insightness.com/) <br>
[<img src="Images/Inightness.png" width="480" />]() <br>
**Specifications**<br>
**Imaging Shutter Type**: Global <br> 
**Resolution and Event Rate**: 320 x 262 at 40 MEPS clocked at 10KHz (Max.) <br>
**Sensor Size**: 1/3.2" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: M12 <br>
**Dimensions**: 35 mm x 35 mm x 28 mm <br>
**Weight**: 15 g (without lens) <br> 
**Additional Notes**: Includes an MPU-9250 IMU as well. Also includes event visual inertial odometry software package as well.<br>

###### [Prophesee VGA Sensor](https://www.prophesee.ai/) <br>
[<img src="Images/Prophesee.PNG" width="480" />]() <br>
**Specifications**<br>
**Imaging Shutter Type**: Global <br> 
**Resolution and Event Rate**: 640 x 480 at 40 MEPS clocked at 10KHz (Max.) <br>
**Sensor Size**: 3/4" <br>
**Color/Monochrome**: RGB Color <br>
**Lens Mount**: C <br>
**Dimensions**: 60 mm x 50 mm x 37 mm <br>
**Weight**: 146 g (with the lens) <br> 
**Additional Notes**: Includes an IMU as well. <br>

<a name="dist"/>

#### Distance Sensors

<a name="lidar"/>

#### LIDAR


- Velodyne Puck
- RP Lidar

<a name="imu"/>

#### IMUs


- Variense
- VectorNav
- InvenSense
 
