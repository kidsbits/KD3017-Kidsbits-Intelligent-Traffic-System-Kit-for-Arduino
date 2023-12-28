
# Projects

## Project 01：Traffic Lights

![Img](/media/111.png)

**Introduction**

I met a big traffic jam on my way to school today. The red light at the intersection where I waited lasted very long and the green light flashed a few times and then changed to yellow. It seems that there's something wrong with the traffic light's digital signal. 

Can we use a traffic light module to simulate the working principle of traffic lights?  

Let's take a look at the tools first.


**Components**

|![Img](/media/KidsunoMainboard.png)|![Img](/media/TrafficLightModule.png)|![Img](/media/ConnectionWire.png)|
| :--: | :--: | :--: |
|Kidsuno Mainboard×1|Traffic Light Module×1|Connection Wire×1|
|![Img](/media/USBCable.png)| ![Img](/media/TrafficLights.png) | |
|USB Cable×1| Traffic Lights×1 | |

![Img](/media/112.png)

**Component Knowledge**

（1）Traffic lights are signal lights that command the traffic operation, which are generally composed of a red light, a green light and a yellow light. The red light means impassable, the green light means passable, and the yellow light means a warning.

（2）To keep the light on, the electricity is needed. When we say that there is electricity, we mean that there is current flowing through an electrical appliance like a light. Current comes to our home from the power station via wires. And the generator of a power station is the power supply, which enables to provide voltage and current. The battery we usually use is also the power supply. Wires can be used to conduct electricity, which connect a path for the current to flow. This path is called a circuit. If we want to make a lamp emit light, both a power supply and a complete circuit are needed.

![Img](/media/113.png)


**Installation of Traffic Lights**

|      ![](media/project-1.png) |
|-------------------------------------------------------|




