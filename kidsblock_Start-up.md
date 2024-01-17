# kidsblock Start-up
## 1. Introduction

Based on Scratch3.0, Kidsblock graphical programming is an editor with secondary development aiming to enable students to understand the fundamental concepts of programming. 

Through the comprehensive projects learning, kids will have an in-depth understanding of logical content, such as conditions, functions, linked lists, etc.. In the same breath, it can help children learn efficient problem-solving methods of thinking  (abstract, model, algorithm, decomposition) --- programming thinking.

Besides, to prevent children from focusing on the use of tools when learning, the software is combined with a graphical editor and code visualization. Languages and tools are diverse, yet programming is inter-operable. In the application of this software, the training of programming thinking is the core element. Hence, learning the way of thinking efficiently can not be limited to the tool itself, but it can pave the way for future life or for advanced programming languages.

| Hardware Support |	Programming Language Support	|Realtime Support|
|:-------------:|:---------------------:|:--------------:|
|Arduino Series		| graphical, Arduino C/C++ |		Yes		|
|Micro:bit V1/V2|	graphical, MicroPython	|		Yes		|
|ESP8266		| graphical, Arduino C/C++ |		No		|
|ESP32			| graphical, Arduino C/C++ |		Yes		|

Based on learning and application, it simplifies code through graphical building blocks to make learning and understanding much easier. What's more, source code is displayed on the right during the whole process, so you can also learn the underlying code.

In addition to graphics, it also supports Arduino and MicroPython. Common hardware support: Arduino series, Micro:bit, ESP8266, ESP32.


## 2. Download Software

* For Windows System: [xiazai.keyesrobot.cn/KidsBlock.exe](https://xiazai.keyesrobot.cn/KidsBlock.exe)
* For MAC System: [xiazai.keyesrobot.cn/KidsBlock.dmg](https://xiazai.keyesrobot.cn/KidsBlock.dmg)

Video Guidance of Installation for MAC System
Video: 

Video Guidance of Installation for Windows System
Video:

## 3. Install Driver
Click ![image-20230530152728047](media/image-20230530152728047.png) at the upper-right conner to select ![image-20230530152802530](media/image-20230530152802530.png). The commonly-used serial driver are packaged in software. 

![image-20230530152654664](media/image-20230530152654664.png)

## 4. Function Description
![image-20230530160234717](media/image-20230530160234717.png)



## 5. Commonly-used Functions
5-1 Select a Hardware
By default, the main interface is Scratch animation programming. At this time, if there is no device connected, you do not need to shift the interface, which is the same as that of Scratch3.0.

When you want to link a hardware to your computer, you need to click ![image-20230530153449783](media/image-20230530153449783.png)select one: 

![Img](media/f05df4212cf062c44ec0aa21d2091edc.png)

![Img](media/b068e878b50569da4f69cca3cd3836ba.png)

And select a corresponding serial port: 

![Img](media/91cba014b06aa8fb3806fb4522bc1122.png)

After selecting hardware, it will automatically jump to the selection of programming language and serial port (COM). Choose the one corresponding to the hardware. 

Pay attention that do not open software with multiple serial ports, otherwise you may not find port because it is occupied by other applications, and the driver will also be activated unsuccessfully.

## 5-2 Realtime Mode
In realtime mode, it integrates animation and hardware programming. When any condition is met, the animation or hardware makes the conditional action. Before that, please remember to download firmware. 

![Img](media/ac35c8e390ba36092266b86539b75ce1.png)

## 5-3 Upload Mode
In upload mode, programs can be saved in hardware to be executed. 

![Img](media/2ee4f06eb9291d8a93a625c521d0f50e.png)

Firstly we select hardware and connections (same as Realtime mode). In this mode, the matters are only about mainboard or modules, and it has nothing to do with animations. 

Generally, there are some basic functional blocks on the left bar, or you may click ![image-20230530154436545](media/image-20230530154436545.png)to extend more functions. 

![Img](media/0ef5d68cb5c84fe8f88334fc26c9a5a3.png)

Now you can choose an extension:

![Img](media/b2cc3b049e522e097f62982d692bf162.png)

When you finish a code, click **Upload**. 

At this time, please ensure that the hardware connection and logic/definition of the program are correct, otherwise it will fail to be uploaded and an error will occur during compilation.

**NOTE**: The compilation and uploading speed are impacted by the complexity of programs as well as the configuration of your computer. If the communication fails to reach hardware for a long time, it will automatically stop. Under this condition, please check the stability of the hardware.

![Img](media/c067296e8a5a0bec2f75eaad45a3412c.png)

![Img](media/e9c08b474e159b18e7941791bef5ed90.png)
