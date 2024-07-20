
# 一、简介
	当前版本V1.3（蓝队版本）红队等下半年吧

这款工具是一款功能强大的网络安全综合工具，旨在为安全从业者、红蓝对抗人员和网络安全爱好者提供全面的网络安全解决方案。它集成了多种实用功能，包括解密、分析、扫描、溯源等，为用户提供了便捷的操作界面和丰富的功能选择。

## V1.3版本 优化概述

### 1、兼容性

- 兼容arm架构系统


### 2、UI

- 2.1 界面放大、缩小按钮
- 2.2 尺寸自适应
- 2.3 默认生成文件目录规定为jar目录
- 2.4 ui -记住密码
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/b58a5fc0aeb14721beb473d83347b16e.png)


### 3、一键解密

- 3.1 兼容AES/DES的zeropadding填充方案自动解密
- 3.2 md5_32/md5_16/sha1解密内置库，提高查询效率
- 3.3 字典爆破项可选
- 3.4 通过密文/流量包自动识别webshell管理工具

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/bd95c973253f431c8081b09764e03ffc.png)

### 4、反编译

- 支持AI优化、添加注释反编译后内容

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/ab9acff27eba4867a6323094e741c729.png)

### 5、归属地查询

- 5.1 银行卡归属地接口优化
- 5.2 手机号归属地库更新
- 5.3 支持批量查询

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/cc3e012edd06481da85dcf1ee8bcc432.png)

### 6、AI分析

- AI保留5次会话记忆
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/ce4b0d63b94c4171be6756237a44e319.png)
### 7、文件原信息
- 支持二维码图片解析

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/ffa31613843949589ce1486f56df4327.png)


# 二、优势

| 特性 | 说明 |
|:---:|:---:|
| 强大全面 | 每个功能相较于同类型工具更强大，功能支持更全面 | 
| 综合性能 | 一体化设计，用户无需切换工具或界面即可完成各项操作 | 
| 用户友好 | 界面简单友好，操作易上手 | 
| 反馈支持 | 重视用户反馈，提供及时支持和帮助 | 

# 三、使用场景

1. 红蓝对抗
2. 流量监测
3. 流量研判
4. 流量审计
5. ~~CTF竞赛~~  （下下个版本）

# 四、运行环境

| 环境 | 说明 |
|:---:|:---:|
| Java版本 | 8 / 11+ (【荐】性能更高) | 
| 兼容平台 | 支持 Windows、Linux 和 Mac 操作系统(兼容arm) | 

# 五、价格与许可

**免费使用**：目前提供的是一个社区版本，完全免费供用户使用。这个版本包含了所有蓝队功能，并且没有任何时间限制，尽情享受工具带来的便利和效益。

**内部版**：工具被设计成可扩展和高度定制化的。虽然提到了"内部版"，但它并不是一个公开可用的版本。内部版拥有所有功能，包括目前公开版中还未开放的所有功能，但未能进行健全的测试与修补。这些功能因为团队资源有限，难以及时地进行功能的测试和维护，暂时没有在公开的社区版中开放。然而，我正在努力完善这些功能，并计划在未来的更新中陆续放出。我的目标是提供一个完整而强大的工具，以满足用户的各种需求。

**未来开源计划**：虽然目前并没有开源工具，但我认识到开源的重要性，并且在未来可能会考虑开源的可能性。我会在确保用户利益和安全的前提下，谨慎地考虑开源的时机和方式。

# 六、快速入门

## 1. 功能介绍
### 1.1 一键解密，洞悉攻击行为

| 方案类型 | 支持情况 |
|:---:|:---:|
| webshell交互流量 | 支持 | 
| 多种加密方式混用 | 支持 | 
| 强混淆数据 | 支持 | 
| 组件密文数据 | 支持 | 
| 中间件等配置 | 支持 | 
| 输入格式多样化 | 支持 | 
| 多种Key爆破方式 | 支持（**解密不出来记得尝试更换方式**） | 
| AI分析 | 支持 | 
| ... | ... |

