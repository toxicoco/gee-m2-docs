---
title: "通过脚本建立一个NPC 动态创建NPC"
source_file: "通过脚本建立一个NPC.htm"
category: "03-功能操作命令"
---

# 通过脚本建立一个NPC 动态创建NPC

通过脚本命令建立一个NPC,服务器重启后消失.


格式: CreateNPC NPC名字 地图 坐标X(-1时随机坐标) 坐标Y(-1时随机坐标) 外观 脚本文件 脚本文件是否要加上地图名称(例如.设置为0时脚本文件必须带“-3”如:“传送员-3.txt” 设置为1时脚本文件不需要带“-3”如:“传送员.txt”这样的好处就是，你可以在任意地图地图创建NPC，只要一个脚本“传送员.txt”而不需要“传送员-0.txt、传送员-3.txt”等等好多NPC脚本)

 注意:

脚本文件必须在Market_Def目录中.



例如:首先在Market_Def中建立一个叫测试-3.txt的脚本文件.

#IF

#ACT


CreateNPC 测试 3 330 330 8

测试-3 0


#SAY

通过脚本建立了一个NPC.








#IF


  #ACT


CreateNPC 测试NPC 3 -1 -1 8

测试NPC 1


#SAY


通过脚本建立了一个NPC 随机坐标