|![](media/a52d0f94adb27b0ed6c1c97f292ded0d.png) <br>![](media/7d6521e217111e9858b1636410419f15.jpeg) ×1 <br>![](media/58c48b663ef8534d032e05df52352a06.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|

|      ![](media/9f2bad219c48845fc7e9b8eb79f15310.jpeg) |
|-------------------------------------------------------|

| ![](media/505c99f64ce992d7bef7241264a3e50a.png) <br>![](media/4120114dea6c13ef2886f37975593af3.jpeg)  ×1 |
|------------------------------------------------------------------------------------------------------|

|        ![](media/0088ff5906b33f98d9438931db3013de.jpeg) |
|---------------------------------------------------------|

| ![](media/70a756797204b7caae989b1cf7bc30b5.png)<br> ![](media/ac96ba06672c266c1c963e3372faacbf.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|      ![](media/5ffe0388602cda38c0a7cdb25b0e264c.jpeg) |
|-------------------------------------------------------|

| ![](media/98c8f3de89f731c58b319637196e4d06.png) <br>![](media/4f5d463b2951635d9ee07c97787a8654.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|    ![](media/71b64a93ec867548a889ae447a482288.jpeg) |
|-----------------------------------------------------|

| ![](media/6937c699a26758a6add3c3adacfeb0a3.png) <br>  ![](media/af57c4fa67ab54e53421709867df2bb0.jpeg) ×1  <br>  ![](media/9624599b741be5c4dcdf55d7103d8937.jpeg) ×1 |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------|

|    ![](media/0205f61625a97b288118148872a7b83e.jpeg) |
|-----------------------------------------------------|

| ![](media/403db89c8dd755ed4a7f4065574e0b98.jpeg)<br> ![](media/365439f309d94e1845facb924e479145.jpeg)  ×1  |
|-------------------------------------------------------------------------------------------------------|

| ![](media/8abaa01eca479fe081331b09b4cdc1dd.png) <br>![](media/77a0d69f6b5bed5477a48e970dfe7b57.jpeg) ×2  <br> ![](media/0cb194ffb8daa2f2268aed63f717a17a.jpeg) ×1 <br> ![](media/a10ebea81ea144a1496473533578b1f4.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

|        ![](media/48cf1ee5333aa7ac23fed49b2e21b48a.jpeg) |
|---------------------------------------------------------|

| ![](media/484ee3c5390b0c0f353063fc83c943c3.png)<br> ![](media/fdebfd3ea175fbef23ab8f986729e1cc.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|   ![](media/1dcc1869d840c5ca3c7dde80e30aab84.jpeg) |
|----------------------------------------------------|

| ![](media/58cd66e6a8f6096291ecd68374b21e95.png) <br>![](media/d3e53bb8cfb08abd959b8469e66f3868.jpeg)  ×1 |
|------------------------------------------------------------------------------------------------------|

|    ![](media/cd9587d0da888c8c6ed86237e5fd8cff.jpeg) |
|-----------------------------------------------------|

| ![](media/5a7eae211ce688aaa6144796f86dc9a7.png) <br>![](media/78deb80c6a215df7e357c2b17fa6b476.jpeg) ×2 |
|-----------------------------------------------------------------------------------------------------|

|   ![](media/a752b951b38cb4081dde2b3ff7ecc079.jpeg) |
|----------------------------------------------------|

| ![](media/bce352d14702480bc76b965e842462b5.png) <br>![](media/7a593393f4fe45f8dee840bb63400c59.jpeg)  ×1 |
|------------------------------------------------------------------------------------------------------|

|   ![](media/b2c2f67a4f5ae3994ca7f5c5d99eb831.jpeg) |
|----------------------------------------------------|

| ![](media/d081b93a5edce25a8b34cc306adf6dbe.jpeg)  Prototype |
|-------------------------------------------------------------|

|  ![](media/af4571da6264bb068e0aa88953a8fd89.jpeg) |
|---------------------------------------------------|


 Function: Light Up the Traffic Lights

![Img](/media/114.png)

 Wiring Diagram

Connect the kidsuno mainboard and computer via a USB cable, and connect the traffic light module to the No.1 interface of the mainboard.

![Img](/media/115.png)

 Description of the Building Blocks

![Img](/media/116.png)

Set **input** or **output** to the specified pin. **input** means input mode,**output** means output mode. Select **input-pullup** can set the input mode for the pin and make it become high level.

![Img](/media/117.png)

Set **high** or **low** to the specified pin. Select **high** means to set high level for the pin. If there is voltage and current, the LED will be on. Select **low** means to set low level for the pin. If there is no voltage and current, the LED will be off.

 Write the Program

① Drag the instruction block ![Img](/media/118.png)in the **Events** module to the script area.

![Img](/media/119.png)

② Drag the instruction block![Img](/media/120.png) in the **Pins** module to the script area and copy it twice. Since the interface of the traffic light module is connected to port 1 on the mainboard <span style="color: rgb(255, 76, 65);">(the red light is connected to D3, the yellow light is connected to D5, and the green light is connected to D6)</span>, then change the number 0 to 3, 5 and 6 and **input** to **output** respectively.

![Img](/media/121.png)

③ Drag the instruction block![Img](/media/122.png) in the **Pins** module to the script area and copy it twice. Then change the number 0 to 3, 5, and 6 respectively.

![Img](/media/123.png)

④ Complete Program

![Img](/media/124.png)


 Test Result

Click ![Img](/media/125.png) to upload the complete program to the kidsuno mainboard and power up, then the lights on the traffic light module will be on. It seems pretty amazing, right?

![Img](/media/911.png)

 Function: Make the Traffic Lights On and Off

![Img](/media/126.png)

 Description of the the Building Blocks

![Img](/media/127.png)

This is a delay block, and change the number 1 to the delayed time

 Write the Program

①  Write the program according to the knowledge learned before and refer to the last program code.

![Img](/media/128.png)

② Drag the instruction block![Img](/media/127.png) in the **Control** module to the script area. The number 1 can be changed to other numbers. Here, the number 1 is taken as an example.

![Img](/media/129.png)

③ Copy the code string![Img](/media/130.png) once and change **high** to **low**.

![Img](/media/131.png)

④ Complete Program

![Img](/media/131.png)

：Test Result 

Click ![Img](/media/125.png) to upload the complete program to the kidsuno mainboard and power up, then the lights on the traffic light module will go on and then off.

![Img](/media/912.png)

![Img](/media/913.png)


 Function of Traffic Lights 

![Img](/media/132.png)

 Flow Chart 

First set the three LED lights to off, then the red light will be on for 5 s then go off, then the yellow light will flash for 3 times then go off, then the green light will be on for 5 s then go off.

![Img](/media/133.png)

 Description of the the Building Blocks

![Img](/media/134.png)

This is a loop statement: do a same thing over and over again.

![Img](/media/135.png)

This is a conditional loop control statement and it will exit the loop  when the number of loops is met. For example, 10 means 10 cycles, and the number 10 can be changed to other numbers.

 Write the Program

① Find the instruction blocks

（1）![Img](/media/136.png)
<br>

（2）![Img](/media/137.png)
<br>

（3）![Img](/media/138.png)
<br>

② Complete Program

![Img](/media/139.png)


Test Result 

Click ![Img](/media/125.png) to upload the complete program to the kidsuno mainboard and power up, then the red light will be on for 5 s then go off, then the yellow light will flash for 3 times then go off, then the green light will be on for 5 s then go off and continue the cycle.

![Img](/media/914.png)

 Extended Project

![Img](/media/141.png)

The extended sample code is below：

![Img](/media/142.png)



<span style="color: rgb(255, 76, 65);">**Note：The sensors, modules and the 270° servo in each project are shared.**</span>

## Project 02： Sound of Traffic Lights

![Img](/media/211.png)

 Introduction

Today, I was walking home from school when I saw the traffic light beep at the intersection. Can we add a sound to the traffic light module in project 01? Let's take a look at the tools first.

 Components

|![Img](/media/KidsunoMainboard.png)|![Img](/media/TrafficLightModule.png)|![Img](/media/ActiveBuzzer.png)|
| :--: | :--: | :--: |
|Kidsuno Mainboard×1|Traffic Light Module×1|Active Buzzer×1|
|![Img](/media/ConnectionWire.png)|![Img](/media/USBCable.png)| ![Img](/media/Sound.png) |
|Connection Wire×2|USB Cable×1| Sound of Traffic Light×1 |

![Img](/media/212.png)


 Installation Steps

Components

Note: The color of the building blocks is subject to the actual object.



|      ![](media/project-2.png) |
|------------------------------------------------------------|

| ![](media/ec4291050c6c3f9a708056422f2025b3.png) <br>![](media/c03623ead395dfe74cf0ceb7d3d1c4c2.jpeg) ×1   <br>   ![](media/a96bde5a35869dfb5d18a780e1e85d45.jpeg)  ×1 |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------|

|           ![](media/aba5e515321fe40bc6c33814c9ed6d1b.jpeg) |
|------------------------------------------------------------|

| ![](media/fe6d4b1d05aaabd2f00b30b76a72dead.png) <br>![](media/3ccead0e3bb98c302477d2270f125b55.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|       ![](media/32aaf7dc11dfe6ca053ca3eac990c934.jpeg) |
|--------------------------------------------------------|

| ![](media/31a4c36a751f97cc3e35ec7c41c0bc9d.png)<br>![](media/4f777e87f5f387b9d129d5770fb45d97.jpeg) ×1 |
|----------------------------------------------------------------------------------------------------|

|       ![](media/d34a1900a19b3cb1a97e87ab6264c0cc.jpeg) |
|--------------------------------------------------------|

| ![](media/2eedd5e9f752e3ea14dc6c2c84ee6838.png) <br> ![](media/a0f9b0160ed1cd56bfeca047d5424818.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------|

|    ![](media/cb6de4674551e6c2b20c783379016ee0.jpeg) |
|-----------------------------------------------------|

| ![](media/a48f6f55608b67b3aafc23ccfe250967.png)<br> ![](media/55d6f9e8ee7f73650c294de74dc8d573.jpeg) ×1   <br>  ![](media/af9cc209a9c0a68c78d4aac83e92d333.jpeg) ×2 |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------|

|    ![](media/93529f1b3f1ebe6f3e7b998434e0e4c6.jpeg) |
|-----------------------------------------------------|

| ![](media/2fb3f90c25df6077bfd16776762c241e.jpeg)<br> ![](media/a8b04a69f84a52b5bcf0eca8db8dcce0.jpeg) ×1  <br> ![](media/23db29ea57a7b691e70f9349932735cb.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|

|      ![](media/14e68cec74109a84d0a4a3ffc218a058.jpeg) |
|-------------------------------------------------------|

| ![](media/1af78ce2e63583156aade9c3aea79cd0.jpeg)   <br>   ![](media/ba70d14176438e70bb5b807b51ea387b.jpeg)1\*8（63mm） ×1  |
|------------------------------------------------------------------------------------------------------------------------|

|    ![](media/62900253aefcc2081c56adc8edcfca75.jpeg) |
|-----------------------------------------------------|

|![](media/acf3f532e69e898ec9e03cf1b0ebf1ac.jpeg)<br>![](media/4a119000ae583d73ba7bb697d7cc91da.jpeg)<br>![](media/9716f24241f995b2e3fead89608526fa.jpeg)×1 <br>![](media/bd6d03023425eb1f839e968a84aede18.jpeg) ×1|
|--------------------------------------------------------------------------------| 

|    ![](media/16d9b31553e70c8a0941412c3eb1f25e.jpeg) |
|-----------------------------------------------------|

| ![](media/b7365d1559f136c61914cc4ce33fbe12.png) <br> ![](media/6cd6009474cc1f9ba3af277e63213a2e.jpeg) ×2 |
|------------------------------------------------------------------------------------------------------|

|    ![](media/d03e5a5468af6c639542fb4df7540c6d.jpeg) |
|-----------------------------------------------------|

| ![](media/8636a47e46cc8edd8f9c6c41f35f144d.jpeg) <br> ![](media/a18be8ec32af701c113aa17e8678fa8d.png) ×1 |                |
|------------------------------------------------------------------------------------------------------|----------------|

|      ![](media/1dad0ba0375cbb260d3e4c9fd34ca4d8.jpeg) |
|-------------------------------------------------------|

| ![](media/40227e2a62e9161a38ca35e42939da67.png)  <br>  ![](media/db39f4f1bcb7d8d718a1540e53b44149.jpeg) ×2 |
|--------------------------------------------------------------------------------------------------------|

|    ![](media/5ac7ec24bf7415031b722a1474f15abb.jpeg) |
|-----------------------------------------------------|

| ![](media/9d8f9086c01609b0b803dfd365d11f55.png)<br> ![](media/feeaf02e8071c5648236da3706841af5.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|   ![](media/10ac28d495bf3d8c214ab4628accb2cc.jpeg) |
|----------------------------------------------------|

| ![](media/c7876e56bbe2982a4361bb4ccf237c6a.png) <br> ![](media/7be070cad94d9bc75559cbc94ced3bbd.jpeg) ×2 |
|------------------------------------------------------------------------------------------------------|

|   ![](media/2fec6093c8af78d38216f91d738256ac.jpeg) |
|----------------------------------------------------|

|  ![](media/bdb2957c3dac8f31eb880d03ceccfb08.png) |
|--------------------------------------------------|

|   ![](media/12d29b7b1af65861b8d0161733ada378.jpeg) |
|----------------------------------------------------|

| ![](media/7ea27fb24d2dfa14877a189f1902e66b.jpeg)   Prototype |
|--------------------------------------------------------------|

|  ![](media/33afd55332295037eb480bd82ade0606.jpeg) |
|---------------------------------------------------|

 Function: Make the Active Buzzer Sound

![Img](/media/213.png)

 Wiring Diagram
Connect the mainboard and computer via a USB cable, and connect the traffic light module to the No.1 interface of the mainboard and the active buzzer to the No.9 interface of the mainboard.

![Img](/media/214.png)

 Write the Program

① Drag the instruction block![Img](/media/215.png) in the **Events** module to the script area.

![Img](/media/216.png)

② Drag the instruction block ![Img](/media/217.png) in the **Pins** module to the script area. Since the interface of the active buzzer module is connected to the D10 pin of interface 9 on the mainboard, then change the number 0 to 10 and the **input** to **output**.

![Img](/media/218.png)

③ Drag the instruction block![Img](/media/219.png) in the **Pins** module to the script area and change the number 0 to 10.

![Img](/media/220.png)

④ Complete Program

![Img](/media/221.png)


 Test Result

Click ![Img](/media/222.png) to upload the complete program to the kidsuno mainboard and power up, then the active buzzer will sound. It seems pretty amazing, right?

![Img](/media/915.png)

 Function: Make the Active Buzzer Beep

![Img](/media/223.png)

 Write the Program

① change the **high** in the previous program to **low**.

![Img](/media/224.png)

② Drag the instruction block![Img](/media/225.png) in the "**Control**" module to the script area. 

![Img](/media/226.png)

③ Drag the instruction block![Img](/media/227.png) in the **Pins** module to the script area and change the number 0 to 10.

![Img](/media/228.png)

④ Drag the instruction block![Img](/media/229.png) in the **Control** module to the script area. The number 1 can be changed to other numbers. Here, the number 0.5 is taken as an example.

![Img](/media/230.png)

⑤ Copy the code string![Img](/media/231.png) once and change **high** to **low** .

![Img](/media/232.png)

⑥ Complete Program

![Img](/media/233.png)

 Test Result

Click ![Img](/media/222.png) to upload the complete program to the kidsuno mainboard and power up, then the active buzzer will beep. It seems pretty amazing, right?

![Img](/media/915.png)

 Function: Sound of Traffic Lights 

![Img](/media/234.png)

 Flow Chart 

First the three LED lights will be off the buzzer will not beep, then the buzzer beeps and the red light flashes for 5 s then goes off , then the yellow light flashes for 3 times then goes off, then the green light will be on for 5 s then go off.

![Img](/media/235.png)

 Write the Program

① Find the instruction blocks

（1）![Img](/media/236.png)
<br>

（2）![Img](/media/237.png)
 <br>

（3）![Img](/media/238.png)
 <br>
 
② Complete Program

![Img](/media/239.png)

 Test Result

Click ![Img](/media/222.png) to upload the complete program to the kidsuno mainboard and power up, then the buzzer beeps and the red light flashes for 5 s then it won’t beep and the light will be off , then the yellow light flashes for 3 times then goes off, then the green light will be on for 5 s then go off.

![Img](/media/916.png)

 Extended Project

![Img](/media/241.png)

The sample code is below：

![Img](/media/242.png)



## Project 03：Street Lamps

![Img](/media/311.png)

 Introduction

Street lamps are ubiquitous in our daily life. For example, some public street lamps come on automatically at night and go off automatically during the day. Do you want to know why? Let’s make a small street lamp together. 

Look at the tools first.

 Components

|![Img](/media/KidsunoMainboard.png)|![Img](/media/Photoresistor.png)|![Img](/media/WhiteLED.png)|
| :--: | :--: | :--: |
|Kidsuno Mainboard×1|Photoresistor×1|White LED Module×1|
|![Img](/media/ConnectionWire.png)|![Img](/media/USBCable.png)| ![Img](/media/StreetLamps.png) |
|Connection Wire×2|USB Cable×1| Street Lamps×1 |

![Img](/media/312.png)

 Installation Steps

Components

Note: The color of the building blocks is

subject to the actual object.

|        ![](media/project-3.png) |
|---------------------------------------------------------|

| ![](media/fb5b77c998a8518c47cf4c95900e990c.png) <br>![](media/a5f3cb3e8cbb5c304bc30db918f6edd8.png) ×1 <br>   ![](media/35314b973941fa92189d66d555f52648.png) ×1 |
|----------------------------------------------------------------------------------------------------------------------------------------------------------|

|        ![](media/9485cfa22a35896d10e3a515616bd963.jpeg) |
|---------------------------------------------------------|

| ![](media/8f5d9f5f74b7cb55cccf52560175e98b.png) <br> ![](media/fdbc8e7dc368c0796037515d49caa32f.jpeg)  ×1 |
|-------------------------------------------------------------------------------------------------------|

|      ![](media/dafed459f81738ab328f23d340d13088.jpeg) |
|-------------------------------------------------------|

| ![](media/21364ef26a4ee64c77f5022992f87760.png) <br>![](media/5c246ad6b8d034627386927af5b734c2.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|     ![](media/b7265f49925f6b96833ea39996d6e722.jpeg) |
|------------------------------------------------------|

| ![](media/8c5979fe01ba2c228c8e82e8e162302a.png) <br>![](media/785ff4c57b29c4b980f22669b128aa36.jpeg)  ×1 |
|------------------------------------------------------------------------------------------------------|

|     ![](media/528ca6518879394e091b254a30a9fadb.jpeg) |
|------------------------------------------------------|

| ![](media/fde04b8c2cba9b40f337461f1c14e3fd.jpeg)<br> ![](media/31198c775405eb82c9702012a2df8d9a.jpeg) ×2  <br>   ![](media/c177393b1648eb1fca3dd26c6d821a9b.jpeg) ×1 |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------|

|  ![](media/7a43800a8d7072f65caaa9cfacd11495.jpeg) |
|---------------------------------------------------|

| ![](media/9b984da1cd1cceac48651416e5e844a4.png)<br>![](media/c99cfacd8b16da5cdc07c2680ede3634.jpeg)  ×1 |
|-----------------------------------------------------------------------------------------------------|

|  ![](media/021c548a2b58206eba19dfec0d608c11.jpeg) |
|---------------------------------------------------|

| ![](media/0838349902d5ef618dfde7cac45d69c8.png) <br>![](media/5654c47e4aa17186672abe3066fb1f81.jpeg) ×2 |
|-----------------------------------------------------------------------------------------------------|

|  ![](media/b5fbeaf454388ea05a53cdf1f884d1b9.jpeg) |
|---------------------------------------------------|

| ![](media/31ab5c9cb2e77e8fd5aa2df36c2c0a7a.png)<br> ![](media/f7add9c151fdfe4cdb5a78896e94f07d.jpeg) ×2 |
|-----------------------------------------------------------------------------------------------------|

|    ![](media/ab046e5c539b907a57402ffd3680989c.jpeg) |
|-----------------------------------------------------|

| ![](media/a965d77cdbd350503d2f381eb7a205ad.png) <br> ![](media/df56a2da68572acf8613e52537b666f3.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------|

|   ![](media/7e476a467be617c9d6f5bd35d8b6fd3c.jpeg) |
|----------------------------------------------------|

| ![](media/12445c73396d798ded8de4a9d09f87bf.png) <br> ![](media/f7add9c151fdfe4cdb5a78896e94f07d.jpeg) ×2 |
|------------------------------------------------------------------------------------------------------|

|   ![](media/099af1a6b15d01aa1641076164da6a3b.jpeg) |
|----------------------------------------------------|

| ![](media/1743c01afe1dea35cba31254085c8816.png)<br>![](media/718815bd3cd0ef64025c4b0a65ba2f83.jpeg) ×1 |
|----------------------------------------------------------------------------------------------------|

|     ![](media/c9b1ef96331ad1b037bf2247cea5f6d9.jpeg) |
|------------------------------------------------------|

| ![](media/a3cb3875d6627a5ba7acec76e566360e.jpeg)  Prototype |
|-------------------------------------------------------------|

|   ![](media/b43a175675b949bcefe84ea3fe5a79f9.jpeg) |
|----------------------------------------------------|

 Function: Detect the Light Intensity 

![Img](/media/313.png)

 Wiring Diagram
Connect the kidsuno mainboard and computer via a USB cable, and connect the photoresistor to the No.7 interface of the mainboard and the LED module to the No.1 interface of the mainboard.

![Img](/media/314.png)

 Description of the the Building Blocks

![Img](/media/315.png)

The block is used to set serial baud rate(generally, the baud rate 9600 is taken as an example)

![Img](/media/316.png)

This block is used to set print mode for the serial port. **warp** means line feed printing, **no-warp** means no line feed printing, **HEX** means hexadecimal printing.

![Img](/media/317.png)

It is used to read the analog signal value of the specified pin（range：0~1023)

 Write the Program

① Drag the instruction block![Img](/media/318.png) in the **Events** module to the script area.

![Img](/media/319.png)

② Drag the instruction block![Img](/media/320.png) in the **Serial** module to the script area and take the baud rate 9600 as an example.

![Img](/media/321.png)

③ Drag the instruction block![Img](/media/322.png) in the **Pins** module to the script area. Since the photoresistor is connected to pin A0 of port 7 on the mainboard, then change the number 0 to A0.

![Img](/media/323.png)

④ Drag the instruction block ![Img](/media/324.png) in the **Control** module to the script area. 

![Img](/media/325.png)

⑤ Drag the instruction block![Img](/media/326.png) in the **Serial** module to the script area.

![Img](/media/327.png)

⑥ Drag the instruction block![Img](/media/328.png) in the **Pins** module to the script area and put it into the block ![Img](/media/329.png).

![Img](/media/330.png)

⑦ Drag the instruction block![Img](/media/331.png) in the **Control** module to the script area and change the number 1 to 0.3.

![Img](/media/332.png)

⑧ Complete Program

![Img](/media/333.png)

 Test Result

Click ![Img](/media/334.png) to upload the complete program to the kidsuno mainboard and power up, then click ![Img](/media/335.png) in the serial monitor area to set the baud rate to 9600. Then the serial monitor will print the analog value read by the photoresistor. When the light intensity in the environment where the photoresistor is located gradually decreases, the analog value increases gradually, otherwise, the analog value decreases.

![Img](/media/917.png) 

![Img](/media/analogvalue.png)

 Function: Photoresistor Controls LED

![Img](/media/336.png)


 Description of the the Building Blocks

![Img](/media/337.png)

It is a conditional statement code executing <span style="color: rgb(255, 76, 65);">if-then-else</span> function: If the logical judgment statement in ![Img](/media/338.png) is satisfied, the code statement below **then** is executed, otherwise, the code below **else** is executed.

 Flow Chart 

First, set the LED to off. When the light intensity value read by the photoresistor is less than 200, the LED will be on, otherwise, it will be off.

![Img](/media/339.png)

 Write the Program

① Find the instruction blocks

（1）![Img](/media/340.png)
<br> 

（2）![Img](/media/341.png)
<br>

（3）![Img](/media/342.png)
<br>

（4）![Img](/media/343.png)
<br>

（5）![Img](/media/344.png)
<br>

② Complete Program

![Img](/media/345.png)


 Test Result

Click ![Img](/media/334.png) to upload the complete program to the kidsuno mainboard and power up, then use your hands to cover the photoresistor . When the light intensity value read by the photoresistor is less than 200, the LED will be on, otherwise, it will be off.

![Img](./media/img-20230714083023.png)

 Extended Project

![Img](/media/346.png)

The sample code is below：

![Img](/media/347.png)




## Project 04：An Automatic Door

![Img](/media/411.png)

 Introduction

I find that there are many interesting inventions in our life. Last time I went to a library with my classmates to borrow a book about learning robots. When we came to the door, it opened automatically.

How magical it is! Today, let's make a device that can open the door automatically. 

Let’s look at the tools first.

 Components

|![Img](/media/KidsunoMainboard.png)|![Img](/media/PIRMotionSensor.png)|![Img](/media/270Servo.png)|
| :--: | :--: | :--: |
|Kidsuno Mainboard×1|PIR Motion Sensor×1|270°Servo×1|
|![Img](/media/ConnectionWire.png)|![Img](/media/USBCable.png)| ![Img](/media/AutomaticDoor.png) |
|Connection Wire×1|USB Cable×1| Automatic Door×1 |

![Img](/media/412.png)

 Function: Rotate the Servo

![Img](/media/413.png)

 Wiring Diagram

Connect the kidsuno mainboard and computer via a USB cable, and connect the servo to the G, V and D13 interface of the mainboard. The brown wire is connected to G, the red wire is connected to V and the orange wire is connected to D13.

![Img](/media/414.png)

 Add the Servo Instruction Module

![Img](/media/415.png)

![Img](/media/416.png)

Diagram of the **Extension** Instruction Block

![Img](/media/417.png)

Add **Servo**

![Img](/media/418.png)


 Description of the the Building Blocks

![Img](/media/419.png)

Set the rotation angle of the servo and the delayed time for a specified pin


 Write the Program

① Drag the instruction block![Img](/media/420.png) in the **Events** module to the script area.

![Img](/media/421.png)

② Drag the instruction block ![Img](/media/422.png) in the **Pins** module to the script area. Since the servo is connected to port G, V and D13 on the mainboard, then change the number 0 to 13 and the **input** to **output**.

![Img](/media/423.png)

③Drag the instruction block ![Img](/media/424.png) in the **servo** module to the script area, then change the number 3 to 13 and the angle number 90 to 93, the delay of 200 remains unchanged.

![Img](/media/425.png)

④ Drag the instruction block ![Img](/media/426.png) in the **Control** module to the script area.


![Img](/media/427.png)

⑤ Drag the instruction block ![Img](/media/424.png) in the **servo** module to the script area, then change the number 3 to 13, the angle number 90 to 93 and the delay of 200 to 500.

![Img](/media/428.png)

⑥ Copy the instruction block![Img](/media/429.png) 3 times in the ![Img](/media/430.png)block and place them into it, then change the angle number 93 to 62, 31 and 0.

![Img](/media/431.png)

⑦ Complete Program

![Img](/media/432.png)

 Test Result

Click ![Img](/media/433.png) to upload the complete program to the kidsuno mainboard and power up, then the servo will rotate from 93°to 62° to 31° to 0° and rotate from 0° to 31° to 62° to 93°.

 Installation Steps



Components

Note: The color of the building blocks is subject to the actual object.

|  ![](media/project-4.png) |
|---------------------------------------------------|


| ![](media/587200386e361ece5df2b7b6790e9a4c.png)<br>![](media/4bb3f1f245a849918e4f6366e049f7ac.jpeg) <br> ![](media/6c5b4211a7c4076fcb0fae95ca67fed4.jpeg)  **×4** <br> ![](media/a4c73851522baf2294a1cd55b6fdd862.png)    **×2** |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/3f93de39a33decf55e9de3d4d5d68810.png)<br>![](media/e9d4a87ef515e74a6a1e764fc784ede5.jpeg) <br> ![](media/4cd4e64661ec614050ff18ec27a8585a.png)   **×2** |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/c5a893bd39072f6c954943dcdb9e5ce0.jpeg)<br> ![](media/6c5b4211a7c4076fcb0fae95ca67fed4.jpeg) **×4**<br> ![](media/9afb3141b7c6eee494cc62fc0c5e11b6.png) |
|----------------------------------------------------------------------------------------------------------------------------------------------------------|

|  ![](media/1a7a2c45c7466884637d73c5c36f0c53.png) **×2** |                                                    |
|---------------------------------------------------------|----------------------------------------------------|
|   ![](media/05c1b26a1f77415bec5d9f6dad98d97e.png)       |   ![](media/cab91b989ca521099c2b052c6cef7949.jpeg) |

|  ![](media/6c5b4211a7c4076fcb0fae95ca67fed4.jpeg) **×2** |                                                   |
|----------------------------------------------------------|---------------------------------------------------|
|   ![](media/40226c07222e2fc3d783804358b68bf8.png)        |  ![](media/266106ba30aeb65183d5fc047bfdca87.jpeg) |

| ![](media/106d2c4e12fef0092212854178fb3f17.jpeg) <br> ![](media/7c8a0120987b836c527351151e524113.png)  **×1**  <br> ![](media/0ecd6ff356dbfa9de86c850dd0dd8d87.png) |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/6c5b4211a7c4076fcb0fae95ca67fed4.jpeg)       **×4** |          ![](media/da6b819a19ea2ff6b7a4c414e05284b2.png) |          ![](media/c94dc0f97282a21a9aad0372985a4a72.jpeg) |
|---------------------------------------------------------------|----------------------------------------------------------|-----------------------------------------------------------|

| ![](media/15fce8cf98f79457c2f03ddde691f713.png)   **×1** <br>![](media/715b7d83aaba7bedc0599f35a173bb4b.png) |            ![](media/d2c4f2d4b504210846054e7bb27f4af3.jpeg) |
|----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|

| ![](media/2f7f2d68cf5f9e826b2f03f271e9dab6.jpeg) <br>![](media/6c5b4211a7c4076fcb0fae95ca67fed4.jpeg) **×2**  <br>![](media/15fd1df71b809b9aabe669cbd60d8875.png) |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/cb0dad6a80de7df90b42d6959bb61b12.jpeg)<br>![](media/7eef75a360206dd3b38667a79b1a44d1.png) **×1** <br>![](media/86d013ce316e51dda177a6d6b73bd1b4.png) |
|--------------------------------------------------------------------------------------------------------------------------------------------------------|

|  ![](media/36a193a1086910c618b2ed4c4a94f83f.jpeg) **×2** |                                                    |
|----------------------------------------------------------|----------------------------------------------------|
|   ![](media/5e34498c51a14036f835ff54285aa252.png)        |   ![](media/d8b58d0ea636c9b4ab8050f8b0269376.jpeg) |

| ![](media/f2589fa38bc23499ddec2a99e549bb1d.jpeg)<br> ![](media/cc07ae00c2becaf2f42a1be0b90bf131.jpeg) **×1**<br> ![](media/33421c74d35bd64097a25d430981cc6f.png) |
|----------------------------------------------------------------------------------------------------------------------------------------------------------|

| Before installing the servo, please initialize its angle                            |                                                    |
|-------------------------------------------------------------------------------------|----------------------------------------------------|
|     ![](media/bb4bb7fad810f12a0a992a6aa3ee5d1e.png)                                 |   ![](media/5e54a53389bd6e1f4c507a00da785d27.jpeg) |
|   Code for initializing the servo   ![](media/sevro.png) |                                                    |

| ![](media/bc461597647a95c1aa2b691735319be8.jpeg)<br>![](media/0da61e7267d629f973a30142b02db827.png)  **×1**<br> ![](media/c60b385d039b98ab4dd978f6c1d5e76c.png) |
|---------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/887b19268c4c8b9099e222589eb92d1b.jpeg) <br>![](media/d2d3a79084051d5e43cc4e4661b4d251.jpeg) **×2**<br> ![](media/72351eb2b0ddd0398eac2044ab0d5ffd.png) |
|----------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/bd9da6dc967e90c2115187b84f7611ab.png)   **×1** <br>![](media/cbc8512bde39b54eb54725c25b325c42.png) |            ![](media/8cd3904ccb5b318953634282d3d47559.jpeg) |
|----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|

|             Installation Diagram | ![](media/c1104116cdbd480fb7dada942a1fee32.jpeg) <br> ![](media/9bce1311a9f328e9ae21387c3bb3524b.jpeg) |
|----------------------------------|----------------------------------------------------------------------------------------------------|

|  ![](media/f3b2f8d80ec356a39b821b7659f0e0ab.jpeg) |
|---------------------------------------------------|

|  ![](media/e8b236459bfe1a71187a4cc8fddd4384.jpeg) |
|---------------------------------------------------|

| ![](media/ed5f11ee990f01f888782697e6a019a9.jpeg) |
|--------------------------------------------------|

| ![](media/35e9328613e3b18584607a2221355726.jpeg) <br> ![](media/d2d3a79084051d5e43cc4e4661b4d251.jpeg) ×2<br> ![](media/fcd8be16c6419a0287df2b661fc5087b.png) |
|-------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/2bea7a7872edebcd475b8ff3936065a9.jpeg) <br>![](media/7eef75a360206dd3b38667a79b1a44d1.png) ×1 <br> ![](media/4df53bb125b35fcf6e0a4ef925874cd1.png) |
|------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/9cd96c3729182c7f5f1cc35a76d1fa3e.jpeg) <br>![](media/d2d3a79084051d5e43cc4e4661b4d251.jpeg) ×2 <br> ![](media/3039acb5dd5c07cc46850947e38979e1.png) |
|-------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/7eef75a360206dd3b38667a79b1a44d1.png)       ×1 |         ![](media/d0800ee002d2207d75c1f303aba1857c.png) |           ![](media/33e2a69080bebc566ac69f7fb36e1baf.jpeg) |
|----------------------------------------------------------|---------------------------------------------------------|------------------------------------------------------------|

|  ![](media/d2d3a79084051d5e43cc4e4661b4d251.jpeg) ×2 |  ![](media/7eef75a360206dd3b38667a79b1a44d1.png) ×1 |
|------------------------------------------------------|-----------------------------------------------------|
|   ![](media/742e81076898a7bbb42322a6b5c5fd8f.png)    |    ![](media/6b899e7c55433930dd94230216d17dc2.jpeg) |

| ![](media/b2b2c27c01b4a34024097cff751a6ced.jpeg)<br>![](media/7d8d9b752a61c0ac66de76cb32d1e484.png) ×2 <br> ![](media/1e9f62095dcdfc96275901c29f4e9fdc.png) |
|-----------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/b183120102e950bbc15ee4c021251d17.jpeg)      ×2 |         ![](media/903f4376864ea808aba412f5935121ea.png) |           ![](media/163f74f2494502a8df8cb50dd4a607e1.jpeg) |
|----------------------------------------------------------|---------------------------------------------------------|------------------------------------------------------------|