- 支持所有常见webshell交互流量解密

| Webshell管理工具 | 支持情况 |
|:---:|:---:|
| 冰蝎 | 支持 | 
| 蚁剑 | 支持 | 
| 哥斯拉 | 支持 | 
| China Chopper | 支持 | 
| Cknife | 支持 | 
| ... | ... |

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/0b922f6282d34b9db0c89a9d2d2463cc.png)
- 支持自动检测多种加密方式混用解密

| 支持的解密方式 | 说明 | 支持情况 |
|:---:|:---:|:---:|
| AES | 高级加密标准 | 支持 |
| DES | 数据加密标准 | 支持 |
| RSA | RSA公钥加密算法 | 支持 |
| Blowfish | 对称密钥分组密码算法 | 支持 |
| XOR | 异或加密算法 | 支持 |
| SHA1 | 安全散列算法 | 支持 |
| MD5 | 消息摘要算法 | 支持 |
| MD5_16 | MD5的16位哈希 | 支持 |
| Base64 | 常用于编码二进制数据的方法 | 支持 |
| Unicode | 字符编码标准 | 支持 |
| Hex | 十六进制编码方式 | 支持 |
| URL | 统一资源定位符编码方式 | 支持 |
| Html | HTML实体编码方式 | 支持 |
| Rot13 | ROT13替换加密算法 | 支持 |
| Chr | ASCII字符编码 | 支持 |
| strRev | 字符串反转 | 支持 |
| Byte | 字节处理 | 支持 |
| Bcel | Java字节码编辑器 | 支持 |
| Gzip | 数据压缩算法 | 支持 |
| 反序列化 | 将数据从序列化的格式还原回原始格式 | 支持 |
| ... | ... | ... |

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/d37c6cb641aa467a9cf9adcdb8df65bd.png)

- 支持强混淆解密（Unicode多u混淆、log4j强混淆等混淆方式）

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/ef90b2a0b20d407991b4a5dd099b7dab.png)

- 支持常见组件密文数据解密

| 支持的组件 | 支持情况 |
|:---:|:---:|
| Shiro | 支持 |
| Log4j | 支持 |
| Cas | 支持 |
| JWT | 支持 |
| ... | ... |

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/ee9c9bb255af4e3bb64c8ed041076b0d.png)
![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/5699c4ed8ce347979f20c59dc736c7b9.png)
- 支持常见中间件等配置解密

| 支持类型 | 支持情况 |
|:---:|:---:|
| WebLogicDB | 支持 |
| JbossDB | 支持 |
| SpringDB | 支持 |
| DruidDB | 支持 |
| FinalshellDB | 支持 |
| Navicat | 支持 |
| 用友DB | 支持 |
| 致远DB | 支持 |
| 帆软DB | 支持 |
| 蓝凌DB | 支持 |
| 强智DB | 支持 |
| RealorDB | 支持 |
| HrmsDB | 支持 |
| H3CDB | 支持 |
| H3C_imcDB | 支持 |
| IvmsDB | 支持 |
| ... | ... |

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/1f4196911ad945dab5700afb7d67f665.png)

- 支持多种用户输入格式

| 支持类型 | 说明 |
|:---:|:---:|
| 纯密文 | 直接输入密文内容 |
| Json请求体 | 例：{"username":"密文","passwd":"密文"} |
| Form Data请求体 | 例：username=密文&passwd=密文 |
| 请求完整包 | 包含请求头部及body内容 |

![™™](https://img-blog.csdnimg.cn/direct/a4b79cb7127442d792e0aa5fd73e2122.png)



- 支持多种Key爆破方式

| 支持类型 | 说明 |
|:---:|:---:|
| 默认Key快速解密 | 快速解密 |
| 指定Key快速解密 | 用户输入Key值进行解密 |
| 使用内置50万Key字典解密 | 速度慢，建议适度调控线程数 |
| 指定Key字典解密 | 用户加载本地Key字典进行解密 |

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/27296db91afb4f8ca92056f048d6bd39.png)

