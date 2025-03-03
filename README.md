# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# 11001ssm企业台账管理平台

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1Kp48e9EtU?p=2)


# 第1章 绪论
## 1.1课题背景
计算机的普及和互联网时代的到来使信息的发布和传播更加方便快捷。人们可以通过计算机上的浏览器访问多个应用系统，从中获取一些可以满足员工生活需求的管理系统。网站系统有时更像是一个大型“展示平台”，人们可以选择所需的信息进行在线申请、请假满足员工需求。

系统所要实现的功能分析，对于现在网络方便的管理，据数据调查显示，对于网上员工的数达到一百万以上，相比过去增长较快，人们通过网上登录的方式已经形成了一种依赖，不管需要什么信息内容，直接上网查找，参考比较大，对企业台账管理平台的类型和特点的内容信息有了详细的了解，让员工更有针对性的选择。这也给员工带来非常大的方便，员工可以不用像传统的方式进行查看信息，这样不仅耽误自己的时间，而且比对过程比较单一，所以企业台账管理平台 的开发不仅仅是能满足员工的需求，还能提高管理员的工作效率，减少原有不必要的工作量。
## 1.2研究意义
随着社会的发展和科学技术的进步，互联网技术越来越受欢迎。网络传播的生活方式逐渐受到广大人民群众的喜爱。越来越多的互联网爱好者开始在互联网上满足他们的基本需求，同时逐渐进入各个员工的生活起居。互联网具有许多优点，例如便利性，速度，高效率和低成本。因此，类似于企业台账管理平台，满足员工工作繁忙的需求，不仅是方便员工随时查看信息的途径，而且还能提高管理效率。

本文首先以企业台账管理平台过程的基本问题作为研究对象。在开发系统之前，我们对现有状况进行了详细的调查和分析。最后，我们利用计算机技术开发了一套完整合适的企业台账管理平台 。该系统的实现主要优势是：该系统主要采用计算机技术开发，它方便快捷；系统可以通过管理员界面查看系统所涉及的企业台账管理平台所有信息管理。

企业台账管理平台软件是一款方便、快捷、实用的信息服务查询软件。随着智能网络在全球市场的不断普及以及各种智能平台的使用，作为中国主流智能的技术开发系统，自然需要这样的软件来满足更多员工的需求和体验。系统的开发与人们的日常需求相关，如通过管理系统获取到员工管理、工资管理、物品库管理、物品申请管理、物品上报管理、请假信息管理、留言板管理、系统管理等信息详细情况，了解最新资讯信息等。

虽然目前已有很多基于java平台的企业台账管理平台相关的平台系统，但尚未出现更详细的功能显示和信息查询。经过分析，用户的第一眼往往是看到一个软件的外观，一个漂亮的界面将吸引用户下一次点击和理解。为了让用户通过无意识的点击尝试进入每个界面和每个按钮，用户可以进一步了解软件的质量，因此良好的软件界面将是吸引员工注意力的第一步。因此，对于每个软件界面设计工作来说，一个应用程序是占据非常重要的一部分，在高端大气中吸引用户界面，满足用户体验将进一步完成整个应用程序的各项功能，良好的用户体验度将继续使用并经常打开并使用此软件。
## 1.3研究内容
本企业台账管理平台平台，使用的是比较成熟的java技术和比较完善的MySQL数据库，将网络企业台账管理平台信息管理系统可以更安全、技术性更强的满足网站所有信息的管理。

企业台账管理平台平台主要实现了管理员模块、员工模块二大部分。通过本企业台账管理平台平台可以提高管理人员的工作效率，减少出错率，对于数据存储及查找有了更方便的操作。

详细内容介绍，将在以下五章中详细阐述：

第一章、绪论，介绍了研究课题选择的背景及意义、研究现状，简要介绍了本文的章节内容。

第二章、引入技术知识，通过引入关键技术进行开发，向系统中涉及直观表达的技术知识。

第三章、重点分析了系统的分析，从系统强大的供需市场出发，对系统开发的可行性，系统流程以及系统性能和功能进行了探讨。

第四章、介绍了系统的详细设计方案，包括系统结构设计和数据库设计。

第五章、系统设计的实现，通过对系统功能设计的详细说明，论证了系统的结构。

