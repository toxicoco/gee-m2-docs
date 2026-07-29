---
title: "打开自定义NPC对话框"
source_file: "打开自定义NPC对话框.htm"
category: "03-功能操作命令"
---

# 打开自定义NPC对话框

打开自定义NPC对话框


OpenBigDialogBox WIL文件编号 图片编号 是否显示关闭按钮(0,1) 关闭按钮坐标X 关闭按钮坐标Y


范例：

[@main]


#ACT


OpenBigDialogBox 16 109


#SAY




[@Label]


#IF


#ACT


CloseBigDialogBox


Close
