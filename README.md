<img width="574" height="221" alt="image" src="https://github.com/user-attachments/assets/937d8aa9-ecc6-418c-bbaa-c8073f3f40ed" /># DC-AC

<img width="716" height="721" alt="image" src="https://github.com/user-attachments/assets/b13b2013-8666-41aa-abc1-60939f6e57bd" />

<img width="665" height="649" alt="image" src="https://github.com/user-attachments/assets/0d1dea99-929a-447a-9356-96b30f00ec3f" />

<img width="717" height="180" alt="image" src="https://github.com/user-attachments/assets/3867cbcc-06af-46af-962b-da2efc3d9cdf" />
12V电源输入，经过电容滤波和LM2596S芯片开关电压输出降压为5V在经过L1电感储能和滤波电容输出，D4肖特基二极管为防止芯片开启时电感反向输出时破坏电路，反向回复电流，芯片关闭时电感反向经过电流，L1电感能防止电流突变 进行储能 
芯片选型LM25996S-5.0 散热好，成本低，输出电流适中，输出电压稳定

<img width="865" height="138" alt="image" src="https://github.com/user-attachments/assets/2c7d2cae-f195-4405-b744-2ab5c452bcc2" />

下面电源经过连接端子通过LED灯确保电流经过


5V电容滤波后经过AMS1117-3.3再经过高低滤波电容输出3.3V
选型AMS1117-3.3是成本较低，散热要求不高，精度满足

<img width="844" height="658" alt="image" src="https://github.com/user-attachments/assets/b1c8f88d-cdfd-487f-ae69-bb7604898bf1" />

<img width="290" height="191" alt="image" src="https://github.com/user-attachments/assets/3807395c-8330-4063-a7ae-a148668a9544" />

<img width="573" height="556" alt="image" src="https://github.com/user-attachments/assets/bcbd59aa-4a4d-4b0b-beb2-2ba3112192ab" />

STM32模块 输出PWM和SD  接受电压和电流数据输出到OLED显示屏

<img width="447" height="628" alt="image" src="https://github.com/user-attachments/assets/d022140f-bdcf-4aa4-9133-128a31c12d7f" />

STM32输出高低电平到DCOUT，通过DCOUT高低电平控制Q3三极管的导通，导通时5V输入，LED灯亮，线圈带电使2和5连接，输出低BE电压小于发射极开启电压，Q4断开，灯灭，线圈不带电

<img width="711" height="622" alt="image" src="https://github.com/user-attachments/assets/74abdea6-74cc-4403-957b-527161fefee4" />

STM32控制PWM和SD的输出，通过IR204STRPBF和VS的电流和C49自举电容和D5肖特基二极管来控制HO和LO高低电流转换来控制Q1和Q2的通断
输入1K电阻防止电流过大损坏芯片

<img width="865" height="175" alt="image" src="https://github.com/user-attachments/assets/03658425-3253-4cd1-9606-7e2a3767af4c" />

R90取样电阻
R90分压加R88分压再接运放得电压倍数 34

<img width="502" height="405" alt="image" src="https://github.com/user-attachments/assets/4138b494-949e-4cb1-9830-724b604073bb" />

1.5V参考电压

<img width="368" height="320" alt="image" src="https://github.com/user-attachments/assets/cbf4f249-00e5-4b80-bd8e-bee2e3fd6a0e" />

上桥下桥靠2104驱动四个mos管输出交流电压

<img width="863" height="427" alt="image" src="https://github.com/user-attachments/assets/8af6f302-8adc-426f-9aa9-4a6a0e984dfb" />