第六章、系统的整体测试，评判系统是否可以上线运行。
# 第2章 技术介绍
## 2.1相关技术
企业台账管理平台是在java + MySQL开发环境的基础上开发的。java是一种服务器端脚本语言，易于学习，实用且面向员工。全球超过35％的java驱动的互联网站点使用java。MySQL是一个数据库管理系统，因为它的体积小但速度快，成本低，或者开源受到中小型网站的青睐。因此，java + MySQL作为一个成熟的开发环境，可以满足企业台账管理平台设计和开发所需的稳定性，安全性和可扩展性要求。
## 2.2java技术
java是JAVA的成员，所以java具有平台无关性，即实现跨平台功能，实现了员工界面和程序代码的解耦合，是的业务逻辑与代码的耦合度更低，开发人员可以在不更改java程序的情况下修改员工的界面。

java页面实质上也是一个HTML页面，只不过它包含了用于产生动态网页内容的JAVA代码，这些JAVA代码可以是JAVA Bean、SQL语句、RMI对象等。例如一个java页面包含了用于产生静态网页的HTML代码，同时也包含了连接数据库的JDBC代码，那么当网页在浏览器中显示时，它既包含了静态的HTML代码，又包含了从数据库中取得的动态内容，正因为如此才能称之为动态网页。

java程序简单实用，面向员工。在同一系统中体现的java技术优势只需要写一次; 同一系统下的多平台设计和开发；灵活且能够在多个服务器上运行；拥有各种强大的免费工具支持；在网页运行时实现服务器端组件。

在网站访问频率不是很高的环境中用作Web应用程序服务器。它是免费的开源，是java程序开发和调试的首选对象。 
## 2.3MySQL数据库
数据库是系统开发过程中不可或缺的一部分。 在WEB应用方面，MySQL AB开发了一个具有很大优势的MySQL关系数据库管理系统。 MySQL可以将数据存储在不同的表中，这非常灵活，并且还可以提高系统在实际应用中的速度。 数据库访问最常用于标准SQL语言，MySQL用于SQL语言，因此它具有高度兼容性。数据库的操作是必不可少的，包括对数据库表的增加、删除、修改、查询等功能。现如今，数据库可以分为关系型数据库和非关系型数据库，Mysql属于关系性数据库，Mysql数据库是一款小型的关系型数据库，它以其自身特点：体积小、速度快、成本低等，Mysql数据库是目前最受欢迎的开源数据库。

在WEB应用技术中， Mysql数据库支持不同的操作系统平台，虽然在不同平台下的安装和配置都不相同，但是差别也不是很大，Mysql在Windows平台下两种安装方式，二进制版和免安装版。安装完Mysql数据库之后，需要启动服务进程，相应的客户端就可以连接数据库，客户端可通过命令行或者图形界面工具登录数据库。
## 2.4 Tomcat介绍
Tomcat 虽然是Apache的扩展，但是它们都是可以独立运行的，二者是不互相干扰的。当配置正确的时候，Apache服务器为HTML页面的运行提供技术支持，Tomcat 的任务则是运行Servle和java 页面。Tomca也具有一定的HTML页面处理功能。Tomcat属于一种轻型的服务器，所以说在中小企业中并不具有普适性。但是当程序员需要开发或调试java 程序时，则通常会将该服务器作为首选。对于一个仅具有计算机基础知识的人来说，计算机系统具有一个好的Apache服务器，可以很好的对HTML 页面进行访问。Tomcat是非常受欢迎的服务器，因为它具有较好的扩展性，而且在运行的时候不需要太多的系统资源，拥有程序员所需要的收发邮件功能，还能够支持负载平衡，该程序能够不断的更新，程序员能够根据自己的需要增加新的功能。

## 2.5 SSM框架

当今流行的“SSM组合框架”是Spring + SpringMVC + MyBatis的缩写，受到很多的追捧，“组合SSM框架”是强强联手、各司其职、协调互补的团队精神。web项目的框架，通常更简单的数据源。Spring属于一个轻量级的反转控制框架(IoC)，但它也是一个面向表面的容器(AOP)。SpringMVC常常用于控制器的分类工作模式，与模型对象分开，程序对象的作用与自动取款机进行处理。这种解耦治疗使整个系统的个性化变得更加容易。MyBatis是一个良好的可持续性框架，支持普通SQL查询，同时允许对存储过程的高级映射进行数据的优化处理。大型Java Web应用程序的由于开发成本太高，开发后难以维护和开发过程中一些难以解决的问题，而采用“SSM组合框架”，它允许建立业务层次结构，并为这个问题提供良好的解决方案。