| ![](media/09833f1df4ab73ed5734a3b14d9c9bf1.jpeg)<br>![](media/d2d3a79084051d5e43cc4e4661b4d251.jpeg) ×2 <br>![](media/046f387be63cc1558f49673d7f277e4e.png) |
|-----------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/96398842d2feab7c0bc8bde3e63838ca.png)<br>![](media/e8fd726b93f418bef27218495412ac93.png) ×1<br>![](media/8da643bce9484be92a3c209a57f54513.png) |
|---------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/40cce290a3477a9f97a88405aa8f5c98.png)     Prototype  ![](media/bb30441dbc5c87c0e2d910682f3a86d9.png) |
|----------------------------------------------------------------------------------------------------------------|


 Wiring Diagram

Connect the kidsuno mainboard and computer via a USB cable, and connect the servo to the G, V and D13 interface of the mainboard and the PIR motion sensor to the No.1 interface of the mainboard.

The brown wire is connected to G, the red wire is connected to V and the orange wire is connected to D13.

![Img](/media/434.png)

 Function: Read the PIR Motion Sensor

![Img](/media/435.png)


 Description of the the Building Blocks

![Img](/media/436.png)

This is the digital signal (0 or 1) for a specified pin.


 Write the Program

① Drag the instruction block ![Img](/media/437.png) in the **Events** module to the script area.

