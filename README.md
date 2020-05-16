# 开源软件供应链点亮计划-暑期2020 

## 开源软件供应链点亮计划-暑期2020”是什么？

“开源软件供应链点亮计划-暑期2020”（以下简称 暑期2020）是由中科院软件所与 openEuler 社区共同举办的一项面向高校学生的暑期活动，旨在鼓励在校学生积极参与开源软件的开发维护，促进国内优秀开源软件社区的蓬勃发展。

该计划将联合各大开源社区，针对重要开源软件的开发与维护提供 mini 项目，并向全国高校学生开放报名。学生可自主选择感兴趣的项目进行申请，并在中选后获得该软件资深维护者（社区导师）亲自指导的机会。根据项目的难易程度和完成情况，参与者还可获取“开源软件供应链点亮计划-暑期2020”活动奖金和奖杯。

**“暑期2020”项目在今年（2020）首次举办，与Google Summer of Code类似，不同点是“暑期2020”只允许中国学生参加，可以看做中国版的GSoC。**

1. 官网：https://isrc.iscas.ac.cn/summer2020
2. 官方新闻：http://www.iscas.ac.cn/xshd2016/xshy2016/202004/t20200426_5563484.html

## 活动的主要参与方有哪些？

活动组织方：中国科学院软件研究所、openEuler 社区主办，中国科学院软件研究所中国科学院软件研究所南京软件技术研究院，华为技术有限公司、中科软科技股份有限公司、深圳华锐金融技术股份有限公司等公司协办，此外，活动组组委会还联合国内公司、科研院所和各大高校共同推广此次活动。

活动参与方主要角色为学生、社区和导师。

1. 学生：学生自由选择项目，与导师沟通实现方案并撰写项目计划书。被选中的学生将在导师指导下，按计划完成开发工作，并将成果贡献给社区。社区评估学生的完成度，主办方根据评估结果发放资助金额给学生。
2. 社区：社区提供项目列表和描述，并安排项目对应的导师，导师与申请者沟通方案、并从申请者中选中一位承接项目。在为期三个月的开发周期中，导师指导学生进行对应项目的开发工作。
3. 导师：社区针对每一个项目指定一个导师，与学生一起制定合适的开发计划和方案，指导学生按计划完成开发。

## 项目的奖金额度是多少，如何确定？

项目难度分为高、中、低三档，对应税前奖金分别为高（12000 元）、中（9000 元）、低（6000 元）。难度分级由社区根据项目任务自行决定。主办方会资助最终有学生申请的项目，在预算范围内主办方会尽可能的支持更多的项目，预期是 200+ 的项目。我们会根据社区反馈的情况，提供少量更大奖金的项目。

## 学生如何报名？

详见：https://isrc.iscas.ac.cn/summer2020/help/student.html#学生如何报名

## Casbin开源项目介绍

Casbin是一个强大的、高效的开源访问控制框架。涉及到Go, Java, Node.js, Javascript (React), Python, PHP, .NET, Delphi, Rust等多种语言。Casbin由北京大学罗杨博士创立于2017年，核心维护团队有数十人。Casbin在业界具有广泛影响力。目前已经被Intel、VMware、Orange、RedHat、T-Mobile等公司开源使用，被腾讯云、Cisco、Microsoft、Verizon等公司闭源使用。具体详见Casbin主页。Casbin Go主项目目前GitHub 6600+ stars，加上所有语言的实现、插件等可达到10000+ stars。Casbin曾经在国际上多次宣讲：

1. 新加坡政府技术部门Open Government Products：https://www.youtube.com/watch?v=OTT84oplR9o ；
2. 俄罗斯最大在线旅游平台tutu.ru：https://www.youtube.com/watch?v=Z5dUxH4PqYM 
3. 2019年香港互联网经济峰会IES上北京大学沈晴霓教授：https://ies2019.cyberport.hk/wp-content/uploads/2019/04/Cyber_Qingni-Shen.pdf

Casbin官网：https://casbin.org/

## 可选项目列表

### 1. Casbin核心引擎（Golang）

1. 项目标题：Casbin核心引擎（Golang）
2. 项目描述：Casbin采用独特的PERM模型语法（model）来实现强大、灵活的访问控制。Casbin Golang版本作为Casbin的第一个语言实现，拥有最多的用户以及最先进的feature。我们希望在Casbin Golang上：1）增强Casbin语法的表达能力，满足用户多样化的策略制定需求；2）优化Casbin在大规模规则集上（百万以上）的策略评估性能。这两个目标是Casbin的核心竞争力，对于其他Casbin语言的实现也会起到非常重要的借鉴意义。
3. 项目难度：高
4. 项目社区导师：[罗杨 (hsluoyz)](https://github.com/hsluoyz)
5. 导师联系方式：hsluoyz@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 增强Casbin语法的表达能力，满足用户多样化的策略制定需求
   - 优化Casbin在大规模规则集上（百万以上）的策略评估性能
   - 解决Casbin Golang主仓库&相关仓库中的issues：https://github.com/casbin/casbin/issues
8. 项目技术要求：
   - 熟悉Golang语言
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin

## 要求

### 工作职责：

- 每周与项目导师进行线上讨论，完成项目规定的开发任务。项目导师由开源项目创始人或其他核心成员担任；
- 积极参与开源社区的建设，参与代码提交、解决Issue、审核PR等日常工作；
- 配合完成官方要求的材料提交等事项，包括项目申请书撰写、社区反馈任务完成度追踪等。

### 职位要求：

- 本科、硕士或博士在读（已毕业、工作的无法参加）；
- 对开源软件、开源社区感兴趣；
- 熟悉一种或多种编程语言，有较强的工程能力，代码格式清晰规范，善于团队协作；
- 有一定英文读写能力，能够熟练运用英语在GitHub进行开发、协作；
- 较强的沟通能力和逻辑表达能力。

### 具有以下条件者优先：

- 熟悉计算机网络、网络安全，有相关项目经验；
- 熟悉Go语言、分布式系统、微服务架构，有相关项目经验；
- 在GitHub较为活跃，有自己的开源项目，或参与过知名开源项目；
- 可以在项目结束后继续长期参与开源社区的开发、建设或维护。

具体项目介绍：https://github.com/casbin/Summer2020#可选项目列表


## 投递要求

详见：https://isrc.iscas.ac.cn/summer2020/help/student.html#学生如何报名

## 联系方式

如对“暑期2020”活动本身有任何疑问，请联系活动官方：https://isrc.iscas.ac.cn/summer2020/#/contactus

Casbin社区管理员、导师联系方式：

1. QQ群：[546057381](https://shang.qq.com/wpa/qunwpa?idkey=8ac8b91fc97ace3d383d0035f7aa06f7d670fd8e8d4837347354a31c18fac885)
2. Gitter：https://gitter.im/casbin/summer