# 第3章 需求分析
## 3.1需求分析概述
任何一个项目在开发研究前，都需要对研发系统本身的需求做一个认真的分析，市场的调研是不可忽视的，从实际场景中确定使用人员的功能需求，从而明确目标，对整个系统的开发有一个更加准确的定位，在这个章节，需要对系统的性能分析，业务流程分析，和数据等进行分析，企业台账管理平台的整体界面简单，功能完善。

需求的可行性是分析和讨论发达的系统能达到什么样的要求。开发的系统平台是否符合之前的要求。只有在预先评估系统的开发中，才能在系统开发和实施之前完成需求。如果您不具备开发一个功能不合格的系统的可行性，那就是开发失败。开发系统是否有用，可以完成之前讨论过的需求，以下分析了小企业台账管理平台的实际需求。

系统设计需要从员工和管理员的实际需求开始，以了解他们需要实施哪些功能以及他们可以包括哪些管理工作。

考虑到企业台账管理平台设计的特点，应满足几个要求：

（1）它可以通过网络开展员工企业台账管理平台工作，促进对我对企业台账一个新的认识。

（2）学习方法变得更加多样化，管理更加标准化;

（3）它提供了一个免费的渠道，以确保数据的实时有效沟通。
## 3.2可行性分析
可行性分析目的是根据所开发系统的员工需求，明确研究方向和目标，通过可行性分析确定系统的框架和功能模块。

可行性分析是对任何管理系统的需求、技术和经济的分析。其中最重要的技术方面的可行性，技术可行性是分析软件开发技术的应用开发系统是可行的。其次，分析软件系统的需求，分析软件需求能否满足预先设计的功能需求。最后讨论了系统的操作可行性和经济可行性。
### 3.2.1经济可行性
在开发任何软件系统之前，它将考虑其后来的经济可行性，即开发和设计软件所需的成本及其在以后运行中可带来的经济效益是否可以匹配，以及软件是否能带来经济效益给员工。在本交互式员工管理软件的设计中，本文的主要目的是为管理员提供一个新的企业台账管理平台，这在经济上是完全可行的。
### 3.2.2技术可行性
系统比较重要的一个分析就是技术可行分析，没有好的技术，再好的设计也是达不到系统的要求，并且对于技术的设计，使用的技术，如何更好的利用技术将所要实现的功能模块进行详细的分析，需要对技术进行详细的了解及自己的所学知识的一个综合使用。技术可行性主要取决于系统设计和开发中使用的各种硬件设施和软件设置，是否可以更好的结合，发挥他们的优势避开他们的弊端进行完美结合，确保技术的安全使用及正常的操作。

企业台账管理平台主要是基于eclipse技术开发，到目前为止，java技术的发展已经非常成熟。同时，它也受到许多开发人员的青睐。而且，在技术层面，Windows平台决定可以完成开发企业台账管理平台的任务。因此，系统开发在技术上是可行的。
## 3.3系统功能设计
软件的员工界面是最直接接触的对象，包括是否允许员工使用简单方便，请求的响应时间，主图像的整体质量，整体布局的质量。

企业台账管理平台的设计基于现有的网络平台，可以实现员工管理及数据信息管理等功能。方便管理员对个人中心、员工管理、工资管理、物品库管理、物品申请管理、物品上报管理、请假信息管理、留言板管理、系统管理有详细的了解及统计分析，随时查看信息状态。 

基于java平台的企业台账管理平台 应用，启动后进入到网站可以前后台管理等进行查看及相应操作，帮助解决常见问题，所有这些数据都将通过后台服务获得，这个服务根据时间进行同步最新数据信息。

系统功能设计是在系统开发和设计思想的总体任务的基础上完成的。该系统的主要任务是实现企业台账管理平台管理，使员工可以通过指令完成整个企业台账管理平台的操作。

从上面的描述中可以基本可以实现软件的功能： 

1、开发实现企业台账管理平台的整个系统程序； 

2、管理员；首页、个人中心、员工管理、工资管理、物品库管理、物品申请管理、物品上报管理、请假信息管理、留言板管理、系统管理

等模块信息的查看及相应操作；

3. 员工：首页、个人中心、工资管理、物品申请管理、物品上报管理、请假信息管理等功能。  
3. 前台首页；首页、物品库、公司公告、留言反馈、个人中心、后台管理等相应操作

5、基础数据管理：实现系统基本信息的添加、修改及删除等操作，并且根据需求进行留言信息的查看及回复相应操作。


