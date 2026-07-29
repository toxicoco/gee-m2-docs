---
title: "为什么我的NPC不能买、卖、修理物品？"
source_file: "为什么我的NPC不能买卖修理物品.htm"
category: "09-常见问题解答"
---

# 为什么我的NPC不能买、卖、修理物品？

**为什么我的NPC不能买、卖、修理物品？**


NPC脚本的第一行加上指定的操作，就可以正常了。



;=================================

(@buy

@sell)

%100

+5

+6

[@main]

欢迎光临！！！

<买/@buy>\

<卖/@sell>\

\


<关闭/@exit>

;================================


功能标志说明：

;买物品

@buy

;卖物品

@sell

;炼药

@makedrug

;存仓库

@storage

;取仓库

@getback

;升级武器

@upgradenow

;取回升级武器

@getbackupgnow

;修理

@repair

;特殊修理

@s_repair

;发祝福语

@@sendmsg
