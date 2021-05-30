# 实习生岗位

包含三个团队的岗位。请注意编号。

## 如何正确的投递简历

在投递简历之前最好对我们有更多一点了解。以下是阅读材料：

- [极简项目管理](https://github.com/lazyparser/minimalist-team-leader) 是目前PLCT实验室的管理方式，实习生也在管理范围内。请先阅读。
- [我们如何进行实习生招聘](https://github.com/lazyparser/weloveinterns/blob/master/how-do-we-interview-interns.md)
- [我们如何对实习生进行能力评定和培养](https://github.com/lazyparser/weloveinterns/blob/master/how-do-we-rank-interns.md)
- [实习生生存手册](https://github.com/lazyparser/survivial-manual-for-interns) 目前还在断断续续的撰写中，欢迎围观和贡献PR (Pull Requests)

阅读之后，接下来就可以发邮件了。以下内容请认真阅读。不符合条件邮件不会收到回复。

有意者请投递简历至：
**吴老师 wuwei2016@iscas.ac.cn**

邮件标题请注明：
**实习生 - 岗位编号 - 姓名 - 手机号码 - 学校**

邮件正文请:
**进行跟应聘职位相关的自我介绍**，不超过300字。

邮件必须附带简历。**没有PDF格式简历的邮件不保证会收到回复**。

## 所有实习生共性要求（技术类）

开放岗位的入职要求（教学助理等非技术类的同学只需要满足前两条）：

1. 良好的沟通理解能力、能够观察和感知他人的态度和观点。能够主动沟通、遇到计划外或坏消息能够大声的说出来。
2. 知道如何陈述bugs/issues以及向其他人求助，如何不浪费同事的时间，将复现bug需要的信息提供完整。
3. 能力值评定一般要求达到LV2级别及以上。参见：[我们如何面试实习生](https://github.com/lazyparser/weloveinterns/blob/master/how-do-we-interview-interns.md)，[我们如何给实习生评级](https://github.com/lazyparser/weloveinterns/blob/master/how-do-we-rank-interns.md)。
4. 热爱编程，经常写代码。C/C++/Java/JavaScript 任何一种常见语言都可以。
5. 熟练使用 Linux 命令行；会一点 Python/Bash 脚本进行自动化。
6. 熟练使用 Google 搜索引擎。
7. 熟练使用 Git，能够自己 rebase 解决 conflicts。
8. （加分）自学了 RISC-V 指令集，包括 RV32GC 和 RV64GC。在自己的电脑上部署运行起来QEMU-RISCV64以及Spike模拟器。
9. （加分）对于网络知识有基本了解并熟练使用，例如SSH任意端口登陆、Port Forwarding、反向链接、ProxyCommand 等配置自行掌握。

## PLCT Lab 的实习生岗位

PLCT全称是程序语言与编译技术实验室，隶属于中科院软件所智能软件研究中心（ISRC），致力于成为编译技术领域的开源领导者，推进开源工具链及运行时系统
等软件基础设施的技术革新，具备主导开发和维护重要基础设施的技术及管理能力。与此同时，努力成为编译领域培养尖端人才的黄埔军校，推动先进编译技术在国
内的普及和发展。

### BJ46 Rust 工具链开发实习生

主要就是做 Rust for RISC-V 的工作，这是 Firefox on RISC-V 的一部分。确保 Rust 工具链和软件在 RV64GC 平台和 RV32GC 上可以跑起来，并进行功能的完善和性能的提升。

入职要求：
LV3+，能进行英语交流，对编译技术有很好的了解。对LLVM工具链和Rust有浓厚的兴趣。
远程实习，不需要坐班。

### BJ45 MLIR 开源开发实习生

我们相信MLIR将会成为未来编译器框架的实施标准。因此从2021年开始，PLCT实验室将 MLIR 列入了「关键开源基础设施」名单，已经跟 LLVM、GCC 一样成为PLCT实验室的长期管理对象。

工作内容：
参与PLCT实验室 MLIR 相关项目的开发。

入职要求：
LV3+，能进行英语交流，对编译技术有很好的了解。对 MLIR 项目有浓厚的兴趣。
远程实习，不需要坐班。

### BJ44 Chisel实习生： chisel-dsp的文档及测试

#### 工作内容
1. 文档
2. 单元测试
3. 基于chisel-dsp设计一个DSP extension （研究生级别课题）

#### 要求
- 掌握Scala语法，会用 Chisel 实现一些基本的设计。

此项工作将由 Sequencer 等社区活跃开发者指导。

### BJ43 Chisel实习生： Chisel 的安全的 AsyncQueue 库（1名）

#### 工作内容
1. 设计
2. 验证
3. Chisel API
4. 单元测试

#### 要求
- 掌握Scala语法
- 了解跨时钟域设计
- 了解FPGA Flow，可以进行简单的FPGA设计（跑马灯等）
- 了解ASIC Flow，可以进行简单的ASIC设计（简单的模块后端Flow）
- (Optional) 了解SMT验证，可以通过z3进行简单的Model Checking

此项工作将由 Sequencer 等社区活跃开发者指导。


### BJ42 Chisel实习生：Chisel 的 Decode API 设计与测试（1名）
#### 工作内容
1. 理解现有QMC代码
2. 标准Decode API
3. 单元测试

#### 要求
- 掌握Scala语法
- 会解卡罗图
- 有算法基础
- (Optional)了解JNI编程

此项工作将由 Sequencer 等社区活跃开发者指导。

### BJ41 Chisel实习生： Verification API（1名）

#### 工作内容
1. Chisel3 Verification API 设计
2. FIRRTL Verification IR Transform（Verilator as backend）
3. SystemVerilog emitting（SVA as backend）
4. FPGA synthesis(Verilog as backend)
5. 单元测试

#### 要求
- 了解FIRRTL基于Transform的设计模式
- 了解SVA（SystemVerilog Assertion）
- (Optional) 了解SMT验证，可以通过z3进行简单的Model Checking

此项工作将由 Sequencer 等社区活跃开发者指导。

### BJ40 Diploamcy SoC framework 开发实习生（1名）

#### 工作内容
1. Diplomacy Framework 单元测试
2. TileLink/AMBA 总线文档和单元测试
3. Wishbone 总线设计

#### 要求
- 熟练掌握Scala
- 了解基础的diplomacy的构建原理
- 熟悉RocketChip，可以自己写简单外设

此项工作将由 Sequencer 等社区活跃开发者指导。

### BJ39 Web 前端开发实习生（1名）

目标：开发和维护包括 [RISC-V 软件生态状态跟踪数据库](https://github.com/isrc-cas/riscv-ecosystem-tracking) 在内的 PLCT Lab 开发维护的各类 Web 页面。包括 HTML/CSS/JS。推荐和鼓励使用最新的前端框架。

入职要求：
LV2+

远程实习，不需要坐班。遵循每个月1号和16号的外部可见交付物报告制度。

### BJ38 LuaJIT 开发实习生（1名）

目标：将 LuaJIT 移植到 RV64G 平台。
背景参考：https://github.com/plctlab/plctlab.github.io/issues/9

入职要求：
LV4+，能进行英语交流，对编译技术有基本了解。如果事先了解过ELF格式、RISC-V或其他指令集、相关ABI文档，那么都算是加分项。
远程实习，不需要坐班。

### BJ37 GCC/Binutils/glibc/linker 开发实习生 （10名）

最近PLCT实验室在参与RISC-V国际基金会的相关新指令扩展的工作，具体内容是为 unratified extensions （就是还在制定中的扩展指令集）进行 GNU Toolchain 的实现，用于验证草案本身在设计上是否存在遗漏缺失、是否在功能或性能上有改进的空间。目前面向大学生及研究生招募开发者，以PLCT实验室实习生的身份，直接参与到RISC-V基金会管理下的GCC工具链开发中，并有可能后续直接将代码（patch）提交到上游（upstream）。最近开始有业界一线的大佬指导和review实习生的代码，是非常难得的学习机会。

与此同时，实习生岗位 BJ18 Clang/LLVM 开发实习生以及 BJ15 QEMU/Spike 开发实习生同样持续招聘。一个完整扩展指令参考实验和验证包括编译器、二进制工具、模拟器，都是需要的。

入职要求：
LV3+，能进行英语交流，对编译技术有基本了解。如果事先了解过ELF格式、RISC-V或其他指令集、相关ABI文档，那么都算是加分项。
远程实习，不需要坐班。


### BJ17 V8 for RISC-V 开发实习生（名额：9名）

工作内容：
参与PLCT实验室 V8 for RISC-V 相关项目的开发。

入职要求：
LV3+，能进行英语交流，对编译技术有基本了解。对 V8 for RISC-V 项目感兴趣。 https://github.com/v8-riscv/v8
远程实习，不需要坐班。

### BJ34 OpenJDK/OpenJ9 for RISC-V 开发实习生（名额：5名）

工作内容：
参与PLCT实验室 OpenJDK/OpenJ9 for RISC-V 相关项目的开发。帮助 RISC-V 社区将 Java 执行速度提高 100x 以上。

入职要求：
LV3+，能进行英语交流，对编译技术有基本了解。对 Java 虚拟机感兴趣。
远程实习，不需要坐班。

### BJ18 Clang/LLVM 开发实习生 (名额：6名)

工作内容：
参与PLCT实验室 Clang/LLVM 相关项目的开发、技术分析、报告撰写。

入职要求：
LV3+，能进行英语交流，对编译技术有基本了解。
远程实习，不需要坐班。

### BJ33 Firefox/Spidermonkey 开发实习生（名额：2名）

工作内容：
就像将 V8 移植到 RISC-V 平台一样，将 Spidermonkey 移植到 RISC-V 平台。跟 mentor 一起将工作提交到 Mozilla upstream。

入职要求：
LV3+ 级别。能够进行英文的交流。
远程实习，不需要坐班。

### BJ32 Dart for RISC-V 开发实习生（名额：2名）

工作内容：
就像将 V8 移植到 RISC-V 平台一样，将 Dart 移植到 RISC-V 平台。负责跟 Dart 上游交流，将移植工作 upstream。

入职要求：
LV4+，能进行英语交流，对编译技术有基本了解。写过 Dart 程序。
远程实习，不需要坐班。

### BJ15 QEMU/Spike 开源模拟器开发实习生（名额：2名）

工作内容：
参与PLCT实验室在QEMU、Spike等相关开源项目的开发。

入职要求：
LV3+，对模拟器的内部实现有兴趣。
远程实习，不需要坐班。

## 机器人团队的实习生岗位

暂无。

## 工业仿真组的实习生岗位

无。

### BJ36 RISC-V公开课教学助理（助教） - 已满

PLCT实验室即将推出面向RISC-V的在线教学课程（MOOC、慕课），包含编译器、虚拟机、模拟器的开发培训。
在线课程需要有助教负责回答学生的问题、批改学生作业、参与设计课程的 quiz 和 lab 内容。

入职要求：
LV2+ 级别，对自己选择的课程范围（LLVM、GCC、V8、QEMU、Spike 之一）有一些经验。有比较多的时间可以投入，响应及时。
如果能够有较为流畅的英语阅读和写作能力是加分项。
远程实习，不需要坐班。

### BJ35 RISC-V公开课制作助理 - 已满

PLCT实验室是RISC-V国际基金会的 Training Partner，提供面向RISC-V的编译器、虚拟机、模拟器的开发培训。
当前的培训是线下、中文的。目前我们正在准备新的在线教学课程（MOOC、慕课），并且希望提供中文和英文两个版本。

助理的工作包含以下一项或多项内容，如果你对以下任何一项工作熟悉或感兴趣都可以报名：
- 课程视频的剪辑和组织、特效处理
- 英文演讲稿和英文讲义内容的校对和润色
- 字幕时间轴制作和校对
- 课程内容的验证性学习（最好是没有经验的新手）
- 漫画或简笔画擅长的同学

入职要求：
LV2+ 级别，不要求编程技能，保留沟通和团队协作的要求。对自己选择的工作内容有一些经验。有比较多的时间可以投入。
远程实习，不需要坐班。