- AI分析恶意脚本

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/12fa2dd7a01d4b68b707205410df52ba.png)

	结果若是不满意，可点击刷新重新获取AI分析结果

### 1.2 专项加解密

- 指定专项解密，由【一键解密】单独提出来的部分加解密方法

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/ea2f7ac347c04d6f80671d2c8a5a4f09.png)

### 1.3 IP筛选

- 支持多种展示形式

| 展示形式 | 支持状态 |
|:---:|:---:|
| IP提取 | 支持 |
| IP提取+归属地查询 | 支持 |
| 原文高亮IP | 支持 |
| 原文高亮IP+注明归属地 | 支持 |

- 支持自定义筛选

| 支持类型 | 支持状态 |
|:---:|:---:|
| 自定义筛选 | 支持 |
| 国内外IP分类 | 支持 |
| 内外网IP分类 | 支持 |
| 地区区域分类 | 支持 |

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/9d9b8350f93648c5b2e2cbff53922e8e.png)

### 1.4 AI分析

- 默认采用自带的AI模型

		致力于提供优质的人工智能体验。然而，由于资金有限以及软件免费的性质，默认的AI模型可能存在一些性能上的局限性。
		后续可能因资金或用户恶意行为导致暂停自带AI功能。

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/d72dc8915ac24308b9a5bef91fbece0b.png)

- 可手动配置ChatGPT

		右上角设置 -> 配置GPT_Model、GPT_API_Key -> 保存
![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/68090f02eb0647efa5fdd53b4eb60477.png)
- 版本计划

		后续支持历史会话

### 1.5 反编译

- 支持的反编译器

| 支持类型 | 支持状态 |
|:---:|:---:|
| idea | 支持 |
| procyon | 支持 |

		设置中可配置默认反编译器

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/2ecba4b50a884dd1b1b4e169f0655fbc.png)

- 版本计划

		支持批量反编译

### 1.6 区块链溯源
- 支持钱包地址查询

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/c08ae1d43b1a4519a94d4c9639cec557.png)

- 支持交易hash查询

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/f808795e93c4445cad1a4e48e527e720.png)

- 支持区块ID查询

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/41de4278baff44f2a23cf26081cd140d.png)

- 支持名词解释查询

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/0193861262dc4e09b54fc0aa6f0fd89b.png)
### 1.7 归属地查询

- 测试版批量查询未公开

| 特性 | 描述 |
|:---:|:---:|
| 支持类型 | 银行卡归属地免费批量查询、手机号归属地免费批量查询。 |
| 支持广泛 | 涵盖超过2000家银行，可精准查询银行卡具体归属地或支行，以及手机号的运营商和省市信息。 |
| 数据筛选 | 提供强大的数据筛选功能，包括数据去重和元素筛选，帮助用户快速处理和分析大量查询结果。 |

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/7b8accbf8da54457aeee019ee2ed510b.png)

### 1.8 文件元信息提取

- 支持多种文件元信息提取，若存在GPS信息，则进行经纬度逆编码，查询具体定位。
![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/31297a6feeb549af8a07a32c06303bf7.png)

### 1.9 扩展模块

- 综合性高，提供全面的资源指南，点击即可访问

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/ed32c11d985a4ec8834dac59114ee305.png)

- 具有可自定义性，根据个人需求，添加**快捷指令** 或 网站导航

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/5f9525291a3f4f8aba690d5f894169a7.png)

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/06f99d58465642e3b5cd43753559e471.png)

### 1.10 信息收集

- 测试版未公开

