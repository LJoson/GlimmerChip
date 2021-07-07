网络资源：

https://github.com/OSCPU



https://github.com/zach0zhang/Single_instruction_cycle_OpenMIPS

https://github.com/chipsalliance/chisel3



南京大学CS课程计算机系统PA实验
https://nju-projectn.github.io/ics-pa-gitbook/ics2020/

http://riscvbook.com/chinese/RISC-V-Reader-Chinese-v2p1.pdf



https://github.com/NJU-ProjectN

https://github.com/OSCPU/NutShell

https://github.com/LvNA-system

Clifford Cummings关于数字电路设计的文章在此：http://www.sunburst-design.com/papers/
西南交大邸志雄老师的静态时序分析STA课程（友情推荐非广告）：http://www.dizhixiong.cn/class2/ 2021/3/21 12:05:50
Emulating a CPU in C++ (6502)
https://www.youtube.com/watch?v=qJgsuQoy9bc&list=PLLwK93hM93Z13TRzPx9JqTIn33feefl37
这不是完整实现，完整编写6502仿真器去看NES仿真器的第2部分：https://youtu.be/8XmxKPJDGU0
代码在这https://github.com/davepoo/6502Emulator
http://www.obelisk.me.uk/6502/

 2021/3/21 12:05:50
自己动手做计算机系列教程，也许只有这一期。
所有资料均可在 https://github.com/wuxx/HC6502 

其他参考资料：

|1）仿真验证环境：
Verilator:https://www.veripool.org/verilator/
|开源仿真器Verilator和RISC-V工具链可以通过apt-get一键安装
|模拟器NEMU
|https:/github.com/NJU-ProjectN/nemu
|裸机运行时环境AM
|https://github.com/NJU-ProjectN/nexus-am
|差分测试资料
Yu，EasyDiff:An Effective and Efficient Framework for Processor Verification，CRVF 2019，https://crvf2019.github.io/pdf/14.pdf
|2018年龙芯杯南京大学二队决赛答辩报告htp://www.nscscc.org/a/wangjie/NSCSCC2018/2018/1010/46.html
|2）RISC-V：
|RISC-V指令集手册
|https:/github.com/riscv/riscv-isa-manual
|RISC-V各种资料（如ABI规范等）
|https://github.com/riscv/

3）Chisel：Chisel Bootcamp-很不错的chisel教程，支持在线运行chisel代码，可以边写chisel代码边学习https://github.com/freechipsproject/chisel-bootcamp
*第1章是scala入门，第2章是chisel基础，第3章是scala高级特性和chisel的混合使用，第4章是FIRRTL后端相关内容
*学习前两章=入门，学习第3=提高，第4可以作为课外阅读材料
Chisel Users Guide-比较系统地整理了chisel的特性，也是不错的入门教程https://github.com/freechipsproject/chisel3/wiki/Short-Users-Guide-to-Chisel Chisel小抄-简明地列出了chisel语言的大部分用法
https://chisel.eecs.berkeley.edu/doc/chisel-cheatsheet3.pdf ChiselAPI-详细地列出了chisel库的所有API供参考
https://chisel.eecs.berkeley.edu/api/latest/index.html Chisel示例项目
https:/github.com/OpenXiangShan/chisel-playground
|用Chisel开发的RISC-V处理器示例项目
https://github.com/ucb-bar/riscv-sodor 

https://github.com/OSCPU/NutShell

 https://github.com/freechipsproject/rocket-chip（不适合入门阅读）https:/github.com/OpenXiangShan/XiangShan（非常复杂的处理器）