![Img](/media/438.png)

② Drag the instruction block ![Img](/media/439.png) in the **Serial** module to the script area and take the baud rate 9600 as an example.

![Img](/media/440.png)

③  Drag the instruction block ![Img](/media/441.png) in the **Pins** module to the script area. Since the PIR motion sensor is connected to pin D5 of port 1 on the mainboard, then change the number 0 to 5.

![Img](/media/442.png)

④ Drag the instruction block ![Img](/media/443.png) in the **Control** module to the script area. 

![Img](/media/444.png)

⑤ Drag the instruction block ![Img](/media/445.png) in the **Serial** module to the script area.

![Img](/media/446.png)

⑥ Drag the instruction block ![Img](/media/447.png) in the **Pins** module to the script area and put it into the block ![Img](/media/448.png), then change number 0 to 5.

![Img](/media/449.png)

⑦ Drag the instruction block ![Img](/media/450.png) in the **Control** module to the script area and change the number 1 to 0.3.

![Img](/media/451.png)

⑧ Complete Program

![Img](/media/452.png)


 Test Result

Click![Img](/media/453.png) to upload the complete program to the kidsuno mainboard and power up, then click ![Img](/media/454.png) in the serial monitor area to set the baud rate to 9600. When the PIR motion sensor detects a person or animal moving, the serial monitor prints a digital signal 1, otherwise it prints 0.

![Img](/media/918.png)

![Img](/media/455.png)

 Function: PIR Motion Sensor Controls the Servo

![Img](/media/456.png)

 Flow Chart 

First, set the angle of the servo to 93°. When the PIR motion sensor detects a person or animal passing by, it will rotate to 0° and it will not rotate if no man or animal is passing by.

![Img](/media/457.png)


 Write the Program

① Find the instruction blocks

（1）![Img](/media/458.png)
<br>  

（2）![Img](/media/459.png)
<br>

（3）![Img](/media/460.png)
<br>

（4）![Img](/media/461.png)
<br>

（5）![Img](/media/462.png)
<br>

（6）![Img](/media/463.png)
<br>

② Complete Program

![Img](/media/464.png)


 Test Result

Click![Img](/media/453.png) to upload the complete program to the kidsuno mainboard and power up. When the PIR motion sensor detects a person or animal passing by, it will rotate to 0° and the door will be opened automatically , and it will not rotate if no man or animal is passing by and the door will not be opened.

![Img](/media/img-20230714083105.png)


 Extended Project

![Img](/media/465.png)

The sample code is below：

![Img](/media/466.png)




## Project 05：Windshield Wipers

![Img](/media/511.png)

 Introduction

Our family drove out for a trip at the weekend, however, it suddenly rained heavily on the way home. My father turned on the windshield wipers and the rain on the front glass of the car was constantly scraped away. Let’s explore the reason!

 Components

|![Img](/media/KidsunoMainboard.png)|![Img](/media/SteamSensor.png)|![Img](/media/270Servo.png)|
| :--: | :--: | :--: |
|Kidsuno Mainboard×1|Steam Sensor×1|270°Servo×1|
|![Img](/media/ConnectionWire.png)|![Img](/media/USBCable.png)| ![Img](/media/WindshieldWipers.png) |
|Connection Wire×1|USB Cable×1| Windshield Wipers×1 |

![Img](/media/512.png)

 Installation Steps

Components

Note: The color of the building blocks is subject to the actual object.

|         ![](media/project-5.png) |
|----------------------------------------------------------|

| ![](media/5a030bbb422a39c874455508dad815d8.jpeg) <br> ![](media/e671f201166e22864ac67a8dd55c3fc0.jpeg)  ×2   <br>   ![](media/1de45ad6ce9a06eab9ca9b941eebedb9.jpeg)  ×1 |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------|

|         ![](media/3017f2d3d28488fe007eac06d2571817.jpeg) |
|----------------------------------------------------------|

| ![](media/fedf754420755a3fde2f33f601eda095.jpeg) <br> ![](media/e671f201166e22864ac67a8dd55c3fc0.jpeg)  ×2 |
|--------------------------------------------------------------------------------------------------------|

|         ![](media/bb5b59e9a47840dacf45a55b1c695c97.jpeg) |
|----------------------------------------------------------|

| ![](media/49126c55c28a176ae985115d384bd40d.jpeg) <br> ![](media/e671f201166e22864ac67a8dd55c3fc0.jpeg)  ×2 |
|--------------------------------------------------------------------------------------------------------|

|      ![](media/239c1cecf7dba7b254d541a410ec8815.jpeg) |
|-------------------------------------------------------|

| ![](media/97c6428faf1a11951f917e05c73f52be.jpeg) <br>![](media/0837c2332a17c97d7ae25ac98968dc30.jpeg)  ×2 |
|-------------------------------------------------------------------------------------------------------|

|      ![](media/10da31c683882b9d96291a1c02cd585b.jpeg) |
|-------------------------------------------------------|

| ![](media/375ed5cf5d48aa6ac3f850731182cb82.jpeg)  <br> ![](media/5f33463bd1ff6bcf3ede93c44b731c02.jpeg)  ×2 |
|---------------------------------------------------------------------------------------------------------|

|       ![](media/29da1cea4a2a3030c402b4b9ca18b939.jpeg) |
|--------------------------------------------------------|

|    ![](media/0c7da4071412e2f04edae8fce8d2091b.jpeg) ×2 <br>![](media/608a966df4c97917411749a9b9c1f941.png) |
|--------------------------------------------------------------------------------------------------------|

|        ![](media/b1f33c58d9bb2764e09c08aee3a93976.jpeg) |
|---------------------------------------------------------|

|  ![](media/5c61a2cd9943272d28f90b83b268ff08.jpeg) ×2 <br>![](media/76bac1f25f52c2909f68680b954608f7.jpeg) |
|-------------------------------------------------------------------------------------------------------|

|  ![](media/e179516967be908376ac3c2d86c35a2a.jpeg) |
|---------------------------------------------------|

| ![](media/b3340a5acec92fdcd99eb778cfbd2ecb.jpeg)  <br>![](media/e671f201166e22864ac67a8dd55c3fc0.jpeg)  ×2 |
|--------------------------------------------------------------------------------------------------------|

|  ![](media/b84238b5cb556038392d45553113b14f.jpeg) |
|---------------------------------------------------|

| ![](media/dbfcd4ecfb2510b97996869198f62fc0.jpeg)   <br>    ![](media/f17977d420a5c91415f9714e2920b30a.jpeg)1\*4（3.1cm） ×1 |
|-------------------------------------------------------------------------------------------------------------------------|

|  ![](media/3fef14445f06ac000d32b7367866916d.jpeg) |
|---------------------------------------------------|

| ![](media/c43c241f13252a9ca7fd08d6c748501b.jpeg) <br> ![](media/24876fbdb9bc57940e6e8d70c4a4f797.jpeg) ×1 |
|-------------------------------------------------------------------------------------------------------|

|  ![](media/13bd7cb277655973207c0bf511d8ec09.jpeg) ×1 | ![](media/69513ed99d559ea779067a8ed8f0ed9c.jpeg) |   |
|------------------------------------------------------|--------------------------------------------------|---|

| ![](media/e7dc5114e0015b925b7859d42bc205c5.jpeg) |
|--------------------------------------------------|

| ![](media/4b4c61b2b49021b1887e2210fce07641.jpeg) <br> ![](media/f9fb0ba9e4e978af4cab7f3d0218e803.jpeg)  ×1    <br>    ![](media/8718c313b58eaf91cea9d1168b4d0cc9.jpeg)  ×1 |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/3c6c85a78ae2cf944e8db412d8c7d760.jpeg) <br>![](media/ac5ae55547e606470e3c146c16cc9871.jpeg)  ×1 |
|-------------------------------------------------------------------------------------------------------|

![](media/add705188879e1e78b5047a3a962b0f2.jpeg)

| ![](media/808b01ed268886269741d41a71f16794.png) <br> ![](media/8718c313b58eaf91cea9d1168b4d0cc9.jpeg) ×2 |
|------------------------------------------------------------------------------------------------------|

| ![](media/a68d8c44365360bfde75edc580a138fc.jpeg) |
|--------------------------------------------------|

| ![](media/e7e39da302fdc29bdde39f228e939193.jpeg) <br> ![](media/0016b18b7878f1e830d077bca0dbae0e.jpeg)  ×1 |
|--------------------------------------------------------------------------------------------------------|

|  ![](media/98645750ff9fd7f5250384dd83d146e8.jpeg) |
|---------------------------------------------------|

| ![](media/526cad4b12291057e57f4c02cfc66929.jpeg) <br> ![](media/4474bac6128a030b6c10f2440c0042c9.jpeg)  ×1 |
|--------------------------------------------------------------------------------------------------------|

|  ![](media/205a170b2f054078db42e5930b6b6e81.png) |
|--------------------------------------------------|