# 第4章 系统设计
## 4.1系统结构设计
企业台账管理平台的设计主要是为了满足员工的实际需求。 因此，它需要通过Internet实现，因此它必须具备硬件和软件基础。该平台最终可以通过科学技术和各种方式达到支持智能化的信息管理的目的。因此，它必须具备网络企业台账管理平台管理所需的环境和各种资料，并保证实现开放性，模块性和实用性三个原则。

企业台账管理平台，主要包括管理员、员工二个员工角色，对于员工角色不同，所使用的功能模块相应不同。

管理员、员工的功能，根据需求可以对系统已有的首页管理员；首页、个人中心、员工管理、工资管理、物品库管理、物品申请管理、物品上报管理、请假信息管理、留言板管理、系统管理

员工；首页、个人中心、工资管理、物品申请管理、物品上报管理、请假信息管理等功能。  

企业台账管理平台等功能模块的管理维护等操作，如下图4-1所示。

![](/md/blog.003.png)

图4-1 系统功能图
## 4.2数据库设计
数据库是信息系统的基础和核心。数据库设计的好坏直接影响到信息系统开发的成败。创建数据库表首先确定实体的属性和实体之间的关系。根据关系创建一个数据表。
### 4.2.1实体ER图
数据库是整个软件编程中最重要的一个步骤，对于数据库问题主要是判定数据库的数量和结构公式的创建。企业台账管理平台使用的是Mysql进行对数据库进行管理，进行保证数据的安全性、稳定性等。

概念模型的设计是为了抽象真实世界的信息，并对信息世界进行建模。它是数据库设计的强大工具。数据库概念模型设计可以通过E-R图描述现实世界的概念模型。系统的E-R图显示了系统中实体之间的链接。而且Mysql数据库是自我保护能力比较强的数据库，下图主要是对数据库实体的E-R图：

管理员信息实体属性图如图4-2所示。

![](/md/blog.004.png)

图4-2管理员信息实体属性图

员工信息：员工工号、员工姓名、密码、部门、性别、联系电话、邮箱、身份证、家庭住址、操作实体属性图如图4-3所示。

![](/md/blog.005.png)

图4-3员工信息实体属性图

物品库信息：物品编号、物品名称、图片、数量、位置、规格、详情实体属性图如图4-4所示。

![](/md/blog.006.png)

图4-4物品库信息实体属性图

请假信息：员工工号、员工姓名、部门、请假时间、审核回复、审核、操作实体属性图如图4-5所示。

![](/md/blog.007.png)

图4-5请假信息实体属性图
### 4.2.2数据表
每个数据库的应用它们都是和区分开的，当运行到一定的程序当中，它就会与自己相关的协议与客户端进行通讯。那么这个系统就会对使这些数据进行连接。当我们选择哪个桥段的时候，接下来就会简单的叙述这个数据库是如何来创建的。当点击完成按钮的时候就会自动在对话框内弹出数据源的名称，在进行点击下一步即可，直接在输入相对应的身份验证和登录密码。

根据系统功能设计的要求和功能模块的划分，农业科成果发布与展示平台的设计与实现一共涉及到四个数据表。下面就介绍一下各别主要数据库表的设计结构及其功能建立数据库表：

表4.yuangong员工表

|Field|Type|Comment|
| :-: | :-: | :-: |
|id|int(11)|主键|
|addtime|varchar(200) |添加时间|
|yuangonggonghao|varchar(200)|员工工号|
|mima|varchar(200)|密码|
|yuangongxingming|varchar(200)|员工姓名|
|bumen|varchar(200)|部门|
|xingbie|varchar(200)|性别|
|lianxidianhua|varchar(200)|联系电话|
|youxiang|varchar(200)|邮箱|
|shenfenzheng|varchar(200)|身份证|
|jiatingzhuzhi||家庭住址|
表4.2 gongzi工资

|Field|Type|Comment|
| :-: | :-: | :-: |
|id|int(11)|主键|
|addtime|varchar(200)|添加时间|
|biaoti|varchar(200)|标题|
|yuangonggonghao|varchar(200)|视频类别|
|yuangongxingming|varchar(200)|员工工号|
|jibengongzi|varchar(200)|员工姓名|
|jiabanxinzi|varchar(200)|基本工资|
|queqinxinzi|varchar(200)|基本薪资|
|gaowenbutie|varchar(200)|高温补贴|
|gonglingjiang|varchar(200)|工龄奖|
|shifagongzi|varchar(200)|实发工资|
|dengjishijian|varchar(200)|登记时间|
表4.qingjiaxinxi请假信息表

