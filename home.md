# Kidsbits Intelligent Traffic System Kit 

<span style="color: rgb(255, 76, 65);">**Note：The sensors and modules and the 270° servo in each project are shared.**</span>
<br>
<br>
![Img](./media/img-20230718101931.jpg)

# Downlaod 

**Downlaod project code :[download Codes](code.zip)**
**Downlaod project assembly tutorial:[download assembly](Assembly.zip)**

# Introduction:

Based on Arduino and compatible with Lego series, intelligent traffic is a kidsbits STEM project dedicated to programming education for children aged 6-9. It integrates multitudes of sensors and modules such as traffic lights, a photoresistor, a white LED, a PIR motion sensor, a 8*8 dot matrix display and an active buzzer. In this connection, it is easy for you to DIY multiple intriguing projects including street lamps, an automatic door, windshield wipers as well as an integrated traffic system.

Just as important is that Scratch graphical programming software allows children to learn from the simplest codes and master systematic programming knowledge. Meanwhile, the Lego series can be used to build various shapes and inject some basic physics and mechanical knowledge to children, thus greatly boosting their logical analysis ability, creative ability, hands-on ability and problem-solving ability.


# Kit list:
| # | Component | QTY | Picture |
| :--: | :--: | :--: |:--: |
| 1 | Kidsuno Mainboard | 1 | ![Img](./media/KidsunoMainboard.png) |
| 2 | Traffic Light Module | 1 | ![Img](./media/TrafficLightModule.png) |
| 3 | Active Buzzer | 1|![Img](./media/ActiveBuzzer.png) |
| 4 | Photoresistor |1 | ![Img](./media/Photoresistor.png) |
| 5 | White LED | 1 | ![Img](./media/WhiteLED.png) |
| 6 | PIR Motion Sensor | 1 |![Img](./media/PIRMotionSensor.png) |
| 7 | Steam Sensor | 1 |![Img](./media/SteamSensor.png) |
| 8 | Obstacle Avoidance Sensor | 1 |![Img](./media/ObstacleAvoidanceSensor.png) |
| 9 | 8×8 Dot Matrix Display | 1 |![Img](./media/88DotMatrixDisplay.png) |
| 10 | Ultrasonic Adapter | 1 |![Img](./media/UltrasonicAdapter.png) |
| 11 | Ultrasonic Sensor | 1 |![Img](./media/UltrasonicSensor.png) |
| 12 | 270° Servo | 1 |![Img](./media/270Servo.png) |
| 13 | USB Cable | 1 |![Img](./media/USBCable.png) |
| 14 | 20cm Connection Wire | 4 |![Img](./media/20cmWire.png) |
| 15 | 30cm Connection Wire | 3 | ![Img](./media/30cmWire.png) |
| 16 | Battery Holder | 1 |![Img](./media/BatteryHolder.png) |
| 17 | Traffic Lights | 1 |![Img](./media/TrafficLights.png) |
| 18 | Sound of Traffic Lights | 1 | ![Img](./media/Sound.png) |
| 19 | Street Lamps | 1 | ![Img](./media/StreetLamps.png) |
| 20 | Automatic Door | 1 |![Img](./media/AutomaticDoor.png) |
| 21 | Windshield Wipers | 1 | ![Img](./media/WindshieldWipers.png) |
| 22 | Barrier Gate | 1 |![Img](./media/BarrierGate.png) |
| 23 | Astern Indicating Device | 1 |![Img](./media/AsternIndicatingDevice.png) |
| 24 | Integrated Traffic System | 1 |![Img](./media/IntegratedTrafficSystem.png) |


# Kidsuno Mainboard Introduction

![Img](/media/Mainboard1.png)

 Introduction：
Arduino STEM electronic building block programming development controller is a board based on the ATmega328P microcontroller. It boasts 14 digital input or output pins (6 of which can be used as PWM output), 8 analog inputs (A4 and A5 as fixed I2C), two row pin ports, a USB port, a DC power port, a DC power switch, a reset button and a 128*64 OLED display.

Importantly, we enable to connect it to a computer via a USB-C cable, or use a DC adapter or batteries to power it.

 Parameters：