| ![](media/2fe7235d840065e732ce1deffda7eb0c.jpeg)<br> ![](media/ff99fea4f1a48c66b9f02f5bb58586d2.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------|

| ![](media/307956b807a27bb06d1bff50710f2daf.jpeg) |
|--------------------------------------------------|

| ![](media/06f73b4372b68471348ab0a815d406f1.jpeg) <br> ![](media/a47e8799548f511ba72e7c4999d7d6f6.jpeg) ×2 |
|-------------------------------------------------------------------------------------------------------|

|   ![](media/d9e095eabc72c85bdc685294c6b40f8e.png) |
|---------------------------------------------------|

| ![](media/66064308ebb91a31097649f4c9b84c9f.jpeg) <br>![](media/adaf4fc744bb1cd91369286e8efaa483.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------|

|   ![](media/d13e1cbb3f81a2e3e66c7cb7788fde6b.jpeg) |
|----------------------------------------------------|

| ![](media/9bcb50c3ee3e4035c4f580886a1259fa.jpeg) <br>![](media/a651753f8bbce0fa91f15c2ced87f861.jpeg) ×2 |
|------------------------------------------------------------------------------------------------------|

|   ![](media/0d2b79edfe827d5b3271edbc26b776bf.jpeg) |
|----------------------------------------------------|

| ![](media/8abdea7078ca500befa8d0fc8b0f08cf.jpeg) <br> Before installing the servo, please initialize its angle     <br>  ![](media/445b388c740c15f5c16d65607cce8e7c.png)  Code for initializing the servo <br>  ![](media/sevro.png) |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

|  ![](media/e9d49435c4ca6a0c5aed89cd690f884e.jpeg)  ×1       <br>       ![](media/be6368e4eda1cf7aaabdbcf6364ee2b9.png)<br>Mind the position of -the wires |
|-----------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/19710ff123410e7531703716f0d389fb.png)        <br>         Make sure the fitting is <br>![](media/bf81f97f91be78a7dc91eedf7d730e65.png)connected to the servo |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/cdf5b8405b831f37a93e8c3082b9e571.jpeg) <br>  ![](media/e5196c17a0a0ff36a5427da1caf03335.jpeg)  ×1 |
|---------------------------------------------------------------------------------------------------------|

|   | ![](media/4f6a3ce49ce3a01eaa10c300e3cdf8aa.jpeg)          |
|---|-----------------------------------------------------------|

|   ![](media/66ebe2baee4b30111a858de4977eaa61.jpeg) |
|----------------------------------------------------|

|   ![](media/3aa5d9568cb16804d4fdc303b321452c.png)<br>The two blue 1x12 Lego pieces should be 90° perpendicular to the red LEGO pieces     <br>    ![](media/ac5279003b2d0e9009a21d7053227221.png)<br>![](media/b60604ab7f539e3fa238b20487e57ace.png)The angle is 90。 |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/39abd6f7144713171651a02588c59c14.jpeg)   Prototype |
|--------------------------------------------------------------|

|  ![](media/c41cdcfa68e88fd0c16f19b4c83b2ad2.jpeg) |
|---------------------------------------------------|



 Function: Steam Sensor Detects Water

![Img](/media/513.png)


 Wiring Diagram

Connect the kidsuno mainboard and computer via a USB cable, and connect the servo to the G, V and D13 interface of the mainboard and the steam sensor to the No.7 interface of the mainboard.
The brown wire is connected to G, the red wire is connected to V and the orange wire is connected to D13.

![Img](/media/514.png)

 Write the Program

① Drag the instruction block ![Img](/media/515.png) in the **Events** module to the script area.

![Img](/media/516.png)

② Drag the instruction block ![Img](/media/517.png) in the **Serial** module to the script area and take the baud rate 9600 as an example.

![Img](/media/518.png)

③ Drag the instruction block ![Img](/media/519.png) in the **Pins** module to the script area. Since the steam sensor is connected to pin A0 of port 7 on the mainboard, then change the number 0 to A0.

![Img](/media/520.png)

④ Drag the instruction block ![Img](/media/521.png) in the **Control** module to the script area. 

![Img](/media/522.png)

⑤ Drag the instruction block ![Img](/media/523.png) in the **Serial** module to the script area.

![Img](/media/524.png)

⑥ Drag the instruction block ![Img](/media/525.png) in the **Pins** module to the script area and put it into the block![Img](/media/526.png).

![Img](/media/527.png)

⑦ Drag the instruction block![Img](/media/528.png) in the **Control** module to the script area and change the number 1 to 0.3.

![Img](/media/529.png)

⑧ Complete Program

![Img](/media/530.png)


 Test Result

Click ![Img](/media/531.png) to upload the complete program to the kidsuno mainboard and power up, then click![Img](/media/532.png) in the serial monitor area to set the baud rate to 9600. When we drip water gradually into the metal detection area of the steam sensor, the analog number will increase gradually.

![Img](/media/533.png)


 Function: Steam Sensor Controls the Servo

![Img](/media/534.png)


 Flow Chart

First, set the angle of the servo to 0°. When the analog value of the steam  sensor is greater than 200, the servo will rotate back and forth at 0-100°, otherwise, it will not rotate and the angle of the servo will be 0°.

![Img](/media/535.png)


 Add the Servo Instruction Module

![Img](/media/536.png)


 Description of Building Blocks 

<span style="color: rgb(255, 76, 65);">This is the variable module. Let’s look at it!</span> 
<br>
<br>

There are commonly used **declare global numeric variable type integer name assigned to 0**, **variable** and **Set variable to 0** instruction squares:

![Img](/media/537.png)

When you need to use this variable, drag the block directly into the script area to edit it!

 Write the Program

① Find the instruction blocks

（1）![Img](/media/538.png)
<br> 

（2）![Img](/media/539.png)
<br>  

（3）![Img](/media/540.png)
<br>

（4）![Img](/media/541.png)
<br>

（5）![Img](/media/542.png)
<br>

（6）![Img](/media/543.png)
<br>

（7）![Img](/media/544.png)
<br>

（8）![Img](/media/545.png)
<br>

② Complete Program

![Img](/media/546.png)


 Test Result

Click![Img](/media/531.png) to upload the complete program to the kidsuno mainboard and power up. Dripping water gradually into the metal detection area of the steam sensor, if the analog value is greater than 200, the servo will rotate back and forth at 0-100° and the windshield wipers will swing, otherwise, it will not rotate and the wipers will not swing.

![Img](/media/img-20230714083149.png)

 Extended Project

![Img](/media/547.png)

The sample code is below：

![Img](/media/548.png)




## Project 06：Barrier Gate

![Img](/media/611.png)

 Introduction

Last time my dad drove me to eat seafood, however, when our car came to the barrier gate of the parking lot, the gate rose automatically, and when the car passed, it fell automatically. 

Maybe you're as curious about this device as I am, let’s make a barrier gate can automatically rise and fall together!
 
The following are the tools we need.

 Components

|![Img](/media/KidsunoMainboard.png)|![Img](/media/ObstacleAvoidanceSensor.png)|![Img](/media/270Servo.png)|
| :--: | :--: | :--: |
|Kidsuno Mainboard×1|Obstacle Avoidance Sensor×1|270°Servo×1|
|![Img](/media/ConnectionWire.png)|![Img](/media/USBCable.png)| ![Img](/media/BarrierGate.png) |
|Connection Wire×1|USB Cable×1| Barrier Gate×1 |

![Img](/media/612.png)


 Installation Steps

|       ![](media/project-6.png) |
|--------------------------------------------------------|

| ![](media/fc788bb5aad5256901714e4121641016.png) <br>![](media/b94569b97200a0268a7d09e97f57968c.jpeg) ×1 <br>  ![](media/02ecaf3e3028041ac7647052644f68ee.jpeg) ×3  <br> ![](media/5537d2db7d8e470054aea7b4467e97e6.jpeg) ×2 <br> ![](media/4bd902b9cec463cfadceba45a3d2de90.jpeg) ×1 <br> ![](media/451b2c28c59958c4781d21ed20605e70.jpeg)  ×1 |
|---------------------------------------------------------------------------------------------------------------------------------------------------|

|       ![](media/4763bf5ec728bc1a849d366b9fa5c604.jpeg) |
|--------------------------------------------------------|

|    ![](media/f97c29f46bf49a2c369e0966613a134d.jpeg)  ×1 |   ![](media/bcd50f47775b8f5b19e44e2d7f410df4.jpeg) ×1  <br>   ![](media/c8b6983caa5b979322aea0029e63f660.png) |
|---------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|

|  ![](media/0666a067afe6008059046c26a4afd880.jpeg) |
|---------------------------------------------------|

| ![](media/f3ee545f4c42c7958158e651ccdfa7d9.jpeg)       ×1 |           ![](media/34861adac49b62046d5a49d3d5e86e77.png) |
|-----------------------------------------------------------|-----------------------------------------------------------|

|        ![](media/b584220a446ab815acd0a1abc7a9d2a5.jpeg) |
|---------------------------------------------------------|

| ![](media/e5670a8e0a4a84325f013736cb22e89e.jpeg) ×1 <br>![](media/6d2b0e0d11477468e1e48db9c0579089.png) |
|-----------------------------------------------------------------------------------------------------|

|   ![](media/ca3df7fadde4c7b38b5bb2f988e8f9b0.jpeg) |
|----------------------------------------------------|

|  ![](media/020d8709f1aad0e9752fbeda407fff84.jpeg) ×1  <br> ![](media/5025cab38f7d6b9968577376f8c13c1c.png) |
|--------------------------------------------------------------------------------------------------------|

|      ![](media/b19600fd424c89e460ff8cf3a5d9a613.jpeg) |
|-------------------------------------------------------|

| ![](media/3932e5f75023af94235ce77830300b58.png)<br>![](media/c3f7f6ab34bfcf74266d1d61fb19f110.jpeg) ×2 |
|----------------------------------------------------------------------------------------------------|

|        ![](media/4dfaf4da4be99af05edc21301479625f.jpeg) |
|---------------------------------------------------------|

| ![](media/3e3d137b6898b4a9f885d7c0ffabc6d0.png)<br>![](media/878dd908042270df627eb8f627277cce.jpeg)  ×1 |
|-----------------------------------------------------------------------------------------------------|

|      ![](media/5569135b0fd14d5e4e52cc34c3e6a0f0.jpeg) |
|-------------------------------------------------------|

| ![](media/cd21a27521c56c76938907556766c351.jpeg) ×2 <br> ![](media/2be7e5a22026bceff1dc2df7a9127a69.png) |
|------------------------------------------------------------------------------------------------------|

|   ![](media/ab042bf714ec4bc909a1536d22568d0d.jpeg) |
|----------------------------------------------------|

| <br> Before installing the servo, please initialize its angle <br> ![](media/445b388c740c15f5c16d65607cce8e7c.png) <br> Code for initializing the servo |      ![](media/sevro.png) |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|

|  ![](media/a53e6e66955a738fb4b4e41cccd77bcf.jpeg)           <br>       ![](media/27e18e2a27b8f4865428e0312e458408.png)<br>Mind the position of the wires <br>![](media/00a0437c08d5963160ae767b75b81237.png) |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

|       ![](media/ddd751d2d2b682e2a4ac33de5d3d81de.jpeg) |
|--------------------------------------------------------|

|       Note: There are no wires on the side near the barrier gate when installing the servo. <br> ![](media/7646df7a436c0e62db601d2571aee4d4.png) |
|----------------------------------------------------------------------------------------------------------------------------------------------|

|      ![](media/084d046ba0e46b8836b8eb85ec409d87.jpeg) |
|-------------------------------------------------------|

|  When installing the barrier gate, ensure that it is parallel to the plate, otherwise it will affect the servo angle <br>![](media/9cee79c64c639b1638e62fe8715b93f1.png) <br> Note:Do not rotate the barrier gate, which will change the servo angle |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

