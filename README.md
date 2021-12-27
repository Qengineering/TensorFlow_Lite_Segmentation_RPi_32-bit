# TensorFlow_Lite_Segmentation_RPi_32
![output image]( https://qengineering.eu/images/Unet_32.jpg )
## TensorFlow Lite Segmentation on a bare Raspberry Pi 32-bit OS. <br/>
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)<br/><br/>
A fast C++ implementation of TensorFlow Lite Unet on a bare Raspberry Pi 4.<br/>
Once overclocked to 1900 MHz, the app runs at 4.0 FPS!<br/>
Special made for a bare Raspberry Pi 4 see [Q-engineering deep learning examples](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html)

------------

Papers: https://arxiv.org/abs/1606.00915 <br/>
Training set: VOC2017 <br/>
Size: 257x257 <br/>

------------

## Benchmark.
Frame rate Unet Lite : 4.0 FPS (RPi 4 @ 1900 MHz - 32 bits OS) <br/>
Frame rate Unet Lite : 7.2 FPS (RPi 4 @ 1850 MHz - 64 bits OS) <br/>

------------

## Dependencies.<br/>
To run the application, you have to:
- TensorFlow Lite framework installed. [Install TensorFlow Lite](https://qengineering.eu/install-tensorflow-2-lite-on-raspberry-pi-4.html) <br/>
- OpenCV installed. [Install OpenCV 4.5](https://qengineering.eu/install-opencv-4.5-on-raspberry-pi-4.html) <br/>
- Code::Blocks installed. (```$ sudo apt-get install codeblocks```)

------------

## Installing the app.
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/TensorFlow_Lite_Segmentation_RPi_32/archive/refs/heads/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
cat.jpg.mp4 <br/>
deeplabv3_257_mv_gpu.tflite <br/>
TestUnet.cpb <br/>
Unet.cpp<br/>

------------

## Running the app.
Run TestUnet.cpb with Code::Blocks. More info or<br/> 
if you want to connect a camera to the app, follow the instructions at [Hands-On](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html#HandsOn).<br/><br/>

------------

[![paypal](https://qengineering.eu/images/TipJarSmall4.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CPZTM5BB3FCYL) 

