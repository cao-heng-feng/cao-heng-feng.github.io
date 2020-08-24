---
layout: post
title:  "煤矿综采工作面智能一体化生产管理平台"
date:   2020-05-23 21:03:36 +0530
categories: Qt UDP
---
本系统软件是一套集设备状态监控、设备信息展示、故障报警通知、通知消息、用户信息管理于一体的煤矿综合集控系统服务器端软件，适用于采煤行业，推动煤矿开采的智能化发展。该系统是在煤矿行业可以减少人员的使用，高级的自动化系统保证了矿井下人员的生命安全，实现了煤矿工作人员随时随地监控采集面的要求，加强了煤矿综合开采的网络化管理，实现综采工作面故障报警的功能，在一定程度上解决了过去煤矿开采现场离不开人的难题。<br>

{:refdef: style="text-align: center;"}
![服务器端]({{ "./images/coal/server.png" | absolute_url }})
{:refdef}
{:refdef: style="text-align: center;"}
服务器端程序
{:refdef}
{:refdef: style="text-align: center;"}
![客户端]({{ "./images/coal/client.png" | absolute_url }})
{:refdef}
{:refdef: style="text-align: center;"}
客户端程序
{:refdef}
{:refdef: style="text-align: center;"}
![控制面板]({{ "./images/coal/control.png" | absolute_url }})
{:refdef}
{:refdef: style="text-align: center;"}
虚拟控制面板
{:refdef}
<br>
本系统基于C++语言的QT软件开发，在保证稳定性、扩展性的前提下，以用户需求划分功能模块，原生开发，结构简单，缩短了开发时间，降低了维护难度。将后台数据库文件部署在本地服务器中，并且将其同步到云端服务器上，即可在手机端，电脑端，平板等联网设备上使用该系统，通过该系统可以远程监测煤矿开采现场的状态信息，也可以查询设备的历史数据信息包括设备信息、报警信息、当前数据等。

通讯方式：串口 UDP

通讯协议：Modbus CAN

功能：设备数据监控，权限管理，报警管理，远程控制。