| 特性 | 描述 |
|:---:|:---:|
| 支持测绘平台 | Fofa、鹰图、ZoomEye、shodan |
| 数据聚合化 | 支持同时使用多方平台检索数据，并进行聚合整理 |
| 智能扩散搜索 | 开启后，将自动对查询的信息进行智能扩散搜索，包括对公司名称进行检索，并拓展至图标、域名、证书等关键信息的深度搜索 |
| 清洗与标准化 | 提供强大的数据清洗功能，确保数据整洁有序 |
| 重复数据过滤 | 通过改进的算法，快速准确地过滤重复数据，包括相似数据的智能识别 |
| 智能脏数据过滤 | 利用先进的机器学习算法，实现智能化的脏数据过滤，确保数据质量。有效解决模糊检索影子资产时，杂数据影响 |

### 1.11 漏洞扫描

- 测试版未公开

| 特性 | 描述 |
|:---:|:---:|
| 内置POC脚本 | 工具内置了大量的POC脚本，覆盖了多种漏洞类型和攻击场景 |
| 高度语言兼容性 | 支持python、json(内测中)、yarm的POC |
| 高度代码兼容性 | 支持用户提供不规范的POC(暂支持python)，智能调用不规范的POC并获取不规范的输出，智能判断是否存在对应漏洞 |

### 1.12 免杀webShell

- 公开版，具有时效性，后续迭代更新，满足部分人需求
- 测试版，暂未公开，高频率更新，维护资源有限

| 特性 | 描述 |
|:---:|:---:|
| 涉及工具 | Godzilla、Behinder、AntSword |
| 支持语言 | JSP、JSPX、PHP、ASP、ASPX |
| 支持混淆 | Base64、AES、RAW、XOR、Unicode、CSHARP、Reflect |
| 自定义型 | 自定义webShell密钥，默认potato |

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/c2b866384def4269b3af78a4e1900268.png)

### 1.13 自定义内存码

- 测试版未公开

| 特性 | 描述 |
|:---:|:---:|
| 支持广泛 | 支持包括Tomcat、Resin、Jetty、WebLogic、WebSphere、Undertow、GlassFish、SpringMVC以及SpringWebFlux等主流中间件和框架 |
| 支持类型 | Filter/Listener/Interceptor/HandlerMethod |
| 支持工具 | Godzilla、Behinder、AntSword |
| 支持高度自定义 | 支持自定义密钥、请求头、类名、路由路径、输出格式、封装类型 |

### 1.14 命令生成

- 测试版未公开

| 特性 | 描述 |
|:---:|:---:|
| 支持类型 | 支持反向shell、正向shell、MSFVenom、HoaxShell、内网代理、文件下载、痕迹清理命令生成，满足渗透测试和攻击需求，提供一站式解决方案 |
| 自定义化 | 可根据特定环境输入IP和端口，系统根据参数生成多种定制化方案，确保适用性和灵活性 |
| 防检测化 | 支持添加编码防止检测，在一定程度上提高生成Payload的免杀能力，确保攻击效果 |
| 常用命令检索 | 支持对常用的内网横向攻击系统命令进行模糊检索，方便用户快速获取所需信息 |

### 1.15 KB提权查询

- 测试版未公开

| 特性 | 描述 |
|:---:|:---:|
| 查询提权信息 | 检查已安装的KB编号，展示存在的提权漏洞的详细信息，包括发布日期、CVE编号、KB编号、标题、影响产品、影响组件、严重性、漏洞影响、替代KB编号、漏洞利用方法 |
| 平替KB检测 | 通过对比是否已存在可替换的KB编号，剔除不存在的提权漏洞信息，减少误报，提高信息准确性 |
| 自定义筛选 | 可根据特定情况，自定义筛选/过滤条件，如影响产品、影响组件、严重性、是否存在漏洞利用等标准，减少误报，提高信息准确性 |

### 1.16 进程分析

| 特性 | 描述 |
|:---:|:---:|
| 进程利用分析 | 分析输入的进程信息，检索可能存在提权或深度利用的进程，并提供相关信息 |
| 杀软检测 | 自动检索当前系统中已安装的杀软，并列出其对应的进程信息 |

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/4da6f22bb226444587d9551b12d8f942.png)
-	后续会迭代，收录更多全面信息

