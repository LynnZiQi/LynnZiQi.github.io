#HW1

#####简单题

1.软件工程的定义



> 软件工程是指导计算机软件开发和维护的 工程学科。采用工程的概念、原理、技术和方法来开发与维护软件，把经过实践考验而证明正确的管理技术和当前能够得到的最好的技术方法结合起来，这就是软件工程。

> <br>IEEE的定义

1）将系统化的、规范的、可度量的方法应用于软件的开发、运行和维护，即将工程化方法应用于软件；

> 2）在（1）中所述方法的研究 



2.阅读经典名著“人月神话”等资料，解释 software crisis、COCOMO 模型。





**software crisis**





> 由于软件生产的复杂性和高成本，使大型软件的生产出现了很大的困难，即出现软件危机。



*软件危机表现形式*



 1. 软件开发成本日益增长

 2. 软件开发进度难以控制

 3. 用户对“已完成”系统不满意的现象经常发生

 4. 软件产品的质量不可靠

 5. 软件的可维护程度低





**COCOMO模式**



>  英文全称为constructive cost

> model，中文为构造性成本模型。它是一种精确、易于使用的，基于模型的成本估算方法，最早由勃姆（Boehm）于1981年提出。从本质上说是一种参数化的项目估算方法，参数建模是把项目的某些特征作为参数，通过建立一个数字模型预测项目成本（类似于居住面积作为参数计算的整体的住房成本）



COCOMO模型中，考虑开发环境，软件开发项目的类型可以分为三种：



 - 组织型

 - 嵌入型

 - 半独立型



按照其详细程度可以分为三级：



 - 基本COCOMO模型

 - 中间COCOMO模型

 - 详细COCOMO模型



3.软件生命周期



> 计算机软件有一个孕育、诞生、成长、成熟、衰亡的生存过程，即软件的生命周期（也称软件开发生命周期SDLC或软件开发过程）。软件生命周期被划分为若干阶段，每个阶段有明确的任务，从而使规模、结构和管理复杂的软件开发过程得到适当的控制和管理。

>  典型划分GB8567（4个时期7个阶段）：

>  

- 软件分析时期：问题定义、可行性研究、需求分析 

- 软件设计时期：总体设计、详细设计 

- 编码与测试时期：编码、测试 

- 运行与维护时期 





4.按照SWEBok的KA划分，本课程关注哪些KA或知识领域？



 - 软件需求 Software Requirements

 - 软件设计 Software Design

 - 软件工程管理 Software Engineering Management

 - 软件工程过程 Software Engineering Process



5.解释 CMMI 的五个级别。例如：Level 1 - Initial：无序，自发生产模式。



> 

 1. 初始级：软件过程是无序的，有时甚至是混乱的，对过程几乎没有定义，成功取决于个人努力。管理是反应式的。

 2. 可管理级：建立了基本的项目管理过程来跟踪费用、进度和功能特性。制定了必要的过程纪律，能重复早先类似应用项目取得的成功经验。

 3. 已定义级：已将软件管理和工程两方面的过程文档化、标准化，并综合成该组织的标准软件过程。所有项目均使用经批准、剪裁的标准软件过程来开发和维护软件，软件产品的生产在整个软件过程是可见的。

 4. 量化管理级：分析对软件过程和产品质量的详细度量数据，对软件过程和产品都有定量的理解与控制。管理有一个作出结论的客观依据，管理能够在定量的范围内预测性能。

 5. 优化管理级：过程的量化反馈和先进的新思想、新技术促使过程持续不断改进。



6.用自己语言简述 SWEBok 或 CMMI 



CMMI模型中，软件组织（或者可以说公司）的软件能力成熟度被划分为五个等级，从一到五数字越大成熟度越高，高成熟度的等级象征着更强的综合软件能力。

企业可以选择进行CMMI的评估。评估是对企业准备的几个评估项目按照CMMI的标准进行检查。每一个级别都包含几个到十几个PA（过程域），如果该级别的全部PA都达到要求了，就可以评估为这个级别。

 CMMI是为了支持企业的商业目标的、提高收益的，不是用来增加管理成本的。更高级别的企业，效能会更高。

<hr>





#####解释 PSP 各项指标及技能要求：







<table style="color:rgb(0,0,0);" border="1" cellspacing="0" cellpadding="0"><tbody><tr><td valign="top"><h4><span style="color:rgb(79,129,189);"><em>PSP2.1</em></span></h4></td><td valign="top"><h4><span style="color:rgb(79,129,189);"><em>&nbsp;</em></span></h4></td></tr><tr><td valign="top"><p><span style="color:rgb(0,0,0);">Planning</span></p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Estimate</p><p><span style="color:rgb(0,0,0);">Development</span></p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Analysis</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Design Spec</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Design Review</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Coding Standard</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Design</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Coding</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Code Review</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Test</p><p><span style="color:rgb(0,0,0);">&nbsp;</span></p><p><span style="color:rgb(0,0,0);">&nbsp;</span></p><p><span style="color:rgb(0,0,0);">Record Time Spent</span></p><p><span style="color:rgb(0,0,0);">Test Report</span></p><p><span style="color:rgb(0,0,0);">Size Measurement</span></p><p><span style="color:rgb(0,0,0);">Postmortem</span></p><p><span style="color:rgb(0,0,0);">Process Improvement Plan</span></p></td><td valign="top"><p><span style="color:rgb(0,0,0);">计划</span></p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;估计这个任务需要多少时间</p><p><span style="color:rgb(0,0,0);">开发</span></p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;分析需求</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;生成设计文档</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;设计复审&nbsp;(和同事审核设计文档)</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;代码规范&nbsp;(为目前的开发制定合适的规范)</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;具体设计</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;具体编码</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;代码复审</p><p><span style="color:rgb(0,0,0);">·</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;测试（包括自我测试，修改代码，提交修改）</p><p><span style="color:rgb(0,0,0);"><br></span></p><p><span style="color:rgb(0,0,0);"><br></span></p><p><span style="color:rgb(0,0,0);">记录时间花费</span></p><p><span style="color:rgb(0,0,0);">测试报告</span></p><p><span style="color:rgb(0,0,0);">计算工作量</span></p><p><span style="color:rgb(0,0,0);">事后总结</span></p><p><span style="color:rgb(0,0,0);">提出过程改进计划</span></p><div><span style="color:rgb(0,0,0);"><br></span></div></td></tr></tbody></table>



•按表格 PSP 2.1， 了解一个软件工程师在接到一个任务之后要做什么，需要哪些技能，解释你打算如何统计每项数据？
<br>
如上表所示，软件工程师在接到一个任务之后需要计划、开发，然后记录时间花费、测试报告、计算工作量、事后总结和提出过程改进计划。其中，计划和开发有更为细节的步骤。
统计数据，比如计划阶段，估计这个任务需要多少时间，不仅要考虑实际编码、测试这些【硬】时间，还要考虑到分析、设计这些【软】时间；计算工作量的时候，主要考虑记录实际工作的时间，即有效利用的部分，比如查找bug，这样的时间花费需要有一个统一的标准进行折算，否则会出现“划水”的现象。记录项目时间花费的时候，还要考虑到有些任务是可以并行执行的。



