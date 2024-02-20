# Machine-Fault-Diagnosis-Dataset-PHM

We have compiled open source datasets of mechinery fault in recent years (from near to far).


We will complete the reposotory as soon as possible.

We hope this reposotory will help you with your research.


Roadmap
==

A-Bearing(轴承)；B-Gear(齿轮)；C-Others (其他)；D-RUL(寿命预测相关)


| 序号（Index） | 年(Year) | 数据集名称(Dataset Name) | 部件名称(Component Name) | 故障产生方式(Fault generation mode) | 工况情况（Working Condition） | 故障情况(Fault Type) | 信号类型(Signal Yype) | 原始数据连接（Orignal Link） | 备用数据连接(Alternate Link) |
|:----------:|:----:|:--------------------------------:|:----------:|:--------------:|:----------:|:----------:|:----------:|:--------------:|:--------------:|
| [A1](#section-id1) |2015| 凯斯西储（CWRU） | 轴承（bearing） |人工注入（Artificial）|4 type| Inner race-outer race-ball| 振动（Acceleration）|[[data link](https://csegroups.case.edu/bearingdatacenter/pages/welcome-case-western-reserve-university-bearing-data-center-website)]                    	 |[[data link](https://pan.quark.cn/s/2b0ceb12ab5a)] |
| [A2](#section-id2) |2016| 帕德博恩（KAT） | 轴承（bearing） | 人工注入和自然失效（Artificial and RTF）　 | 4 type　 | / | 振动（Acceleration）　 |[[data link](https://mb.uni-paderborn.de/kat/forschung/datacenter/bearing-datacenter/)]  |[[data link](https://pan.quark.cn/s/98940eefefb2)] |
| [A3](#section-id3) |2013| 江南大学（JNU） | 轴承（bearing） |人工注入（Artificial） 　 | 3 type　 | Inner race-outer race-ball 　 |振动（Acceleration） 　 | |[[data link](https://pan.quark.cn/s/b2344c54c6d7)] |
| [A4](#section-id4) |2013| 美国机械故障预测技术委员会(MFPT) | 轴承（bearing） | 　 | 　 | 　 |振动（Acceleration）| |[[data link](https://pan.quark.cn/s/ee6d4d3ef162)] |
| [A5](#section-id5)|2006| 辛辛那提大学（IMS） | 轴承（bearing） | 　 | 　 | 　 |振动（Acceleration） 　 |[[data link](https://www.nasa.gov/intelligent-systems-division)]       |[[data link]()] |
| [A6](#section-id6)|2019| 都灵大学（DIRG） | 轴承（bearing） | 　 | 　 | 　 | 振动（Acceleration）　 | |[[data link]()] |
| [A7](#section-id7) |2016| 自吸泵 | 轴承（bearing） |人工注入（Artificial） 　 | 　 | 　 | 　 | /|[[data link](https://pan.quark.cn/s/6ccea2154a06)] |
| [A8](#section-id8) |2023| 哈工大 | 轴承（bearing） | 　 | 　 | 　 | 　 |[[data link](https://github.com/HouLeiHIT/HIT-dataset)]     |[[data link]()] |
| [A9](#section-id9) |2021| SQV变转速 | 轴承（bearing） |人工注入（Artificial）| 　 | Inner race-outer race| 　 | |[[data link]()]  |
| [A10](#section-id10) |2023| 越南大学 | 轴承（bearing） |人工注入（Artificial）　 | 　 | 　 | 　 | |[[data link]()] |
| [A11](#section-id11) |2021| DC竞赛 | 轴承（bearing）| /　 | /　 | /　 | /　 |/ |[[data link]()] |
| [A12](#section-id12) |2024| 华中科技大学轴承（HUSTbearing） | 轴承（bearing） |人工注入（Artificial） 　 | 　 | 　 | 　 |/ |[[data link](https://github.com/CHAOZHAO-1/HUSTbearing-dataset)] |
| [B1](#section-id13)  |2019| 东南大学 | 齿轮(Gear) |人工注入（Artificial） 　 | 　 | 　 | 　 | |[[data link]()] |
| [B2](#section-id14)  |2009| PHM09 | 齿轮(Gear) |人工注入（Artificial） 　 | 　 | 　 | 　 | /|[[data link](https://pan.quark.cn/s/88180e4fccde)] |
| [B3](#section-id15)  |2023| 行星齿轮 | 齿轮(Gear) |人工注入（Artificial）　 | 　 | 　 | 　 | |[[data link]()] |
| [B4](#section-id16)  |2021| 西安交通 | 齿轮(Gear) |人工注入（Artificial） 　 | 　 | 　 | 　 | |[[data link]()] |
| [B5](#section-id17)  |2021| 一阶减速器 | 齿轮(Gear) |人工注入（Artificial） 　 | 　 | 　 | 　 | | [[data link](https://pan.quark.cn/s/7e881548f5a1)]|
| [B6](#section-id18)  |2024 | 华中科技大学齿轮（HUSTGear） | 齿轮(Gear) |人工注入（Artificial） 　 | 　 | 　 | 　 |/ |[[data link](https://github.com/CHAOZHAO-1/HUSTgearbox-dataset))] |
| [C1](#section-id19)  |2015| 工业过程故障 | 工业过程 | 　 | 　 | 　 | 　 | | [[data link]()]|
| [C2](#section-id20)  |2020| 冷却机故障 | 冷却机 | 　 | 　 | 　 | 　 | |[[data link]()] |
| [C3](#section-id21)  |2019| 转子故障 | 转子 | 　 | 　 | 　 | 　 | |[[data link]()] |
| [C4](#section-id22)  |2018| 发动机 | 发动机 | 　 | 　 | 　 | 　 | | [[data link]()]|
| [C5](#section-id23)  |2024| 海上石油勘探电浅泵 | 泵 | 　 | 　 | 　 | 　 | |[[data link]()] |
| [C6](#section-id24)  |2023| 科大讯飞水泵状态挑战赛公开数据 | 水泵 | 　 | 　 | 　 | 　 | |[[data link]()] |
| [C7](#section-id25)  |2022| 德国火车数据集 | 火车轮毂 | 　 | 　 | 　 | 　 | | [[data link]()]|
| [C8](#section-id26)  |2023| 变压器故障数据集 | 变压器 | 　 | 　 | 　 | 　 | | [[data link]()]|



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

RPM- rpm during testing 转每分钟，除以60为旋转频率；

B -滚动体故障；IR – 内圈故障；OR –外圈故障；

驱动端和风扇端轴承外圈的损伤点分别放置在3点钟、6点钟、12点钟三个不同位置。

数据文件为Matlab格式。每个文件包含风扇和驱动端振动数据，以及电机转速。

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

[1]  
[2]  

# A2-帕德博恩大学轴承数据集（KAT）

## 试验台
<a name="section-id2"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A2.jpg)


## 数据集简要概述

试验台由几个模块组成（从左到右依次为）：电动机、扭矩测量轴、滚动轴承测试模块、飞轮和负载电机，如上图所示。通过将不同损伤类型的滚珠轴承安装在轴承测试模块中，生成实验数据。

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

[1]  
[2]  


# A3-江南大学轴承数据集（JNU）

## 试验台
<a name="section-id3"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A3.png)


## 数据集简要概述

采样频率：50khz
转速：600 800 1000
内圈：ib
外圈：ob
滚动体：tb
正常：N



## 使用该数据集的相关论文

[1]  
[2]  

# A4-美国机械故障预测技术委员会轴承数据集（MFPT）
## 试验台
<a name="section-id4"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A4.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2] 


# A5-辛辛那提大学轴承数据集（IMS）
## 试验台
<a name="section-id5"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A5.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  

# A6-都灵大学轴承数据集
## 试验台
<a name="section-id6"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A6.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  


# A7-自吸泵轴承数据集
## 试验台
<a name="section-id7"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A7.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  



# A8-哈工大轴承数据集
## 试验台
<a name="section-id8"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A8.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  


# A9-SQV变转速轴承数据集
## 试验台
<a name="section-id9"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A9.png)


## 数据集简要概述

收集了上述六种故障轴承和正常状态（NC）轴承的振动信号，共七种不同的健康状态。每次实验采集时长为15秒，包含一个完整的从静止状态逐渐加速至3000rpm，后保持稳定，最后逐渐减速为0的加减速过程。


## 使用该数据集的相关论文

[1]  
[2]  


# A10-越南大学轴承数据集
## 试验台
<a name="section-id10"></a>
![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A10.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  


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


## 使用该数据集的相关论文

[1]  
[2]  

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


# Contact

If you have any problem, please feel free to contact me.

Name: Chao Zhao

Email address: zhaochao734@hust.edu.cn
