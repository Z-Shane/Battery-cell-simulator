这是在设计FSAE（FSEC）比赛工况的电池管理系统时，额外设计的小工具，可安全的进行BMS开发，提高开发速度，模拟电芯多种故障状态。

This is an additional small tool designed when developing the battery management system for the FSAE (FSEC) competition. It can safely facilitate BMS development, increase the development speed, and simulate various fault states of battery cells.

采用12v供电，具有防反接电路。利用隔离电源➕LDO实现对电芯电压模拟。

It is powered by 12v and features an anti-reverse connection circuit. The cell's voltage is simulated using the isolated power supply ➕LDO.

调节蓝色可变电阻实现对单体电压的调节。

The voltage of individual cells is regulated by adjusting the blue variable resistor.

如果有需求，可以再根据你的AFE温度采样电路增加可变电阻进行模拟。

If necessary, you can add a variable resistor to your AFE temperature sampling circuit for simulation.

此仓库包含三个文件，可用于直接制造的15串电芯模拟器的Gerber文件，嘉立创eda的工程文件以及原理图。

This warehouse contains three files: the Gerber file for a 15-string cell simulator , the engineering file of 嘉立创eda, and the schematic diagram.

可根据自己的需求调整串数并重新layout.

You can adjust the number of strings according to your own needs and re-layout.

如果对你有帮助，请在你的PCB板子上留下湖南大学方程式赛车队的对标（HUR），请勿用于商业用途。

If it is helpful to you, please leave the logo of Hunan University Racing Team (HUR) on your PCB board. Do not use it for commercial purposes.


<img width="1005" height="932" alt="image" src="https://github.com/user-attachments/assets/1bda0caa-c48e-4934-a8c1-5c27ca7998b7" />

<img width="1614" height="575" alt="image" src="https://github.com/user-attachments/assets/5bf5226a-2bec-4d64-be02-1af837d672dc" />

<img width="350" height="927" alt="image" src="https://github.com/user-attachments/assets/ad1ec8b6-2f9c-4e70-9b6d-eabe6b0c02ab" />
