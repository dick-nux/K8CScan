<h3>K8Cscan5.3 Update 20191018</h3>
<br>
K8Cscan一款专用于大型内网渗透的高并发插件化扫描神器，包含信息收集、网络资产、漏洞扫描、密码爆破、漏洞利用，支持批量A段/B段/C段以及跨网段扫描。5.3版本内置27个功能模块,通过各种协议以及方法快速获取目标网络存活主机IP、计算机名、工作组、网络共享、网卡物理地址、操作系统版本、网站域名、Web中间件、路由器（Cisco）、数据库等网络资产信息,内置MS17-010(SMB漏洞)、Weblogic漏洞检测，内置6种密码认证爆破3种数据库(Mysql、Oracle、MSSQL)、FTP密码爆破(文件服务器)、SSH密码爆破(Linux主机)、IPC/WMI两种方式爆破Windows主机密码，Web指纹识别模块可识别62种Web应用。高度自定义插件支持.NET程序集、DLL(C#/Delphi/VC)、PowerShell等语言编写的插件以及无编程功底通过配置INI加载任意程序命令，可快速扩展扫描或利用能力。支持Cobalt Strike联动使用27个功能扫描目标内网或跳板扫描外网目标，可快速拓展内网进行横向移动。<br>

<br>
使用说明: https://github.com/k8gege/K8CScan/wiki<br>
CS联动https://github.com/k8gege/K8CscanAggressor<br>
<br>
工具演示:<br>
<img src=https://github.com/k8gege/K8CScan/blob/master/Images/K8Cscan.gif></img>
Cobalt Strike<br>
<img src=https://github.com/k8gege/K8CScan/blob/master/Images/CobaltStrike.gif></img>

<br>
包括但不限于以下教程<br>
4.Linux版Cscan使用<br>
5.Cobalt Strike联动<br>
6.DiyMoudle自定义模块<br>
7.Exploit Generator插件生成器<br>
C#插件DLL源码 批量端口扫描<br>
C#插件EXE源码 批量Base64<br>
Cscan.ini例子 批量SSH上控<br>
Cscan.ini例子 批量Win上控<br>
PowerShell插件 批量Base64<br>
信息收集 C段域名URL扫描<br>
信息收集 C段旁站扫描<br>
信息收集 Web指纹识别<br>
信息收集 Web目录扫描<br>
信息收集 Web资产扫描<br>
信息收集 子域名爆破<br>
信息收集 存活主机扫描<br>
信息收集 思科设备扫描<br>
信息收集 操作系统探测<br>
信息收集 枚举MSSQL主机<br>
信息收集 枚举网络共享资源<br>
加密解密 批量Base64密码<br>
加密解密 批量Hex密码<br>
实用功能 批量域名解析<br>
密码爆破 FTP文件服务器<br>
密码爆破 IpcScan(Windows)<br>
密码爆破 MSSQL数据库<br>
密码爆破 MySQL数据库<br>
密码爆破 Oracle数据库<br>
密码爆破 SmbScan(Windows)<br>
密码爆破 SSHscan(Linux)<br>
密码爆破 WmiScan(Windows)<br>
漏洞利用 CVE 2016 3088 ActiveMQ GetShell Exploit<br>
漏洞利用 CVE 2019 0604 SharePoint GetShell Exploit<br>
漏洞利用 CVE 2019 9621 Zimbra GetShell Exploit<br>
漏洞扫描 CVE 2017 0148 MS17 010 SMB永恒之蓝<br>
漏洞扫描 CVE 2019 0708 Windows Rdp远程代码执行<br>
漏洞扫描 CVE 2019 2725 Weblogic GetShell Exploit<br>
漏洞扫描 PhpStudy后门<br>
