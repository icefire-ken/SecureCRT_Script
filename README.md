# 简介

- 工作中经常需要对客户的网络设备进行巡检，之前都是用SecureCRT开启记录Log Session，依次远程登录到每个设备上，依次输入巡检命令收集设备巡检信息；

- 本脚本可以在SecureCRT中运行，利用脚本代替手动输入巡检命令的过程。

# 使用方法

在SecureCRT的Session Options —— Terminal —— Mapped Keys， 映射快捷键（如F1）。
Function选择Run Script，选择本脚本。

# 更新日志

## 2022.05.30

初次上传脚本；
基本实现自动输入巡检命令功能；
可根据手动输入的设备类型，自动输入相应的巡检命令。
