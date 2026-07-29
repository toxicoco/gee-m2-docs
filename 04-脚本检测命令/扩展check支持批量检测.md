---
title: "扩展check支持批量检测"
source_file: "扩展check支持批量检测.htm"
category: "04-脚本检测命令"
---

# 扩展check支持批量检测

**扩展check支持批量检测**




扩展check支持批量检测


多个非连续的标识可以用逗号隔开，连续可用 - 串联

格式：check [1,2,4-6,8] 1


#if

check [1,2,4-6,8] 1

#act

SENDMSG 6  1,2,4,5,6,8全为1
