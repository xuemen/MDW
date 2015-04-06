#项目配置备忘
#Project Configuration Memo

##项目综述
1. 项目名称：创业实训
1. 项目代号：MDW（Modeling and Deploy Workshop）
1. 项目经理：黄勇刚
1. 项目输出：[记录种类英文缩写]
	1. 项目模型
	2. 部署包[DP:Deployment Package]
	3. 其它输出在模型中明确。
1. 项目预算及支付方式：
	1. 初始模型：4096 JT
	2. 初始模型生效前的杂费：2048 JT
	3. 之后的利益分配根据模型进行。
1. 项目进度计划：
	1. 2015年4月中旬完成项目建模。
	2. 2015年暑假完成首版部署包，开始公测。
	3. 2015年秋季学期开始正式运营。
		1. 工作周期为：
			* 寒假+春季学期
			* 暑假+秋季学期
		2. 每年1月、7月输出下一个工作周期的工作计划。
		3. 每年4月、10月输出上一个工作周期的工作总结。

##版本管理
1. 版本库路径：http://git.oschina.net/hyg/MDW
2. 版本库文件夹增补定义：
	1. log：发布工作日志
		1. 项目日志： MDW.PLog.yyyymm.md  （yyyy=年，mm=月）
		2. 个人工作日志：MDW.Log.Name.yyyymm.md  (Name=中文名)
		3. 工单：MDW.Ticket.xxx.yaml   （xxx是流水号）
	2. doc：存放给项目模型以及部署包中的文档。
	3. client：存放客户端软件代码及附属文件。
	4. server：存放服务端软件代码及附属文件。
	5. 项目输出的文件格式：**MDW.eee[.nnn[-m]].xxx**
		eee- 记录种类英文缩写
		nnn- 流水号。项目文件在项目内唯一。
		m  - 附件序号。
		xxx- 文件后缀
	6. 审议意见文件格式：**NICON.eee[.nnn].aaa.xxx**
		aaa- 审议者中文名。其它部分同被审议文件。

##沟通管理
1. wiki路径：http://git.oschina.net/hyg/MDW/wikis/home  
1. bug跟踪路径：http://git.oschina.net/hyg/MDW/issues  