### 1.17 信息生成

| 特性 | 描述 |
|:---:|:---:|
| 支持类型 | 个人信息、通讯信息、单位组织信息、银行卡信息 |

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/e4851573fc6445f9a4046c7c097eaa35.png)

## 2. 使用技巧

### 2.1 窗口菜单

- 为所有窗口文本添加右键菜单，以便用户可以方便地进行全选、复制等操作。

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/ec8996582b9e4419bedf26d771ba69d7.png)

### 2.2 个性化设置

- 用户可自定义配置代理(支持http\socks)、反编译器和AI模型

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/e961955bbbd54b7a892ab37356c67b67.png)

# 七、获取方式

- GitHub链接：[https://github.com/HotBoy-java/PotatoTool/releases/tag/Release](https://github.com/HotBoy-java/PotatoTool/releases/tag/Release)
- 启动命令后+debug，可打印解密报错，用于提交bug信息（例：java -jar xxx.jar debug）
- 推荐使用java11+，性能更高
- **启动密码：potato520**

# 八、常见问题
	
	Q:输入密码时卡顿
 	A:UI使用javafx,在jdk8中，该组件内置且官方未优化线程渲染。同时初始化时需要加载大量资源，导致软件初始化时（正好会显示输入密码界面）卡顿。然而jdk8以后的版本均对javafx渲染进行优化，不会因其他线程导致卡顿，所以更推荐使用jdk11+


  	Q:一键解密一直失败
   	A:可能该密文采用了个性化的Key进行加密，我们需要爆破Key，所以需要更换解密方式，比如选择内置50w字典爆破。若还是失败，可以和作者沟通讨论一下，完善工具


  	Q:一键解密卡死、卡顿
   	A:涉及md5解密、key爆破解密，会根据当前电脑内核数创建最大数量线程，性能差/后台开启过多程序的电脑会造成卡顿，不用担心，等待即可。【下个版本将优化默认采用最大线程/2的线程数量，并且用户可自定义线程数】


  	Q:UI界面显示不全
   	A:因界面采用DPI自适应，且未测试不常见的分辨率，所以导致部分分辨率显示异常，建议更换分辨率尝试。【下个版本考虑大小固定，DPI自适应作为可选项】


	Q:内测版能公布么
 	A:内部版暂不对外开放，UI上有很多bug，功能上也没有进行全面测试。但是后面会陆续开放，不会存在收费问题


	Q:启动失败，报错 mach-o file, but is an incompatible architecture (have 'x86_64', need 'arm64e' or 'arm64')
 	A:非常抱歉，目前发现在Mac上的M系列处理器的兼容性还有待改进。即使在1.8版本中能够运行，但涉及到反序列化时可能会遇到问题。这种情况下建议您在虚拟机中使用。【已经计划在下一个版本中改进对M系列处理器的兼容性】
  

	Q:自带的AI,交互问答时，传输给AI的信息会自动缺失最后一个字符（比如用户发送：现在你是一名老师  服务端收到的：现在你是一名老）
 	A:现在的UI存在的bug，导致传输时剔除掉用户问题最后一个字符，临时解决办法是问题后面加上句号或其他结束符号。【已经计划在下一个版本中改进】


	Q:自带的AI,交互问答时，在询问关于POC编写等敏感信息时拒绝回答
 	A:模型暂未添加sa，后续会对内置模型进行针对性sa训练，临时解决办法是根据网上bypass方案进行询问（注意，因资源有限，且使用人较多，故服务端未开启上下文对话模式）【因资源问题，优化周期比较久】


## 帮宝子点个star吧，Stargazers over time
[![Stargazers over time](https://starchart.cc/HotBoy-java/PotatoTool.svg?variant=adaptive)](https://starchart.cc/HotBoy-java/PotatoTool)

