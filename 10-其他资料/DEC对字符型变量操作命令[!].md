---
title: "DEC对字符型变量操作命令[!]"
source_file: "DEC对字符型变量操作命令[!].htm"
category: "10-其他资料"
---

# DEC对字符型变量操作命令[!]

DEC对字符型变量操作命令。


MOV命令做了一些改进。


[@Main]


  #ACT


  MOV S1 Geem2引擎M2


  MOV S2 Geem2引擎M2


  DEC S1 Geem2引擎 ;删除S1中的“Geem2引擎”字符串


DEC S2 1 3     ;删除S2中的第1至第6个字符串 这个要注意，一个汉字是2个字节长度，不要删除半个汉字的情况，否则会乱码。


结果 S1=M2


  S2=引擎
