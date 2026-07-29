---
title: "打开NPC对话框"
source_file: "打开NPC对话框.html"
category: "03-功能操作命令"
---

# 打开NPC对话框

**功能：**打开NPC对话框


**格式：**ClickNPC

NPC名称    ClickNPCLocal 坐标X 坐标Y


按NPC名称打开对话框(要求在NPC可对话范围内才有效)

ClickNPC 比奇老兵


按坐标打开对话框(要求在NPC可对话范围内才有效)

ClickNPCLocal 330 270





例子


[@main]

比奇老兵有任务给你\ \

<了解/@找NPC>


[@找NPC]

#if

FindNpcPoint 0 比奇老兵 N1 N2

#act

DEC N2 1

GotoNow

<$STR(N1)> <$STR(N2)>


QF里添加寻路到达触发打开npc对话框

寻路QF触发

[@FindPathBegin]

#IF

#ACT

SENDMSG

6 提示：开始寻路

[@FindPathStop]

#IF

#ACT

SENDMSG 6

提示：寻路中断了

[@FindPathEnd]

#if

#act

;;按名称打开对话框

ClickNPC

比奇老兵

;;按坐标打开对话框

;;ClickNPCLocal 330 270
