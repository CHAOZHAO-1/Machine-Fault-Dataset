# Machine-Fault-Diagnosis-Dataset-PHM

**Updata: 2024-05-10, All data connections are now ready!!!!!**

We have compiled open source datasets of machinery fault in recent years (from near to far).

We will complete the repository as soon as possible.

We hope this repository will help you with your research.


Roadmap
==

A-Bearing(轴承)；B-Gear(齿轮)；C-Others (其他)；D-RUL(寿命预测相关)
|                                            原始数据连接（Orignal   Link）                                           	| 备用数据连接(Alternate Link)                       	| 序号（Index）        	| 年(Year) 	| 数据集名称(Dataset Name)         	| 部件名称(Component Name) 	| 故障产生方式(Fault generation mode)        	| 工况情况（Working Condition） 	| 故障情况(Fault Type)                   	| 信号类型(Signal Yype)    	|
|:-------------------------------------------------------------------------------------------------------------------:	|----------------------------------------------------	|----------------------	|----------	|----------------------------------	|--------------------------	|--------------------------------------------	|-------------------------------	|----------------------------------------	|--------------------------	|
| [[data   link](https://engineering.case.edu/bearingdatacenter/download-data-file)]                                  	| [[data link](https://pan.quark.cn/s/9982eb5f3364)] 	| [A1](#section-id1)   	| 2015     	| 凯斯西储（CWRU）                 	| 轴承（bearing）          	| 人工注入（Artificial）                     	| 4 type (0,1,2,3 hp)           	| Inner race-outer race-ball             	| 振动（Acceleration）     	|
| [[data   link](https://mb.uni-paderborn.de/kat/forschung/kat-datacenter/bearing-datacenter/data-sets-and-download)] 	| [[data link](https://pan.quark.cn/s/2e5b67e8fec4)] 	| [A2](#section-id2)   	| 2016     	| 帕德博恩（KAT）                  	| 轴承（bearing）          	| 人工注入和自然失效（Artificial and RTF）　 	| 4 type　                      	| /                                      	| 振动（Acceleration）　   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/b820f4ccaa75)] 	| [A3](#section-id3)   	| 2013     	| 江南大学（JNU）                  	| 轴承（bearing）          	| 人工注入（Artificial） 　                  	| 3 type（600,800,1000）        	| Inner race-outer race-ball 　          	| 振动（Acceleration） 　  	|
| [[data   link](https://www.mfpt.org/fault-data-sets/)]                                                              	| [[data link](https://pan.quark.cn/s/a8ef4a6f806e)] 	| [A4](#section-id4)   	| 2013     	| 美国机械故障预测技术委员会(MFPT) 	| 轴承（bearing）          	| 人工注入（Artificial）　                   	| /                             	| Inner race-outer race　                	| 振动（Acceleration）     	|
| [[data   link](https://www.nasa.gov/intelligent-systems-division/#bearing)]                                         	| [[data link](https://pan.quark.cn/s/c459b893a748)] 	| [A5](#section-id5)   	| 2006     	| 辛辛那提大学（IMS）              	| 轴承（bearing）          	| 自然失效（Artificial and RTF）             	| /　                           	| Inner race-outer race-ball 　          	| 振动（Acceleration）     	|
| [[data   link](ftp://ftp.polito.it/people/DIRG_BearingData/)]                                                       	| [[data link](https://pan.quark.cn/s/107b919581ea)] 	| [A6](#section-id6)   	| 2019     	| 都灵大学（DIRG）                 	| 轴承（bearing）          	| 人工注入和自然失效（Artificial and RTF）   	| /　                           	| Inner race-outer race　                	| 振动（Acceleration）　   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/b9cb8f0d3417)] 	| [A7](#section-id7)   	| 2016     	| 自吸泵（SCP）                    	| 轴承（bearing）          	| 人工注入（Artificial）                     	| /　                           	| Inner race-outer race-ball             	| 振动（Acceleration）　   	|
| [[data   link](https://github.com/HouLeiHIT/HIT-dataset)]                                                           	| [[data link](https://pan.quark.cn/s/57637395e45e)] 	| [A8](#section-id8)   	| 2023     	| 哈工大(HIT)                      	| 轴承（bearing）          	| 人工注入（Artificial）                     	| /　                           	| Inner race-outer race                  	| 振动（Acceleration）　   	|
| [[data link]()]                                                                                                     	| [[data link](https://pan.quark.cn/s/a6d1f772fb07)] 	| [A9](#section-id9)   	| 2021     	| SQV变转速                        	| 轴承（bearing）          	| 人工注入（Artificial）                     	| /　                           	| Inner race-outer race                  	| 振动（Acceleration）　   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/5bb98ecb8e79)] 	| [A10](#section-id10) 	| 2023     	| 越南大学                         	| 轴承（bearing）          	| 人工注入（Artificial）                     	| 3 type　                      	| Inner race-outer race-ball             	| 振动（Acceleration）     	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/e2ab44db62aa)] 	| [A11](#section-id11) 	| 2021     	| DC竞赛                           	| 轴承（bearing）          	| /　                                        	| /　                           	| /　                                    	| /　                      	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/1726006de15a)] 	| [A12](#section-id12) 	| 2024     	| 华中科技大学轴承（HUSTbearing）  	| 轴承（bearing）          	| 人工注入（Artificial） 　                  	| 4 type　                      	| Inner race-outer race-ball-Combination 	| 振动（Acceleration）　   	|
| [[data link]()]                                                                                                     	| [[data link](https://pan.quark.cn/s/7690e4d4e0aa)] 	| [B1](#section-id13)  	| 2019     	| 东南大学                         	| 齿轮(Gear)               	| 人工注入（Artificial） 　                  	| 2 type　                      	| 5 type                                 	| 振动（Acceleration）　　 	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/edd382287d69)] 	| [B2](#section-id14)  	| 2009     	| PHM09                            	| 齿轮(Gear)               	| 人工注入（Artificial） 　                  	| 10 type　                     	| /　                                    	| 振动（Acceleration）　   	|
| [[data link]()]                                                                                                     	| [[data link](https://pan.quark.cn/s/32aea4fbd229)] 	| [B3](#section-id15)  	| 2023     	| 行星齿轮                         	| 齿轮(Gear)               	| 人工注入（Artificial）　                   	| /　                           	| /　                                    	| 振动（Acceleration）　   	|
| [[data link]()]                                                                                                     	| [[data link](https://pan.quark.cn/s/051b5b6cda3f)] 	| [B4](#section-id16)  	| 2021     	| 西安交通                         	| 齿轮(Gear)               	| 人工注入（Artificial） 　                  	| /　                           	| /　                                    	| 振动（Acceleration）　   	|
| [[data link]()]                                                                                                     	| [[data link](https://pan.quark.cn/s/9c4fb31447f9)] 	| [B5](#section-id17)  	| 2021     	| 一阶减速器（LW）                 	| 齿轮(Gear)               	| 人工注入（Artificial） 　                  	| 6 type　                      	| 4 type                                 	| 振动（Acceleration）　   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/4d3bf3297f74)] 	| [B6](#section-id18)  	| 2024     	| 华中科技大学齿轮（HUSTGear）     	| 齿轮(Gear)               	| 人工注入（Artificial） 　                  	| 4 type　                      	| 3 type                                 	| 振动（Acceleration）　   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/2fc5f930648b)] 	| [C1](#section-id19)  	| 2015     	| 工业过程故障                     	| 工业过程(Process)        	| /　                                        	| /　                           	| 5 type                                 	| 24 维变量（Variables）   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/6d1ec2b7f004)] 	| [C2](#section-id20)  	| 2020     	| 冷却机故障                       	| 冷却机(Chiller)          	| /                                          	| /                             	| 7 type                                 	| /                        	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/ee74b087b0f0)] 	| [C3](#section-id21)  	| 2019     	| 转子故障                         	| 转子(Rotor)              	| /                                          	| /                             	| /                                      	| 振动（Acceleration）　   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/e6e0f4b556dd)] 	| [C4](#section-id22)  	| 2018     	| 发动机                           	| 发动机(Engine)           	| /                                          	| /                             	| /                                      	| /                        	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/b2850c92701a)] 	| [C5](#section-id23)  	| 2024     	| 海上石油勘探电浅泵               	| 泵(Pump)                 	| /                                          	| /                             	| /                                      	| /                        	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/e412cedabb2b)] 	| [C6](#section-id24)  	| 2023     	| 科大讯飞水泵状态挑战赛           	| 水泵(Pump)               	| /                                          	| /                             	| /                                      	| /                        	|
| [[data link]()]                                                                                                     	| [[data link](https://pan.quark.cn/s/df64f70c77c0)] 	| [C7](#section-id25)  	| 2022     	| 德国火车                         	| 火车轮毂(Train)          	| 人工注入和自然失效（Artificial and RTF）   	| /                             	| /                                      	| 振动（Acceleration）　   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/0e4fd9fa46ee)] 	| [C8](#section-id26)  	| 2023     	| 变压器故障                       	| 变压器(Transformer)      	| /                                          	| /                             	| /                                      	| /                        	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/abcfaa2c66b3)] 	| [D1](#section-id27)  	| 2018     	| 西交全寿命周期                   	| 轴承（bearing）          	| 自然失效（Artificial and RTF）             	| /                             	| /                                      	| 振动（Acceleration）　   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/fcfbfba0743c)] 	| [D2](#section-id28)  	| 1996     	| 磨削退化(Tool mill)              	| 刀具（Tool）             	| 自然失效（Artificial and RTF）             	| /                             	| /                                      	| 振动（Acceleration）　   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/cf663fda7dca)] 	| [D3](#section-id29)  	| 2021     	| UNSW                             	| 轴承（bearing）          	| 自然失效（Artificial and RTF）             	| /                             	| /                                      	| 振动（Acceleration）　   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/03d90fb23238)] 	| [D4](#section-id30)  	| 2012     	| PHM2012                          	| 轴承（bearing）          	| 自然失效（Artificial and RTF）             	| /                             	| /                                      	| 振动（Acceleration）　   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/89925bcef3f9)] 	| [D5](#section-id31)  	| 2020     	| CMPASS引擎退化                   	| 轴承（bearing）          	| 自然失效（Artificial and RTF）             	| /                             	| /                                      	| 振动（Acceleration）　   	|
| /                                                                                                                   	| [[data link](https://pan.quark.cn/s/d38935c0e01a)] 	| [D6](#section-id32)  	| 2010     	| PHM2010                          	| 轴承（bearing）          	| 自然失效（Artificial and RTF）             	| /                             	| /                                      	| 振动（Acceleration）　   	|

# A1-凯斯西储轴承数据集（CWRU）
<a name="section-id1"></a>
## 试验台

![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A1.png)


一个1.5KW（2马力）的电动机（图左侧）；

一个扭矩传感器/ 译码器（图中间连接处）；

 一个功率测试计（图右侧）；

驱动端轴承为SKF6205 ，采样频率为12Khz和48Khz；

电子控制器(图中没显示) 。

## 数据集简要概述
DE - drive end accelerometer data 驱动端加速度数据；

FE - fan end accelerometer data 风扇端加速度数据；

BA - base accelerometer data 基座加速度数据（正常）；

time - time series data 时间序列数据；

RPM- rpm during testing 转/每分钟，除以60为旋转频率；

B -滚动体故障；IR – 内圈故障；OR –外圈故障；

驱动端和风扇端轴承外圈的损伤点分别放置在3点钟、6点钟、12点钟三个不同位置。

数据文件为MATLAB格式。每个文件包含风扇和驱动端振动数据，以及电机转速。

例子：12k_Fan_End_OR007@6_3_297.mat

        12k：12KHZ采样频率

        Fan_End_OR：风扇端外圈故障

        007：直径

        @6：外圈的损伤点在6点钟位置

        3：表电机载荷模式

        297：编号。

数据集由 
        12kHz采样率下电机端轴承的故障数据（DE）60个、

        12kHz采样率下风扇端轴承的故障数据（FE）45个、

        48kHz采样率下电机端轴承的故障数据（DE）52个，

        还有正常运转的轴承数据4个组成。

## 使用该数据集的相关论文

[1]  Smith, Wade A., and Robert B. Randall. "Rolling element bearing diagnostics using the Case Western Reserve University data: A benchmark study." Mechanical systems and signal processing 64 (2015): 100-131.  
[2]  Wen, Long, et al. "A new convolutional neural network-based data-driven fault diagnosis method." IEEE Transactions on Industrial Electronics 65.7 (2017): 5990-5998.  

# A2-帕德博恩大学轴承数据集（KAT）

## 试验台
<a name="section-id2"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A2.jpg)


## 数据集简要概述

试验台由几个模块组成（从左到右依次为）：（1）电动机、（2）扭矩测量轴、（3）滚动轴承测试模块、（4）飞轮和（5）负载电机，如上图所示。
通过将不同损伤类型的滚珠轴承安装在轴承测试模块中，生成实验数据。

从帕德伯恩大学获得的PU数据集是一个6203轴承数据集，包括人为诱发的和真实的损害。采用压电加速度计采集轴承座的振动信号，采样频率为64 kHz。通过改变驱动系统的转速，测试轴承上的径向力，以及驱动系统上的负载扭矩，PU数据集由四种运行条件组成

人工损伤主要通过电火花（裂纹）、钻孔（剥落）和电动雕刻机（点蚀）  
电放电加工electrical discharge machining (EDM)（滚动方向长度为0.25毫米的沟槽和深度为1-2 mm）  
钻孔drilling （直径：0.9 mm，2 mm，3毫米）  
手动电动雕刻（损坏长度从1-4毫米）manual electric engraving  


真实损伤轴承通过加速寿命试验台得到

电机电流的采样频率为：64KHz

振动信号的采样频率为：64KHz

机械参数(加载力，加载力矩，速度)的采样频率:4KHz

温度的采样频率为：1Hz


## 使用该数据集的相关论文

[1] Lessmeier, Christian, et al. "Condition monitoring of bearing damage in electromechanical drive systems by using motor current signals of electric motors: A benchmark data set for data-driven classification." PHM Society European Conference. Vol. 3. No. 1. 2016.  
[2] Zhu, Zhiyu, et al. "A convolutional neural network based on a capsule network with strong generalization for bearing fault diagnosis." Neurocomputing 323 (2019): 62-75.  



# A3-江南大学轴承数据集（JNU）

## 试验台
<a name="section-id3"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A3.png)


## 数据集简要概述

采样频率：50khz  
转速：600, 800, 1000 (rpm/min)  
内圈：ib  
外圈：ob  
滚动体：tb  
正常：N  



## 使用该数据集的相关论文

[1]  Zhao, Chao, and Weiming Shen. "Dual adversarial network for cross-domain open set fault diagnosis." Reliability Engineering & System Safety 221 (2022): 108358.  
[2]  Zhao, Baining, et al. "Signal-to-signal translation for fault diagnosis of bearings and gears with few fault samples." IEEE Transactions on Instrumentation and Measurement 70 (2021): 1-10.  

# A4-美国机械故障预测技术委员会轴承数据集（MFPT）
## 试验台
<a name="section-id4"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A4.png)


## 数据集简要概述

MFPT 数据包含 23 个在各种故障条件下从机器收集的数据集。

前20个数据集是从轴承试验台收集的，其中3个在良好条件下，3个在恒定载荷下出现外圈故障，7个在各种载荷下出现外圈故障，7个在各种载荷下出现内圈故障。  


其余三个数据集来自真实世界的机器：油泵轴承、中速轴承和行星轴承。故障位置未知。在此示例中，您仅使用从具有已知条件的测试远程测试机组 （Rig） 收集的数据。  

每个数据集都包含一个加速度信号、采样率、轴速、负载重量和四个代表不同故障位置的临界频率：
球通过频率外圈 （BPFO  
球通过频率内圈 （BPFI  
基本列车频率 （FTF） 
球旋转频率 （BSF）  


## 使用该数据集的相关论文

[1] Zuo, Lin, et al. "A spiking neural network-based approach to bearing fault diagnosis." Journal of Manufacturing Systems 61 (2021): 714-724.   
[2] Sun, Guodong, et al. "Fine-grained fault diagnosis method of rolling bearing combining multisynchrosqueezing transform and sparse feature coding based on dictionary learning." Shock and Vibration 2019 (2019): 1-13.    

# A5-辛辛那提大学轴承数据集（IMS）
## 试验台
<a name="section-id5"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A5.png)


## 数据集简要概述
该数据集文件统一是Ascll格式的数据。文件每10分钟记录一次数据，每个文件由20,480个点组成，采样率设置为20.48K H。因此一个文件也就是采集了1s的数据。

（1）数据集1有4个轴承
每个轴承分别有两个通道，在试验-失效实验结束时，轴承3出现内圈缺陷，轴承4出现滚子元件缺陷。 
 
（2）数据集2有4个轴承
每个轴承一个通道。在试验到失效实验结束时，轴承1发生了外圈故障。  

（3）数据集3有4个轴承
每个轴承一个通道。在试验到失效实验结束时，轴承3发生了外圈故障。  

## 使用该数据集的相关论文

[1]  Zhang, Shen, et al. "Semi-supervised bearing fault diagnosis and classification using variational autoencoder-based deep generative models." IEEE Sensors Journal 21.5 (2020): 6476-6486.  
[2]  Zhang, Ran, et al. "Fault diagnosis from raw sensor data using deep neural networks considering temporal coherence." Sensors 17.3 (2017): 549.  

# A6-都灵大学轴承数据集（DIRG）
## 试验台
<a name="section-id6"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A6.png)


## 数据集简要概述



| Name | Defect                          | Dimension (mm) |
|------|---------------------------------|----------------|
| 0A   | NO DEFECT                       | -              |
| 1A   | Diameter of an indentation on the inner ring | 450            |
| 2A   | Diameter of an indentation on the inner ring | 250            |
| 3A   | Diameter of an indentation on the inner ring | 150            |
| 4A   | Diameter of an indentation on a roller      | 450            |
| 5A   | Diameter of an indentation on a roller      | 250            |
| 6A   | Diameter of an indentation on a roller      | 150            |




| Nominal Load (N) | Nominal Speed (Hz) | Nominal Speed (Hz) | Nominal Speed (Hz) | Nominal Speed (Hz) |
|------------------|---------------------|---------------------|---------------------|---------------------|
| 0                | 100                 | 200                 | 300                 | 400                 | 500                 |
| 1000             | 100                 | 200                 | 300                 | 400                 | 500                 |
| 1400             | 100                 | 200                 | 300                 | 400                 | -                   |
| 1800             | 100                 | 200                 | 300                 | -                   | -                   |

六个通道的时间历史数据以采样频率fs = 51,200 Hz进行收集，持续时间为T = 10秒。数据记录在文件中，其名称采用以下格式：CnA_fff_vvv_m.ma。

## 使用该数据集的相关论文

[1]  Wang, Yu, et al. "Curriculum learning-based domain generalization for cross-domain fault diagnosis with category shift." Mechanical Systems and Signal Processing 212 (2024): 111295.  
[2]  Wang, Cunjun, et al. "Mix-VAEs: A novel multisensor information fusion model for intelligent fault diagnosis." Neurocomputing 492 (2022): 234-244.  


# A7-自吸泵轴承数据集（SCP）
## 试验台
<a name="section-id7"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A7.png)


## 数据集简要概述

故障类型：正常，内圈，外圈，滚珠

单一工况








# A8-哈工大轴承数据集 (HIT)
## 试验台
<a name="section-id8"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A8.png)


## 数据集简要概述

故障类型：正常，内圈，外圈

工况超20种

# A9-SQV变转速轴承数据集
## 试验台
<a name="section-id9"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A9.png)


## 数据集简要概述

收集了上述六种故障轴承和正常状态（NC）轴承的振动信号，共七种不同的健康状态：正常, 内圈故障（轻度、中度和重度）, 外圈故障（轻度、中度和重度）。每次实验采集时长为15秒，包含一个完整的从静止状态逐渐加速至3000rpm，后保持稳定，最后逐渐减速为0的加减速过程。
轴承型号：NSK6203

采频：fs=25600Hz
通道2： 振动信号
通道3： 转速脉冲信号



Bearing: NSK6203
Sampling frequency: 25600Hz

Channel 2: Vibration signal 
Channel 3: Rotational speed pulse signal


## 使用该数据集的相关论文

[1]  
[2]  


# A10-越南大学轴承数据集
## 试验台
<a name="section-id10"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A10.png)


## 数据集简要概述

该数据集包含了5种类型的轴承（6204、6205、6206、6207和6208）在3种工作条件（0瓦、200瓦和400瓦）下的6种缺陷类型（内圈、外圈、球及其2种复合故障）的99个原始振动信号。

每个振动信号以每秒51200个样本的速率进行采样，持续10秒。

# A11-DC竞赛轴承数据集
## 数据集简要概述
<a name="section-id11"></a>

轴承有3种故障：外圈故障，内圈故障，滚珠故障，外加正常的工作状态。

结合轴承的3种直径（直径1,直径2,直径3），轴承的工作状态有10类

可供下载使用的有2个文件：

1.train.csv，训练集数据，1到6000为按时间序列连续采样的振动信号数值，每行数据是一个样本，共792条数据，第一列id字段为样本编号，最后一列label字段为标签数据，即轴承的工作状态，用数字0到9表示。

2.test_data.csv，测试集数据，共528条数据，除无label字段外，其他字段同训练集。

总的来说，每行数据除去id和label后是轴承一段时间的振动信号数据，选手需要用这些振动信号去判定轴承的工作状态label。

注意：同一列的数据不一定是同一个时间点的采样数据，即不要把每一列当作一个特征。


# A12-华中科技大学轴承数据集（HUST）
## 试验台
<a name="section-id12"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A12.png)


## 数据集简要概述

This dataset comprises vibration signals from bearings in nine different health states under four distinct operating conditions. These datasets are publicly available, and anyone can use them to validate diagnosis algorithms for rolling element bearings. 


## 使用该数据集的相关论文

[1]  Zhao, Chao, and Weiming Shen. "A federated distillation domain generalization framework for machinery fault diagnosis with data privacy." Engineering Applications of Artificial Intelligence 130 (2024): 107765.    
[2]  Zhao, Chao, and Weiming Shen. "Federated domain generalization: A secure and robust framework for intelligent fault diagnosis." IEEE Transactions on Industrial Informatics (2023).  


# B1-东南大学齿轮数据集（SEU）
## 试验台
<a name="section-id13"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/B1.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  

# B2-PHM09齿轮数据集（PHM09）
## 试验台
<a name="section-id14"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/B2.jpg)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  

# B3-行星齿轮齿轮数据集（XXXX）
## 试验台
<a name="section-id15"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/B3.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  


# B4-西安交通大学齿轮数据集（XXXX）
## 试验台
<a name="section-id16"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/B4-1.jpg)

![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/B4-2.jpg)

## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  




# B5-一阶减速器齿轮数据集（XXXX）
## 试验台
<a name="section-id17"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/B5.jpg)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  


# B6-华中科技大学齿轮数据集（HUSTgearbox）
## 试验台
<a name="section-id18"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/B6.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  


# C1-工业过程数据集（XXXX）
## 试验台
<a name="section-id19"></a>
It seems no related description file.


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  


# C2-冷却机故障数据集（XXXX）
## 试验台
<a name="section-id20"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/C2.png)


## 数据集简要概述

7类故障
4种故障程度
第一列是标签

## 使用该数据集的相关论文

[1]  
[2]  


# C3-转子故障数据集（XXXX）
## 试验台
<a name="section-id21"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/C3.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  

# C4-发动机故障数据集（XXXX）
## 试验台
<a name="section-id22"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/C4.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  

# C5-海上石油勘探电浅泵故障数据集（XXXX）
## 试验台
<a name="section-id23"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/C5.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  


# C6-科大讯飞水泵状态挑战赛公开数据故障数据集（XXXX）
## 试验台
<a name="section-id24"></a>
It seems no related description file.


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  



# C7-德国火车数据故障数据集（XXXX）
## 试验台
<a name="section-id25"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/C7.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  



# C8-变压器故障数据集（XXXX）
## 试验台
<a name="section-id26"></a>

## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  

# D1-西交全寿命周期数据集（XXXX）
## 试验台
<a name="section-id27"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/D1.png)
## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  

# D2-磨削退化数据集（XXXX）
## 试验台
<a name="section-id28"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/D2.png)
## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  

# D3-UNSW数据集（XXXX）
## 试验台
<a name="section-id29"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/D3.png)
## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  

# D4-PHM2012数据集（XXXX）
## 试验台
<a name="section-id30"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/D4.png)
## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]

# D5-CMPASS引擎退化数据集（XXXX）
## 试验台
<a name="section-id31"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/D5.png)
## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]

# D6-PHM2010数据集（XXXX）
## 试验台
<a name="section-id32"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/D6.PNG)

## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]

# Contact

If you have any problem, please feel free to contact me.

Name: Chao Zhao

Email address: zhaochao734@hust.edu.cn


# Contact

If you have any problem, please feel free to contact me.

Name: Chao Zhao

Email address: zhaochao734@hust.edu.cn


# Contact

If you have any problem, please feel free to contact me.

Name: Chao Zhao

Email address: zhaochao734@hust.edu.cn
