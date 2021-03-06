# 近距离通信协议：NFC

## NFC概述

近距离无线通信NFC是Near Field Communication缩写，即近距离无线通讯技术，是一种短距离的高频无线通信技术，允许电子设备之间进行非接触式点对点数据传输（在10厘米内）交换数据。

NFC提供了一种简单、触控式的解决方案，可以让消费者简单直观地交换信息、访问内容与服务。这个技术由免接触式射频识别（RFID）演变而来，并向下兼容RFID，最早由Philips、Nokia和Sony主推，主要可能用于手机等手持设备中。由于近场通讯具有天然的安全性，因此，NFC技术被认为在手机支付等领域具有很大的应用前景。NFC将非接触读卡器、非接触卡和点对点（Peer-to-Peer）功能整合进一块单芯片，为消费者的生活方式开创了不计其数的全新机遇。

这是一个开放接口平台，可以对无线网络进行快速、主动设置，也是虚拟连接器，服务于现有蜂窝状网络、蓝牙和无线802.11设备。和RFID不同，NFC采用了双向的识别和连接。在20cm距离内工作于13.56MHz频率范围。它能快速自动地建立无线网络，为蜂窝设备、蓝牙设备、Wi-Fi设备提供一个“虚拟连接”，使电子设备可以在短距离范围进行通讯。

## NFC技术原理
NFC的设备可以在主动或被动模式下交换数据。

**在被动模式下**，启动NFC通信的设备，也称为NFC发起设备(主设备)，在整个通信过程中提供射频场。它可以选择106kbps、212kbps或424kbps其中一种传输速度，将数据发送到另一台设备。另一台设备称为NFC目标设备(从设备)，不必产生射频场，而使用负载调制(load modulation)技术，即可以相同的速度将数据传回发起设备。 移动设备主要以被动模式操作，可以大幅降低功耗，并延长电池寿命。电池电量较低的设备可以要求以被动模式充当目标设备，而不是发起设备。

**在主动模式下**，每台设备要向另一台设备发送数据时，都必须产生自己的射频场。这是对等网络通信的标准模式，可以获得非常快速的连接设置。

## NFC应用
NFC技术的应用可以分为四种基本的类别：

- 接触通过(TouchandGo)，如门禁管制、车票和门票等，使用者只需携带储存着票证或门控密码的移动设备靠近读取装置即可。
- 接触确认(TouchandConfirm)，如移动支付，用户通过输入密码或者仅是接受交易，确认该次交易行为。
- 接触连接(TouchandConnect)，如把两个内建NFC的装置相连接，进行点对点数据传输，例如下载音乐、图片互传和同步交换通讯簿等。
- 接触浏览(TouchandExplore)，NFC设备可以提供一种以上有用的功能，消费者将能够通过浏览一个NFC设备，了解提供的是何种功能和服务。
