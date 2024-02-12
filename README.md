# Machine-Fault-Diagnosis-Dataset-PHM

We have compiled open source datasets of mechinery fault in recent years (from near to far).


We will complete the reposotory as soon as possible.

We hope this reposotory will help you with your research.


Roadmap
==

A-Bearing(轴承)；B-Gear(齿轮)；C-Others (其他)；D-RUL(寿命预测相关)
| 序号（Index） | 年(Year) 	| 数据集名称(dataset name) | 部件名称(component name) | 故障产生方式 	| 工况情况 	| 故障情况 	| 信号类型 	| 原始数据连接 	| 备用数据连接 	|
|----------	|----	|--------------------------------	|----------	|--------------	|----------	|----------	|----------	|--------------	|--------------	|
| [A1] (#A1-凯斯西储轴承数据集（cwru）)      	| 　 	| 凯斯西储（CWRU）               	| 轴承     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| A2       	| 　 	| 帕德博恩（KAT）                	| 轴承     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| A3       	| 　 	| 江南大学（JNU）                	| 轴承     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| A4       	| 　 	| 美国机械故障预测技术委员会(MFPT)  | 轴承     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| A5       	| 　 	| 辛辛那提大学（IMS）              | 轴承     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| A6       	| 　 	| 都灵大学（DIRG）                 | 轴承     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| A7       	| 　 	| 自吸泵                         	| 轴承     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| A8       	| 　 	| 哈工大                         	| 轴承     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| A9       	| 　 	| SQV变转速                      	| 轴承     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| A10      	| 　 	| 越南大学                       	| 轴承     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| A11      	| 　 	| DC竞赛                         	| 轴承     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| A12      	| 　 	| 华中科技大学轴承（HUSTbearing）  | 轴承     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| B1       	| 　 	| 东南大学                       	| 齿轮     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| B2       	| 　 	| PHM09                          	| 齿轮     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| B3       	| 　 	| 行星齿轮                       	| 齿轮     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| B4       	| 　 	| 西安交通                       	| 齿轮     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| B5       	| 　 	| 一阶减速器                     	| 齿轮     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| B6       	| 　 	| 华中科技大学齿轮（HUSTGear）      | 齿轮     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| C1       	| 　 	| 工业过程故障                   	| 工业过程 	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| C2       	| 　 	| 冷却机故障                     	| 冷却机   	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| C3       	| 　 	| 转子故障                       	| 转子     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| C4       	| 　 	| 发动机                         	| 发动机   	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| C5       	| 　 	| 海上石油勘探电浅泵             	| 泵       	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| C6       	| 　 	| 科大讯飞水泵状态挑战赛公开数据 	  | 水泵     	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| C7       	| 　 	| 德国火车数据集                 	| 火车轮毂 	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| C8       	| 　 	| 变压器故障数据集               	| 变压器   	| 　           	| 　       	| 　       	| 　       	|              	|              	|
| D1　      | 　 	| 　                             	| 　       	| 　           	| 　       	| 　       	| 　       	|              	|              	|


# A1-凯斯西储轴承数据集（CWRU）
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

![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A2.jpg)


## 数据集简要概述


## 使用该数据集的相关论文

[1]  
[2]  


# A3-江南大学轴承数据集（JNU）

## 试验台

![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A3.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]
[2]

# A4-美国机械故障预测技术委员会轴承数据集（MFPT）
## 试验台

![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A4.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]
[2]


# A5-辛辛那提大学轴承数据集（IMS）
## 试验台

![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A5.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]
[2]

# A6-都灵大学轴承数据集
## 试验台

![image](https://github.com/CHAOZHAO-1/Machine-Fault-Dataset/blob/main/IMG/A6.png)


## 数据集简要概述


## 使用该数据集的相关论文

[1]
[2]


# A7-自吸泵轴承数据集
## 试验台

![image]()


## 数据集简要概述


## 使用该数据集的相关论文

[1]
[2]



# A8-哈工大轴承数据集
## 试验台

![image]()


## 数据集简要概述


## 使用该数据集的相关论文

[1]
[2]


# A9-SQV变转速轴承数据集
## 试验台

![image]()


## 数据集简要概述


## 使用该数据集的相关论文

[1]
[2]


# A10-越南大学轴承数据集
## 试验台

![image]()


## 数据集简要概述


## 使用该数据集的相关论文

[1]
[2]


# A11-DC竞赛轴承数据集
## 试验台

![image]()


## 数据集简要概述


## 使用该数据集的相关论文

[1]
[2]


# A12-华中科技大学轴承数据集（HUST）
## 试验台

![image]()


## 数据集简要概述


## 使用该数据集的相关论文

[1]
[2]

# Contact

If you have any problem, please feel free to contact me.

Name: Chao Zhao

Email address: zhaochao734@hust.edu.cn
