# 远距离非蜂窝通信协议：Zigbee

## 简介

ZigBee这个名字来源于蜂群的通信方式：蜜蜂之间通过跳Zigzag形状的舞蹈来交互消息，以便共享食物源的方向、位置和距离等信息。借此意义Zigbee作为新一代无线通讯技术的命名。

ZigBee是一种高可靠的无线数传网络，类似于CDMA和GSM网络。

ZigBee数传模块类似于移动网络基站。

ZigBee是一个由可多到65000个无线数传模块组成的一个无线网络平台，在整个网络范围内，每一个网络模块之间可以相互通信，每个网络节点间的距离可以从标准的75m无限扩展。通讯距离从标准的75m到几百米、几公里，并且支持无限扩展（依靠节点数增加）。

与移动通信的CDMA网或GSM网不同的是，ZigBee网络主要是为工业现场自动化控制数据传输而建立，因而，它必须具有简单，使用方便，工作可靠，价格低的特点；而移动通信网主要是为语音通信而建立，每个基站价值一般都在几十万甚至上百万元人民币，而每个ZigBee网络“基站”（节点）却不到1000元人民币。

## 技术特点

ZigBee是一种无线连接,可工作在2.4GHz(全球流行)、868MHz(欧洲流行)和915 MHz(美国流行)3个频段上,分别具有最高250kbit/s、20kbit/s和40kbit/s的传输速率,它的传输距离在10-75m的范围内,但可以继续增加。

作为一种无线通信技术,ZigBee具有如下特点:

(1)低功耗

(2)成本低

(3)时延短

(4)网络容量大

(5)可靠

(6)安全

## ZigBee协议栈

ZigBee协议栈结构是基于标准OSI七层模型的，包括高层应用规范、应用汇聚层、网络层、媒体接入层和物理层，如下图所示。

![image](https://raw.githubusercontent.com/zhusheng/blog/master/iot/protocol06.png)

IEEE 802.15.4定义了两个物理层标准，分别是2.4GHz物理层和868/915MHz物理层。两者均基于直接序列扩频（DSSS）技术。

868MHz只有一个信道，传输速率为20kb/s；902MHz～928MHZ频段有10个信道，信道间隔为2MHz，传输速率为40kb/s。以上这两个频段都采用BPSK调制。

2.4GHz～2.4835 GHz频段有16个信道，信道间隔为5MHz，能够提供250kb/s的传输速率，采用O-QPSK调制。

为了提高传输数据的可靠性，IEEE 802.15.4定义的媒体接入控制（MAC）层采用了CSMA-CA和时隙CSMA-CA信道接入方式和完全握手协议。

应用汇聚层主要负责把不同的应用映射到ZigBee网络上，主要包括安全与鉴权、多个业务数据流的会聚、设备发现和业务发现。

### 应用领域

（1）家庭和建筑物的自动化控制：照明、空调、窗帘等家具设备的远程控制；

（2）消费性电子设备：电视、DVD、CD机等电器的远程遥控。

（3）PC外设：无线键盘、鼠标、游戏操纵杆等；

（4）工业控制：使数据的自动采集、分析和处理变得更加容易；

（5） 医疗设备控制：医疗传感器、病人的紧急呼叫按钮等；

（6）交互式玩具。


   
