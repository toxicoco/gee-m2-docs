---
title: "检查人物登录IP"
source_file: "检查人物登录IP.htm"
category: "04-脚本检测命令"
---

# 检查人物登录IP

**功能：**

       

检查人物登录IP.


**格式：

**       

CHECKIPLIST

会员.txt


;==========================================

;按IP检查

[@checkiplist0]

#IF

 

CHECKIPLIST

IP会员.txt

#SAY

你是会员

#ELSESAY

你不是会员

;==========================================