| ![](media/8b9333a8a1a743825cab3923f08a02d7.jpeg) <br> Prototype |
|-------------------------------------------------------------|



 Function: Read the Obstacle Avoidance Sensor

![Img](/media/613.png)

 Wiring Diagram

Connect the kidsuno mainboard and computer via a USB cable, and connect the servo to the G, V and D13 interface of the mainboard and the obstacle avoidance sensor to the No.1 interface of the mainboard.

<span style="color: rgb(255, 76, 65);">Note:</span> The brown wire is connected to G, the red wire is connected to V and the orange wire is connected to D13.

![Img](/media/614.png)

 Write the Program

① Drag the instruction block ![Img](/media/615.png) in the **Events** module to the script area.

![Img](/media/616.png)

② Drag the instruction block ![Img](/media/617.png) in the **Serial** module to the script area and take the baud rate 9600 as an example.

![Img](/media/618.png)

③ Drag the instruction block![Img](/media/619.png) in the **Pins** module to the script area. Since the obstacle avoidance sensor is connected to pin D5 of port 1 on the mainboard, then change the number 0 to 5.

![Img](/media/620.png)

④ Drag the instruction block ![Img](/media/621.png) in the **Control** module to the script area.

![Img](/media/622.png)

⑤ Drag the instruction block ![Img](/media/623.png) in the **Serial** module to the script area.

![Img](/media/624.png)

⑥ Drag the instruction block ![Img](/media/625.png) in the **Pins** module to the script area and put it into the block![Img](/media/626.png), then change the number 0 to 5.

![Img](/media/627.png)

⑦ Drag the instruction block ![Img](/media/628.png) in the **Control** module to the script area and change the number 1 to 0.3.

![Img](/media/629.png)

⑧ Complete Program

![Img](/media/630.png)


 Test Result

Click![Img](/media/631.png) to upload the complete program to the kidsuno mainboard and power up, then click ![Img](/media/632.png) in the serial monitor area to set the baud rate to 9600. When the obstacle avoidance sensor detects an obstacle, the serial monitor will print a digital signal 0, otherwise, it will print 1.

![Img](/media/919.png)

![Img](/media/633.png)


 Function: Obstacle Avoidance Sensor Controls the Servo

![Img](/media/634.png)


 Flow Chart 

First, set the angle of the servo to 32°. When the obstacle avoidance sensor detects an obstacle, the servo will rotate to 100°, otherwise it will not rotate.

![Img](/media/635.png)


 Add the Servo Instruction Module

![Img](/media/636.png)


 Write the Program

① Find the instruction blocks

（1）![Img](/media/637.png)
<br> 

（2）![Img](/media/638.png)
<br>

（3）![Img](/media/639.png)
<br>

（4）![Img](/media/640.png)
<br>

（5）![Img](/media/641.png)
<br>

（6）![Img](/media/642.png)
<br>

（7）![Img](/media/643.png)
<br>

（8） ![Img](/media/644.png)
<br>

② Complete Program

![Img](/media/645.png)

 Test Result

Click![Img](/media/631.png) to upload the complete program to the kidsuno mainboard and power up. When the obstacle avoidance sensor detects an obstacle, the servo will rotate to 100° and the barrier gate will open, otherwise it will not rotate and the barrier gate will close.

![Img](/media/img-20230714083213.png)



## Project 07：Astern Indicating Device

![Img](/media/711.png)

 Introduction

With the development of science and technology, cars boast the ability of intelligent environment perception, which can automatically analyze the safety and danger when driving. 

For example, we can observe the specific situation behind the car if we turn on the astern indicating device when backing up, which can avoid the car being knocked. Let’s make an astern indicating device together!
 
The following are the tools we need.

 Components

|![Img](/media/KidsunoMainboard.png)|![Img](/media/UltrasonicAdapter.png)|![Img](/media/UltrasonicSensor.png)| ![Img](/media/AsternIndicatingDevice.png) |
| :--: | :--: | :--: | :--: |
|Kidsuno Mainboard×1|Ultrasonic Adapter Board×1|Ultrasonic Sensor×1| Astern Indicating Device×1 |
|![Img](/media/88DotMatrixDisplay.png)|![Img](/media/ConnectionWire.png)|![Img](/media/USBCable.png)| |
|8×8 Dot Matrix Display×1|Connection Wire×2|USB Cable×1| |

![Img](/media/712.png)


 Installation Steps

|        ![](media/project-7.png) |
|---------------------------------------------------------|