- Microcontroller：ATmega328P
- Operating Voltage：5V
- Input Voltage：USB:5V,DC:6-12V
- Digital I/O Pins：14(of which 6 provide PWM output
- PWM Digital I/O Pins：6
- Analog Input Pins：8（A4 and A5 as fixed I2C）
- DC Current per I/O Pin：20mA
- Flash Memory：32KB(ATmega328P)of which 0.5 KB used by bootloader
- SRAM：2KB(ATmega328P)
- EEPROM：1KB(ATmega328P)
- Total Current： The max output of USB power supply is 400mA，and DC is 1.6A
- Max Power：8W
- Clock Speed：16MHZ
- Dimensions：87.5mm×60mm×20mm
- Weight：37g(without housing)
- Operating Temperature Range：-10℃~50℃ 

 Schematic Diagram：

![Img](/media/11.png)

![Img](/media/22.png)

![Img](/media/33.png)

 Ports Description of Kidsuno Mainboard

![Img](./media/PortsDescription.png)

 Mainboard External Battery Holder

![Img](./media/Mainboardexternalbatteryholder.png)

The end of the battery holder with the spring is negative pole (-), and the other is positive pole (+). <span style="color: rgb(255, 76, 0);">(AA batteries are not provided)</span>



# Getting started with KidsBlock 

## Download KidsBlock Software

The Kidsblock, based on the Scratch graphical programming software, integrates multiple mainstream mainboards, sensors as well as modules. It can be programmed by dragging graphical blocks and using the C/C++ programming language, making programming easy and interesting for children to learn.

**Install Kidsblock Software---windows**

**[Windows system](https://www.kidsblock.cn/Down/KidsBlock.exe)**



1. Double click “KidsBlock Setup.exe”![Img](./media/123.png).

2. Click **Anyone who uses this computer(all users)** and **Next**.

![Img](./media/124.png)


3. Click **Browse（B）...** to choose the Disk where the software will be placed（<span style="color: rgb(255, 76, 65);">here, we choose C Drive</span>），then click **Install**.

![Img](./media/125.png) 

![Img](./media/126.png)


4. After a few seconds, the installation is complete. Tap **Finish** to open the installed Kidsblock software.

![Img](./media/127.png)


5. If the computer security alert window appears, click **Allow access**, the interface of the software is below:

![Img](./media/128.png)


6. Update the latest version of the KidsBlock.

![Img](./media/129.png)

We can manually update the software in the Settings.

![Img](./media/130.png)

If it is the latest version, it will display.

![Img](./media/131.png)


**Install Kidsblock Software---MacOS**


1. Download link：**[MACOS system](https://www.kidsblock.cn/Down/KidsBlock-MACOS.dmg)**

2. Double-click KidsBlock icon，then drag KidsBlock Desktop to the Applications folder.

![Img](./media/133.png)

3. It’s installing the kidsblock program on your computer.

![Img](./media/134.png)

4. After the installation is finished, you will view the KidsBlock icon.

![Img](./media/a.png)

5. Click KidsBlock software icon to start the software, it shows that it can't be opened, because the default Apple computer only allows the installation of software in the App Store, other software is not allowed to install. Thus we need to modify the computer settings to start the software.

![Img](./media/ab.png)

6. Open your computer's settings interface, click Privacy & Security, switch the security option to "App Store and identified developers", then click "Open Anyway".

![Img](./media/abc.png)

7. Tap Open.

![Img](./media/abcd.png)

8. Open the software.

![Img](./media/abcde.png)

9. It is the software interface.

![Img](./media/abcdef.png)



## How to use KidsBlock
<span style="color: rgb(255, 76, 65);">（We will demonstrate how to use KidsBlock on Windows system（MacOS can refer to it）</span>
<br>
<br>

1.Interface：

![Img](./media/135.png)

2.Click![Img](./media/136.png) to switch to different languages.

![Img](./media/137.png)

3.Tap![Img](./media/138.png) to select **Install driver**. As shown below:

![Img](./media/139.png)

A. Click **Next** at the **Device Driver Installation Wizard page**.

![Img](./media/140.png)

B. After a while, click **Finish**.

![Img](./media/141.png)

C. Then click **Next**.

![Img](./media/142.png)

D. And click **Finish**.

![Img](./media/143.png)

E. Then click **Allow** and **Install**.

![Img](./media/144.png)

F. After a while，click **Finish**.

![Img](./media/145.png)

G. Select **Extract**.

![Img](./media/146.png)

H. Click **Next**.

![Img](./media/147.png)

I. Next, click **I accept this agreement** and **Next**.

![Img](./media/148.png)

J. Click **Finish**.

![Img](./media/149.png)

K. After a while, click **INSTALL**.

![Img](./media/150.png)

O. After a few seconds, when the driver is installed, just click **OK**.

![Img](./media/151.png)

4.Click![Img](./media/152.png) to enter the main page, and select the control board needed. In this project, we select the kidsUno mainboard and click **Connect**, then it is connected. Click Go to Editor to return the code editor. 

Icon![Img](./media/153.png) will change into ![Img](./media/154.png) and ![Img](./media/155.png) will change into ![Img](./media/156.png). This means the kidsUno mainboard and ports（COM）are connected. 

![Img](./media/157.png)

![Img](./media/158.png)

![Img](./media/159.png)

![Img](./media/160.png)

5.If the kidsUno mainboard is connected , but icon![Img](./media/161.png) doesn’t change into ![Img](./media/162.png). You need to click to connect the COM port.

Click![Img](./media/163.png). Then you will find a page pop up, showing Connected.

![Img](./media/164.png)

![Img](./media/158.png)

![Img](./media/159.png)

![Img](./media/160.png)

To disconnect the port, just click![Img](./media/165.png) and Disconnect.

![Img](./media/166.png)

6.The kidsUno mainboard and the COM port are connected, then ![Img](./media/167.png) automatically switches to ![Img](./media/168.png).

![Img](./media/169.png)

![Img](./media/170.png)

<span style="color: rgb(255, 76, 65);">Note：</span>If you want to update libraries of KidsBlock, click then Clear cache and restart.

![Img](./media/171.png)

7.![Img](./media/172.png)stands for extension libraries of sensors and modules. 
Click ![Img](./media/173.png)to enter the page of extension libraries, click a sensor or module to add. For example, if click the **passive buzzer** module,**Not loaded** will change into **Loaded**. Then the passive buzzer![Img](./media/174.png) is added.

![Img](./media/175.png)

![Img](./media/176.png)

![Img](./media/177.png)

Click![Img](./media/178.png) to return to the code editor. Then you can view the passive buzzer in the blocks area.

![Img](./media/179.png)

If you want to delete the **passive buzzer**, click![Img](./media/180.png) to select the passive buzzer![Img](./media/181.png). Then **Loaded** will change into **Not loaded**. Then the passive buzzer is deleted.

![Img](./media/182.png)

![Img](./media/183.png)

The way of deleting other sensors or modules is as same as the passive buzzer.
<br>
<br>

8.How to open SB3 type files：

The first method：Double-click SB3 type files to open them.

For instance, open![Img](./media/184.png), then we need to double-click it.

![Img](./media/185.png)

The second method: Open Kidsblock，click **file** and **Load from your computer**，then select the SB3 type file on the computer.（for example![Img](./media/184.png)）

![Img](./media/186.png)

![Img](./media/187.png)

![Img](./media/185.png)

<span style="color: rgb(255, 76, 65);">Note：Please refer to the following link for MacOS：</span>
[https://kidsblocksite.readthedocs.io/en/latest/](https://kidsblocksite.readthedocs.io/en/latest/)



<span style="color: rgb(255, 76, 65);">**Note：The sensors, modules and the 270° servo in each project are shared.**</span>

# Projects

## Project 01：Traffic Lights

![Img](../media/111.png)

 Introduction

I met a big traffic jam on my way to school today. The red light at the intersection where I waited lasted very long and the green light flashed a few times and then changed to yellow. It seems that there's something wrong with the traffic light's digital signal. 

Can we use a traffic light module to simulate the working principle of traffic lights?  

Let's take a look at the tools first.


 Components

|![Img](../media/KidsunoMainboard.png)|![Img](../media/TrafficLightModule.png)|![Img](../media/ConnectionWire.png)|
| :--: | :--: | :--: |
|Kidsuno Mainboard×1|Traffic Light Module×1|Connection Wire×1|
|![Img](../media/USBCable.png)| ![Img](../media/TrafficLights.png) | |
|USB Cable×1| Traffic Lights×1 | |

![Img](../media/112.png)

 Component Knowledge
（1）Traffic lights are signal lights that command the traffic operation, which are generally composed of a red light, a green light and a yellow light. The red light means impassable, the green light means passable, and the yellow light means a warning.

（2）To keep the light on, the electricity is needed. When we say that there is electricity, we mean that there is current flowing through an electrical appliance like a light. Current comes to our home from the power station via wires. And the generator of a power station is the power supply, which enables to provide voltage and current. The battery we usually use is also the power supply. Wires can be used to conduct electricity, which connect a path for the current to flow. This path is called a circuit. If we want to make a lamp emit light, both a power supply and a complete circuit are needed.

![Img](../media/113.png)

 Installation of Traffic Lights

Please refer to the following link：https://www.dropbox.com/scl/fo/whacdlki5y44kevau03qa/h?dl=0&rlkey=ogbigsw7lxv8zhkvr1oqhlkmz

 Function: Light Up the Traffic Lights

![Img](../media/114.png)

 Wiring Diagram

Connect the kidsuno mainboard and computer via a USB cable, and connect the traffic light module to the No.1 interface of the mainboard.

![Img](../media/115.png)

 Description of the Building Blocks

![Img](../media/116.png)

Set **input** or **output** to the specified pin. **input** means input mode,**output** means output mode. Select **input-pullup** can set the input mode for the pin and make it become high level.

![Img](../media/117.png)

Set **high** or **low** to the specified pin. Select **high** means to set high level for the pin. If there is voltage and current, the LED will be on. Select **low** means to set low level for the pin. If there is no voltage and current, the LED will be off.

 Write the Program

① Drag the instruction block ![Img](../media/118.png)in the **Events** module to the script area.

![Img](../media/119.png)

② Drag the instruction block![Img](../media/120.png) in the **Pins** module to the script area and copy it twice. Since the interface of the traffic light module is connected to port 1 on the mainboard <span style="color: rgb(255, 76, 65);">(the red light is connected to D3, the yellow light is connected to D5, and the green light is connected to D6)</span>, then change the number 0 to 3, 5 and 6 and **input** to **output** respectively.

![Img](../media/121.png)

③ Drag the instruction block![Img](../media/122.png) in the **Pins** module to the script area and copy it twice. Then change the number 0 to 3, 5, and 6 respectively.

![Img](../media/123.png)

④ Complete Program

![Img](../media/124.png)


 Test Result

Click ![Img](../media/125.png) to upload the complete program to the kidsuno mainboard and power up, then the lights on the traffic light module will be on. It seems pretty amazing, right?

![Img](../media/911.png)

 Function: Make the Traffic Lights On and Off

![Img](../media/126.png)

 Description of the the Building Blocks

![Img](../media/127.png)

This is a delay block, and change the number 1 to the delayed time

 Write the Program

①  Write the program according to the knowledge learned before and refer to the last program code.

![Img](../media/128.png)

② Drag the instruction block![Img](../media/127.png) in the **Control** module to the script area. The number 1 can be changed to other numbers. Here, the number 1 is taken as an example.

![Img](../media/129.png)

③ Copy the code string![Img](../media/130.png) once and change **high** to **low**.

![Img](../media/131.png)

④ Complete Program

![Img](../media/131.png)

：Test Result 

Click ![Img](../media/125.png) to upload the complete program to the kidsuno mainboard and power up, then the lights on the traffic light module will go on and then off.

![Img](../media/912.png)

![Img](../media/913.png)


 Function of Traffic Lights 

![Img](../media/132.png)

 Flow Chart 

First set the three LED lights to off, then the red light will be on for 5 s then go off, then the yellow light will flash for 3 times then go off, then the green light will be on for 5 s then go off.

![Img](../media/133.png)

 Description of the the Building Blocks

![Img](../media/134.png)

This is a loop statement: do a same thing over and over again.

![Img](../media/135.png)

This is a conditional loop control statement and it will exit the loop  when the number of loops is met. For example, 10 means 10 cycles, and the number 10 can be changed to other numbers.

 Write the Program

① Find the instruction blocks

（1）![Img](../media/136.png)
<br>

（2）![Img](../media/137.png)
<br>

（3）![Img](../media/138.png)
<br>

② Complete Program

![Img](../media/139.png)


Test Result 

Click ![Img](../media/125.png) to upload the complete program to the kidsuno mainboard and power up, then the red light will be on for 5 s then go off, then the yellow light will flash for 3 times then go off, then the green light will be on for 5 s then go off and continue the cycle.

![Img](../media/914.png)

 Extended Project

![Img](../media/141.png)

The extended sample code is below：

![Img](../media/142.png)



<span style="color: rgb(255, 76, 65);">**Note：The sensors, modules and the 270° servo in each project are shared.**</span>

## Project 02： Sound of Traffic Lights

![Img](../media/211.png)

 Introduction

Today, I was walking home from school when I saw the traffic light beep at the intersection. Can we add a sound to the traffic light module in project 01? Let's take a look at the tools first.

 Components

|![Img](../media/KidsunoMainboard.png)|![Img](../media/TrafficLightModule.png)|![Img](../media/ActiveBuzzer.png)|
| :--: | :--: | :--: |
|Kidsuno Mainboard×1|Traffic Light Module×1|Active Buzzer×1|
|![Img](../media/ConnectionWire.png)|![Img](../media/USBCable.png)| ![Img](../media/Sound.png) |
|Connection Wire×2|USB Cable×1| Sound of Traffic Light×1 |

![Img](../media/212.png)


 Installation Steps

Please refer to the following link：https://www.dropbox.com/scl/fo/whacdlki5y44kevau03qa/h?dl=0&rlkey=ogbigsw7lxv8zhkvr1oqhlkmz

 Function: Make the Active Buzzer Sound

![Img](../media/213.png)

 Wiring Diagram
Connect the mainboard and computer via a USB cable, and connect the traffic light module to the No.1 interface of the mainboard and the active buzzer to the No.9 interface of the mainboard.

![Img](../media/214.png)

 Write the Program

① Drag the instruction block![Img](../media/215.png) in the **Events** module to the script area.

![Img](../media/216.png)

② Drag the instruction block ![Img](../media/217.png) in the **Pins** module to the script area. Since the interface of the active buzzer module is connected to the D10 pin of interface 9 on the mainboard, then change the number 0 to 10 and the **input** to **output**.

![Img](../media/218.png)

③ Drag the instruction block![Img](../media/219.png) in the **Pins** module to the script area and change the number 0 to 10.

![Img](../media/220.png)

④ Complete Program

![Img](../media/221.png)


 Test Result

Click ![Img](../media/222.png) to upload the complete program to the kidsuno mainboard and power up, then the active buzzer will sound. It seems pretty amazing, right?

![Img](../media/915.png)

 Function: Make the Active Buzzer Beep

![Img](../media/223.png)

 Write the Program

① change the **high** in the previous program to **low**.

![Img](../media/224.png)

② Drag the instruction block![Img](../media/225.png) in the "**Control**" module to the script area. 

![Img](../media/226.png)

③ Drag the instruction block![Img](../media/227.png) in the **Pins** module to the script area and change the number 0 to 10.

![Img](../media/228.png)

④ Drag the instruction block![Img](../media/229.png) in the **Control** module to the script area. The number 1 can be changed to other numbers. Here, the number 0.5 is taken as an example.

![Img](../media/230.png)

⑤ Copy the code string![Img](../media/231.png) once and change **high** to **low** .

![Img](../media/232.png)

⑥ Complete Program

![Img](../media/233.png)

 Test Result

Click ![Img](../media/222.png) to upload the complete program to the kidsuno mainboard and power up, then the active buzzer will beep. It seems pretty amazing, right?

![Img](../media/915.png)

 Function: Sound of Traffic Lights 

![Img](../media/234.png)

 Flow Chart 

First the three LED lights will be off the buzzer will not beep, then the buzzer beeps and the red light flashes for 5 s then goes off , then the yellow light flashes for 3 times then goes off, then the green light will be on for 5 s then go off.

![Img](../media/235.png)

 Write the Program

① Find the instruction blocks

（1）![Img](../media/236.png)
<br>

（2）![Img](../media/237.png)
 <br>

（3）![Img](../media/238.png)
 <br>
 
② Complete Program

![Img](../media/239.png)

 Test Result

Click ![Img](../media/222.png) to upload the complete program to the kidsuno mainboard and power up, then the buzzer beeps and the red light flashes for 5 s then it won’t beep and the light will be off , then the yellow light flashes for 3 times then goes off, then the green light will be on for 5 s then go off.

![Img](../media/916.png)

 Extended Project

![Img](../media/241.png)

The sample code is below：

![Img](../media/242.png)



## Project 03：Street Lamps

![Img](../media/311.png)

 Introduction

Street lamps are ubiquitous in our daily life. For example, some public street lamps come on automatically at night and go off automatically during the day. Do you want to know why? Let’s make a small street lamp together. 

Look at the tools first.

 Components

|![Img](../media/KidsunoMainboard.png)|![Img](../media/Photoresistor.png)|![Img](../media/WhiteLED.png)|
| :--: | :--: | :--: |
|Kidsuno Mainboard×1|Photoresistor×1|White LED Module×1|
|![Img](../media/ConnectionWire.png)|![Img](../media/USBCable.png)| ![Img](../media/StreetLamps.png) |
|Connection Wire×2|USB Cable×1| Street Lamps×1 |

![Img](../media/312.png)

 Installation Steps

Please refer to the following link：https://www.dropbox.com/scl/fo/whacdlki5y44kevau03qa/h?dl=0&rlkey=ogbigsw7lxv8zhkvr1oqhlkmz

 Function: Detect the Light Intensity 

![Img](../media/313.png)

 Wiring Diagram
Connect the kidsuno mainboard and computer via a USB cable, and connect the photoresistor to the No.7 interface of the mainboard and the LED module to the No.1 interface of the mainboard.

![Img](../media/314.png)

 Description of the the Building Blocks

![Img](../media/315.png)

The block is used to set serial baud rate(generally, the baud rate 9600 is taken as an example)

![Img](../media/316.png)

This block is used to set print mode for the serial port. **warp** means line feed printing, **no-warp** means no line feed printing, **HEX** means hexadecimal printing.

![Img](../media/317.png)

It is used to read the analog signal value of the specified pin（range：0~1023)

 Write the Program

① Drag the instruction block![Img](../media/318.png) in the **Events** module to the script area.

![Img](../media/319.png)

② Drag the instruction block![Img](../media/320.png) in the **Serial** module to the script area and take the baud rate 9600 as an example.

![Img](../media/321.png)

③ Drag the instruction block![Img](../media/322.png) in the **Pins** module to the script area. Since the photoresistor is connected to pin A0 of port 7 on the mainboard, then change the number 0 to A0.

![Img](../media/323.png)

④ Drag the instruction block ![Img](../media/324.png) in the **Control** module to the script area. 

![Img](../media/325.png)

⑤ Drag the instruction block![Img](../media/326.png) in the **Serial** module to the script area.

![Img](../media/327.png)

⑥ Drag the instruction block![Img](../media/328.png) in the **Pins** module to the script area and put it into the block ![Img](../media/329.png).

![Img](../media/330.png)

⑦ Drag the instruction block![Img](../media/331.png) in the **Control** module to the script area and change the number 1 to 0.3.

![Img](../media/332.png)

⑧ Complete Program

![Img](../media/333.png)

 Test Result

Click ![Img](../media/334.png) to upload the complete program to the kidsuno mainboard and power up, then click ![Img](../media/335.png) in the serial monitor area to set the baud rate to 9600. Then the serial monitor will print the analog value read by the photoresistor. When the light intensity in the environment where the photoresistor is located gradually decreases, the analog value increases gradually, otherwise, the analog value decreases.

![Img](../media/917.png) 

![Img](../media/analogvalue.png)

 Function: Photoresistor Controls LED

![Img](../media/336.png)


 Description of the the Building Blocks

![Img](../media/337.png)

It is a conditional statement code executing <span style="color: rgb(255, 76, 65);">if-then-else</span> function: If the logical judgment statement in ![Img](../media/338.png) is satisfied, the code statement below **then** is executed, otherwise, the code below **else** is executed.

 Flow Chart 

First, set the LED to off. When the light intensity value read by the photoresistor is less than 200, the LED will be on, otherwise, it will be off.

![Img](../media/339.png)

 Write the Program

① Find the instruction blocks

（1）![Img](../media/340.png)
<br> 

（2）![Img](../media/341.png)
<br>

（3）![Img](../media/342.png)
<br>

（4）![Img](../media/343.png)
<br>

（5）![Img](../media/344.png)
<br>

② Complete Program

![Img](../media/345.png)


 Test Result

Click ![Img](../media/334.png) to upload the complete program to the kidsuno mainboard and power up, then use your hands to cover the photoresistor . When the light intensity value read by the photoresistor is less than 200, the LED will be on, otherwise, it will be off.

![Img](./media/img-20230714083023.png)

 Extended Project

![Img](../media/346.png)

The sample code is below：

![Img](../media/347.png)




## Project 04：An Automatic Door

![Img](../media/411.png)

 Introduction

I find that there are many interesting inventions in our life. Last time I went to a library with my classmates to borrow a book about learning robots. When we came to the door, it opened automatically.

How magical it is! Today, let's make a device that can open the door automatically. 

Let’s look at the tools first.

 Components

|![Img](../media/KidsunoMainboard.png)|![Img](../media/PIRMotionSensor.png)|![Img](../media/270Servo.png)|
| :--: | :--: | :--: |
|Kidsuno Mainboard×1|PIR Motion Sensor×1|270°Servo×1|
|![Img](../media/ConnectionWire.png)|![Img](../media/USBCable.png)| ![Img](../media/AutomaticDoor.png) |
|Connection Wire×1|USB Cable×1| Automatic Door×1 |

![Img](../media/412.png)

 Function: Rotate the Servo

![Img](../media/413.png)

 Wiring Diagram

Connect the kidsuno mainboard and computer via a USB cable, and connect the servo to the G, V and D13 interface of the mainboard. The brown wire is connected to G, the red wire is connected to V and the orange wire is connected to D13.

![Img](../media/414.png)

 Add the Servo Instruction Module

![Img](../media/415.png)

![Img](../media/416.png)

Diagram of the **Extension** Instruction Block

![Img](../media/417.png)

Add **Servo**

![Img](../media/418.png)


 Description of the the Building Blocks

![Img](../media/419.png)

Set the rotation angle of the servo and the delayed time for a specified pin


 Write the Program

① Drag the instruction block![Img](../media/420.png) in the **Events** module to the script area.

![Img](../media/421.png)

② Drag the instruction block ![Img](../media/422.png) in the **Pins** module to the script area. Since the servo is connected to port G, V and D13 on the mainboard, then change the number 0 to 13 and the **input** to **output**.

![Img](../media/423.png)

③Drag the instruction block ![Img](../media/424.png) in the **servo** module to the script area, then change the number 3 to 13 and the angle number 90 to 93, the delay of 200 remains unchanged.

![Img](../media/425.png)

④ Drag the instruction block ![Img](../media/426.png) in the **Control** module to the script area.


![Img](../media/427.png)

⑤ Drag the instruction block ![Img](../media/424.png) in the **servo** module to the script area, then change the number 3 to 13, the angle number 90 to 93 and the delay of 200 to 500.

![Img](../media/428.png)

⑥ Copy the instruction block![Img](../media/429.png) 3 times in the ![Img](../media/430.png)block and place them into it, then change the angle number 93 to 62, 31 and 0.

![Img](../media/431.png)

⑦ Complete Program

![Img](../media/432.png)

 Test Result

Click ![Img](../media/433.png) to upload the complete program to the kidsuno mainboard and power up, then the servo will rotate from 93°to 62° to 31° to 0° and rotate from 0° to 31° to 62° to 93°.

 Installation Steps

Please refer to the following link：https://www.dropbox.com/scl/fo/whacdlki5y44kevau03qa/h?dl=0&rlkey=ogbigsw7lxv8zhkvr1oqhlkmz

 Wiring Diagram

Connect the kidsuno mainboard and computer via a USB cable, and connect the servo to the G, V and D13 interface of the mainboard and the PIR motion sensor to the No.1 interface of the mainboard.

The brown wire is connected to G, the red wire is connected to V and the orange wire is connected to D13.

![Img](../media/434.png)

 Function: Read the PIR Motion Sensor

![Img](../media/435.png)


 Description of the the Building Blocks

![Img](../media/436.png)

This is the digital signal (0 or 1) for a specified pin.


 Write the Program

① Drag the instruction block ![Img](../media/437.png) in the **Events** module to the script area.

![Img](../media/438.png)

② Drag the instruction block ![Img](../media/439.png) in the **Serial** module to the script area and take the baud rate 9600 as an example.

![Img](../media/440.png)

③  Drag the instruction block ![Img](../media/441.png) in the **Pins** module to the script area. Since the PIR motion sensor is connected to pin D5 of port 1 on the mainboard, then change the number 0 to 5.

![Img](../media/442.png)

④ Drag the instruction block ![Img](../media/443.png) in the **Control** module to the script area. 

![Img](../media/444.png)

⑤ Drag the instruction block ![Img](../media/445.png) in the **Serial** module to the script area.

![Img](../media/446.png)

⑥ Drag the instruction block ![Img](../media/447.png) in the **Pins** module to the script area and put it into the block ![Img](../media/448.png), then change number 0 to 5.

![Img](../media/449.png)

⑦ Drag the instruction block ![Img](../media/450.png) in the **Control** module to the script area and change the number 1 to 0.3.

![Img](../media/451.png)

⑧ Complete Program

![Img](../media/452.png)


 Test Result

Click![Img](../media/453.png) to upload the complete program to the kidsuno mainboard and power up, then click ![Img](../media/454.png) in the serial monitor area to set the baud rate to 9600. When the PIR motion sensor detects a person or animal moving, the serial monitor prints a digital signal 1, otherwise it prints 0.

![Img](../media/918.png)

![Img](../media/455.png)

 Function: PIR Motion Sensor Controls the Servo

![Img](../media/456.png)

 Flow Chart 

First, set the angle of the servo to 93°. When the PIR motion sensor detects a person or animal passing by, it will rotate to 0° and it will not rotate if no man or animal is passing by.

![Img](../media/457.png)


 Write the Program

① Find the instruction blocks

（1）![Img](../media/458.png)
<br>  

（2）![Img](../media/459.png)
<br>

（3）![Img](../media/460.png)
<br>

（4）![Img](../media/461.png)
<br>

（5）![Img](../media/462.png)
<br>

（6）![Img](../media/463.png)
<br>

② Complete Program

![Img](../media/464.png)


 Test Result

Click![Img](../media/453.png) to upload the complete program to the kidsuno mainboard and power up. When the PIR motion sensor detects a person or animal passing by, it will rotate to 0° and the door will be opened automatically , and it will not rotate if no man or animal is passing by and the door will not be opened.

![Img](../media/img-20230714083105.png)


 Extended Project

![Img](../media/465.png)

The sample code is below：

![Img](../media/466.png)




## Project 05：Windshield Wipers

![Img](../media/511.png)

 Introduction

Our family drove out for a trip at the weekend, however, it suddenly rained heavily on the way home. My father turned on the windshield wipers and the rain on the front glass of the car was constantly scraped away. Let’s explore the reason!

 Components

|![Img](../media/KidsunoMainboard.png)|![Img](../media/SteamSensor.png)|![Img](../media/270Servo.png)|
| :--: | :--: | :--: |
|Kidsuno Mainboard×1|Steam Sensor×1|270°Servo×1|
|![Img](../media/ConnectionWire.png)|![Img](../media/USBCable.png)| ![Img](../media/WindshieldWipers.png) |
|Connection Wire×1|USB Cable×1| Windshield Wipers×1 |

![Img](../media/512.png)

 Installation Steps

Please refer to the following link：https://www.dropbox.com/scl/fo/whacdlki5y44kevau03qa/h?dl=0&rlkey=ogbigsw7lxv8zhkvr1oqhlkmz


 Function: Steam Sensor Detects Water

![Img](../media/513.png)


 Wiring Diagram

Connect the kidsuno mainboard and computer via a USB cable, and connect the servo to the G, V and D13 interface of the mainboard and the steam sensor to the No.7 interface of the mainboard.
The brown wire is connected to G, the red wire is connected to V and the orange wire is connected to D13.

![Img](../media/514.png)

 Write the Program

① Drag the instruction block ![Img](../media/515.png) in the **Events** module to the script area.

![Img](../media/516.png)

② Drag the instruction block ![Img](../media/517.png) in the **Serial** module to the script area and take the baud rate 9600 as an example.

![Img](../media/518.png)

③ Drag the instruction block ![Img](../media/519.png) in the **Pins** module to the script area. Since the steam sensor is connected to pin A0 of port 7 on the mainboard, then change the number 0 to A0.

![Img](../media/520.png)

④ Drag the instruction block ![Img](../media/521.png) in the **Control** module to the script area. 

![Img](../media/522.png)

⑤ Drag the instruction block ![Img](../media/523.png) in the **Serial** module to the script area.

![Img](../media/524.png)

⑥ Drag the instruction block ![Img](../media/525.png) in the **Pins** module to the script area and put it into the block![Img](../media/526.png).

![Img](../media/527.png)

⑦ Drag the instruction block![Img](../media/528.png) in the **Control** module to the script area and change the number 1 to 0.3.

![Img](../media/529.png)

⑧ Complete Program

![Img](../media/530.png)


 Test Result

Click ![Img](../media/531.png) to upload the complete program to the kidsuno mainboard and power up, then click![Img](../media/532.png) in the serial monitor area to set the baud rate to 9600. When we drip water gradually into the metal detection area of the steam sensor, the analog number will increase gradually.

![Img](../media/533.png)


 Function: Steam Sensor Controls the Servo

![Img](../media/534.png)


 Flow Chart

First, set the angle of the servo to 0°. When the analog value of the steam  sensor is greater than 200, the servo will rotate back and forth at 0-100°, otherwise, it will not rotate and the angle of the servo will be 0°.

![Img](../media/535.png)


 Add the Servo Instruction Module

![Img](../media/536.png)


 Description of Building Blocks 

<span style="color: rgb(255, 76, 65);">This is the variable module. Let’s look at it!</span> 
<br>
<br>

There are commonly used **declare global numeric variable type integer name assigned to 0**, **variable** and **Set variable to 0** instruction squares:

![Img](../media/537.png)

When you need to use this variable, drag the block directly into the script area to edit it!

 Write the Program

① Find the instruction blocks

（1）![Img](../media/538.png)
<br> 

（2）![Img](../media/539.png)
<br>  

（3）![Img](../media/540.png)
<br>

（4）![Img](../media/541.png)
<br>

（5）![Img](../media/542.png)
<br>

（6）![Img](../media/543.png)
<br>

（7）![Img](../media/544.png)
<br>

（8）![Img](../media/545.png)
<br>

② Complete Program

![Img](../media/546.png)


 Test Result

Click![Img](../media/531.png) to upload the complete program to the kidsuno mainboard and power up. Dripping water gradually into the metal detection area of the steam sensor, if the analog value is greater than 200, the servo will rotate back and forth at 0-100° and the windshield wipers will swing, otherwise, it will not rotate and the wipers will not swing.

![Img](../media/img-20230714083149.png)

 Extended Project

![Img](../media/547.png)

The sample code is below：

![Img](../media/548.png)




## Project 06：Barrier Gate

![Img](../media/611.png)

 Introduction

Last time my dad drove me to eat seafood, however, when our car came to the barrier gate of the parking lot, the gate rose automatically, and when the car passed, it fell automatically. 

Maybe you're as curious about this device as I am, let’s make a barrier gate can automatically rise and fall together!
 
The following are the tools we need.

 Components

|![Img](../media/KidsunoMainboard.png)|![Img](../media/ObstacleAvoidanceSensor.png)|![Img](../media/270Servo.png)|
| :--: | :--: | :--: |
|Kidsuno Mainboard×1|Obstacle Avoidance Sensor×1|270°Servo×1|
|![Img](../media/ConnectionWire.png)|![Img](../media/USBCable.png)| ![Img](../media/BarrierGate.png) |
|Connection Wire×1|USB Cable×1| Barrier Gate×1 |

![Img](../media/612.png)


 Installation Steps

Please refer to the following link：https://www.dropbox.com/scl/fo/whacdlki5y44kevau03qa/h?dl=0&rlkey=ogbigsw7lxv8zhkvr1oqhlkmz


 Function: Read the Obstacle Avoidance Sensor

![Img](../media/613.png)

 Wiring Diagram

Connect the kidsuno mainboard and computer via a USB cable, and connect the servo to the G, V and D13 interface of the mainboard and the obstacle avoidance sensor to the No.1 interface of the mainboard.

<span style="color: rgb(255, 76, 65);">Note:</span> The brown wire is connected to G, the red wire is connected to V and the orange wire is connected to D13.

![Img](../media/614.png)

 Write the Program

① Drag the instruction block ![Img](../media/615.png) in the **Events** module to the script area.

![Img](../media/616.png)

② Drag the instruction block ![Img](../media/617.png) in the **Serial** module to the script area and take the baud rate 9600 as an example.

![Img](../media/618.png)

③ Drag the instruction block![Img](../media/619.png) in the **Pins** module to the script area. Since the obstacle avoidance sensor is connected to pin D5 of port 1 on the mainboard, then change the number 0 to 5.

![Img](../media/620.png)

④ Drag the instruction block ![Img](../media/621.png) in the **Control** module to the script area.

![Img](../media/622.png)

⑤ Drag the instruction block ![Img](../media/623.png) in the **Serial** module to the script area.

![Img](../media/624.png)

⑥ Drag the instruction block ![Img](../media/625.png) in the **Pins** module to the script area and put it into the block![Img](../media/626.png), then change the number 0 to 5.

![Img](../media/627.png)

⑦ Drag the instruction block ![Img](../media/628.png) in the **Control** module to the script area and change the number 1 to 0.3.

![Img](../media/629.png)

⑧ Complete Program

![Img](../media/630.png)


 Test Result

Click![Img](../media/631.png) to upload the complete program to the kidsuno mainboard and power up, then click ![Img](../media/632.png) in the serial monitor area to set the baud rate to 9600. When the obstacle avoidance sensor detects an obstacle, the serial monitor will print a digital signal 0, otherwise, it will print 1.

![Img](../media/919.png)

![Img](../media/633.png)


 Function: Obstacle Avoidance Sensor Controls the Servo

![Img](../media/634.png)


 Flow Chart 

First, set the angle of the servo to 32°. When the obstacle avoidance sensor detects an obstacle, the servo will rotate to 100°, otherwise it will not rotate.

![Img](../media/635.png)


 Add the Servo Instruction Module

![Img](../media/636.png)


 Write the Program

① Find the instruction blocks

（1）![Img](../media/637.png)
<br> 

（2）![Img](../media/638.png)
<br>

（3）![Img](../media/639.png)
<br>

（4）![Img](../media/640.png)
<br>

（5）![Img](../media/641.png)
<br>

（6）![Img](../media/642.png)
<br>

（7）![Img](../media/643.png)
<br>

（8） ![Img](../media/644.png)
<br>

② Complete Program

![Img](../media/645.png)

 Test Result

Click![Img](../media/631.png) to upload the complete program to the kidsuno mainboard and power up. When the obstacle avoidance sensor detects an obstacle, the servo will rotate to 100° and the barrier gate will open, otherwise it will not rotate and the barrier gate will close.

![Img](../media/img-20230714083213.png)



## Project 07：Astern Indicating Device

![Img](../media/711.png)

 Introduction

With the development of science and technology, cars boast the ability of intelligent environment perception, which can automatically analyze the safety and danger when driving. 

For example, we can observe the specific situation behind the car if we turn on the astern indicating device when backing up, which can avoid the car being knocked. Let’s make an astern indicating device together!
 
The following are the tools we need.

 Components

|![Img](../media/KidsunoMainboard.png)|![Img](../media/UltrasonicAdapter.png)|![Img](../media/UltrasonicSensor.png)| ![Img](../media/AsternIndicatingDevice.png) |
| :--: | :--: | :--: | :--: |
|Kidsuno Mainboard×1|Ultrasonic Adapter Board×1|Ultrasonic Sensor×1| Astern Indicating Device×1 |
|![Img](../media/88DotMatrixDisplay.png)|![Img](../media/ConnectionWire.png)|![Img](../media/USBCable.png)| |
|8×8 Dot Matrix Display×1|Connection Wire×2|USB Cable×1| |

![Img](../media/712.png)


 Installation Steps

Please refer to the following link：https://www.dropbox.com/scl/fo/whacdlki5y44kevau03qa/h?dl=0&rlkey=ogbigsw7lxv8zhkvr1oqhlkmz


 Function: 8*8 Dot Matrix Displays Expression Patterns

![Img](../media/713.png)


 Wiring Diagram

Connect the kidsuno mainboard and computer via a USB cable. Then connect the 8×8 dot matrix module to the No.8 interface of the mainboard and the ultrasonic adapter board to the No.9 interface of the mainboard. The Vcc, Trig, Echo, and Gnd of the ultrasonic sensor correspond to the same port of the ultrasonic adapter board.

![Img](../media/714.png)

 Add the Instruction Library of the 8*8 Dot Matrix

To use the 8×8 dot matrix , we need to call the "Display" module in the "Extension" function. Click "Matrix 8*8 IIC" then tap ![Img](../media/744.png) to return to the programming interface.

![Img](../media/715.png)

**Extension** Instruction 

![Img](../media/716.png)

Add **Matrix 8*8 IIC** Display                        

![Img](../media/717.png)


 Write the Program

① Drag the instruction block![Img](../media/718.png) in the **Events** module to the script area.

![Img](../media/719.png)

② Click the **Matrix HT16K33** module on the left of the instruction area, then all the 8*8 dot matrix instruction blocks will be displayed.

![Img](../media/720.png)

![Img](../media/721.png)

③ Drag the instruction block![Img](../media/722.png) and ![Img](../media/723.png) in the **Matrix HT16K33** module to the script area.

![Img](../media/724.png)

④ Drag the instruction block ![Img](../media/725.png) in the **Control** module to the script area.

![Img](../media/726.png)

⑤ Drag the instruction block![Img](../media/727.png) ,![Img](../media/728.png) and ![Img](../media/729.png) in the **Matrix HT16K33** module to the script area.

![Img](../media/730.png)

⑥ Drag the instruction block ![Img](../media/731.png) in the **Control** module to the script area and change the number 1 to 2.

![Img](../media/732.png)

⑦ Copy the instruction block![Img](../media/733.png)10 times and put them into the block ![Img](../media/734.png) respectively, then change the expression pattern ![Img](../media/735.png) to![Img](../media/736.png).

![Img](../media/737.png)

⑧ Complete Program

![Img](../media/738.png)

 Test Result

Click![Img](../media/742.png) to upload the complete program to the kidsuno mainboard and power up, then the the 8*8 dot matrix will display colorful expression patterns.

![Img](../media/920.png)

 Function：Ultrasonic Sensor Detects Distance

![Img](../media/743.png)


 Add the Instruction Library of the Ultrasonic Sensor

To use the ultrasonic sensor , we need to call the **Sensor** module in the **Extension** function. Click **Ultrasonic** then tap ![Img](../media/744.png) to return to the programming interface.

![Img](../media/745.png)

**Extension** Instruction 

![Img](../media/746.png)

Add **Ultrasonic** Sensor

![Img](../media/747.png)

 Description of the the Building Blocks

![Img](../media/748.png)

This is the ultrasonic sensor instruction block used to measure the distance for the specified pin. The distance unit can be selected as cm or inch.


 Write the Program

① Drag the instruction block in the **Events** module to the script area.

![Img](../media/749.png)

②  Drag the instruction block  in the **Serial** module to the script area and take the baud rate 9600 as an example.

![Img](../media/750.png)

③ Drag the instruction block ![Img](../media/751.png) in the **Pins** module to the script area and copy once. Since the ultrasonic sensor is connected to port 9 on the mainboard(Trig corresponds to pin D10 and Echo corresponds to pin D11), then change the number 0 to 10 and 11, and change the input behind number 10 to output.

![Img](../media/752.png)

④ Drag the instruction block ![Img](../media/753.png) in the **Control** module to the script area.

![Img](../media/754.png)

⑤ Drag the instruction block ![Img](../media/755.png) in the **Serial** module to the script area.

![Img](../media/756.png)

⑥ Drag the instruction block ![Img](../media/757.png) in the **Ultrasonic** module to the script area and put it into the block![Img](../media/758.png), then change the number 2 to 10, 6 to 11, and take the distance unit cm as an example.

![Img](../media/759.png)

⑦ Drag the instruction block ![Img](../media/760.png) in the **Control** module to the script area and change the number 1 to 0.3.

![Img](../media/761.png)

⑧ Complete Program

![Img](../media/762.png)


 Test Result

Click![Img](../media/763.png) to upload the complete program to the kidsuno mainboard and power up, then click![Img](../media/764.png) in the serial monitor area to set the baud rate to 9600.

Moving your hand in front of the ultrasonic sensor, the distance displayed becomes smaller when we are close to the sensor and larger when we are far away from it.

![Img](../media/921.png)

![Img](../media/765.png)


 Function: Ultrasonic Sensor Controls the 8*8 Dot Matrix

![Img](../media/766.png)


 Flow Chart 

Initialize the 8*8 dot matrix and read the distance value of the ultrasonic sensor. If the distance is greater than 0 and less than 10cm, the 8*8 dot matrix shows a "stop" pattern, otherwise, it displays a "backward" pattern.

![Img](../media/767.png)


 Write the Program

① Find the instruction blocks

（1）![Img](../media/768.png)
<br>

（2）![Img](../media/769.png)
<br>

（3）![Img](../media/770.png)
<br>

（4）![Img](../media/771.png)
<br>

（5）![Img](../media/772.png)
<br>

（6）![Img](../media/773.png)
<br>

（7）![Img](../media/774.png)
<br>

（8）![Img](../media/775.png)
<br>

（9）![Img](../media/776.png)
<br>

② Complete Program

![Img](../media/777.png)

 Test Result

Click![Img](../media/763.png) to upload the complete program to the kidsuno mainboard and power up. When the ultrasonic sensor detects the object within a range of 0cm to 10cm, the 8*8 dot matrix shows a "Stop" pattern, otherwise, it displays a "backward" pattern.

![Img](../media/img-20230714083256.png)


 Extended Project

![Img](../media/778.png)


The sample code is below：

![Img](../media/779.png)


## Project 08：Intelligent Integrated Traffic System

![Img](../media/811.png)

 Introduction

We have learned a host of projects before, can we put them together to make an integrated traffic system？Maybe you can't wait to do it，let’s get started!

The following are the tools we need.

 Components

|![Img](../media/KidsunoMainboard.png)|![Img](../media/TrafficLightModule.png)|![Img](../media/ActiveBuzzer.png)|![Img](../media/Photoresistor.png)|
| :--: | :--: | :--: | :--: |
|Kidsuno Mainboard×1|Traffic Light Module×1|Active Buzzer×1|Photoresistor×1|
|![Img](../media/ObstacleAvoidanceSensor.png)|![Img](../media/UltrasonicAdapter.png)|![Img](../media/UltrasonicSensor.png)|![Img](../media/88DotMatrixDisplay.png)|
|Obstacle Avoidance Sensor×1|Ultrasonic Adapter×1|Ultrasonic Sensor×1|8×8 Dot Matrix Display×1|
|![Img](/media/WhiteLED.png)|![Img](../media/270Servo.png)|![Img](../media/ConnectionWire.png)|![Img](../media/ConnectionWire.png)| 
|White LED×1|270°Servo×1|20cm Connection Wire×4|30cm Connection Wire×3| 
|![Img](../media/USBCable.png)|![Img](../media/IntegratedTrafficSystem.png) | | |
USB Cable×1|Integrated Traffic System×1 | | |

 Function: Make An Integrated Traffic System

![Img](../media/812.png)


 Installation Steps 

Please refer to the following link：https://www.dropbox.com/scl/fo/whacdlki5y44kevau03qa/h?dl=0&rlkey=ogbigsw7lxv8zhkvr1oqhlkmz

 Wiring Diagram

![Img](../media/813.png)

|Module|Kidsuno Mainboard|Module|Kidsuno Mainboard|
| :--: | :--: | :--: | :--: |
|Traffic Lights|Port 1(Red light→D3,Yellow light→D5,Green light→D6)|Active Buzzer|Port 6(D4)|
|Servo|Brown wire→G,Red wire→V,Yellow wire→D13|Obstacle Avoidance Sensor|Port 7(D8)|
|8×8 Dot Matrix|Port(5V, SDA, SCL, GND）|Photoresistor|Port 3(A3)|
|LED Module|Port 4(D2)|Ultrasonic Adapter Board|Port 9(Trig→D10, Echo→D11)|

<br>

| Ultrasonic Sensor | Ultrasonic Adapter |
| :--: | :--: |
| Vcc | VCC |
| Trig | Trig |
| Echo | Echo |
| Gnd | GND |

 Add the Servo, Ultrasonic Sensor and 8*8 Dot Matrix Instruction Module

![Img](../media/814.png)
<br>

![Img](../media/815.png)

**Extension** Instruction 
<br>

![Img](../media/816.png)

Add **Servo** Module

![Img](../media/817.png)

Add **Ultrasonic** Sensor

![Img](../media/818.png)

Add **Matrix 8*8 IIC** Display

![Img](../media/819.png)

 Flow Chart

![Img](../media/820.png)


 Write the Program

![Img](../media/821.png)

 Test Result

Click![Img](../media/822.png) to upload the complete program to the kidsuno mainboard and power up. Then the effect of the intelligent integrate traffic system will appear.

![Img](../media/img-20230714083338.png)









































































































































































































































































