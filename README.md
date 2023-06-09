# TensorFlow_Lite_SSD_RPi_32-bits
![output image]( https://qengineering.eu/images/James_17.jpg )<br/>
## TensorFlow Lite SSD running at 17 FPS on bare Raspberry Pi 4

A fast C++ implementation of TensorFlow Lite on a bare Raspberry Pi 4.
Once overclocked to 2000 MHz, the app runs an amazing 17 FPS!
Without any hardware accelerator, just you and your Pi.

https://arxiv.org/abs/1611.10012 <br/>
Training set: COCO <br/>
Size: 300x300 <br/>
Frame rate V1 Lite : 17 FPS (RPi 4 @ 2000 MHz - 32 bits OS) <br/>
Frame rate V1 Lite : 24 FPS (RPi 4 @ 1925 MHz - 64 bits OS) see https://github.com/Qengineering/TensorFlow_Lite_SSD_RPi_64-bits <br/>
<br/>
Special made for a bare Raspberry Pi see: https://qengineering.eu/install-tensorflow-2-lite-on-raspberry-pi-4.html <br/>
<br/>
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/TensorFlow_Lite_SSD_RPi_32-bits/archive/refs/heads/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
James.mp4 <br/>
COCO_labels.txt <br/>
detect.tflite <br/>
TestTensorFlow_Lite.cpb <br/>
MobileNetV1.cpp<br/>
 <br/>
Run TestTensorFlow_Lite.cpb with Code::Blocks. More info or<br/> 
if you want to connect a camera to the app, follow the instructions at [Hands-On](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html#HandsOn).<br/><br/>

See the movie at: https://youtu.be/uspw6KztkeQ

------------

[![paypal](https://qengineering.eu/images/TipJarSmall4.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CPZTM5BB3FCYL) 