| ![](media/a0b672c9f22dd8ddcb8a727cf36a503e.png) <br> ![](media/f599d356f6154038df8deda362c8461b.jpeg) ×1 <br>  ![](media/c066824842374ef126038411f4b4b73b.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|

|        ![](media/aeb1649d530c369d498074831502427c.jpeg) |
|---------------------------------------------------------|

| ![](media/ac2de8da120e7a3ba81d923afd44f10d.png) <br> ![](media/a2c432c3a071606cb341e4d4fd2b3c3f.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------|

|        ![](media/45d5aaf5304ccafa193f6b8302ab218f.jpeg) |
|---------------------------------------------------------|

| ![](media/f6b8389b99ed609b4fb8fc19a3a8206f.png)  <br> ![](media/a2c432c3a071606cb341e4d4fd2b3c3f.jpeg) ×1 |
|-------------------------------------------------------------------------------------------------------|

|      ![](media/33b4011bdc9fef1b59b3c407a6f5bdc5.jpeg) |
|-------------------------------------------------------|

| ![](media/560e79cd22ca4c1a2935ab724a702365.png) <br> ![](media/73b756b1db9b4c80d70af382f3cf2828.jpeg) ×7 |
|------------------------------------------------------------------------------------------------------|

|      ![](media/331b9c703d8f2da5cbd19d1431b2e838.jpeg) |
|-------------------------------------------------------|

| ![](media/afd1aadaadf26b352cb3afa74a72e62f.png)  <br> ![](media/8afb23a0cc2bfe372fd8f8811b33a648.jpeg) ×2 |
|-------------------------------------------------------------------------------------------------------|

|   ![](media/54e7cb5acc6aec591eac25d42e42fa62.jpeg) |
|----------------------------------------------------|

| ![](media/18dcdd205ab0f94a57939a23bb5ca3ca.png)  <br> ![](media/1441c681b4ebe5cfed3257ab7005a9fc.jpeg) ×1 |
|-------------------------------------------------------------------------------------------------------|

|  ![](media/64c42c6a05866b95ae583c4b93ccd040.jpeg) |
|---------------------------------------------------|

| ![](media/6f9f92b86b6e8bd92eacfa9bf2c89fef.png)  <br> ![](media/c055eccdef3ff898dc1f646e43b66b00.jpeg) ×1 |
|-------------------------------------------------------------------------------------------------------|

|     ![](media/f32ca2d30d8c945e05f1ecbae4c0e604.jpeg) |
|------------------------------------------------------|

| ![](media/9b10930e9b9c8b232827e765af8f09ce.png) <br>![](media/d242fcf0cf2ad7c93ba9a8f70b73ab3d.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|    ![](media/052a494d0059eada63a3485e83141469.jpeg) |
|-----------------------------------------------------|

| ![](media/6e28daf59d2d0498947514a51c015042.jpeg)   <br> Prototype |
|---------------------------------------------------------------|

|    ![](media/6c467d989d9b8880f245d007161e1f9c.jpeg) |
|-----------------------------------------------------|



 Function: 8*8 Dot Matrix Displays Expression Patterns

![Img](/media/713.png)


 Wiring Diagram

Connect the kidsuno mainboard and computer via a USB cable. Then connect the 8×8 dot matrix module to the No.8 interface of the mainboard and the ultrasonic adapter board to the No.9 interface of the mainboard. The Vcc, Trig, Echo, and Gnd of the ultrasonic sensor correspond to the same port of the ultrasonic adapter board.

![Img](/media/714.png)

 Add the Instruction Library of the 8*8 Dot Matrix

To use the 8×8 dot matrix , we need to call the "Display" module in the "Extension" function. Click "Matrix 8*8 IIC" then tap ![Img](/media/744.png) to return to the programming interface.

![Img](/media/715.png)

**Extension** Instruction 

![Img](/media/716.png)

Add **Matrix 8*8 IIC** Display                        

![Img](/media/717.png)


 Write the Program

① Drag the instruction block![Img](/media/718.png) in the **Events** module to the script area.

![Img](/media/719.png)

② Click the **Matrix HT16K33** module on the left of the instruction area, then all the 8*8 dot matrix instruction blocks will be displayed.

![Img](/media/720.png)

![Img](/media/721.png)

③ Drag the instruction block![Img](/media/722.png) and ![Img](/media/723.png) in the **Matrix HT16K33** module to the script area.

![Img](/media/724.png)

④ Drag the instruction block ![Img](/media/725.png) in the **Control** module to the script area.

![Img](/media/726.png)

⑤ Drag the instruction block![Img](/media/727.png) ,![Img](/media/728.png) and ![Img](/media/729.png) in the **Matrix HT16K33** module to the script area.

![Img](/media/730.png)

⑥ Drag the instruction block ![Img](/media/731.png) in the **Control** module to the script area and change the number 1 to 2.

![Img](/media/732.png)

⑦ Copy the instruction block![Img](/media/733.png)10 times and put them into the block ![Img](/media/734.png) respectively, then change the expression pattern ![Img](/media/735.png) to![Img](/media/736.png).

![Img](/media/737.png)

⑧ Complete Program

![Img](/media/738.png)

 Test Result

Click![Img](/media/742.png) to upload the complete program to the kidsuno mainboard and power up, then the the 8*8 dot matrix will display colorful expression patterns.

![Img](/media/920.png)

 Function：Ultrasonic Sensor Detects Distance

![Img](/media/743.png)


 Add the Instruction Library of the Ultrasonic Sensor

To use the ultrasonic sensor , we need to call the **Sensor** module in the **Extension** function. Click **Ultrasonic** then tap ![Img](/media/744.png) to return to the programming interface.

![Img](/media/745.png)

**Extension** Instruction 

![Img](/media/746.png)

Add **Ultrasonic** Sensor

![Img](/media/747.png)

 Description of the the Building Blocks

![Img](/media/748.png)

This is the ultrasonic sensor instruction block used to measure the distance for the specified pin. The distance unit can be selected as cm or inch.


 Write the Program

① Drag the instruction block in the **Events** module to the script area.

![Img](/media/749.png)

②  Drag the instruction block  in the **Serial** module to the script area and take the baud rate 9600 as an example.

![Img](/media/750.png)

③ Drag the instruction block ![Img](/media/751.png) in the **Pins** module to the script area and copy once. Since the ultrasonic sensor is connected to port 9 on the mainboard(Trig corresponds to pin D10 and Echo corresponds to pin D11), then change the number 0 to 10 and 11, and change the input behind number 10 to output.

![Img](/media/752.png)

④ Drag the instruction block ![Img](/media/753.png) in the **Control** module to the script area.

![Img](/media/754.png)

⑤ Drag the instruction block ![Img](/media/755.png) in the **Serial** module to the script area.

![Img](/media/756.png)

⑥ Drag the instruction block ![Img](/media/757.png) in the **Ultrasonic** module to the script area and put it into the block![Img](/media/758.png), then change the number 2 to 10, 6 to 11, and take the distance unit cm as an example.

![Img](/media/759.png)

⑦ Drag the instruction block ![Img](/media/760.png) in the **Control** module to the script area and change the number 1 to 0.3.

![Img](/media/761.png)

⑧ Complete Program

![Img](/media/762.png)


 Test Result

Click![Img](/media/763.png) to upload the complete program to the kidsuno mainboard and power up, then click![Img](/media/764.png) in the serial monitor area to set the baud rate to 9600.

Moving your hand in front of the ultrasonic sensor, the distance displayed becomes smaller when we are close to the sensor and larger when we are far away from it.

![Img](/media/921.png)

![Img](/media/765.png)


 Function: Ultrasonic Sensor Controls the 8*8 Dot Matrix

![Img](/media/766.png)


 Flow Chart 

Initialize the 8*8 dot matrix and read the distance value of the ultrasonic sensor. If the distance is greater than 0 and less than 10cm, the 8*8 dot matrix shows a "stop" pattern, otherwise, it displays a "backward" pattern.

![Img](/media/767.png)


 Write the Program

① Find the instruction blocks

（1）![Img](/media/768.png)
<br>

（2）![Img](/media/769.png)
<br>

（3）![Img](/media/770.png)
<br>

（4）![Img](/media/771.png)
<br>

（5）![Img](/media/772.png)
<br>

（6）![Img](/media/773.png)
<br>

（7）![Img](/media/774.png)
<br>

（8）![Img](/media/775.png)
<br>

（9）![Img](/media/776.png)
<br>

② Complete Program

![Img](/media/777.png)

 Test Result

Click![Img](/media/763.png) to upload the complete program to the kidsuno mainboard and power up. When the ultrasonic sensor detects the object within a range of 0cm to 10cm, the 8*8 dot matrix shows a "Stop" pattern, otherwise, it displays a "backward" pattern.

![Img](/media/img-20230714083256.png)


 Extended Project

![Img](/media/778.png)


The sample code is below：

![Img](/media/779.png)


## Project 08：Intelligent Integrated Traffic System

![Img](/media/811.png)

 Introduction

We have learned a host of projects before, can we put them together to make an integrated traffic system？Maybe you can't wait to do it，let’s get started!

The following are the tools we need.

 Components

|![Img](/media/KidsunoMainboard.png)|![Img](/media/TrafficLightModule.png)|![Img](/media/ActiveBuzzer.png)|![Img](/media/Photoresistor.png)|
| :--: | :--: | :--: | :--: |
|Kidsuno Mainboard×1|Traffic Light Module×1|Active Buzzer×1|Photoresistor×1|
|![Img](/media/ObstacleAvoidanceSensor.png)|![Img](/media/UltrasonicAdapter.png)|![Img](/media/UltrasonicSensor.png)|![Img](/media/88DotMatrixDisplay.png)|
|Obstacle Avoidance Sensor×1|Ultrasonic Adapter×1|Ultrasonic Sensor×1|8×8 Dot Matrix Display×1|
|![Img](/media/WhiteLED.png)|![Img](/media/270Servo.png)|![Img](/media/ConnectionWire.png)|![Img](/media/ConnectionWire.png)| 
|White LED×1|270°Servo×1|20cm Connection Wire×4|30cm Connection Wire×3| 
|![Img](/media/USBCable.png)|![Img](/media/IntegratedTrafficSystem.png) | | |
USB Cable×1|Integrated Traffic System×1 | | |

 Function: Make An Integrated Traffic System

![Img](/media/812.png)


 Installation Steps 

|        ![](media/project-8.1.png) |
|---------------------------------------------------------|

|        ![](media/project-8.2.png) |
|---------------------------------------------------------|

|        ![](media/project-8.3.png) |
|---------------------------------------------------------|


| ![](media/cce412c57063813fca545f49af07edd5.jpeg)<br>![](media/71824d3c4d02d50795c769727cc6eeb5.jpeg) ×2 |
|-----------------------------------------------------------------------------------------------------|

|        ![](media/a0b885f3fcf5a1b6bba96426477e5244.jpeg) |
|---------------------------------------------------------|

| ![](media/3ce914873cfa0e4d8e723e604cbeef97.jpeg)<br>![](media/71824d3c4d02d50795c769727cc6eeb5.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|       ![](media/73eb7f30c4f0aa2cedc2d25c8fe6c373.jpeg) |
|--------------------------------------------------------|

| ![](media/433dd94e8c7d26b42ae68ae69dbca112.jpeg) <br>![](media/c2761f836813ad1ea1894a7d59ab17b7.jpeg) ×7 |
|------------------------------------------------------------------------------------------------------|

|      ![](media/7f70ca7bc2b80c170176858d4665d123.jpeg) |
|-------------------------------------------------------|

| ![](media/2ab130b9f966f3c2bea7c1bf1bcbb34e.jpeg) ×2 <br>![](media/978472c08699356d8e41531bc78f88f8.jpeg) |
|------------------------------------------------------------------------------------------------------|

|       ![](media/ab50629bd3f770e2c659c9939224ca5f.jpeg) |
|--------------------------------------------------------|

| ![](media/8074fa84a8d4643be2f557c631031649.png)<br>![](media/0f365d8cca679c0616c980cc3e7504b3.jpeg) ×1 |
|----------------------------------------------------------------------------------------------------|

| ![](media/ecb04875cb8914e5613c98c22e2248e4.jpeg) |
|--------------------------------------------------|

| ![](media/4a537ee84fed9e8bc666a586fcddbb28.png)<br> ![](media/1e504364f59ef18e74ad0bb758a864ca.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|   ![](media/aa952df658a37397d4057fcfb021ba6f.jpeg) |
|----------------------------------------------------|

| ![](media/9f054842f5d66863eef9ecb7f092ec50.jpeg) <br>![](media/072e0e0da529af79dbd419f5385e541c.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------|

|    ![](media/6a85748079f59a8d69dea44e93f22d5a.jpeg) |
|-----------------------------------------------------|

| ![](media/20849435eb5af1894226b0230e162d26.jpeg) <br>![](media/2e37fe50f46b66c5771a2fb1e358aa91.jpeg) ×1  <br> ![](media/103f25a6fd2993c26e58736d85563bb4.jpeg) ×3  <br> ![](media/6b98069a8f6587f628f7d76d1cd1aa92.jpeg) ×2 <br>  ![](media/155d8b9a7aa5d9091ca12d59a8fc6254.jpeg) ×1 <br> ![](media/f1ac8f4502bb3b7e8097443327c7c841.jpeg) |
|--------------------------------------------------------------------|

|         ![](media/f1e5e5a4f82be8acb320825f2818b0e9.jpeg) |
|----------------------------------------------------------|

| ![](media/e61869f0804b981b65b6bf07a12a11c6.jpeg) <br>![](media/e31f6baf4e0429383510b6bcbde3306c.jpeg) ×1    <br>   ![](media/11963db0006edc98ac4cc1cacc5a6549.jpeg) ×1 |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------|

|        ![](media/fadcd1bd1c48c9df9f62fc8c021d6d0d.jpeg) |
|---------------------------------------------------------|

| ![](media/d82099e6fe969dd6d125bbb2b53d0ed1.jpeg) <br>![](media/e31f6baf4e0429383510b6bcbde3306c.jpeg)  ×1 |
|-------------------------------------------------------------------------------------------------------|

|         ![](media/da0833e7ca319685ea4bfbf5f927dd86.jpeg) |
|----------------------------------------------------------|

| ![](media/a2bac8f61e1957d1f44233ff4537bddd.jpeg) <br>![](media/725c1ae0f87eb0740671b922a2a43766.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------|

|          ![](media/da80e275c259622c887173f538963e2f.jpeg) |
|-----------------------------------------------------------|

| ![](media/fc2dc94470617e881aadbb7800b3b9e7.jpeg)<br> ![](media/a03eabc2fe08ed895ed2fea3f62ab2fc.jpeg) ×2 |
|------------------------------------------------------------------------------------------------------|

|    ![](media/564cd43d00cb4094aaa4e82acf1c12ed.jpeg) |
|-----------------------------------------------------|

| ![](media/a6b1e3a6d5751473c0143847a1651b7b.png) <br>![](media/7a15bcee6c3b5ef1f3db8dd54d390f85.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|      ![](media/745d08007689451bead6cd9839c2d63d.jpeg) |
|-------------------------------------------------------|

| ![](media/1cacce0d7c6f22725bb05024f6d15bf2.jpeg)<br> ![](media/dbd6fcc1ac0666a6ae9797e3b3bf7dde.jpeg) ×2 |
|------------------------------------------------------------------------------------------------------|

|     ![](media/c267e5c97443f26377216cac018f318e.jpeg) |
|------------------------------------------------------|

|  Before installing the servo, please initialize its angle <br>  ![](media/445b388c740c15f5c16d65607cce8e7c.png)  <br> Code for initializing the servo |       ![](media/sevro.png) |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|

|      ![](media/45b4d6155e5250b1d2b180489bda8419.png) |
|------------------------------------------------------|

|     ![](media/c124d7c0151cd7a2429c7ab409f015bb.jpeg) |
|------------------------------------------------------|

|           ![](media/91020230a45cff0a585d585a7df85200.jpeg)<br>The direction of the barrier gate remains horizontal |
|----------------------------------------------------------------------------------------------------------------|

|   ![](media/e4070dc564f66578d25d8c3762416e8f.jpeg) |
|----------------------------------------------------|

| ![](media/bf4cf2b71a9e5ea42cd19527d049b1b0.jpeg)<br>![](media/bf02a6a96245de7b6729258c92ce972c.jpeg) ×2 |
|-----------------------------------------------------------------------------------------------------|

|           ![](media/89cab42e6c3e5df544752638e15a534a.jpeg) |
|------------------------------------------------------------|

| ![](media/7eec6c85ed395169f63885cfba775c07.jpeg)<br> ![](media/578cc425e6c313a9cd3b445e1db94c82.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------|

|     ![](media/f4c26d96a929a8e1db363526b7777659.jpeg) |
|------------------------------------------------------|

| ![](media/80f1b25b7da67bfd505dc01f366b0168.jpeg) <br>![](media/9290986412bd6cc3ebd7ac45b13d24b9.jpeg) ×1   <br> ![](media/4a76e34a453c3b6afac67575b6b21e13.jpeg) ×2 |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------|

|  ![](media/1ce262f9098349aad82b57b39cb4b723.jpeg) |
|---------------------------------------------------|

| ![](media/c224e679c93f853e95f6f0e606d97c48.jpeg)<br>![](media/69a58094800ef0b73faa5ede332e2688.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|   ![](media/ead601266ffdfa40c24eb80c74b17d11.jpeg) |
|----------------------------------------------------|

| ![](media/60ec9eeadb98bfdd09cdd45b77e7e3f9.jpeg) <br>![](media/57af5f9e185e9368185422e6419e3dec.jpeg) ×2 |
|------------------------------------------------------------------------------------------------------|

| ![](media/a7e1ae0f5e265ca52336de9167594d8b.jpeg) |
|--------------------------------------------------|

| ![](media/dcceeb3832fdbc0dc95f4f4d64cf4404.jpeg) <br>![](media/a96b74f8a34f8f703ac188e84babc6e3.jpeg) ×2 |
|------------------------------------------------------------------------------------------------------|

|  ![](media/8bc06d1ca62f4573ba41e2c9c896e451.jpeg) |
|---------------------------------------------------|

| ![](media/2a8d5723a8393a348727eee57767cc2f.png) <br>![](media/9a5e499ad08cc90a5510bf6f8dbcb416.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|   ![](media/eab16b32478be0ca3f1593a42b89cc07.jpeg) |
|----------------------------------------------------|

| ![](media/cd524a101e7359ab672155e7f480b6c9.jpeg)<br>![](media/857196738b2e1836320435f058a1931b.jpeg) ×2 |
|-----------------------------------------------------------------------------------------------------|

|   ![](media/5114a0b77cc67e20943d9312dd5eb9b5.jpeg) |
|----------------------------------------------------|

| ![](media/912e4947285b088295a8c9e05a87f560.png) <br>![](media/32c40016dbcdb991a2a03f6faa9b18b5.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

| ![](media/e8ed7c1cb2cefc47bfb734e7222e6b4e.jpeg) |
|--------------------------------------------------|

| ![](media/bf4cf2b71a9e5ea42cd19527d049b1b0.jpeg)<br> ![](media/72bdfe0e6eff93cda1cb6d384d40d255.jpeg) ×2 |
|------------------------------------------------------------------------------------------------------|

|             ![](media/89cab42e6c3e5df544752638e15a534a.jpeg) |
|--------------------------------------------------------------|

| ![](media/f4822fd07058a11c70985bb6f6abf9a5.jpeg)<br> ![](media/578cc425e6c313a9cd3b445e1db94c82.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------|

|   ![](media/1b6394eae99917dc442b8cde146cd4fb.jpeg) |
|----------------------------------------------------|

| ![](media/befa5f25f50480947111d89428fc6637.jpeg)<br>![](media/a0ce3069b4f780a5df14281fd2b190c9.jpeg) ×1  <br>  ![](media/4d8a36d9136e550f3b54c7406158eb11.jpeg) ×2 |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|

|   ![](media/4b0687c04e5179e6784c15f7e13894b3.jpeg) |
|----------------------------------------------------|

| ![](media/6f5319e7926579766ba92ca9a8648ad5.jpeg) <br>![](media/c0111e43aa4481ad81f6a5ceacea1011.jpeg) ×1    <br>  ![](media/b494beed6c5e2d5fa0d7dd224e00c856.jpeg)  ×1 |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|

|   ![](media/8fa45482e9ad9ac3a524766bd1b089c3.jpeg) |
|----------------------------------------------------|

| ![](media/5de3800c24334d4e222904301da53435.jpeg)<br> ![](media/69a58094800ef0b73faa5ede332e2688.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------|

|  ![](media/d32aedb0b20aea426ab9d24c9f3c3e38.jpeg) |
|---------------------------------------------------|

| ![](media/677cd6f688b1f5b5a7cd9fecfec09b01.jpeg) <br>![](media/106de0632f2ef7f2b9979f6fe0c55548.jpeg) ×2   <br> ![](media/97d8ee39e7565156a6cdddb05e8c2d16.jpeg) ×1    <br>  ![](media/22adf246cd0a6be7bdaf50b837fce3df.jpeg) ×1 |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

|   ![](media/efc6741477ba4ca202861c0c5c720661.jpeg) |
|----------------------------------------------------|

| ![](media/3438d0daf25b77775cec806082cec1e0.jpeg) <br>![](media/fc6e3e3fb1c8f0d24fcc965fc5870c92.jpeg) ×2 |
|------------------------------------------------------------------------------------------------------|

|   ![](media/e8806ffb55daa2dead10a9f1d70b1a6b.jpeg) |
|----------------------------------------------------|

| ![](media/8ba12a8710c7c70e31f8ea7f0ba5f93d.jpeg)<br> ![](media/a15a1470e9dc96ecfc0b516a5421caa6.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------|

|  ![](media/c9230f450e3fb490a5f79fc3bb5719fb.jpeg) |
|---------------------------------------------------|

| ![](media/4ccf4beb7817b4ee1bdc4ad0b346f6e1.jpeg)<br> ![](media/3ca9b0396c4ab8cf484fb54fce405944.jpeg)  ×2 |
|------------------------------------------------------------------------------------------------------|

|    ![](media/7a4af2c0e22621471ce338d40089a65b.jpeg) |
|-----------------------------------------------------|

| ![](media/c4e727393867b95d52b2e0c20023908a.png)<br> ![](media/5c08065cccaddb2385eeae9633e3bedf.jpeg) ×1 |
|----------------------------------------------------------------------------------------------------|

| ![](media/1f61c66651add6bd93f71f8e24054540.jpeg) |
|--------------------------------------------------|

|  ![](media/84c6865a56cc7217322440b8f7f0dc51.jpeg) |
|---------------------------------------------------|

|   ![](media/b2c25cdf71b4ded4f428c509c8cfa522.jpeg) |
|----------------------------------------------------|

| ![](media/86f501aea516f43f167da4041a9ab55d.png)<br> ![](media/2098c6a30d1ed2488e5ae4667af7fcf1.jpeg) ×1 |
|-----------------------------------------------------------------------------------------------------|

|   ![](media/b6433096c820fdf833e00de8e5a98c35.jpeg) |
|----------------------------------------------------|

| ![](media/610d674e8be0c9b5f0d754f53d53606f.jpeg) |
|--------------------------------------------------|

| ![](media/a98e3f2630561497f57991e439ec70cb.jpeg) <br> ![](media/90eb36cbd46247f3812a7e0b2f5ae1c5.jpeg)  ×1 |
|--------------------------------------------------------------------------------------------------------|

|     ![](media/95297ec7f1f634ae347ff850d62e4520.jpeg) |
|------------------------------------------------------|

| ![](media/9bb1834aa6f3a82972f756fa56b13ce9.jpeg)<br> ![](media/b502ebf13c07a42cf502356cb8fbfd12.jpeg) ×1 |
|------------------------------------------------------------------------------------------------------|

|      ![](media/efb95aa03980607fb74a65094004a9e1.jpeg) |
|-------------------------------------------------------|

| ![](media/8b669de61313b547cab9cd5a3615d432.jpeg) <br> ![](media/d7b8f41482c5be70b2b2b18dfdde288b.jpeg) ×1 |
|-------------------------------------------------------------------------------------------------------|

|       ![](media/59e0f5aedfb9b24f59b4d4f8e0863c57.jpeg) |
|--------------------------------------------------------|

| ![](media/c60b00fda1ed781050f80de3fc43f37b.jpeg)  <br> ![](media/174fb0d996008c9bd16ed1bb4187abdd.jpeg) ×1 |
|--------------------------------------------------------------------------------------------------------|

|         ![](media/536774b60f0c3c163cb0d811ba599bf8.jpeg) |
|----------------------------------------------------------|

| ![](media/dabd5cdc6120f580519e20a5b9aa0bf7.png)<br> ![](media/054684b406ef8e07f76dbadefb41cf87.jpeg)  ×2   <br>  ![](media/13d73a98fe981068613eef79363efb13.jpeg) ×1 |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------|

|         ![](media/68936bdc9cdd63a812a69d9d9e086dd6.jpeg) |
|----------------------------------------------------------|

| ![](media/9ca7536c8b7d10de11aba5f85ba14f1b.jpeg) <br>![](media/a290c9f03463bdec99a861d8e0faf7ce.jpeg) ×3 |
|------------------------------------------------------------------------------------------------------|

|       ![](media/230f800dbb06be80acdf94767fd0e638.jpeg) |
|--------------------------------------------------------|

| ![](media/b1f80f903c306f9403af0c5d3b03d072.jpeg) ×1 <br> ![](media/a2fa8ae61e9754d20077d50362575f11.jpeg) |
|-------------------------------------------------------------------------------------------------------|

|         ![](media/0290ecae7677e6c9b6cc46fee124d88e.jpeg) |
|----------------------------------------------------------|

|   ![](media/96ef7862abac3920e584ca0001d3af06.jpeg) ×4  <br>  ![](media/40c7729194440b342b6d083934461cca.png) |
|----------------------------------------------------------------------------------------------------------|

|         ![](media/c2aa8b74cab30da8361ae496b215c9cf.jpeg) |
|----------------------------------------------------------|

| ![](media/2c0b06fb90b0b3d902568eb43e14ab2b.png) <br>![](media/5c662d831955a727582867ac00f548cb.jpeg) ×4 |    2\*4 |
|-----------------------------------------------------------------------------------------------------|---------|

|           ![](media/6ae2e0899f7ded8767a769afad8d660c.jpeg) |
|------------------------------------------------------------|

|  ![](media/1431dbfb74d25552d20748f8e3c42e39.jpeg)    |    2\*4 |
|------------------------------------------------------|---------|
| ×4   ![](media/e0c7b9928fd2b2a5db5819e2b15aa0a7.png) |         |

|        ![](media/2a9456dc08f4da3727de2fc6fed6ecae.jpeg) |
|---------------------------------------------------------|

| ![](media/09bbfd3e156d5894fbc76889fd913095.jpeg)     2\*4  ×2 <br> ![](media/fe0eca78711d44fc0d80bf927be2feaa.png) |
|----------------------------------------------------------------------------------------------------------------|

|        ![](media/38471620827c76108cdb52d359b5b944.jpeg) |
|---------------------------------------------------------|

| ![](media/713b20aa88ee3ed0b99f83eddf25d4ae.png)<br>![](media/4537cca8512e020d29055dcde856b62c.jpeg) ×5 |  1\*4 |
|----------------------------------------------------------------------------------------------------|-------|

|       ![](media/a599525ce3c9a56665165d6f06be64df.jpeg) |
|--------------------------------------------------------|

| ![](media/14875cd77199245a201e1ef90fc98b71.png)<br>![](media/4537cca8512e020d29055dcde856b62c.jpeg) ×2 |  1\*4 |
|----------------------------------------------------------------------------------------------------|-------|

|      ![](media/a6b87802666e905ba1c716ec4c47e45d.jpeg) |
|-------------------------------------------------------|

| ![](media/6f53e48a91f1b0cca3f6853795183344.jpeg) ×2  <br> ![](media/83831406ef44c8bd80ee10ae4787dbd3.png) |
|-------------------------------------------------------------------------------------------------------|

|        ![](media/985a1d9e9a8a8d919b10a672f67873b5.jpeg) |
|---------------------------------------------------------|

| ![](media/4a2182b5d36c99036b8b8bb39a55a765.jpeg) ×4  <br> ![](media/d8609f0aa8526ce3621689758ee2989c.png) |
|-------------------------------------------------------------------------------------------------------|

|         ![](media/1d9ad011e6030756df1a3d06dbc597d2.jpeg) |
|----------------------------------------------------------|

|   ![](media/0382eecdb75f81f5a64f3e405a4c2e7c.png) |
|---------------------------------------------------|

|      ![](media/1d5d594febddbf9b46123b4e03ef92a8.jpeg) |
|-------------------------------------------------------|

|                                                 |
|-------------------------------------------------|
| ![](media/52c009aec9c2f917e561148ef8159c95.png) |
|                                                 |

|                                                  |
|--------------------------------------------------|
| ![](media/9a1e5741b68d81a1f69793830310eb60.jpeg) |
|                                                  |

|   The barrier gate should be parallel to the board |
|----------------------------------------------------|
| ![](media/4965fc4332c19749e11298b35d09af74.png)    |
|                                                    |

|                                                  |
|--------------------------------------------------|
| ![](media/79adb61a4d41eed986fbe2712e8665ea.jpeg) |
|                                                  |

|    ![](media/007af33018e6fbb6e8d5d9c40478d430.png) |
|----------------------------------------------------|

|   ![](media/47fbbf6c60125ea4be2cab9e7ec4c4de.jpeg) |
|----------------------------------------------------|

|   ![](media/7619a8ec4f12e6a7153d8824721a3189.png) |
|---------------------------------------------------|

|      ![](media/45ddb041f8a9e934faf6c6df507b0379.jpeg) |
|-------------------------------------------------------|

|      ![](media/a3b61d07ab3fa6a53114190048501723.png)<br>The main board can be placed between the gate and the street lamps |
|------------------------------------------------------------------------------------------------------------------------|

|   Prototype |
|-------------|

|  ![](media/3281dc70db55bf2edbb8ee2e7a34f7b0.jpeg) |
|---------------------------------------------------|


 Wiring Diagram

![Img](/media/813.png)

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

![Img](/media/814.png)
<br>

![Img](/media/815.png)

**Extension** Instruction 
<br>

![Img](/media/816.png)

Add **Servo** Module

![Img](/media/817.png)

Add **Ultrasonic** Sensor

![Img](/media/818.png)

Add **Matrix 8*8 IIC** Display

![Img](/media/819.png)

 Flow Chart

![Img](/media/820.png)


 Write the Program

![Img](/media/821.png)

 Test Result

Click![Img](/media/822.png) to upload the complete program to the kidsuno mainboard and power up. Then the effect of the intelligent integrate traffic system will appear.

![Img](/media/img-20230714083338.png)









































































































































































































































































