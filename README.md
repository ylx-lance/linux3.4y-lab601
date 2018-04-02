# linux3.4y-lab601

一个修改版的Linux内核源码，修改点：
1. 支持800x600的电阻触摸屏:
- 电阻触摸芯片型号 tsc2007
- 电阻触摸屏型号：AM-800600P4TMQW-TB0H
-  CPU型号：S5P4418
- Android源码版本：Android5.1
- Android开发板型号：NanoPI T2(友善之臂提供)
- 为实现电阻触摸，你还需要做的工作，**将tsc2007.idc文件放入Android系统的system/usr/idc目录下**
2. 支持在Android Native层修改线程的调度策略和CPU亲和性
+ 在原生Android配套的Linux内核中是被屏蔽掉的
