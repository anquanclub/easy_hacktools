# 懒人快速验证漏洞小工具
懒人必备 简简单单 快速验证 逐步完善 持续更新
该工具主要是方便自己整理容易复现的poc，批量测试，然后恰烂洞，大佬勿喷呀（抱住狗头）
## 前言
因为以前收集的poc都是东一个西一个的存放，到用的时间好多都找不到了，花了一天时间稍微总结了一下。
## 版本介绍
目前简单写了50个函数的验证函数，支持多线程测试
![image](https://user-images.githubusercontent.com/60703362/218304975-c40d3ea5-098f-4267-83f8-8cf045b65fa1.png)
## 使用教程
方式1:
按程序提示传入参数

方式2:
```
python3 main.py -t threads -m 漏洞选项 -u 漏洞列表.txt
```
![image](https://user-images.githubusercontent.com/60703362/218305110-ef963c12-be8b-4724-b7b5-f98ce2450275.png)