|Field|Type|Comment|
| :-: | :-: | :-: |
|id|int(11)|主键|
|addtime|varchar(200)|添加时间|
|yuangonggonghao|varchar(200)|员工工号|
|yuangongxingming|varchar(200)|员工姓名|
|bumen|varchar(200)|部门|
|qingjiayuanyin|varchar(200)|请假原因|
|qingjiashijian|varchar(200)|请假时间|
|sfsh|varchar(200)|是否审核|
|shhf|varchar(200)|审核回复|
# 第5章 系统实现
## 5.1员工功能模块
员工登录功能是系统中一个非常重要的功能模块。这个函数模块需要做的第一件事是设计系统的安全性。不能说任何打开登录界面的人都可以进入系统。我们想控制管理。成员的账号和密码，只有拥有权限的员工才能通过这个登录界面进入系统管理界面，这是非常重要的。员工想要登录和使用系统首先进入注册、登录账户和登录密码，然后我们使用程序来检索，检索数据库中的账户信息一致输入账号密码，如果输入账号信息让员工登录时，如果它不存在，给一个提示,非法登陆，所以这个功能模块是非常重要的。

员工通过网址进入到网站界面，进行填写自己的员工名和密码等信息输入完成后员工登录成功，如图5-1所示，如果员工没有自己的账户信息，则需要员工进行在线注册，员工注册时根据需求可以通过注册界面提示的文本框信息进行在线填写自己的基本信息内容，信息编辑完成后核对信息无误后进行在线提交，新的员工登陆完成，如图5-2所示。

![](/md/blog.008.png)

图5-1注册界面

![](/md/blog.009.png)

图5-2登陆界面

员工登录进入到网站界面，可以进行查看首页、物品库、公司公告、留言反馈、个人中心、后台管理等功能模块，进行相对应操作，通过个人中心进行查看个人信息、信息修改，进行查看操作，如图5-3所示。

![](/md/blog.010.png) 

图5-3个人中心界面

员工通过点击物品库可以进行查看物品编号、物品名称、图片、数量、位置、规格、详情等信息，进行查看等操作，如图5-4所示。员工点击视频公告信息页面，可以进行查看公告信息等信息，如图5-5所示。

![](/md/blog.011.png)

图5-4 物品库界面

![](/md/blog.012.png)

图5-5公告信息界面图

留言反馈，员工通过点击留言反馈可以进行留言等信息，如图5-6所示。

![](/md/blog.013.png)

图5-6留言反馈界面



个人中心，员工通过点击个人中心可以进行员工工号、员工姓名、密码、部门、性别、联系电话、邮箱、身份证、家庭住址等信息进行添加、删除、修改等等操作，如图5-7所示。

![](/md/blog.014.png)

图5-7个人中心界面
##
## 5.2员工后台功能模块
员工通过点击后台管理，进入页面可以查看个人中心并进行增删改查等进行相对应操作，如图5-8所示。

![](/md/blog.015.png)

图5-8员工后台个人中心界面

物品申请管理：通过物品申请管理可以进行获取物品编号、物品名称、数量、员工工号、员工姓名等进行修改、删除信息，如图5-9所示。

![](/md/blog.016.png)

图5-9物品申请管理界面
## 5.3管理员功能模块
管理员通过后台登录窗口进行输入自己的账号信息、密码、角色等信息，进行登录，如图5-10所示。

![](/md/blog.017.png)

图5-10管理员登录界面

个人信息，管理员通过列表进行查看员工工号、员工姓名、密码、部门、性别、联系电话、邮箱、身份证、家庭住址等信息进行添加、修改或删除操作，如图5-11所示。

![](/md/blog.018.png)

![](/md/blog.019.png)

图5-11个人信息界面

物品库管理，管理员通过物品库管理可以在线查看物品编号、物品名称、图片、数量、位置、规格等信息，进行详情或修改、删除操作，如图5-12所示。

![](/md/blog.020.png)

图5-12物品库管理界面

请假信息，管理员通过请假信息可以在线查看员工工号、员工姓名、部门、请假时间、审核回复、审核、操作操作等信息，进行查看或修改、删除操作，如图5-13所示。

![](/md/blog.021.png)

图5-13请假信息界面

管理员通过系统管理页面查看轮播图/公司公告等进行上传图片进行添加、删除、修改以及查看并对整个系统进行维护等操作，进行查看或添加修改或删除，如图5-14所示。

![](/md/blog.022.png)

图5-14系统管理界面图

第6章 系统测试











