---
title: "NPC界面调用怪物外形"
source_file: "NPC界面调用怪物外形.html"
category: "03-功能操作命令"
---

# NPC界面调用怪物外形

**功能: **怪物外形调用到NPC界面


**格式:**




**例子:**

[@main]

#if

#act

GetDBMonsterFieldValue

暗之双头血魔 appr <$STR(N$怪物APPR)>

GetDBMonsterFieldValue 暗之双头血魔 race

<$STR(N$怪物RACE)>

#say

:<$STR(N$怪物RACE)>:0:4:100:200>
