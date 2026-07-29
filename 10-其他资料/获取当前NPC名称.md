---
title: "获取当前NPC名称"
source_file: "获取当前NPC名称.html"
category: "10-其他资料"
---

# 获取当前NPC名称

获取当前NPC名字命令

[@main]

#IF

#act

GetNpcName S1

SendMsg 6 当前NPC名称<$STR(S1)>
