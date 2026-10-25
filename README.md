# control-plane-security-notes
《控制平面攻防笔记》配套资源｜eNSP/EVE-NG 拓扑、pcap 抓包、Scapy 脚本、Markdown 文稿，攻防并重，仅授权实验环境研究
# 控制平面攻防笔记
> ⚠️ 免责声明：本仓库全部实验脚本、拓扑、抓包，**仅允许在本人拥有完全授权的仿真实验环境中复现**。禁止在任何未授权内网、生产网络使用。专栏攻防并重，用于理解协议风险、学习基线加固。

专栏首发：先知社区
静态知识库：https://xxx.github.io/control-plane-security-notes/

## 环境选择
- eNSP：适合新手学习协议、华为设备配置
- EVE-NG / PNETLAB：适合Scapy自定义报文、高阶控制平面实验

## 目录
预备篇：Lesson01 环境搭建与以太网帧基础
二层攻防：Lesson02 ARP欺骗｜Lesson03 DHCP欺骗｜Lesson04 VRRP劫持｜Lesson05 VLAN Hopping｜Lesson06 STP劫持｜Lesson07 二层综合侦查
三层IGP攻防：Lesson08 OSPF｜Lesson09 OSPF认证｜Lesson10 IS-IS｜Lesson11 ICMP重定向｜Lesson12 静态路由安全｜Lesson13 三层侦查
高阶对抗：Lesson14 信任域边界｜Lesson15 设备接管｜Lesson16 控制平面操纵｜Lesson17 VXLAN｜Lesson18 统一检测体系

## 配套资源说明
- labs：eNSP `.ensp` / EVE `.unl`
- pcaps：Wireshark抓包
- scapy_scripts：可直接运行的Python脚本
- drawio：拓扑源文件，可自行修改

## 依赖
pip install -r requirements.txt
