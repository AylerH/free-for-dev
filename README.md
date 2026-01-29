# free-for.dev

现在，开发者和开源作者们有许多提供免费层级的服务，但要找到这些服务并做出明智的决策需要花费时间。

以下是一份包含免费开发者层级的软件（SaaS、PaaS、IaaS等）及其他服务的列表。

这个列表的范围仅限于那些基础设施开发者（如系统管理员、DevOps实践者等）可能会觉得有用的服务。我们非常喜欢所有的免费服务，但希望这个列表能保持主题相关性。有时候这个列表会有些模糊不清，所以这只是我的个人意见；如果我不接受你的贡献，请不要感到被冒犯。

这个列表是通过1600多人提交的拉取请求、评审意见以及共同努力而得出的。你也可以通过发送[拉取请求](https://github.com/ripienaar/free-for-dev)来帮忙，以便添加更多服务或移除那些已经改变或已退役的服务。[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

**注意**：此列表仅适用于即服务类型的产品，不适用于自托管软件。要符合资格，该服务必须提供免费层，而不仅仅是免费试用。如果免费层是按时间限制的，那么有效期必须至少持续一年。我们从安全角度来考虑免费层的问题，因此单点登录是可行的，但我不接受那些将TLS功能仅限付费层使用的服务。

# 目录

  * [主要云提供商始终免费的条款](#major-cloud-providers)
  * [云管理解决方案](#cloud-management-solutions)
  * [分析、事件与统计信息](#analytics-events-and-statistics)
  * [API、数据与机器学习](#apis-data-and-ml)
  * [工件存储库](#artifact-repos)
  * 基础服务](#baas)
  * 低代码平台](#low-code-platform)
  * 内容分发网络与保护](#cdn-and-protection)
  * 持续集成与持续交付](#ci-and-cd)
  * 内容管理系统](#cms)
  * 代码生成](#code-generation)  * [代码质量](#code-quality)
  * [代码搜索与浏览](#code-search-and-browsing)
  * [崩溃与异常处理](#crash-and-exception-handling)
  * [地图上的数据可视化](#data-visualization-on-maps)
  * [托管的数据服务](#managed-data-services)
  * [设计与用户界面](#design-and-ui)
  * [设计灵感](#design-inspiration)
  * [开发博客网站](#dev-blogging-sites)
  * [DNS](#dns)
  * [与Docker相关的内容](#docker-related)
  * [域名](#domain)
  * [教育与职业发展](#education-and-career-development)
  * [电子邮件](#email)
  * [功能开关管理平台](#feature-toggles-management-platforms)
  * [字体](#font)
  * [表单](#forms)
  * [生成式AI](#generative-ai)
  * [基础设施即服务](#iaas)
  * [集成开发环境与代码编辑](#ide-and-code-editing)
  * [国际移动号码验证API与SDK](#international-mobile-number-verification-api-and-sdk)
  * [问题跟踪与项目管理](#issue-tracking-and-project-management)  * [日志管理](#log-management)
  * [移动应用分发与反馈](#mobile-app-distribution-and-feedback)
  * [管理系统](#management-system)
  * [消息传递与流媒体服务](#messaging-and-streaming)
  * [其他事项](#miscellaneous)
  * [监控](#monitoring)
  * [PaaS](#paas)
  * [软件包构建系统](#package-build-system)
  * [支付与计费功能集成](#payment-and-billing-integration)
  * [隐私管理](#privacy-management)
  * [截图相关接口](#screenshot-apis)
  * [与Flutter相关的操作，以及无需Mac即可构建iOS应用的方法](#flutter-related-and-building-ios-apps-without-mac)
  * [搜索功能](#search)
  * [安全与PKI](#security-and-pki)
  * [认证、授权与用户管理](#authentication-authorization-and-user-management)
  * [源代码仓库](#source-code-repos)
  * [存储与媒体处理](#storage-and-media-processing)  * [隧道技术、WebRTC、Web Socket服务器及其他路由器](#tunneling-webrtc-web-socket-servers-and-other-routers)
  * [测试](#testing)
  * [团队与协作工具](#tools-for-teams-and-collaboration)
  * [翻译管理](#translation-management)
  * [访客会话录制](#visitor-session-recording)
  * [网站托管](#web-hosting)
  * [评论平台](#commenting-platforms)
  * [基于浏览器的硬件仿真](#browser-based-hardware-emulation-written-in-javascript)
  * [远程桌面工具](#remote-desktop-tools)
  * [游戏开发](#game-development)
  * [其他免费资源](#other-free-resources)

## 主要云服务提供商

  * [谷歌云平台](https://cloud.google.com)
    * 应用引擎 - 每天有28小时用于前端实例的运行时间，每天有9小时用于后端实例的运行时间
    * 云Firestore - 1GB的存储容量，每天可进行50,000次读取、20,000次写入、20,000次删除操作    * 计算引擎 - 1台非抢占式e2-micro实例，30GB硬盘，5GB快照存储（仅限某些地区使用），每月从北美到所有地区的网络出口流量为1GB，适用于中国及澳大利亚以外的地区
    * 云存储 - 5GB存储空间，每月网络出口流量为1GB
    * 云Shell - 基于Web的Linux shell工具，拥有5GB的持久化存储空间。每周使用时限为60小时
    * 云消息服务 - 每月可存储10GB的消息
    * 云函数 - 每月可调用200万次，包括后台调用和HTTP调用
    * 云运行平台 - 每月可处理200万次请求，拥有360,000GB秒的内存，180,000vCPU秒的运算时间，每月从北美到所有地区的网络出口流量为1GB
    * 谷歌Kubernetes引擎 - 对于单个区域集群，无需支付集群管理费用。每个用户节点将按照标准的计算引擎价格进行计费
    * 大数据 - 每月可查询1TB的数据，每月存储空间为10GB
    * 云构建工具 - 每天可使用120分钟进行构建操作    * 云源仓库 - 最多支持5位用户，存储容量达50GB，出流量达50GB
    * [Google Colab](https://colab.research.google.com/) - 免费的Jupyter笔记本开发环境
    * [Firebase Studio](https://firebase.studio) - Google Firebase Studio（前称Project IDX）。在Google Cloud上运行的在线VSCode环境
    * 完整详细的列表 - https://cloud.google.com/free

  * [亚马逊网络服务](https://aws.amazon.com)
    * [CloudFront](https://aws.amazon.com/cloudfront/) - 每月出流量达1TB，每月可调用函数数量达2百万个
    * [CloudWatch](https://aws.amazon.com/cloudwatch/) - 可自定义10个指标，并配置10个警报
    * [CodeBuild](https://aws.amazon.com/codebuild/) - 每月构建时间不超过100分钟
    * [CodeCommit](https://aws.amazon.com/codecommit/) - 支持5位活跃用户，存储容量达50GB，每月请求数量达10000次
    * [CodePipeline](https://aws.amazon.com/codepipeline/) - 每月有1个活跃的构建管道
    * [DynamoDB](https://aws.amazon.com/dynamodb/) - 25GB的NoSQL数据库    * [EC2](https://aws.amazon.com/ec2/) - 每月750小时的使用时长，可选择t2.micro或t3.micro实例，有效期为12个月。每月享有100GB的出口带宽。
    * [EBS](https://aws.amazon.com/ebs/) - 每月30GB的通用型SSD或磁带存储，有效期为12个月。
    * [弹性负载平衡](https://aws.amazon.com/elasticloadbalancing/) - 每月750小时的使用时长，有效期为12个月。
    * [RDS](https://aws.amazon.com/rds/) - 每月750小时的使用时长，可选择db.t2.micro、db.t3.micro或db.t4g.micro实例。每月享有20GB的通用型SSD存储和20GB的存储备份空间，有效期为12个月。
    * [S3](https://aws.amazon.com/s3/) - 每月5GB的标准对象存储空间，每月可发送2K次Get请求和2K次Put请求，有效期为12个月。
    * [Glacier](https://aws.amazon.com/glacier/) - 每月10GB的长期对象存储空间。
    * [Lambda](https://aws.amazon.com/lambda/) - 每月可发送100万次请求。
    * [SNS](https://aws.amazon.com/sns/) - 每月可发送100万条消息。
    * [SES](https://aws.amazon.com/ses/) - 每月可发送3,000条消息，有效期为12个月。    * [SQS](https://aws.amazon.com/sqs/) - 已处理100万次消息队列请求
    * 完整详细列表 - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [虚拟机](https://azure.microsoft.com/services/virtual-machines/) - 1台B1S Linux虚拟机，1台B1S Windows虚拟机（使用12个月）
    * [应用服务](https://azure.microsoft.com/services/app-service/) - 10个Web、移动或API应用（每天使用60 CPU分钟）
    * [函数](https://azure.microsoft.com/services/functions/) - 每月处理100万次请求
    * [开发测试实验室](https://azure.microsoft.com/services/devtest-lab/) - 提供快速、简单且高效的开发测试环境
    * [活动目录](https://azure.microsoft.com/services/active-directory/) - 500,000个对象
    * [活动目录B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 每月存储50,000个用户    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5名活跃用户，无限量的私有Git仓库
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — 10个免费并行任务，适用于Linux、macOS和Windows系统的开源项目，且任务持续时间无限制
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 每天可处理8,000条消息
    * [负载均衡器](https://azure.microsoft.com/services/load-balancer/) - 提供1个免费的公共负载均衡IP地址
    * [通知中心](https://azure.microsoft.com/services/notification-hubs/) - 可发送100万条推送通知
    * [带宽](https://azure.microsoft.com/pricing/details/bandwidth/) - 每月入站15GB、出站5GB的带宽
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 提供25GB的存储空间和1000个处理单元的处理能力    * [静态 Web 应用](https://azure.microsoft.com/pricing/details/app-service/static/) — 使用免费的 SSL、身份验证/授权功能以及自定义域名，构建、部署和托管静态应用和无服务器函数
    * [存储服务](https://azure.microsoft.com/services/storage/) - 5GB 的 LRS 文件或 Blob 存储（12个月期限）
    * [认知服务](https://azure.microsoft.com/services/cognitive-services/) - 包括计算机视觉、翻译、面部检测、机器人等功能的 AI/ML 应用程序接口，提供免费试用，但支持有限量的操作
    * [认知搜索](https://azure.microsoft.com/services/search/#features) - 基于 AI的搜索和索引服务，适用于 10,000 份文档，免费使用
    * [Azure Kubernetes 服务](https://azure.microsoft.com/services/kubernetes-service/) - 托管的可观察云服务，提供免费的集群管理
    * [事件网格](https://azure.microsoft.com/services/event-grid/) - 每月可处理 100,000 个事件
    * 完整的详细列表 - https://azure.microsoft.com/free/  *  [Oracle Cloud](https://www.oracle.com/cloud/)
    * 计算服务
       - 2台基于AMD的计算虚拟机，每台配备1/8个OCPU和1GB内存
       - 4台基于Arm的Ampere A1核心服务器，总内存为24GB，可作为一个虚拟机使用，或最多可同时运行4个虚拟机
       - 当这些实例被认定为“空闲”时，系统会自动回收资源（参见文档：https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm#compute__idleinstances）
    * 块存储卷 - 2个卷，总容量为200GB，用于计算服务
    * 对象存储 - 10GB存储空间
    * 负载均衡器 - 1个实例，带宽可达10Mbps
    * 数据库 - 2个数据库，每个数据库存储容量均为20GB
    * 监控服务 - 支持5亿条数据点的采集，以及10亿条数据点的检索
    * 带宽 - 每月可释放10TB的带宽，基于x64架构的虚拟机的最大速度为50Mbps，而基于Arm架构的虚拟机则可以达到500Mbps
    * 公共IP地址 - 虚拟机配备2个IPv4地址，负载均衡器配备1个IPv4地址
    * 通知服务 - 每月提供100万种交付选项，每月发送1000封电子邮件
    * 完整、详细的服务列表 - https://www.oracle.com/cloud/free/  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * Cloudant数据库 - 1GB的数据存储
    * Db2数据库 - 100MB的数据存储
    * API Connect - 每月50,000次API调用
    * 可用性监控 - 每月3百万个数据点
    * 日志分析 - 每天500MB的日志存储
    * 完整、详细的列表 - https://www.ibm.com/cloud/free/

  * [Cloudflare](https://www.cloudflare.com/)
    * [应用服务](https://www.cloudflare.com/plans/) - 为无限数量的域名提供免费的DNS服务、DDoS防护、CDN服务，以及免费的SSL服务、防火墙规则与页面规则、WAF、机器人防御、免费的无限制速率限制服务（每个域名最多1条规则）、分析服务、电子邮件转发服务
    * [零信任与SASE服务](https://www.cloudflare.com/plans/zero-trust-services/) - 最多支持50个用户，24小时的活动日志记录，支持三个网络位置    * [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) - 您可以通过该服务将本地运行的HTTP端口通过隧道暴露到trycloudflare.com上的随机子域名上。使用[Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/do-more-with-tunnels/trycloudflare/)即可，无需创建账户。在[Zero Trust](https://www.cloudflare.com/products/zero-trust/)计划中，该服务还提供更多功能（如TCP隧道、负载均衡、VPN等）。免费计划可用。
    * [Workers](https://developers.cloudflare.com/workers/) - 可在Cloudflare的全球网络中免费部署无服务器代码，每日请求上限为10万次。
    * [Workers KV](https://developers.cloudflare.com/kv/) - 每日可进行10万次读取请求、1000次写入请求、1000次删除请求、1000次列表请求，存储数据上限为1GB。
    * [R2](https://developers.cloudflare.com/r2/) - 每月使用额度为10GB，每月可处理100万笔A类操作，每月可处理1000万笔B类操作。    * [D1](https://developers.cloudflare.com/d1/) – 每天可读取500万行数据，每天可写入10万行数据，存储容量为1GB。
    * [Pages](https://developers.cloudflare.com/pages/) – 在Cloudflare快速且安全的全球网络中开发和部署您的Web应用程序。每月提供500个构建版本，支持100个自定义域名，集成SSL功能，无限数量的预览部署，并通过Cloudflare Workers集成实现全栈功能。
    * [Queues](https://developers.cloudflare.com/queues/) – 每月可处理100万次操作。
    * [TURN](https://developers.cloudflare.com/calls/turn/) – 每月可免费使用1TB的流量。

    * [Zoho](https://www.zoho.com)——最初是一家电子邮件服务提供商，但现在提供一系列服务，其中一些服务有免费计划。具有免费计划的服务列表如下：
        * [电子邮件](https://zoho.com/mail) – 5个用户免费使用。每个用户的存储容量为5GB，附件大小限制为25MB，支持1个域名。    * [Zoho Assist](https://www.zoho.com/assist) — Zoho Assist的永久免费计划包括一个同时使用的远程支持许可证，以及5台无人值守电脑的许可证，这些许可证可无限期使用，适用于专业人员和普通员工。
    * [Sprints](https://zoho.com/sprints) — 5个用户可享受免费服务，每个用户可以创建5个项目，并拥有500MB的存储空间。
    * [Docs](https://zoho.com/docs) — 5个用户可享受免费服务，上传文件的限制为1GB，存储空间为5GB。Zoho Office Suite（Writer、Sheets、Show）也包含在免费服务中。
    * [Projects](https://zoho.com/projects) — 3个用户可以免费创建2个项目，附件大小限制为10MB。同样的计划也适用于[Bugtracker](https://zoho.com/bugtracker)。
    * [Connect](https://zoho.com/connect) — 25个用户可以免费使用团队协作功能，包括三个小组、三个自定义应用、3个协作板、3个手册，以及10种集成功能，同时还拥有频道、事件和论坛功能。
    * [Meeting](https://zoho.com/meeting) — 最多可容纳3名与会者参加会议，同时可邀请10名在线参会者参加网络会议。    * [Vault](https://zoho.com/vault) — 适用于个人的密码管理工具。
    * [Showtime](https://zoho.com/showtime) — 另一种用于远程会议的工具，可支持最多5名参会者。
    * [Notebook](https://zoho.com/notebook) — 一种免费替代Evernote的工具。
    * [Wiki](https://zoho.com/wiki) — 适用于3个用户的免费工具，拥有50MB的存储空间、无限页面数、ZIP格式备份、RSS与Atom Feed功能，以及访问控制和可自定义的CSS样式。
    * [订阅服务](https://zoho.com/subscriptions) — 循环计费管理服务，适用于20个客户/订阅者，且单个用户可免费使用。所有支付事宜均由Zoho负责处理。最后的40个订阅数据会被存储起来。
    * [结账服务](https://zoho.com/checkout) — 产品计费管理服务，支持3页的账单生成，最多可处理50笔付款。    * [Desk](https://zoho.com/desk) — 客户支持管理工具，配备三名客服人员，拥有私有的知识库和电子邮件支持。与[Assist](https://zoho.com/assist)集成，可同时管理一名远程技术员和5台无人值守的电脑。
    * [Cliq](https://zoho.com/cliq) — 团队聊天软件，提供100GB的存储空间，支持无限用户数，每个频道可容纳100名用户，并支持单点登录功能。
    * [Campaigns](https://zoho.com/campaigns) — 电子邮件营销工具。
    * [Forms](https://zoho.com/forms) — 表单创建工具。
    * [Sign](https://zoho.com/sign) — 无纸化签名工具。
    * [Surveys](https://zoho.com/surveys) — 在线调查工具。
    * [Bookings](https://zoho.com/bookings) — 预约安排工具。

**[⬆️ 返回目录顶部](#table-of-contents)**

## 云管理解决方案

  * [Brainboard](https://www.brainboard.co) — 一种协作解决方案，可端到端地可视化构建和管理云基础设施。  * [Cloud 66](https://www.cloud66.com/) - 针对个人项目提供免费服务（包含一台部署服务器、一个静态网站）。Cloud 66能为你提供构建、部署和管理应用程序所需的一切，让你无需担心“服务器相关的问题”，即可在任何云环境中进行应用程序的开发。
  * [deployment.io](https://deployment.io) - Deployment.io帮助开发者自动化在AWS上的部署流程。在我们的免费层，一个开发者（单用户）可以无限次地部署静态网站、Web服务以及环境。免费层内每月可免费执行10次部署操作，并包含预览功能及自动部署功能。
  * [Pulumi](https://www.pulumi.com/) — 一款现代的基础设施即代码平台，允许你使用熟悉的编程语言和工具来构建、部署和管理云基础设施。  * [scalr.com](https://scalr.com/) – Scalr是一款Terraform自动化和协作工具，旨在提升对由Terraform管理的基础设施及配置进行协作和自动化的效率。支持完整的Terraform CLI接口调用，具备OPA集成功能，并拥有分层配置模型。无需单点登录。所有功能均包含在内。每月可免费使用多达50次运行。

**[⬆️ 返回顶部](#目录)

## 源代码仓库

  * [Bitbucket](https://bitbucket.org/) – 为最多5名用户提供无限量的公共和私有Git仓库，并具备CI/CD管道功能。* [Codeberg](https://codeberg.org/) —— 为免费和开源项目提供无限量的公共和私有Git仓库（可支持无限数量的协作者）。由[Forgejo](https://forgejo.org/)提供支持。提供静态网站托管服务，可使用[Codeberg Pages](https://codeberg.page/)。还提供CI/CD托管服务，可通过[Codeberg的CI](https://docs.codeberg.org/ci/)实现。此外，还提供翻译服务，可通过[Codeberg Translate](https://translate.codeberg.org/)实现。该平台还提供包和容器托管服务、项目管理和问题跟踪功能。*

*[framagit.org](https://framagit.org/)— Framagit是基于GitLab软件的Framasoft软件仓库平台，提供CI、静态页面、项目页面和问题跟踪功能。*

*[GitGud](https://gitgud.io)— 提供无限量的私有和公共仓库，永久免费使用。由GitLab & Sapphire提供支持。不提供CI/CD服务。*  * [GitHub](https://github.com/) — 拥有无限数量的公共仓库和私人仓库（可支持无限数量的合作者）。包含持续集成与持续交付、开发环境、静态托管、包和容器托管、项目管理和人工智能辅助工具。
  * [gitlab.com](https://about.gitlab.com/) — 拥有无限数量的公共和私人Git仓库，最多可支持5位合作者。包含持续集成与持续交付、静态托管、容器注册表、项目管理和问题跟踪功能。
  * [heptapod.net](https://foss.heptapod.net/) — Heptapod是GitLab Community Edition的友好分支版本，支持Mercurial协议。
  * [Pagure.io](https://pagure.io) — Pagure.io是一个免费且开源的软件代码协作平台，适用于基于Git协议的FOSS许可项目。  * [pijul.com](https://pijul.com/) - 无限量免费且开源的分布式版本控制系统。其独特之处在于基于完善的补丁理论，这使得该系统易于学习、使用及分发。解决了git/hg/svn/darcs的许多问题。
  * [projectlocker.com](https://projectlocker.com) — 一款免费的私有项目托管服务（支持Git和Subversion），提供50MB的存储空间。
  * [RocketGit](https://rocketgit.com) — 基于Git的仓库托管服务。提供无限量的公共和私有仓库。
  * [savannah.gnu.org](https://savannah.gnu.org/) - 作为免费软件项目的协作软件开发管理系统（适用于GNU项目）。
  * [savannah.nongnu.org](https://savannah.nongnu.org/) - 作为免费软件项目的协作软件开发管理系统（适用于非GNU项目）。

**[⬆️ 返回顶部](#目录)

## API、数据及机器学习  * [Abstract API](https://www.abstractapi.com) — 适用于各种场景的API套件，包括IP地理定位、性别检测或电子邮件验证等功能。
  * [Apify](https://www.apify.com/) — 一款用于网络抓取和自动化的平台，可以为任何网站创建API并提取数据。提供现成的抓取工具、集成代理服务以及定制解决方案。免费计划每月包含5美元的平台积分。
  * [APITemplate.io](https://apitemplate.io) - 通过简单的API或自动化工具（如Zapier和Airtable）自动生成图像和PDF文档。无需使用CSS/HTML。免费计划每月可生成50张图片，并提供3个模板。
  * [APIVerve](https://apiverve.com) - 免费获取超过120种API的即时访问权限，这些API注重质量、一致性和可靠性。免费计划每月最多可使用50个API令牌。（可能已被下架，2025-06-25）  * [Arize AI](https://arize.com/) - 基于机器学习的模型监控工具，可检测数据质量、性能下降等潜在问题。可免费监控最多两个模型。
  * [Beeceptor](https://beeceptor.com) - 一款无需编程、基于云的平台，可用于模拟和调试多种协议的API（REST、SOAP、gRPC和GraphQL）。该平台提供基于规则的即时服务器服务，支持CRUD操作、状态模拟、代理功能以及CORS管理，从而加快集成和测试速度。免费计划包含每天50次请求，并提供一个公共的仪表板/端点，任何人都可以查看提交的请求和响应。
  * [BigDataCloud](https://www.bigdatacloud.com/) - 提供快速、准确且免费的API服务，适用于现代网络应用，如IP地理定位、逆向地理编码、网络洞察、电子邮件和电话验证、客户信息获取等。使用量可无限或每月最多10K到50K次。  * [Browse AI](https://www.browse.ai) — 用于提取和监控网络上的数据。每月免费使用1000次请求。
  * [BrowserCat](https://www.browsercat.com) - 无头浏览器API，适用于自动化、数据抓取、AI代理网络访问、图片/PDF生成等场景。免费计划每月允许进行1000次请求。
  * [Calendarific](https://calendarific.com) - 面向企业级用户的公共假日API服务，涵盖200多个国家。免费计划每月允许进行500次调用。
  * [Canopy](https://www.canopyapi.co/) - 用于获取Amazon.com产品、搜索和分类数据的GraphQL API。免费计划每月允许进行100次调用。
  * [CarAPI.dev](https://carapi.dev) — 全面的汽车数据API，包含VIN解码、被盗车辆检查、车辆估值、检测数据等功能。免费级别每月在所有9个端点上允许进行100次请求。  * [Cloudmersive](https://cloudmersive.com/) — 实用型API平台，可完全访问包含文档转换、病毒扫描等功能的丰富API库。每月使用额度为600次调用，仅适用于北美地区，最大文件大小为2.5MB。
  * [Colaboratory](https://colab.research.google.com) — 基于Web的免费Python笔记本环境，配备Nvidia Tesla K80 GPU。
  * [CometML](https://www.comet.com/site/) — 用于实验跟踪、模型生产管理、模型注册以及完整数据追溯的MLOps平台，涵盖从训练到生产的整个工作流程。适用于个人和学者免费使用。
  * [Commerce Layer](https://commercelayer.io) — 可构建、放置和管理订单的复合式商业API。开发者计划允许每月创建100个订单，并且免费支持多达1,000种商品SKU。
  * [Composio](https://composio.dev/) — 用于AI代理和大型语言模型集成的集成平台。可整合超过200种工具，实现跨代理网络的集成。  * [转换工具](https://conversiontools.io/) - 适用于文档、图片、视频、音频和电子书的在线文件转换工具。提供REST API，支持Node.js、PHP、Python等语言。可处理最大50GB的文件（适用于付费计划）。免费版受文件大小（20MB）和转换次数（每天30次，每月300次）的限制。
  * [国家-州-城市微服务API](https://country-state-city.rebuscando.info/) - 提供包括国家、地区、省份、城市、邮政编码等丰富信息的API和微服务。免费版每天可调用最多100次。
  * [Coupler](https://www.coupler.io/) - 用于应用程序之间数据同步的数据集成工具。可创建实时仪表板和报告，对数据进行转换和操作，并收集数据以供备份。免费版仅限一个用户、一个数据连接、一个数据源和一个数据目标。同时需要手动更新数据。  * [CraftMyPDF](https://craftmypdf.com) – 可通过拖放编辑器及简单的API，从可复用的模板自动生成PDF文档。免费计划每月可生成100份PDF文档，并提供3个模板。
  * [Cube](https://cube.dev/) – 帮助数据工程师和应用程序开发者从现代数据存储中访问数据，将其整理成一致的定义格式，并传递给每个应用程序。使用Cube的最快方式是通过Cube Cloud，该服务的免费级别每天最多可执行1,000次查询。
  * [CurlHub](https://curlhub.io) – 用于检查和调试API调用的代理服务。免费计划每月可执行10,000次请求。
  * [CurrencyScoop](https://currencyscoop.com) – 面向金融科技应用的实时货币数据API。免费计划每月可执行5,000次调用。
  * [CustomJS](https://www.customjs.io) – 提供将HTML转换为PDF，或将PDF转换为PNG/文本，以及进行PDF合并、提取等功能的API。免费级别每月可执行600次调用。  * [Data Fetcher](https://datafetcher.com) - 无需编写代码即可将 Airtable 连接到任何应用程序或 API。提供类似 Postman 的界面，用于在 Airtable 中执行 API 请求。支持与数十种应用程序的集成。免费计划每月可运行 100 次操作。
  * [Data Miner](https://dataminer.io/) - 一款浏览器扩展程序（适用于 Google Chrome 和 MS Edge），用于从网页中提取 CSV 或 Excel 格式的数据。免费计划每月可处理 500 个网页。
  * [Dataimporter.io](https://www.dataimporter.io) - 用于连接、清理和导入数据到 Salesforce 的工具。免费计划每月最多可导入 20,000 条记录。
  * [Datalore](https://datalore.jetbrains.com) - 由 Jetbrains 提供的 Python 笔记工具。提供 10GB 的存储空间，每月可运行 120 小时。
  * [DB Designer](https://www.dbdesigner.net/) - 基于云端的数据库模式设计和建模工具。免费计划包含 2 个数据库模型，每个模型包含 10 个表。  * [DB-IP](https://db-ip.com/api/free) - 免费的IP地理位置API，每天每个IP最多可发起1k次请求。该服务采用CC-BY 4.0许可证协议，使用免费。
  * [DeepAR](https://developer.deepar.ai) — 适用于任何平台的增强现实面部滤镜，只需一个SDK即可实现。免费计划最多支持10个月活跃用户，并支持追踪最多4张面部特征。
  * [Deepnote](https://deepnote.com) - 一款新的数据科学笔记应用。Jupyter界面支持实时协作，运行在云端。免费套餐包括无限的个人项目、无限的基础机器（配备5GB内存和2个CPU核心），以及最多包含3个编辑器的团队使用权限。
  * [DiffJSON](https://diffjson.com) - 一款在线工具，用于比较两个JSON数据结构之间的差异，帮助您快速定位JSON数据中的差异。
  * [Disease.sh](https://disease.sh/) — 一款免费API，提供准确的数据，帮助构建与新冠疫情相关的实用应用程序。  * [Doczilla](https://www.doczilla.app/) — 一种SaaS形式的API，能够直接从HTML/CSS/JS代码中生成截图或PDF文件。免费计划每月可生成250份文档。
  * [Doppio](https://doppio.sh/) — 一种管理型API，使用顶级渲染技术生成并私密存储PDF文件和截图。免费计划每月可生成400份PDF文件和截图。
  * [drawDB](https://drawdb.app/) — 一款免费且开源的在线数据库图编辑工具，无需注册即可使用。
  * [DynamicDocs](https://advicement.io) - 基于LaTeX模板生成包含JSON数据的PDF文档。免费计划每月可调用50次API，并访问模板库。
  * [Earnings Feed](https://earningsfeed.com/api) - 实时获取SEC的证券文件、内部交易信息以及机构持股信息。免费级别每月可请求15次。* [Export SDK](https://exportsdk.com) – 提供PDF生成器API，并配有拖放式模板编辑器。该SDK支持与No-code工具的集成。免费套餐每月可生成250页文档，支持无限用户数量，并提供三种模板。*
* [ExtendsClass](https://extendsclass.com/rest-client-online.html) – 免费的网络式HTTP客户端，用于发送HTTP请求。*
* [Financial Data](https://financialdata.net/) – 提供股市和金融数据API。免费套餐每天可发送300个请求。*
* [FormatJSONOnline.com](https://formatjsononline.com) – 一款免费的浏览器式工具，可即时对JSON数据进行格式化、验证、比较和压缩。*
* [FraudLabs Pro](https://www.fraudlabspro.com) – 用于筛查信用卡支付交易中的欺诈行为。该REST API可根据订单输入参数检测所有可能的欺诈行为。免费微型套餐每月可处理500笔交易。*  * [FreeIPAPI](https://freeipapi.com) - 为商业和非商业用户提供的免费、快速且可靠的IP地理定位API，支持JSON格式。
  * [Geolocated.io](https://geolocated.io) — 具有多大陆地服务器的IP地理定位API，提供免费计划，每天可请求2,000次。
  * [Hex](https://hex.tech/) - 一个用于笔记本、数据应用和知识库协作的数据平台。提供免费社区级别服务，最多支持五个项目。
  * [Hook0](https://www.hook0.com/) - Hook0是一种开源的Web钩子服务，方便在线产品提供Web钩子功能。可免费发送每天最多100个事件，并保留7天的历史记录。
  * [Hoppscotch](https://hoppscotch.io) - 一款免费、快速且美观的API请求构建工具。
  * [huggingface.co](https://huggingface.co) - 用于构建、训练和部署Pytorch、TensorFlow和JAX自然语言处理模型。每月最多可处理30,000个字符的输入。* [Insomnia](https://insomnia.rest) – 开源API客户端，用于设计和测试API，支持REST和GraphQL接口。
* [Invantive Cloud](https://cloud.invantive.com/) – 可通过Invantive SQL或OData4（通常是Power BI或Power Query）访问70多个（云）平台，包括Exact Online、Twinfield、ActiveCampaign或Visma等平台。包含数据复制和交换功能。为开发人员和实施顾问提供免费计划。特定平台提供免费服务，但数据量有限制。
* [ipwho.org提供的IP地理定位API](https://ipwho.org/) – 每天可免费请求2,000次。速度快，企业级API，价格合理。受到开发者、企业、政府和教育客户的信任。服务器位于12个以上地区。
* [IP地理定位API](https://www.abstractapi.com/ip-geolocation-api) – 来自Abstract公司的IP地理定位API，可免费请求1,000次。  * [IP地理定位](https://ipgeolocation.io/) — IP地理定位API，开发者可永久免费使用，但每天请求次数限制为1,000次。
  * [ip-api](https://ip-api.com) — IP地理定位API，非商业用途可免费使用，无需API密钥。免费计划下，同一IP地址的每分钟请求次数限制为45次。
  * [IP.City](https://ip.city) — 每天可免费进行100次IP地理定位请求。
  * [IP2Location.io](https://www.ip2location.io/) — 免费、快速且可靠的IP地理定位API。可获取城市、坐标、ISP、ASN等数据。免费计划每月包含50,000个信用点。IP2Location.io还每月提供500次免费的WHOIS查询和托管域名查询服务。可查看域名注册详情，并查找特定IP地址上托管的域名。如需更多功能，可升级至付费计划。
  * [ipaddress.sh](https://ipaddress.sh) — 提供简单服务，可获取不同格式的公共IP地址。* [ipapi.is](https://ipapi.is/) - 由开发者为开发者提供的可靠IP地址API，具有最佳的地理位置检测能力。免费计划可支持1000次查询，无需注册。
* [ipapi.co/](https://ipapi.co/) - 由Kloudend, Inc提供的IP地址位置API，基于AWS构建的可靠地理定位服务，受到《财富》500强企业的信任。免费计划每月可支持30k次查询（每天1k次），无需注册。
* [ipbase.com](https://ipbase.com) - IP地理定位API - 永久免费计划，每月可请求150次。
* [IPinfo](https://ipinfo.io/) - 快速、准确且免费的IP地址数据API，每月最多可请求50k次。提供包含地理定位、公司信息、运营商、IP范围、域名、滥用联系等信息在内的API。所有付费API均可免费试用。  * [IPLocate](https://www.iplocate.io) —  IP地理定位API，每天最多可请求1,000次。包含代理/VPN检测、ASN数据、IP与公司之间的映射等功能。IPLocate还提供免费下载的IP到国家以及IP到ASN的数据库，格式为CSV或GeoIP兼容的MMDB格式。
  * [IPTrace](https://iptrace.io) — 一个非常简单的API，为您的业务提供可靠且有用的IP地理定位数据，每月可免费查询50,000次。
  * [JSON IP](https://getjsonip.com) — 返回被请求的客户的公共IP地址。免费级别无需注册。通过CORS技术，数据可以直接通过客户端JavaScript从浏览器中请求。适用于监控客户端和服务器IP地址变化的服务。请求数量无限制。
  * [JSON转表格](https://jsontotable.org) — 将JSON格式的数据转换为可在线查看、编辑和分享的互动表格。  * [JSON2Video](https://json2video.com) - 一款视频编辑API，可用于自动化视频营销和社交媒体视频的制作，支持编程操作或无需编码即可使用。
  * [JSONGrid](https://jsongrid.com) - 一款免费工具，可将复杂的JSON数据可视化、编辑、过滤，并呈现为美观的表格格式。可保存和通过链接分享JSON数据。
  * [JSONing](https://jsoning.com/api/) — 从JSON对象中创建虚拟的REST API，并可自定义HTTP状态码、头部信息以及响应体内容。
  * [JSONSwiss](https://www.jsonswiss.com/) - JSONSwiss是一款强大的在线JSON查看器、编辑器和验证工具。支持格式化、可视化、搜索和操作JSON数据，具备AI驱动的修复功能，支持树状视图、表格视图，并可生成代码。此外，还支持将JSON转换为CSV、XML、YAML等格式。  * [KillBait API](https://killbait.com/api/doc) - KillBait API允许用户提交URL进行内容评估，检测潜在的诱骗性内容，并对文章进行分类。该API适用于中等频率的发布，每小时最多可提交1个URL，每天最多可提交10个URL。媒体合作伙伴可以请求更高的限制。
  * [Kreya](https://kreya.app) — 免费的gRPC GUI客户端，用于调用和测试gRPC API。可以通过服务器反射功能导入gRPC API。
  * [LoginLlama](https://loginllama.app) - 一款登录安全API，能够检测欺诈性登录行为，并通知客户。每月免费提供1000次登录尝试。
  * [市场数据API](https://www.marketdata.app) - 提供实时和历史的金融数据，涵盖股票、期权、共同基金等。Free Forever API级别允许免费进行100次每日API请求。  * [Maxim AI](https://getmaxim.ai/) – 用于模拟、评估并观察您的AI代理。Maxim是一个端到端的评估与观测平台，帮助团队更可靠地部署AI代理，并将部署速度提高5倍以上。对于独立开发者和小团队来说，可以永久免费使用（3个用户席位）。
  * [microlink.io](https://microlink.io/) – 可将任何网站转换为数据，例如元标签标准化、美观的链接预览、数据抓取功能或截图服务。每天可免费请求50次。
  * [Mintlify](https://mintlify.com) – 现代标准的API文档工具。拥有美观且易于维护的用户界面组件、应用内搜索以及互动式练习区。单个编辑者可以免费使用。
  * [MockAPI](https://www.mockapi.io/) – MockAPI是一个简单的工具，可让您快速模拟API、生成自定义数据，并使用RESTful接口执行操作。MockAPI旨在作为原型设计、测试或学习的工具。每个项目可免费使用1个项目/2个资源。  * [Mockerito](https://mockerito.com/) — 免费的模拟REST API服务，提供涵盖9个领域的真实数据（电子商务、金融、医疗健康、教育、招聘、社交媒体、股市、天气和航空）。无需注册，无需API密钥，请求数量无限制。非常适合前端原型设计、API测试以及Web开发的学习和教学。
  * [Mockfly](https://www.mockfly.dev/) — Mockfly是一款可靠的API模拟和特性标志管理工具。通过直观的界面快速生成并控制模拟API。免费套餐每天可发送500个请求。
  * [Mocko.dev](https://mocko.dev/) — 免费提供API代理服务，可在云端选择要模拟的端点，并监控流量。可加快开发速度和集成测试的效率。  * [Multi-Exit IP地址检查器](https://ip.alstra.ca/) — 一款免费且简单的工具，可用于检查您在多个节点的出口IP地址，并了解您的IP地址在不同全球区域和服务中的表现。适用于测试基于规则的DNS分割工具，如Control D。
  * [新闻API](https://newsapi.org) — 通过代码搜索网络上的新闻，并获取JSON格式的结果。开发者每天可免费进行100次查询。新闻文章的查询有24小时的延迟。
  * [numlookupapi.com](https://numlookupapi.com) - 免费电话号码验证API - 每月可免费进行100次查询。
  * [OCR.Space](https://ocr.space/) — 一种OCR API，可以解析图像和PDF文件，并将文本结果以JSON格式返回。每月免费进行25,000次查询，文件大小限制为1MB。
  * [OpenAPI3设计师](https://openapidesigner.com/) — 可免费创建Open API 3的定义。
  * [Parseur](https://parseur.com) — 每月免费进行20次查询：从PDF文件和电子邮件中提取数据。采用人工智能技术。提供完整的API访问权限。  * [PDF-API.io](https://pdf-api.io) -  PDF自动化API，提供可视化模板编辑器、HTML转PDF功能、动态数据集成以及基于API的PDF渲染功能。免费计划每月提供一个模板，可处理100份PDF文件。
  * [PDFBolt](https://pdfbolt.com) - 专为开发者设计的PDF生成API，注重隐私保护。提供类似Stripe的文档格式，每月可免费进行500次PDF转换。
  * [pdfEndpoint.com](https://pdfendpoint.com) - 通过简单的API轻松将HTML或URL转换为PDF。免费每月可处理100次转换。
  * [Pixela](https://pixe.la/) - 免费的一天流式数据库服务。所有操作通过API完成。还支持使用热力图与折线图进行可视化展示。
  * [Postman](https://postman.com) — 通过Postman简化工作流程，并加快API开发速度。Postman是一款用于API开发的协作平台。可永久免费使用Postman应用程序。Postman的云功能也在一定限制下可永久免费使用。  * [PrefectCloud](https://www.prefect.io/cloud/) — 一个全面的数据流自动化平台。免费计划包含5个已部署的工作流，以及每月500分钟的无服务器计算额度。
  * [Preset Cloud](https://preset.io/) - 一款托管式的Apache Superset服务。最多5个用户的团队可以永久免费使用，支持无限量的仪表盘和图表，拥有无需编程即可创建图表的功能，以及协作式SQL编辑器。
  * [ProxySentry](https://proxysentry.io/) - 一款用于检测住宅代理和VPN的IP API。ProxySentry在rapidapi.com上提供免费层，每月可发送10k次请求。
  * [Reducto](https://reducto.ai) - 可将任何非结构化文档（PDF、XLSX、JPG、PPTX等）转换为结构化的JSON数据。可以解析、提取数据，并编辑PDF表单。免费层包含15k免费额度，之后需付费使用。
  * [Rendi](https://rendi.dev) - FFmpeg API - 一个用于FFmpeg的REST API，无需处理基础设施即可在线运行FFmpeg。免费层包含每月的处理配额，以及4个vCPU资源。  * [RequestBin.com](https://requestbin.com) — 创建一个免费的服务端点，您可以在该端点上发送HTTP请求。发送到该端点的所有HTTP请求都会附带相关的负载和头部信息，这样您就可以观察来自Web钩子和其他服务的建议。
  * [ROBOHASH](https://robohash.org/) - 一款Web服务，可以根据任何文本生成独特且有趣的图片。
  * [Scraper's Proxy](https://scrapersproxy.com) — 一款简单的HTTP代理API，用于进行数据抓取。您可以匿名进行数据抓取，无需担心受到限制、封锁或验证码的阻碍。每月前100次成功的抓取操作是免费的，包括JavaScript渲染功能（如果您联系支持部门，还可以获得更多功能）。
  * [ScrapingAnt](https://scrapingant.com/) — 一款无界面的Chrome数据抓取API，并提供免费的代理服务。支持JavaScript渲染，拥有高级的轮换代理服务，能够避免验证码的干扰。提供免费的10,000个API积分。  * [SerpApi](https://serpapi.com/) - 实时搜索引擎抓取API。可为Google、YouTube、Bing、Baidu、Walmart等许多平台提供结构化JSON结果。免费计划每月可调用100次API。
  * [Sheetson](https://sheetson.com) - 可将任何Google Sheets表格转换为RESTful API接口。提供免费计划，每张表格可免费调用1,000行数据。
  * [Simplescraper](https://simplescraper.io) - 每次操作完成后会触发您的Web钩子。免费计划包含100个云端抓取积分。
  * [Siterelic](https://siterelic.com/) - Siterelic API支持截图、网站审计、TLS扫描、DNS查询、TTF测试等功能。免费计划每月可调用100次API。
  * [SmartParse](https://smartparse.io) - SmartParse是一个数据迁移和CSV转API的平台，提供节省时间和成本的开发工具。免费计划每月包含300个处理单元、浏览器上传功能、数据隔离、电路断路器以及作业提醒功能。  * [Sofodata](https://www.sofodata.com/) - 从CSV文件创建安全的RESTful API。上传CSV文件后，可通过其API立即访问数据，从而加快应用程序的开发速度。免费计划包含2个API，每月可调用2,500次API。无需信用卡即可使用。
  * [Sqlable](https://sqlable.com/) - 一系列免费的在线SQL工具，包括SQL格式化和验证工具、SQL正则表达式测试工具、虚拟数据生成器以及互动的数据库游戏区。
  * [Supportivekoala](https://supportivekoala.com/) - 可通过模板根据输入自动生成图片。免费计划每月可生成最多50张图片。
  * [Svix](https://www.svix.com/) - 提供Web钩子服务。每月可免费发送多达50,000条消息。
  * [Tavily AI](https://tavily.com/) - 提供在线搜索、快速洞察以及全面的研究功能，同时具备研究结果组织的能力。免费计划每月可请求1000次，无需信用卡即可使用。  * [The IP API](https://theipapi.com/) - 基于 IP 的地理定位 API，每天可免费调用 1000 次。提供有关 IP 地址位置的信息，包括国家、城市、地区等。
  * [TinyMCE](https://www.tiny.cloud) - 富文本编辑 API。核心功能可免费无限使用。
  * [Tomorrow.io 天气 API](https://www.tomorrow.io/weather-api/) - 提供免费的天气 API 服务。提供准确且最新的天气预报，涵盖全球范围，同时提供历史数据和天气监测功能。
  * [Treblle](https://www.treblle.com) - Treblle 帮助团队构建、发布和管理 API。具备先进的 API 日志聚合、可观测性、文档编写和调试功能。免费版可免费使用所有功能，但每月免费版的使用次数上限为 25 万次。
  * [UniRateAPI](https://unirateapi.com) - 实时提供 590 多种货币和加密货币的最新汇率。免费版可无限次调用 API，非常适合开发人员和金融应用。  * [vatcheckapi.com](https://vatcheckapi.com) - 简单且免费的增值税号码验证API。每月可免费进行150次验证。
  * [WeatherXu](https://weatherxu.com/) — 全球天气数据服务，包括当前天气状况、每小时及每日天气预报，以及通过我们的API获取天气警报。集成AI模型和机器学习系统，分析和结合多种天气模型，以提高天气预报的准确性。免费套餐每月可调用2万次API。
  * [WebScraping.AI](https://webscraping.ai) - 简单的网页抓取API，内置解析功能、Chrome渲染以及代理设置。每月可免费调用2000次API。
  * [Weights & Biases](https://wandb.ai) — 以开发者为中心的机器学习运维平台。通过实验跟踪、数据集版本管理以及模型管理功能，更快构建更优秀的模型。仅适用于个人项目，免费套餐包含100GB的存储空间。
  * [What The Diff](https://whatthediff.ai) - 由AI驱动的代码审查助手。免费计划每月最多可使用25,000个代币（约10次代码审查）。  * [wolfram.com](https://wolfram.com/language/) — 云端的基于知识算法的工具。
  * [wrapapi.com](https://wrapapi.com/) — 可将任何网站转换为参数化的API。每月可调用3万次API。
  * [Zenscrape](https://zenscrape.com/web-scraping-api) — 带有无头浏览器、固定IP地址以及简单定价模式的网络抓取API。每月可免费调用1000次API，同时为学生和非营利组织提供额外折扣。
  * [Zipcodebase](https://zipcodebase.com) — 免费的邮政编码API，可访问全球邮政编码数据。每月可免费请求5000次。
  * [Zipcodestack](https://zipcodestack.com) — 免费的邮政编码API及邮政编码验证服务。每月可免费请求1万次。* [Zuplo](https://zuplo.com/) – 一款免费的开源API管理平台，用于设计、构建和部署API。只需几分钟即可为任何API添加API密钥认证、速率限制、开发者文档以及 monetization 功能。该平台采用OpenAPI原生架构，完全可编程，并支持Web标准API和TypeScript。免费计划支持最多10个项目，无限数量的边缘环境，每月支持1百万次请求，以及10GB的出口流量。

**[⬆️ 返回顶部](#目录)**

## 工件仓库

* [Gemfury](https://gemfury.com) – 为Maven、PyPi、NPM、Go Module、Nuget、APT和RPM仓库提供私有和公共工件仓库。公共项目可免费使用。
* [jitpack.io](https://jitpack.io/) – 为GitHub上的JVM和Android项目提供Maven仓库，公共项目可免费使用。
* [paperspace](https://www.paperspace.com/) – 用于构建和扩展AI模型，开发、训练并部署AI应用程序。免费计划适用于公共项目，支持5GB的存储空间和基础实例。  * [RepoFlow](https://repoflow.io) - RepoFlow通过支持npm、PyPI、Docker、Go、Helm等工具，简化了包管理流程。可免费试用，包含10GB存储、10GB带宽、100个包以及无限用户数，支持在云端使用，或用于个人自托管环境。
  * [RepoForge](https://repoforge.io) - 基于私有云技术的Python、Debian、NPM包和Docker注册表存储库。为开源/公共项目提供免费计划。
  * [repsy.io](https://repsy.io) — 1GB免费私有/公共Maven存储库。

**[⬆️ 返回顶部](#目录)

## 团队协作工具

  * [3Cols](https://3cols.com/) - 一款免费的基于云的代码片段管理工具，适用于个人和团队协作。
  * [BookmarkOS.com](https://bookmarkos.com) - 提供免费的桌面管理工具，包括书签管理、标签管理和任务管理功能，支持文件夹协作，且界面可自定义。  * [Braid](https://www.braidchat.com/) — 一款专为团队设计的聊天应用。适用于公开访问的群组，免费使用，用户数量无限制，历史记录与集成功能也相当丰富。此外，该应用还提供可自主托管的开源版本。
  * [Calendly](https://calendly.com) — 用于连接和安排会议的工具。免费版支持每个用户最多连接1个日历应用，会议次数也无限制。同时提供桌面版和移动版应用。
  * [cally.com](https://cally.com/) — 可轻松找到适合会议的日期和时间。使用简单，适用于小型到大型团队。
  * [Chanty.com](https://chanty.com/) — Chanty是Slack的另一种替代方案。适用于小型团队（最多10人）的免费版，支持无限量的公开和私聊对话、历史记录查询、无限量的一对一音频通话、无限量的语音消息、十种集成功能，以及每团队20GB的存储空间。  * [DevToolLab](https://devtoollab.com) — 在线开发者工具平台，提供所有基础工具的免费访问权限，能够自动保存每个工具的一个记录，具有标准的处理速度，并拥有社区支持。
  * [Discord](https://discord.com/) — 可在公共或私有房间中进行聊天。支持 Markdown格式的文本编辑、语音、视频以及屏幕共享功能。免费服务，适用于无限数量的用户。
  * [Dubble](https://dubble.so/) — 提供免费的逐步指南生成工具。可以截图、记录流程，并与团队协作。还支持异步屏幕录制功能。
  * [Duckly](https://duckly.com/) — 允许与团队实时进行交流和协作。支持与集成开发环境、终端共享、语音、视频以及屏幕共享功能。适用于小型团队，免费使用。
  * [element.io](https://element.io/) — 基于Matrix技术的去中心化、开源的通信工具。支持群组聊天、直接消息传递、加密文件传输、语音和视频聊天，并且能够轻松与其他服务集成。* [evernote.com](https://evernote.com/) — 用于整理信息的工具。可以分享你的笔记，并与其他人合作。
* [Fibery](https://fibery.io/) — 连接式工作空间平台。单个用户免费使用，最多可拥有2GB的磁盘空间。
* [Fibo](https://fibo.dev) — 适用于敏捷团队的免费在线实时Scrum Poker工具，允许无限数量的成员估算故事点，从而加快规划过程。
* [Fizzy](https://www.fizzy.do/) — 基于看板的项目管理和问题跟踪平台。可以创建公共看板、设置Web钩子、使用卡片标记，并跟踪无限数量的用户——最多可处理1000个项目，免费使用。
* [flat.social](https://flat.social) — 可交互式定制化的团队会议和欢乐时光社交平台。无限数量的会议，最多可同时支持8个用户，免费使用。
* [flock.com](https://flock.com) — 让团队沟通更加便捷的工具。免费提供无限的消息、频道、用户、应用程序以及集成功能。  * [GitBook](https://www.gitbook.com/) — 用于记录和整理技术知识的平台，涵盖从产品文档到内部知识库和API的各个方面。提供免费计划，适合个人开发者使用。
  * [GitDailies](https://gitdailies.com) — 每日报告团队在GitHub上的提交和拉取请求活动情况。包含推送可视化工具、同行识别系统以及自定义警报构建工具。免费计划支持无限用户数、三个仓库以及3种警报配置。
  * [gitter.im](https://gitter.im/) — 专为GitHub设计的聊天工具。提供无限数量的公共和私有房间，对于最多25人的团队来说是完全免费的。
  * [gokanban.io](https://gokanban.io) — 基于语法规则的Kanban板工具，无需注册即可快速使用。免费使用，没有任何限制。* [Hackmd.io](https://hackmd.io/) – 支持实时协作和编写 Markdown 格式文档/文件的工具。类似于 Google Docs，但专为 Markdown 文件设计。免费提供无限数量的“笔记”，但私有笔记和模板的协作人数有限制。
* [HeySpace](https://hey.space) – 具备聊天、日历、时间轴和视频通话功能的任务管理工具。最多支持 5 个用户免费使用。
* [Huly](https://huly.io/) – 一站式项目管理平台（可替代 Linear、Jira、Slack、Notion、Motion）——支持无限用户数量，每个工作区拥有 10GB 的存储空间，以及 10GB 的视频/音频流量。
* [Keybase](https://keybase.io/) – 一款开源的 Slack 替代品，可保护家庭成员、社区以及公司内部的聊天记录和文件安全。
* [Linkinize](https://linkinize.com) – 适用于团队的书签管理工具，支持标签、多工作区以及协作功能。免费计划包含 4 个工作区和 10 个团队成员。  * [Lockitbot](https://www.lockitbot.com/) — 可在Slack中管理和锁定共享资源，如房间、开发环境、服务器等。最多可管理2个资源，免费使用。
  * [meet.jit.si](https://meet.jit.si/) — 一键式视频通话和屏幕共享功能，免费使用。
  * [Miro](https://miro.com/) — 适用于分布式团队的可扩展、安全、跨设备且适合企业使用的协作白板工具。提供免费增值计划。
  * [Notion](https://www.notion.so/) — 一款支持Markdown的笔记和协作应用，可集成任务、维基和数据库功能。该公司将这款应用描述为用于笔记记录、项目管理和任务管理的全能工作空间。除了跨平台应用外，还可以通过大多数网络浏览器访问。
  * [Nuclino](https://www.nuclino.com) — 一款轻量级且易于协作的维基工具，用于存储团队的知识、文档和笔记。免费计划包含所有基本功能，最多可存储50个条目，并拥有5GB的存储空间。  * [OnlineInterview.io](https://onlineinterview.io/) - 免费的代码面试平台，包含嵌入式视频聊天、绘图板和在线代码编辑器，用户可以在浏览器中编译和运行代码。只需点击一下即可创建远程面试房间。
  * [paste.sh](https://paste.sh/) — 这是一个基于JavaScript和Crypto技术的简单文件粘贴工具。
  * [Pastefy](https://pastefy.app/) - 美观且简单的Pastebin工具，支持可选的客户端加密、多标签粘贴、API接口、高亮显示编辑器等功能。
  * [Pendulums](https://pendulums.io/) - Pendulums是一款免费的时间管理工具，通过易于使用的界面和有价值的统计数据，帮助用户更好地管理时间。
  * [Proton Pass](https://proton.me/pass) — 密码管理器，内置电子邮件别名、两步验证认证器、密钥共享功能。支持网页、浏览器扩展、移动应用和桌面版本。  * [Pullflow](https://pullflow.com) — Pullflow 提供了一个基于人工智能的协作平台，可用于在 GitHub、Slack 和 VS Code 之间进行代码审查。
  * [Pumble](https://pumble.com) - 免费团队聊天应用。拥有无限的用户数量和消息记录，永久免费使用。
  * [Quidlo Timesheets](https://www.quidlo.com/timesheets) - 一款简单的团队时间记录和跟踪应用。免费计划包含时间跟踪功能，并支持最多 10 名用户生成报告。
  * [Raindrop.io](https://raindrop.io) - 一款适用于 macOS、Windows、Android、iOS 和网页的私密且安全的书签应用。免费提供无限数量的书签和协作功能。  * [Revolt.chat](https://revolt.chat/) — 一款开源替代方案，用于替代[Discord](https://discord.com/)。该平台尊重用户的隐私，同时免费提供了Discord的大部分专有功能。Revolt.chat是一款既安全又快速的全方位应用程序，且完全免费。所有功能都是免费的。与大多数主流聊天应用不同，该平台还支持官方及非官方的插件。
  * [Rocket.Chat](https://rocket.chat/) — 一款开源通信平台，具备全通道功能、矩阵式联邦架构、与其他应用程序的连接功能、无限消息发送以及完整的消息历史记录。
  * [ruttl.com](https://ruttl.com/) — 一款最佳的全方位反馈工具，可用于收集数字反馈，并用于审查网站、PDF文件以及图片。
  * [浏览器屏幕共享](https://screensharing.net) — 一款免费屏幕共享工具，用户可以直接通过浏览器与协作者共享屏幕，无需下载或注册。* seafile.com — 私有或云存储服务，文件共享、同步、讨论功能。云版本仅提供1GB存储空间。
* SiteDots.com — 可直接在网站项目上分享反馈，无需使用模拟工具、画布或变通方法。完全免费的实用功能层。
* Slab.com — 适用于团队的现代知识管理服务。最多支持10名用户免费使用。
* slack.com — 无限用户数，但部分功能有限制。
* StatusPile.com — 状态页面的集合。可以追踪您上游供应商的状态页面吗？
* Stickies.App.com — 用于头脑风暴、内容策划和笔记的视觉协作应用。最多支持3个“墙”，无限用户数，1GB存储空间。  * [StreamBackdrops](https://streambackdrops.com) — 提供适用于视频通话和团队会议的免费高清虚拟背景。适用于Zoom、Teams和Google Meet的专业背景。无需注册，可免费用于个人用途。
  * [talky.io](https://talky.io/) — 免费群组视频聊天工具。匿名模式，采用点对点连接方式，无需插件、注册或付费。
  * [Teamcamp](https://www.teamcamp.app) - 适用于软件开发公司的全能项目管理应用。
  * [Teamhood](https://teamhood.com/) - 免费的项目、任务和问题跟踪软件。支持Kanban模式以及完整的Scrum实施流程。具备时间跟踪功能。适用于最多5个用户的小型团队，免费使用。
  * [Teamplify](https://teamplify.com) - 通过Team Analytics和Smart Daily Standup功能提升团队开发流程。为以远程办公为主的团队提供完整的时间管理功能。适用于最多5个用户的小型团队，免费使用。  * [Telegram](https://telegram.org/) — Telegram适用于那些追求快速、可靠的消息传递和通话功能的人。商业用户和小团队可能会喜欢其支持大组通话、用户名功能、桌面应用程序以及强大的文件共享功能。
  * [Tencent RTC](https://trtc.io/) — Tencent实时通信服务为群组音频/视频通话提供了解决方案。首年每月可享受10,000分钟的免费通话时间。
  * [TimeCamp](https://www.timecamp.com/) — 适用于无限用户的免费时间跟踪软件。易于与Jira、Trello、Asana等项目管理工具集成。
  * [tldraw.com](https://tldraw.com) — 免费的开源白板工具和图表制作工具，具备智能箭头、对齐功能、便签功能以及SVG导出功能。支持多人协作编辑。还提供免费的官方VS Code扩展程序。  * [transfernow](https://www.transfernow.net/) — 最简洁、最快且最安全的文件传输和共享工具。无需订阅即可发送照片、视频及其他大文件。
  * [Tugboat](https://tugboat.qa) — 可预览每个拉取请求的功能，支持自动化和按需预览。对所有用户免费；非营利组织可免费使用Nano级别的功能。符合条件的团队可享受折扣。
  * [twist.com](https://twist.com) — 适合异步沟通的团队沟通工具，确保对话保持条理且紧扣主题。提供免费和无限使用的计划。符合条件的团队可享受折扣。
  * [userforge.com](https://userforge.com/) — 在线连接用户角色、用户故事和上下文映射工具。帮助保持设计和开发的同步，最多支持3个角色和2名协作者。
  * [Visual Debug](https://visualdebug.com) — 用于改善客户与开发之间沟通的可视化反馈工具。
  * [Webex](https://www.webex.com/) — 视频会议工具，免费计划支持每次会议40分钟，最多可容纳100名参与者。  * [Webvizio](https://webvizio.com) — 网站反馈工具、网站审核软件以及漏洞报告工具，可简化在实时网站、网页应用、图片、PDF文件及设计文件上的开发协作。
  * [whereby.com](https://whereby.com/) — 一键视频通话服务，免费提供（之前名为appear.in）。
  * [windmill.dev](https://windmill.dev/) — 开源开发者平台，可通过极少的Python和TypeScript脚本快速构建生产级的多步骤自动化程序和内部应用。作为免费用户，您可以创建最多三个非高级的工作空间。
  * [wistia.com](https://wistia.com/) — 视频托管服务，包含观众分析、高清视频传输以及营销工具，帮助了解您的访客信息。提供25种视频格式，并拥有Wistia品牌播放器。
  * [wormhol.org](https://www.wormhol.org/) — 简单的文件共享服务。可无限共享最大5GB的文件，并可与任意数量的同伴共享文件。  * [Wormhole](https://wormhole.app/) - 通过端到端加密技术，可共享最大5GB的文件，有效期长达24小时。对于超过5GB的文件，则采用点对点传输方式直接发送。
  * [zoom.us](https://zoom.us/) — 提供安全的视频和网络会议功能。免费套餐的会议时长有限，仅为40分钟。
  * [Zulip](https://zulip.com/) — 支持实时聊天功能，采用类似电子邮件的线程式模型。免费套餐包含10,000条消息存储空间和最大5GB的文件存储。此外，该平台还提供可自主托管的开源版本。

**[⬆️ 返回顶部](#目录)

## 内容管理系统

  * [Contentful](https://www.contentful.com/) — 无框架内容管理系统。提供云端的内容管理和交付API。免费套餐包含5个用户、25K条记录、48种内容类型以及2种本地化选项。
  * [Cosmic](https://www.cosmicjs.com/) — 无框架内容管理系统及API工具包。为开发者提供免费个人套餐。* [Crystallize](https://crystallize.com) — 一款无头化的内容管理系统，支持电子商务功能，并具备内置的GraphQL接口。免费版本包含无限用户数、1000个目录项、每月5GB的带宽，以及每月25,000次API调用权限。
* [DatoCMS](https://www.datocms.com/) — 为小型项目提供免费服务。DatoCMS是一款基于GraphQL的内容管理系统。较低级别的服务方案中，每月可调用10万次API。
* [Hygraph](https://hygraph.com/) — 为小型项目提供免费服务。采用GraphQL接口的API。推荐用户从传统的解决方案转向使用GraphQL原生无头化内容管理系统，并优先提供全渠道内容管理API。
* [Prismic](https://www.prismic.io/) — 一款无头化内容管理系统。具有完全托管且可扩展的API接口。社区计划提供无限API调用权限、文档、自定义类型、资源以及一个用户使用的本地化设置。这些功能都是您下一个项目所需的一切。对于开放内容或开源项目，还有更免费的套餐可供选择。  * [Sanity.io](https://www.sanity.io/) - 提供结构化内容的平台，拥有开源编辑环境和实时托管的数据存储。支持无限个项目数量、无限的管理员用户数量、三个非管理员用户、两个数据集、50万次API调用、10GB带宽，以及每个项目免费提供的5GB资产。
  * [Solo](https://soloist.ai) - 由Mozilla提供的免费AI网站创建工具，只需简单的输入即可为您的业务创建美观的网站。提供免费自定义域名，无需信用卡即可使用。
  * [Squidex](https://squidex.io/) - 为小型项目提供免费服务。支持API和GraphQL接口。采用开源技术，基于事件源机制，自动处理每次变更。  * [Storyblok](https://www.storyblok.com) - 一款适用于开发者和营销人员的无头内容管理系统，可与所有现代框架兼容。社区版（免费）包含管理API、可视化编辑器、十个数据源、自定义字段类型、国际化功能（无限语言/区域设置）、资产管理器（最多支持2500个资产）、图片优化服务、搜索查询功能以及每月250GB的流量。
  * [TinaCMS](https://tina.io/) — 取代Forestry.io的开源Git支持无头内容管理系统，支持Markdown、MDX和JSON格式。基础版是免费的，支持两个用户同时使用。
  * [WPJack](https://wpjack.com) - 在5分钟内即可在任何云平台上搭建WordPress网站！免费版包含1台服务器、2个网站、免费SSL证书以及无限数量的定时任务。没有时间限制或有效期问题——完全按照您自己的方式来管理网站。

**[⬆️ 返回顶部](#目录)

## 代码生成* [Appinvento](https://appinvento.io/)——一款免费的无代码应用构建工具。用户可以完全访问自动生成的后端源代码，并可以创建无限数量的API和路由。免费计划包含三个项目和五个表格。
* [DhiWise](https://www.dhiwise.com/)——将Figma设计转化为动态的Flutter和React应用程序。其代码生成技术旨在优化工作流程，以构建可生产使用的移动端和网页应用。
* [Karbon Sites](https://www.karbonsites.space)——一款由人工智能驱动的网站构建和编辑器，能够根据文本提示、草图或简历生成可生产使用的前端代码。该工具支持原生Android（APK）导出功能，并提供免费版，每月可生成5次代码（通过自定义Gemini API密钥可实现无限次生成）。* [Metalama](https://www.postsharp.net/metalama)——一款专门针对C#的语言工具，能够在编译过程中即时生成样板代码，从而保持源代码的整洁性。该工具适用于开源项目，其商业友好的免费版本可支持最多三个方面的功能。
* [Supermaven](https://www.supermaven.com/)——一款针对VS Code、JetBrains和Neovim的高性能AI代码补全插件。其免费版本提供无限的内联补全功能，且注重超低延迟。
* [v0.dev](https://v0.dev/)——由Vercel开发，该平台能够生成易于复制粘贴的React代码，使用shadcn/ui和Tailwind CSS进行设计。它采用信用制度，提供1,200个初始信用点，以及每月200个免费信用点。

**[⬆️ 返回目录](#目录内容)**

## 代码质量

* [beanstalkapp.com](https://beanstalkapp.com/)——提供完整的代码编写、审核和部署流程。该平台为单个用户提供免费账户，并支持一个存储容量为100MB的仓库。  * [codacy.com](https://www.codacy.com/) — 为PHP、Python、Ruby、Java、JavaScript、Scala、CSS以及CoffeeScript提供自动化代码审查服务，适用于无限数量的公共和私有代码库，完全免费。
  * [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev) — 一款自动化基础设施即代码审查工具，适用于DevOps环境，可与GitHub、Bitbucket以及GitLab集成（甚至适用于自托管环境）。除了标准编程语言外，该工具还能分析Ansible、Terraform、CloudFormation、Kubernetes等工具的使用情况。（开源，免费使用）
  * [codecov.io](https://codecov.io/) — 代码覆盖率工具（SaaS模式），适用于开源项目，免费服务适用于一个私有代码库。
  * [CodeFactor](https://www.codefactor.io) — 为Git代码提供自动化代码审查服务。免费版本包含无限用户数量、无限公共代码库以及一个私有代码库。  * [coderabbit.ai](https://coderabbit.ai) — 一款由人工智能驱动的代码审查工具，可与GitHub/GitLab集成。免费版每小时可处理200个文件，进行3次代码审查，并支持50次对话。适用于开源项目，永久免费使用。
  * [CodSpeed](https://codspeed.io) - 可在持续集成管道中自动化性能监控。通过精确且一致的指标，在部署前发现性能下降问题。适用于开源项目，永久免费使用。
  * [coveralls.io](https://coveralls.io/) — 用于展示测试覆盖率报告的工具，适用于开源项目，免费使用。
  * [deepscan.io](https://deepscan.io) — 高级静态分析工具，可自动检测JavaScript代码中的运行时错误。适用于开源项目，免费使用。
  * [DeepSource](https://deepsource.io/) - DeepSource持续分析源代码的变化，发现并修复与安全、性能、反模式、漏洞风险、文档和风格相关的问题。可与GitHub、GitLab和Bitbucket无缝集成。  * [DiffText](https://difftext.com) - 可即时找出两段代码之间的差异。完全免费使用。
  * [eversql.com](https://www.eversql.com/) — EverSQL - 数据库优化的首选平台。可自动获取关于数据库和SQL查询的关键信息。
  * [gerrithub.io](https://review.gerrithub.io/) — 免费为GitHub仓库提供Gerrit代码审查服务。
  * [goreportcard.com](https://goreportcard.com/) — Go项目的代码质量分析工具，开源项目可免费使用。
  * [gtmetrix.com](https://gtmetrix.com/) — 提供网站优化的报告和详细建议。
  * [holistic.dev](https://holistic.dev/) - 用于Postgresql优化的首选静态代码分析工具。可自动检测性能、安全以及架构相关问题。
  * [houndci.com](https://houndci.com/) — 关于GitHub提交中的代码质量的评论服务，开源项目可免费使用。  * [reviewable.io](https://reviewable.io/) — 针对 GitHub 仓库的代码审查服务，适用于公共或个人仓库，免费使用。
  * [scan.coverity.com](https://scan.coverity.com/) — 针对 Java、C/C++、C# 和 JavaScript 的静态代码分析服务，适用于开源项目，免费使用。
  * [scrutinizer-ci.com](https://scrutinizer-ci.com/) — 持续检查平台，适用于开源项目，免费使用。
  * [semanticdiff.com](https://app.semanticdiff.com/) — 针对 GitHub 的拉取请求和提交记录进行语言识别的差异分析服务，适用于公共仓库，免费使用。
  * [shields.io](https://shields.io) — 为开源项目提供质量元数据徽章，适用于开源项目。
  * [sonarcloud.io](https://sonarcloud.io) — 针对 Java、JavaScript、C/C++、C#、VB.NET、PHP、Objective-C、Swift、Python、Groovy 等多种语言进行的自动源代码分析服务，适用于开源项目，免费使用。

**[⬆️ 返回目录顶部](#目录内容)**

## 代码搜索与浏览  * [CodeKeep](https://codekeep.io) - 谷歌的代码片段管理工具。可以整理、发现并分享代码片段，具备强大的代码截图功能，支持预设模板和链接功能。
  * [libraries.io](https://libraries.io/) — 可搜索32种不同的包管理器，并提供依赖项更新通知，对开源项目免费使用。
  * [Namae](https://namae.dev/) - 可搜索如GitHub、Gitlab、Heroku、Netlify等网站，以查找您的项目名称的可用性。
  * [tickgit.com](https://www.tickgit.com/) — 显示`TODO`注释（及其他标记），以便识别值得改进的代码部分。

**[⬆️ 返回顶部](#目录)

## 持续集成与持续交付

  * [appcircle.io](https://appcircle.io) — 企业级移动DevOps平台，可自动化移动应用的构建、测试和发布流程，从而实现更快速、高效的发布周期。每次构建时间最多30分钟，每月可构建20次，同时可并行构建1次。* [appveyor.com](https://www.appveyor.com/) — 适用于Windows的CD服务，开源版本免费使用。
* [bitrise.io](https://www.bitrise.io/) — 适用于移动应用的CI/CD工具，支持原生或混合应用。每月可免费构建200个构建任务，构建时间为10分钟，最多可同时运行两个团队。开源项目可享受45分钟的构建时间，以及无限多的团队规模。
* [buddy.works](https://buddy.works/) — 提供CI/CD服务，每月可免费运行5个构建任务，同时可运行120个构建任务。
* [Buildkite](https://buildkite.com) — 提供免费的CI管道服务，最多可支持3个用户，每月可处理5000个任务。测试分析免费开发者层每月可执行10万次测试任务，对于开源项目还有更多免费功能。
* [bytebase.com](https://www.bytebase.com/) — 提供数据库系统的CI/CD服务以及DevOps解决方案。在用户数量不超过20人且数据库实例数量不超过10个的情况下，可享受免费服务。  * [CircleCI](https://circleci.com/) — 提供全面的免费计划，包含所有功能。该服务适用于GitHub、GitLab和BitBucket仓库。支持多种资源类型、Docker、Windows、Mac OS、ARM执行器、本地运行器等功能。每月执行时间上限为6000分钟，可无限次使用协作功能，私有项目可同时运行30个任务，开源项目可免费使用多达80,000分钟进行构建。
  * [cirrus-ci.org](https://cirrus-ci.org) - 适用于公共GitHub仓库的免费服务
  * [cirun.io](https://cirun.io) - 适用于公共GitHub仓库的免费服务
  * [codemagic.io](https://codemagic.io/) - 每月免费提供500分钟构建时间
  * [deployhq.com](https://www.deployhq.com/) — 每个项目可进行10次每日部署（每月30分钟构建时间）  * [LocalOps](https://localops.co/) - 可在30分钟内将应用程序部署到AWS/GCP/Azure上。能够在任何云环境中搭建标准化应用程序环境，并具备内置的持续部署自动化功能以及高级的可观测性功能。免费计划支持1个用户和1个应用程序环境。
  * [Make](https://www.make.com/en) — 该工作流程自动化工具允许您通过用户界面连接应用程序并自动化工作流程。它支持多种应用程序和最受欢迎的API。对于公共GitHub仓库，提供免费服务；免费层包含100MB的存储空间、1000次操作以及15分钟的最小间隔时间。
  * [Mergify](https://mergify.com) — 用于GitHub的工作流程自动化和合并队列服务——对于公共GitHub仓库，提供免费服务。
  * [Nx Cloud](https://nx.dev/ci) - Nx Cloud通过远程缓存、任务分配等功能，能够加快CI流程的速度，甚至能够自动分割E2E测试运行。免费计划适用于最多30名贡献者，并附带15000信用点。  * [RunMyJob](https://runmyjob.io/) - 通过实时扩展功能，让运行 GitHub Actions 和 GitLab CI 管道变得更加智能。免费套餐包括 400 虚拟 CPU 分钟、800 吉字节内存分钟，以及最多 10 个并发作业，配备高性能运行器（每个作业拥有 12 个虚拟 CPU 和 32 吉字节内存）。
  * [Shipfox](https://www.shipfox.io/) - 让运行 GitHub 动作的速度提高两倍，每月可免费使用 3,000 分钟构建时间。
  * [Spacelift](https://spacelift.io/) - 作为基础设施即代码的管理平台。免费计划包含：IaC 协作功能、Terraform 模块注册表、ChatOps 集成、通过 Open Policy Agent 进行持续资源合规性检查、基于 SAML 2.0 的单点登录功能，以及访问公共工作队列：每月最多 200 分钟。
  * [Squash Labs](https://www.squash.io/) - 为每个分支创建虚拟机，并通过独特的 URL 地址提供应用程序访问。支持无限数量的公共和私有仓库，虚拟机大小最大可达 2 吉字节。  * [Terramate](https://terramate.io/) - Terramate是一个用于协调和管理基础设施即代码工具的平台，这些工具包括Terraform、OpenTofu和Terragrunt等。最多支持2名用户使用，包含所有功能。
  * [Terrateam](https://terrateam.io) - 以GitOps为核心的Terraform自动化工具，具备基于拉取请求的工作流程、通过自托管的运行器实现项目隔离，以及为有序操作提供分层运行的能力。最多支持3名用户免费使用。

**[⬆️ 返回顶部](#目录)

## 测试

  * [Appetize](https://appetize.io) — 可以在浏览器上直接在这个基于云的Android手机/平板电脑模拟器以及iPhone/iPad模拟器上测试您的Android和iOS应用程序。免费版包含每月两次的并发会话，每次会话使用时间为30分钟。对于开源项目，没有应用程序大小限制。
  * [Argos](https://argos-ci.com) - 为开发者提供开源的可视化测试工具。无限项目数量，每月可生成5,000张截图。对于开源项目，完全免费。  * [Bencher](https://bencher.dev/)- 一套持续的基准测试工具套件，用于发现持续集成过程的性能退化问题。所有公共项目均可免费使用。
  * [BugBug](https://bugbug.io/)- 一款轻量级的网络应用测试自动化工具。学习起来非常容易，无需编写代码。你可以在自己的电脑上免费运行无限数量的测试。此外，还提供云监控服务以及持续集成/持续交付的集成功能，只需支付额外的月费。
  * [checkbot.io](https://www.checkbot.io/)- 一款浏览器扩展程序，用于测试你的网站是否遵循50多种SEO、性能和安全方面的最佳实践。对于小型网站，提供免费服务。
  * [Checkly](https://checklyhq.com)- 为现代DevOps团队设计的代码优先合成式监控工具。以远低于传统供应商的价格监控你的API和应用程序。该工具基于“代码驱动监控”的工作流程和Playwright技术。为开发者提供丰富的免费服务。  * [CORS-Tester](https://cors-error.dev/cors-tester/) - 一款免费工具，适用于开发人员和API测试人员，用于检查某个API是否针对特定域名启用了CORS功能，并识别存在的缺陷。可以获得实用的测试见解。
  * [cypress.io](https://www.cypress.io/) - 对浏览器中运行的任何内容进行快速、简单且可靠的测试。Cypress测试运行器始终免费且开源，没有任何限制和约束。对于最多5个用户的开源项目，Cypress仪表板也是免费的。
  * [everystep-automation.com](https://www.everystep-automation.com/) — 记录并重放在网页浏览器中执行的所有步骤，并生成脚本。该服务是免费的，但功能有限。
  * [gridlastic.com](https://www.gridlastic.com/) — 使用Selenium Grid进行测试，免费计划下最多可同时运行4个Selenium节点，每月最多支持10组测试，每组测试时间不超过4,000分钟。* katalon.com - 提供一款测试平台，可以帮助各种规模、不同测试成熟度水平的团队进行测试工作。包括 Katalon Studio、TestOps（包含免费可视化测试功能）、TestCloud 以及 Katalon Recorder。

* Keploy.io - Keploy 是一款面向开发者的功能测试工具包。通过录制 API 调用来生成 API 的完整测试（KTests），同时还可以进行模拟或替换测试（KMocks）。该工具对开源项目是免费的。

* loadmill.com - 通过分析网络流量，自动生成 API 和负载测试。每月可免费模拟最多 50 个并发用户，测试时间最长可达 60 分钟。

* lost-pixel.com - 为 Storybook、Ladle、Histoire 故事以及 Web 应用提供全面的视觉回归测试服务。支持无限数量的团队成员参与测试，对于开源项目完全免费，每月可处理 7,000 个测试案例。  * [pagegym.com](https://pagegym.com) - 提供页面加载时间分析和优化工具。免费计划每天可进行10次测试，每周进行5次实验，每月最多可处理15GB的数据。
  * [percy.io](https://percy.io) - 为任何Web应用程序、静态网站、风格指南或组件库添加可视化测试功能。支持无限数量的团队成员、免费试用版以及无限数量的项目，每月可创建5,000个测试快照。
  * [qase.io](https://qase.io) - 为开发团队和测试团队提供测试管理系统。可管理测试用例、组织测试运行、执行测试、跟踪缺陷以及衡量影响。免费版包含所有核心功能，同时提供500MB的存储空间，并支持最多3名用户的使用。  * [Repeato](https://repeato.app/) 一款基于计算机视觉和人工智能技术的No-code移动应用测试自动化工具。适用于原生应用、Flutter、React Native、Web、Ionic等多种应用框架。免费版最多支持10次iOS测试以及10次Android测试，但包含付费版的大部分功能，包括无限次测试运行。
  * [Requestly](https://requestly.com/) 一款开源的Chrome扩展程序，可用于拦截、重定向和模拟HTTP请求。提供[调试器](https://requestly.com/products/web-debugger/)、[模拟服务器](https://requestly.com/products/mock-server/)、[API客户端](https://requestly.com/products/api-client/)以及[会话录制](https://requestly.com/products/session-book/)功能。支持重定向URL、修改HTTP头信息、模拟API调用、注入自定义JavaScript代码、修改GraphQL请求、生成模拟API端点、记录网络与控制台日志。免费版最多可创建10条规则。完全免费，且为开源软件。  * [seotest.me](https://seotest.me/) — 免费的页面级SEO网站测试工具。每天可免费测试10个网站。提供了有用的SEO学习资源和建议，帮助提升任何网站的页面级SEO效果，无论使用何种技术。
  * [snippets.uilicious.com](https://snippets.uilicious.com) — 类似于CodePen，但用于跨浏览器测试。UI-licious允许你编写测试代码，如用户故事，并提供一个免费的平台——UI-licious Snippets——你可以在Chrome上无限次地测试，每次测试无需注册，每次测试时间最长可达3分钟。发现了错误？你可以复制唯一的URL到测试中，向开发人员展示如何重现该错误。
  * [SSR（服务器端渲染）检查器](https://www.crawlably.com/ssr-checker/) — 通过视觉方式比较页面在服务器上的渲染版本与普通版本，来检查任何URL的SSR（服务器端渲染）情况。* testingbot.com — 硒码浏览器和设备测试服务，[开源版本免费使用](https://testingbot.com/open-source)
* Testspace.com — 用于发布自动化测试结果的仪表板，以及利用GitHub实现手动测试代码化的框架。该服务[开源版本免费使用](https://github.com/marketplace/testspace-com)，每月可生成450份测试结果报告。
* tesults.com — 测试结果报告与测试用例管理服务。与常用的测试框架集成。开源软件开发者、个人用户、教育工作者以及小型团队均可申请优惠价格或免费服务，除了基础免费项目之外还有更多选择。
* UseWebhook.com — 从浏览器中捕获并检查Web钩子信号。可以转发到本地主机，也可以从历史记录中重新播放。免费使用。  * [Vaadin](https://vaadin.com) — 使用 Java 或 TypeScript 构建可扩展的用户界面，并利用集成工具、组件和设计系统来加快迭代速度、提升设计质量并简化开发流程。支持无限个项目，且五年内均可享受免费维护服务。
  * [webhook-test.com](https://webhook-test.com) - 通过独特的 URL 来调试和检查 webhook 及 HTTP 请求。完全免费，用户可以创建无限数量的 URL，并获取相关建议。
  * [webhook.site](https://webhook.site) - 通过自定义 URL 来验证 webhook、出站的 HTTP 请求或电子邮件。临时 URL 和电子邮件地址始终免费使用。
  * [websitepulse.com](https://www.websitepulse.com/tools/) — 各种免费的网络和服务器工具。
  * [kogiQA](https://kogiqa.com) — 一种无需使用选择器即可工作的 Web 界面自动化工具。每位开发者每月可免费使用 500 次操作。

**[⬆️ 返回目录顶部](#table-of-contents)**

## 安全与 PKI  * [aikido.dev](https://www.aikido.dev) — 一站式应用安全平台，涵盖SCA、SAST、CSPML、DAST、秘密密钥、代码安全性、恶意软件、容器扫描、EOL等安全领域。免费计划包含两名用户、扫描10个仓库、1个云环境、2个容器和1个域名。
  * [CertKit](https://www.certkit.io/certificate-management) — 用于管理SSL证书的申请、续费和监控。可查询证书透明度日志。在测试版结束后，3个证书和1名用户可免费使用。
  * [crypteron.com](https://www.crypteron.com/) — 以云技术为基础，为开发者提供的安全平台，可预防.NET和Java应用程序中的数据泄露。
  * [CyberChef](https://gchq.github.io/CyberChef/) — 一款简单直观的网络应用，用于分析和解码/编码数据，无需使用复杂的工具或编程语言。堪称密码学和加密技术的多功能工具。所有功能均可免费使用，且无使用限制。若希望自行托管，该软件为开源软件。  * [Datree](https://www.datree.io/) — 开源的CLI工具，通过确保清单和Helm图表遵循最佳实践以及组织的政策，来防止Kubernetes配置错误。
  * [Dependabot](https://dependabot.com/) — 针对Ruby、JavaScript、Python、PHP、Elixir、Rust、Java（Maven和Gradle）、.NET、Go、Elm、Docker、Terraform、Git子模块以及GitHub Actions的自动化依赖更新工具。
  * [DJ Checkup](https://djcheckup.com) — 使用此免费的自动化工具扫描您的Django网站，查找安全漏洞。该工具由Pony Checkup项目衍生而来。
  * [Doppler](https://doppler.com/) — 适用于应用程序秘密和配置的统一秘密管理器，支持与各种云服务提供商同步。五名用户可免费使用，并具备基本访问权限。  * [Dotenv](https://dotenv.org/) — 同步你的环境配置文件，操作快速且安全。不要再通过不安全的渠道如Slack和电子邮件来分享环境配置文件了，也再不要丢失重要的环境配置文件。最多可免费为3名团队成员使用。
  * [GitGuardian](https://www.gitguardian.com) — 通过自动的秘密检测与修复功能，确保秘密不会留在源代码文件中。扫描你的Git仓库，可检测350多种类型的秘密和敏感文件。个人或25名以下开发人员的团队均可免费使用。
  * [HasMySecretLeaked](https://gitguardian.com/hasmysecretleaked) — 免费搜索公开在公共GitHub仓库、Gist、问题和评论中的2000万条秘密信息。
  * [Have I been pwned?](https://haveibeenpwned.com) — 通过REST API获取有关安全漏洞的信息。
  * [hostedscan.com](https://hostedscan.com) — 针对Web应用程序、服务器和网络的在线漏洞扫描工具。每月可免费进行10次扫描。  * [Infisical](https://infisical.com/) — 一个开源平台，可以让你在团队和基础设施的不同环境中管理开发者密钥：从本地开发到预发布/生产环境，支持第三方服务。最多5个开发者可以使用该平台。
  * [Internet.nl](https://internet.nl) — 测试现代互联网标准，如IPv6、DNSSEC、HTTPS、DMARC、STARTTLS和DANE。
  * [letsencrypt.org](https://letsencrypt.org/) — 提供免费的SSL证书颁发机构服务，其颁发的证书被所有主要浏览器所信任。
  * [meterian.io](https://www.meterian.io/) — 监控Java、JavaScript、.NET、Scala、Ruby和NodeJS项目中的依赖项安全漏洞。单个私有项目可以使用该平台，开源项目则可以使用无限次。
  * [Mozilla Observatory](https://observatory.mozilla.org/) — 查找并修复网站中的安全漏洞。  * [Project Gatekeeper](https://gatekeeper.binarybiology.top/) - 一款集成的SSL工具包，提供多种功能，如私钥生成器、CSR生成器、SSL证书解码器、证书匹配器以及订单SSL证书生成服务。我们允许用户通过CNAME记录而非TXT记录来生成Let's Encrypt、Google Trust和BuyPass提供的免费SSL证书。
  * [Protectumus](https://protectumus.com) - 提供免费的网站安全检测、网站杀毒服务以及针对PHP的服务器防火墙功能。免费用户可接收电子邮件通知。
  * [Public Cloud Threat Intelligence](https://cloudintel.himanshuanand.com/) — 针对公共云基础设施的威胁指标分析服务，具有较高的准确性。部分内容可在github上找到（https://github.com/unknownhad/AWSAttacks）。完整列表可通过API获取。  * [pyup.io](https://pyup.io) — 监控Python依赖项中的安全漏洞，并自动进行更新。仅适用于一个私人项目，对于开源项目则支持无限数量的项目。
  * [qualys.com](https://www.qualys.com/community-edition) — 查找Web应用程序中的漏洞，进行OWASP风险的审计。
  * [Socket](https://socket.dev) — 为个人开发者、小型团队以及开源项目提供免费的供应链安全服务。包含免费的应用程序以及防火墙CLI工具，可保护您的代码免受脆弱和恶意依赖项的威胁。能够检测到70多种供应链风险指标。
  * [SOOS](https://soos.io) — 为开源项目提供免费且无限次的SCA扫描服务。在发布之前检测并修复安全威胁。使用简单有效的解决方案来保护您的项目。
  * [ssllabs.com](https://www.ssllabs.com/ssltest/) — 对任何SSL Web服务器的配置进行深入分析。
  * [Sucuri SiteCheck](https://sitecheck.sucuri.net) — 提供免费的网站安全检查和恶意软件扫描服务。  * [TestTLS.com](https://testtls.com) - 用于测试SSL/TLS服务的平台，以验证服务器的安全性配置、证书、证书链等。不仅限于HTTPS服务。
  * [Virgil Security](https://virgilsecurity.com/) - 提供工具和服务，用于在您的数字解决方案中实现端到端加密、数据库保护、物联网安全等功能。适用于最多250个用户的免费服务。

**[⬆️ 返回顶部](#目录)

## 认证、授权与用户管理

  * [360username](https://360username.com/) - 一款免费工具，可在90多个社交平台中搜索用户名，以查找匹配的个人信息。
  * [Aserto](https://www.aserto.com) - 提供细粒度的应用程序和API授权服务。适用于最多1000个用户和100个授权实例的免费服务。
  * [asgardeo.io](https://wso2.com/asgardeo) - 提供SSO、多因素认证、无密码认证等功能的无缝集成。提供前端和后端应用的SDK。适用于最多1000个用户和五个身份提供者。  * [Auth0](https://auth0.com/) — 提供托管式单点登录服务。免费计划包含25,000个用户管理器、无限量的社交连接、自定义域名等功能。
  * [Authgear](https://www.authgear.com) — 可快速为应用程序添加无密码登录、一次性密码、双因素认证和单点登录功能。所有前端功能均已包含。免费用户最多可拥有5000个用户管理器。
  * [Authress](https://authress.io/) — 提供身份验证登录和访问控制功能，任何项目均可使用无限量的身份提供者。支持Facebook、Google、Twitter等平台。首次1000次API调用为免费。
  * [Authy](https://authy.com) — 可在多个设备上使用双因素认证，并支持备份功能。可作为Google Authenticator的替代方案。免费用户最多可成功认证100次。
  * [Cerbos Hub](https://www.cerbos.dev/product-cerbos-hub) — 一款完整的授权管理系统，用于编写、测试和部署访问策略。支持细粒度授权和访问控制，免费用户每月最多可管理100个活跃的主体。  * [Clerk](https://clerk.com) — 用户管理、身份验证、双因素认证/多因素认证、用于登录、注册、用户资料等的预构建用户界面组件。每月最多支持10,000个活跃用户。
  * [Cloud-IAM](https://www.cloud-iam.com/) — 基于Keycloak的身份与访问管理服务。每月最多支持100个用户和一个域名。
  * [Descope](https://www.descope.com/) — 高度可定制的AuthN流程，采用无代码开发方式以及API/SDK接口。每月免费提供7,500个活跃用户，最多支持50个租户（最多5个SAML/SSO租户）。
  * [duo.com](https://duo.com/) — 为网站或应用程序提供双因素认证功能。每月免费支持10个用户，支持所有身份验证方式，无限制数量用户、集成功能以及硬件令牌。
  * [Kinde](https://kinde.com/) — 简单且强大的身份验证解决方案，可轻松与您的产品集成。只需7,500个免费活跃用户即可开始使用。  * [logintc.com](https://www.logintc.com/) — 通过推送通知实现双因素认证（2FA），适用于10个用户，同时支持VPN、网站和SSH服务。
  * [Logto](https://logto.io/) - 用于开发、保护和管理产品的用户身份，支持认证和授权功能。最多支持5,000个月活跃用户，提供开源的自行托管选项。
  * [MojoAuth](https://mojoauth.com/) - 让在网页、移动应用或任何应用中实现无密码认证变得简单快捷。
  * [Okta](https://developer.okta.com/signup/) — 提供用户管理、认证和授权服务。最多支持100个月活跃用户，免费使用。
  * [Ory](https://ory.sh/) - 提供AuthN/AuthZ/OAuth2.0/零信任安全管理平台。开发者账户永久免费，具备所有安全功能，可拥有无限数量的团队成员，每日活跃用户达200人，每月权限检查次数可达25k次。  * [Permit.io](https://permit.io) - 一种授权服务提供商平台，支持RBAC、ABAC和ReBAC功能，适用于可扩展的微服务，具有实时更新功能，且无需编写代码即可使用政策管理界面。提供每月1000活跃用户的免费试用版。
  * [Phase Two](https://phasetwo.io) - 开源的身份与访问管理解决方案。免费版本支持最多1000用户，最多支持10个单点登录连接。该平台利用Phase Two的增强型Keycloak容器，包含[组织管理功能](https://phasetwo.io/product/organizations/)。
  * [PropelAuth](https://propelauth.com) — 只需几行代码即可向任何规模的公司出售该产品。免费版本支持最多200用户，可处理10k笔交易邮件（带有“由PropelAuth提供支持”的标识）。
  * [Stack Auth](https://stack-auth.com) — 开源的身份验证解决方案，使用起来非常方便。是最适合开发者的解决方案，只需五分钟即可开始使用。可免费自托管，或提供有管理的SaaS版本，每月活跃用户数量上限为10k。  * [Stytch](https://www.stytch.com/) - 一个一体化平台，提供用于身份验证和防欺诈的API及SDK。免费计划包含10,000个每月活跃用户、无限的组织数量、5个SSO或SCIM连接，以及1,000个M2M令牌。
  * [SuperTokens](https://supertokens.com/) - 开源用户身份验证解决方案，可原生集成到您的应用中。适合快速启动，同时能够控制用户和开发者的体验。免费服务适用于最多5,000个每月活跃用户。
  * [WorkOS](https://workos.com/) - 提供免费的用户管理和身份验证服务，适用于最多100万每月活跃用户。支持电子邮件+密码、社交认证、Magic认证、多因素认证等多种方式。
  * [ZITADEL Cloud](https://zitadel.com) - 一站式用户和访问管理解决方案，适用于多租户（B2B）应用场景。免费服务适用于最多25,000个已认证请求，并提供所有安全功能（如OTP、无密码认证、策略管理等）。


**[⬆️ 返回顶部](#目录)**## 移动应用分发与反馈

  * [Appho.st](https://appho.st) - 移动应用托管平台。免费计划包含五个应用，每月下载量有限，文件大小上限为100MB。
  * [Diawi](https://www.diawi.com) - 可直接将iOS和Android应用部署到设备上。免费计划：应用上传、密码保护链接、1天有效期、最多安装10次。
  * [GetUpdraft](https://www.getupdraft.com) - 用于测试的移动应用分发服务。免费计划包含1个应用项目、3个应用版本、500MB存储空间，每月最多安装100个应用。
  * [InstallOnAir](https://www.installonair.com) - 通过无线方式分发iOS和Android应用。免费计划：无限上传、私密链接、访客有效期限2天、注册用户有效期限60天。
  * [Loadly](https://loadly.io) - iOS和Android测试版应用分发服务，提供完全免费的服务，包括无限下载、高速下载和无限上传功能。

**[⬆️ 返回顶部](#目录)## 管理系统

  * [Bitnami官网](https://bitnami.com/) — 用于在IaaS环境下部署准备好的应用程序。免费提供对1个AWS微服务的管理服务。
  * [Esper](https://esper.io) — 为Android设备提供MDM和MAM功能，支持DevOps。免费提供100台设备，只需1个用户许可证，且应用程序存储为25MB。
  * [Jamf官网](https://www.jamf.com/) — 用于管理iPad、iPhone和Mac设备等设备的服务。免费提供3台设备。
  * [Miradore](https://miradore.com) — 设备管理服务。可随时了解您的设备状况，并免费管理无限数量的设备。免费计划仅提供基础功能。
  * [moss.sh](https://moss.sh) — 帮助开发者部署和管理他们的Web应用程序和服务器。每月最多可免费部署25个Git项目。
  * [Ploi.io](https://ploi.io/) — 用于轻松管理和部署服务器及网站的服务器管理工具。单个服务器免费使用。
  * [RunCloud.io](https://runcloud.io/) — 主要专注于PHP项目的服务器管理服务。单个服务器免费使用。  * [serveravatar.com](https://serveravatar.com) — 通过自动化配置来管理和监控基于PHP的Web服务器。单个服务器免费使用。
  * [xcloud.host](https://xcloud.host) — 具有用户友好界面的服务器管理和部署平台。单个服务器可享免费套餐。

**[⬆️ 返回顶部](#目录)

## 消息传递与流媒体

  * [Ably](https://www.ably.com/) - 提供实时消息传递服务，具备存在性、持久性以及保证送达的功能。免费套餐每月包含3百万条消息、100个峰值连接以及100个峰值通道。
  * [cloudamqp.com](https://www.cloudamqp.com/) — 作为服务的RabbitMQ。Little Lemur套餐：每月最多支持100万条消息，最多支持20个并发连接，最多支持100个队列，最多支持10,000条已排队消息，支持多节点部署。  * [courier.com](https://www.courier.com/) — 提供单一的API，可用于推送消息、应用内通知、电子邮件、聊天、短信以及其他消息传递渠道。免费计划包含每月10,000条消息的发送权限。
  * [EMQX Serverless](https://www.emqx.com/en/cloud/serverless-mqtt) — 可扩展且安全的无服务器MQTT代理，可快速部署。每月免费使用1百万会话分钟数（无需信用卡）。
  * [Engage](https://engage.so/) — 一站式客户参与与自动化工具，包括电子邮件、推送消息、短信通知、产品体验活动、横幅推送等功能的SaaS解决方案。每月免费使用，最多可支持1,000个活跃用户。
  * [engagespot.co](https://engagespot.co/) — 为开发者提供多通道通知基础设施，包含内置的应用内收件箱以及无需编程即可使用的模板编辑器。免费计划包含每月10,000条消息的发送权限。  * [HiveMQ](https://www.hivemq.com/mqtt-cloud-broker/) - 将您的MQTT设备连接到云原生物联网消息代理。免费，最多可连接100台设备（无需信用卡）。
  * [httpSMS](https://httpsms.com) - 使用您的安卓手机作为短信网关来发送和接收文本消息。每月免费发送和接收最多200条消息。
  * [knock.app](https://knock.app) – 为开发者提供通知基础设施。通过一次API调用，即可向多个渠道发送通知，如应用内通知、电子邮件、短信、Slack和推送通知。免费计划包含每月10,000条通知。
  * [NotificationAPI.com](https://www.notificationapi.com/) — 在5分钟内为任何软件添加用户通知。免费计划包含每月10,000条通知，以及100条短信和自动电话。  * [Novu.co](https://novu.co) — 为开发者提供开源的通知系统。提供简单的组件和API，可在一个地方管理所有通信渠道：电子邮件、短信、直接消息、应用内消息以及推送通知。免费计划每月可发送30,000条通知，并保留90天的数据。
  * [Pocket Alert](https://pocketalert.app) — 向iOS和Android设备发送推送通知。可通过API或Web钩子轻松集成，并完全控制通知的发送。免费计划：每天最多向1台设备和1个应用发送50条消息。
  * [pubnub.com](https://www.pubnub.com/) — 提供Swift、Kotlin和React的消息传递服务，每月处理100万次交易。一次交易可能包含多条消息。
  * [pusher.com](https://pusher.com/) — 实时消息服务。最多可免费支持100个同时连接，每天可发送200,000条消息。
  * [scaledrone.com](https://www.scaledrone.com/) — 实时消息服务。最多可免费支持20个同时连接，每天可发送100,000个事件。  * [SMSGate](https://sms-gate.app) - SMS Gateway for Android™ 通过云路由功能，让您能够使用设备发送和接收短信。这是一款完全免费的云服务（如果日发送短信数量超过10,000条，系统会发送提示信息，以确保所有用户都能获得优质服务）。
  * [SuprSend](https://www.suprsend.com/) - SuprSend是一种通知基础设施，采用API优先的方式简化产品通知的发送流程。通过单一的通知API，可以在多个渠道创建和发送事务性通知、周期性通知以及互动通知。在免费计划中，您每月可以发送10,000条通知，包括多种工作流节点，如摘要处理、批量处理、多通道处理、偏好设置处理、广播通知等。
  * [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io)作为服务提供。支持全球各地的AWS、GCP和Azure环境。免费使用，无限制，且支持4K消息大小、50个活跃连接以及每月5GB的数据存储。* [webpushr](https://www.webpushr.com/) – 网页推送通知服务。为最多10,000名订阅者提供免费服务，支持无限量的推送通知和浏览器内消息传递功能。

**[⬆️ 返回顶部](#目录)**

## 日志管理

* [bugfender.com](https://bugfender.com/) – 每天最多可处理100,000条日志，存储时间为24小时。
* [log.dog](https://log.dog/) – LogDog是一款适用于iOS和Android设备的远程调试/日志管理SDK，具有网页界面。能够实时捕获所有日志、请求和事件，并允许对其进行拦截。每月最多可免费处理100MB的日志。
* [logflare.app](https://logflare.app/) – 每月每个应用程序最多可处理12,960,000条日志，存储时间为3天。
* [logtail.com](https://logtail.com/) – 基于ClickHouse的SQL兼容日志管理工具。每月最多可免费处理1GB的日志，存储时间为3天。
* [logzab.com](https://logzab.com/) – 审计跟踪管理系统。每月可免费处理1,000条用户活动日志，存储时间为1个月，最多支持5个项目。  * [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-siem/) — 由Manage Engine提供的日志管理服务。免费计划提供50GB存储空间，15天的存储保留时间，以及7天的搜索功能。
  * [openobserve.ai](https://openobserve.ai/) — 每月免费提供200GB的数据处理量，15天的保留时间。

**[⬆️ 返回顶部](#目录)

## 翻译管理

  * [AutoLocalise.com](https://www.autolocalise.com/) — 无需管理翻译文件即可进行即时翻译。每月最多10,000个字符的翻译服务免费，支持无限语言。
  * [crowdin.com](https://crowdin.com/) — 无限项目数量、无限字符串数量，以及开源项目的合作者支持。
  * [Free PO editor](https://pofile.net/free-po-editor) — 免费提供给所有人使用。
  * [Lingo.dev](https://lingo.dev) — 基于开源AI技术的CLI工具，适用于网站和移动应用的本地化工作。可以自行使用LLM，或者每月通过Lingo.dev提供的本地化引擎使用10,000个免费词汇。  * [lingohub.com](https://lingohub.com/) — 适用于开源项目，最多支持3个用户，全程免费
  * [localazy.com](https://localazy.com) - 免费提供1000个源语言字符串，支持无限语言、无限贡献者，适用于初创企业和开源项目
  * [Localit](https://localit.io) – 快速、易于开发的本地化平台，具备无缝且免费的GitHub/GitLab集成功能，支持人工智能辅助和手动翻译，提供丰富的免费计划（包含2个用户、500个翻译密钥以及无限项目）
  * [localizely.com](https://localizely.com/) — 适用于开源项目，免费使用
  * [Loco](https://localise.biz/) — 免费提供最多2000次翻译，支持无限翻译人员、十种语言/项目，可处理1000个可翻译资源/项目
  * [POEditor](https://poeditor.com/) — 免费提供最多100个字符串的翻译服务
  * [SimpleLocalize](https://simplelocalize.io/) - 免费提供最多100个翻译密钥、无限字符串数量、无限语言支持，适用于初创企业项目
  * [Texterify](https://texterify.com/) - 单个用户免费使用  * [Tolgee](https://tolgee.io) - 提供免费的SaaS服务，支持有限的翻译功能，同时提供永久免费的自托管版本。
  * [transifex.com](https://www.transifex.com/) — 针对开源项目提供免费服务。

**[⬆️ 返回顶部](#目录)

## 监控服务

  * [assertible.com](https://assertible.com) — 提供自动化的API测试与监控服务。为团队和个人提供免费计划。
  * [Better Stack](https://betterstack.com/better-uptime) - 提供一站式监控、事件管理、紧急调度/警报以及状态页面功能。免费计划包含10个监控器，每3分钟检查一次状态，并提供状态页面。
  * [bleemeo.com](https://bleemeo.com) - 为3台服务器提供免费服务，包含5个运行时间监控器，用户数量无限制，仪表板数量无限制，警报规则也无限制。
  * [checklyhq.com](https://checklyhq.com) - 提供开源的E2E/合成监控服务以及深入的API监控服务，适用于开发者。免费计划包含1个用户，可运行10k个API和网络监控，以及1.5k次浏览器检查。  * [核心网页指标历史](https://punits.dev/core-web-vitals-historical/) - 查询某个网址或网站的核心网页指标历史数据。
  * [cronitor.io](https://cronitor.io/) - 提供关于定时任务、网站、API等性能方面的洞察以及运行时间监控功能。提供免费版本，包含五个监控器。
  * [datadoghq.com](https://www.datadoghq.com/) — 最多5个节点可享受免费服务。
  * [deadmanssnitch.com](https://deadmanssnitch.com/) — 提供定时任务的监控服务。提供一个免费监控器，如果你能推荐其他人注册，还可以获得更多监控器。
  * [downtimemonkey.com](https://downtimemonkey.com/) — 提供60个运行时间监控器，每5分钟更新一次数据。提供电子邮件和Slack警报功能。
  * [economize.cloud](https://economize.cloud) — Economize帮助用户了解云基础设施的成本，通过整理云资源来优化并报告相关数据。每月在Google Cloud Platform上的支出不超过5,000美元的用户可享受免费服务。  * [fivenines.io](https://fivenines.io/) — 用于监控Linux服务器的平台，提供实时仪表盘和警报功能。最多支持5台服务器，无需信用卡即可免费使用，每60秒更新一次数据。
  * [Grafana Cloud](https://grafana.com/products/cloud/) — 一种可组合的可观测性平台，将指标和日志与Grafana集成。免费试用：3个用户、10个仪表盘、100个警报，指标存储使用Prometheus和Graphite（存储容量达10,000系列，保留14天），日志存储使用Loki（存储容量50GB，保留14天）。
  * [healthchecks.io](https://healthchecks.io) — 用于监控定时任务和后台任务。最多支持20个检查任务，免费使用。
  * [incidenthub.cloud](https://incidenthub.cloud/) — 云和SaaS形式的状态页面聚合工具。最多支持20个监控项，2个通知渠道（Slack和Discord），免费使用，永久免费。
  * [inspector.dev](https://www.inspector.dev) — 一种完整的实时监控仪表板，不到一分钟即可创建，同样提供永久免费使用权限。  * [instatus.com](https://instatus.com) - 只需10秒即可创建美观的状态页面。永久免费使用，支持无限数量的子站和无限数量的团队。
  * [linkok.com](https://linkok.com) - 在线断链检查工具，小型网站（最多100页）可免费使用，开源项目则完全免费。
  * [loader.io](https://loader.io/) - 免费负载测试工具，但存在一定限制。
  * [Middleware.io](https://middleware.io/) - 中间件可观测性平台，能全面监控您的应用程序和整个技术栈，从而能够大规模监控和诊断问题。该平台为开发社区提供永久免费计划，允许对最多1百万条日志事件进行监控，以及对最多2个主机进行基础设施监控和APM管理。
  * [MonitorMonk](https://monitormonk.com) - 以极简风格提供正常运行时间监控服务，同时拥有美观的状态页面。永久免费计划支持对最多10个网站或API端点进行HTTPS、关键词、SSL以及响应时间监控，并提供2个仪表盘/状态页面。  * [netdata.cloud](https://www.netdata.cloud/) — Netdata是一个开源工具，用于收集实时数据指标。这是一个不断发展的产品，也可以在GitHub上找到！
  * [newrelic.com](https://www.newrelic.com) — New Relic的可观测性平台，旨在帮助工程师打造更完美的软件。无论是单体应用还是无服务器应用程序，都可以为所有应用程序添加监控功能，然后进行分析、故障排除和优化。免费套餐每月提供100GB的数据存储、一个免费的全权限用户账户，以及无限量的免费主要用户。
  * [OnlineOrNot.com](https://onlineornot.com/) — OnlineOrNot提供网站和API的正常运行时间监控，以及定时任务和计划任务的监控。还提供状态页面。前五个检查以3分钟间隔进行，免费。免费套餐通过Slack、Discord和电子邮件发送警报。  * [OntarioNet.ca CN测试](https://cntest.ontarionet.ca) — 用于检查一个网站是否在中国被防火墙阻止。该工具通过比较中国服务器与美国服务器所检测到的DNS结果和ASN信息，来识别DNS污染问题。
  * [pagecrawl.io](https://pagecrawl.io/) — 用于监控网站的变化。免费服务，最多可同时监控6个网站，并每天进行检查。
  * [pagertree.com](https://pagertree.com/) — 提供简单的警报通知和值班管理功能。免费服务，最多可支持5个用户。
  * [phare.io](https://phare.io/) — 提供免费的上线监控服务，最多可处理100,000个事件，且项目数量和无限制的状态页面都无需付费。
  * [pingbreak.com](https://pingbreak.com/) — 提供现代的上线监控服务。可以检查无限数量的URL，并通过Discord、Slack或电子邮件接收故障通知。
  * [Pingmeter.com](https://pingmeter.com/) — 提供5种上线监控服务，每10分钟进行一次监控。可以监控SSH、HTTP、HTTPS以及任何自定义的TCP端口。  * [pingpong.one](https://pingpong.one/) — 先进的状态页面平台，包含监控功能。免费套餐包含一个可自定义的公共状态页面，并配有SSL子域名。专业版免费提供给开源项目和非营利组织使用。
  * [Pulsetic](https://pulsetic.com) - 10个监控器，6个月的历史运行记录/日志，无限数量的状态页面，以及自定义域名支持！免费提供无限时长及无限电子邮件警报功能。无需使用信用卡即可享受服务。
  * [robusta.dev](https://home.robusta.dev/) — 基于Prometheus的强大Kubernetes监控工具。可以选择使用自己的Prometheus工具，或者安装完整的监控套件。免费套餐最多支持20个Kubernetes节点。可通过Slack、Microsoft Teams、Discord等渠道接收警报。同时支持与PagerDuty、OpsGenie、VictorOps、DataDog等许多工具的集成。  * [Servervana](https://servervana.com) - 提供高级的服务器运行时间监控功能，支持大型项目与团队。包含HTTP监控、基于浏览器的监控、DNS监控、域名监控、状态页面等功能。免费版包含10个HTTP监控器、1个DNS监控器以及1个状态页面。
  * [Simple Observability](https://simpleobservability.com) — 提供强大的服务器监控功能，适用于指标和日志的统一管理，无需复杂设置。单个服务器免费使用。
  * [sitesure.net](https://sitesure.net) - 提供网站和定时任务监控功能，免费使用2个监控器。
  * [skylight.io](https://www.skylight.io/) — 前100,000次请求免费使用（仅限Rails环境）。
  * [stathat.com](https://www.stathat.com/) — 免费试用10个统计功能，无使用期限限制。
  * [statuscake.com](https://www.statuscake.com/) — 提供网站监控功能，免费使用无限次测试功能，但存在使用限制。
  * [statusgator.com](https://statusgator.com/) — 提供状态页面监控功能，免费使用3个监控器。* [SweetUptime](https://dicloud.net/sweetuptime-server-uptime-monitoring/) — 服务器监控、运行时间监控、DNS与域名监控服务。可免费监控10台服务器、10个运行时间以及10个域名。
* [syagent.com](https://syagent.com/) — 非商业性的免费服务器监控服务，提供警报和指标数据。
* [UptimeObserver.com](https://uptimeobserver.com) — 可获取20个运行时间监控工具，每5分钟更新一次数据，并拥有可自定义的状态页面——甚至可用于商业用途。可通过电子邮件和Telegram获得无限量的实时通知。开始使用无需信用卡。
* [uptimetoolbox.com](https://uptimetoolbox.com/) — 免费监控5个网站，每60秒更新一次数据，并提供公开的状态页面。
* [Wachete](https://www.wachete.com) — 监控5个页面，每24小时检查一次。
* [Xitoring.com](https://xitoring.com/) — 运行时间监控：20个免费服务；Linux和Windows Server监控：5个免费服务；状态页面：1个免费服务。还有移动应用、多种通知渠道等更多功能！**[返回顶部](#table-of-contents)**

## 崩溃与异常处理

  * [Axiom](https://axiom.co/) — 可存储高达0.5 TB的日志，存储周期为30天。支持与Vercel等平台的集成，并可通过电子邮件/Discord进行数据查询通知。
  * [Bugsink](https://www.bugsink.com/) — 支持使用Sentry-SDK进行错误跟踪。每月最多可处理5,000个错误时免费使用，若自行托管则无需限制。
  * [bugsnag.com](https://www.bugsnag.com/) — 初始试用后，每月最多可处理2,000个错误时免费使用。
  * [CatchJS.com](https://catchjs.com/) — 支持JavaScript错误跟踪，并附带截图和点击轨迹信息。适用于开源项目，免费使用。
  * [elmah.io](https://elmah.io/) — 为Web开发者提供错误记录及运行时间监控功能。适用于开源项目，免费提供小型企业订阅服务。
  * [Embrace](https://embrace.io/) — 提供移动应用监控服务。适用于小型团队，每年用户会话数量最多可达1百万次时免费使用。  * [Exceptionless](https://exceptionless.com) — 实时错误报告、功能监控、日志记录等。每月限3k事件/1个用户免费使用。开源代码，易于自行托管，可无限使用。
  * [GlitchTip](https://glitchtip.com/) — 简单且开源的错误跟踪工具。兼容开源的Sentry SDK。每月免费限1000事件，或可自行托管，无限制使用。
  * [honeybadger.io](https://www.honeybadger.io) - 异常监控、运行时间监控及定时任务监控。适用于小型团队和开源项目，每月限12,000个错误记录免费使用。
  * [Jam](https://jam.dev) - 开发者友好的一键式错误报告功能。免费计划，可无限使用Jam功能。
  * [memfault.com](https://memfault.com) — 云端的设备观测和调试平台。针对[Nordic](https://app.memfault.com/register-nordic)、[NXP](https://app.memfault.com/register-nxp)和[Laird](https://app.memfault.com/register-laird)设备，每月免费限100个设备使用。  * [rollbar.com](https://rollbar.com/) — 异常和错误监控服务，免费计划每月允许处理5,000个错误，支持无限用户，数据保留期限为30天。
  * [Semaphr](https://semaphr.com) — 为移动应用提供免费的全方位故障排除功能。
  * [sentry.io](https://sentry.io/) — Sentry能够实时跟踪应用程序中的异常，提供小型免费计划。每月处理5,000个错误或1个用户时免费使用，若自行托管服务则使用不受限制。
  * [Whitespace](https://whitespace.dev) — 通过浏览器即可一键提交错误报告。免费计划支持无限次录制，适用于个人使用。

**[⬆️ 返回顶部](#目录)

## 搜索

  * [algolia.com](https://www.algolia.com/) — 提供托管搜索解决方案，具备拼写容忍度、相关性以及用户界面库等功能，可轻松创建搜索体验。免费“构建”计划包含1百万份文档和每月10,000次搜索权限。同时提供免费的[开发者文档搜索](https://docsearch.algolia.com/)。  * [bonsai.io](https://bonsai.io/) — 提供免费的1GB内存和1GB存储空间
  * [CommandBar](https://www.commandbar.com/) - 提供统一的搜索栏服务，是一款基于Web的用户界面小部件/插件，用户可以通过该插件在产品中搜索内容、功能等，从而提高产品的可发现性。对于最多1,000名月活跃用户，该服务是免费的，且命令数量无限制。
  * [Orama Cloud](https://orama.com/pricing) — 提供免费的3个索引，10万份文档和索引，支持无限量的全文、向量和混合搜索，且数据分析服务可享受60天的免费试用。
  * [searchly.com](http://www.searchly.com/) — 提供免费的2个索引和20MB的存储空间

**[⬆️ 返回顶部](#目录)

## 教育与职业发展

  * [Cisco Networking Academy, Skills for All](https://skillsforall.com/) - 提供与认证相关的免费课程，涵盖网络安全、网络技术和Python等主题。  * [DeepLearning.AI短期课程](https://www.deeplearning.ai/short-courses/) – 由行业领先专家提供的免费短期课程，让您在1小时以内掌握最新的生成式AI工具与技术。
  * [DevNet学院](https://devnet-academy.com/) – 为Cisco DevNet专家/CCIE自动化认证提供免费、自定进度的培训。涵盖Python Click和Flask-RESTx相关知识。
  * [Django教程.dev](https://django-tutorial.dev) – 提供免费在线教程，帮助您学习Django框架。同时，网站还会为用户撰写的文章提供免费的反向链接。
  * [edX](https://www.edx.org/) – 提供来自250所顶尖机构的4000多门免费在线课程，这些机构包括哈佛大学和麻省理工学院等知名学府，涉及计算机科学、工程学和数据科学等领域。
  * [Exercism](https://exercism.org) – 提供免费的开源编程教育服务，涵盖超过75种编程语言，并配有人工指导。该组织属于非营利性机构。  * [免费专业简历模板及编辑器](https://www.overleaf.com/latex/templates/tagged/cv) – 免费平台，提供大量经验丰富的专业人士的简历模板，可完全克隆、编辑并下载，同时优化了ATS系统。
  * [FreeCodeCamp](https://www.freecodecamp.org/) – 开源平台，提供数据分析、信息安全、网页开发等领域的免费课程和认证。
  * [Full Stack Open](https://fullstackopen.com/en/) – 提供基于React、Node.js、GraphQL、TypeScript等技术的现代网页开发免费大学级课程。完全在线且可自主安排学习进度。
  * [交互式简历](https://interactive-cv.com)——由AI驱动的可编辑简历工具，支持实时编辑，并经过ATS系统优化。免费版包含自动将简历转换为高级模板的功能（如哈佛、Europass模板）、PDF导出功能，以及带有无限职位发布洞察和简历分享功能的聊天/语音功能。  *  Khan Academy (https://www.khanacademy.org/computing/computer-programming) - 提供免费的在线教程，帮助学习者学习基础及高级的HTML/CSS、JavaScript和SQL技能。
  *  LabEx (https://labex.io) - 通过互动实验室和实际项目，培养在Linux、DevOps、网络安全、编程、数据科学等方面的技能。
  *  MIT OpenCourseWare (https://ocw.mit.edu/) - MIT OpenCourseWare是一个在线平台，提供来自超过2,500门MIT课程的教材，免费向全球的学习者和教育工作者分享知识。其YouTube频道可以在[@mitocw](https://www.youtube.com/@mitocw/featured)找到。
  *  Roadmap.sh (https://roadmap.sh) - 提供涵盖从区块链到用户体验设计各个方面的免费学习路线图。
  *  The Odin Project (https://www.theodinproject.com/) - 一个免费的开源平台，提供专注于JavaScript和Ruby的Web开发课程。* [W3Schools](https://www.w3schools.com/) - 提供关于HTML、CSS、JavaScript等网页开发技术的免费教程。

**[⬆️ 返回顶部](#目录)

## 电子邮件服务

* [10minutemail](https://10minutemail.com) - 用于测试的免费、临时电子邮件服务。
* [AhaSend](https://ahasend.com) - 事务性电子邮件服务，每月免费发送1000封电子邮件，免费计划支持无限数量的域名、团队成员、Web钩子和消息路由。
* [AnonAddy](https://anonaddy.com) - 开源匿名电子邮件转发服务，可免费创建无限数量的电子邮件别名。
* [Antideo](https://www.antideo.com) - 免费级别每小时可进行10次电子邮件验证、IP和电话号码验证。无需使用信用卡。
* [Brevo](https://www.brevo.com/) - 每月可发送9,000封电子邮件，每天免费发送300封电子邮件。
* [Bump](https://bump.email/) - 免费提供10个Bump电子邮件地址，支持一个自定义域名。  * [Burnermail](https://burnermail.io/) – 提供免费的5个邮箱地址、1个邮箱账户，以及7天的邮箱使用记录。
  * [Buttondown](https://buttondown.email/) — 新闻通讯服务。最多可免费为100名订阅者提供服务。
  * [Contact.do](https://contact.do/) — 通过链接提供联系表单服务，信息简洁明了。
  * [debugmail.io](https://debugmail.io/) — 适用于开发者的易用测试邮件服务器。
  * [dkimvalidator.com](https://dkimvalidator.com/) — 测试电子邮件的DNS/SPF/DKIM/DMARC设置是否正确，由roundsphere.com提供免费服务。
  * [DNSExit](https://dnsexit.com/) — 在您的域名下免费提供最多2个邮箱地址，并拥有100MB的存储空间。支持IMAP、POP3、SMTP、SPF/DKIM等协议。
  * [EmailJS](https://www.emailjs.com/) — 这不是一个完整的邮件服务器，只是一个可以从中直接发送邮件的邮件客户端。免费套餐每月可发送200次请求，提供2个邮件模板，请求大小上限为50Kb，支持有限的联系人记录。  * [EmailLabs.io](https://emaillabs.io/en) — 每月可免费发送多达9,000封邮件，每天最多可发送300封邮件。
  * [EmailOctopus](https://emailoctopus.com) - 每月可免费为最多2,500名订阅者发送邮件，发送数量上限为10,000封。
  * [Emailvalidation.io](https://emailvalidation.io) - 每月可免费进行100次邮件验证。
  * [EtherealMail](https://ethereal.email) - Ethereal Mail是一种假的SMTP服务，主要面向Nodemailer和EmailEngine用户（但不仅限于这些用户）。它是一项完全免费的防交易邮件服务，在此服务中，邮件永远不会被发送出去。
  * [forwardemail.net](https://forwardemail.net) — 为自定义域名提供免费的邮件转发服务。可以创建并转发无限数量的带有您域名地址的邮件（**注意**：如果您使用.casa、.cf、.click、.email、.fit、.ga、.gdn、.gq、.lat、.loan、.london、.men、.ml、.pl、.rest、.ru、.tk、.top、.work等顶级域名，则需要付费使用）。* [Imitate Email](https://imitate.email) – 沙盒电子邮件服务器，用于测试邮件功能，适用于构建、测试及持续交付环境。免费账户可永久使用每天15封电子邮件。
* [ImprovMX](https://improvmx.com) – 免费电子邮件转发服务。
* [Inboxes App](https://inboxesapp.com) – 每天可创建最多3个临时电子邮件，通过方便的Chrome扩展程序在完成后删除这些邮件。非常适合测试注册流程。
* [inboxkitten.com](https://inboxkitten.com/) – 免费临时/一次性电子邮件收件箱服务，支持最多3天自动删除邮件。采用开源架构，可自行托管。
* [mail-tester.com](https://www.mail-tester.com) – 测试电子邮件的DNS/SPF/DKIM/DMARC设置是否正确，每月免费使用20次。
* [Maileroo](https://maileroo.com) – 为开发者提供SMTP中继和电子邮件API服务。每月可发送5,000封电子邮件，支持无限域名，提供免费电子邮件验证、黑名单监控、邮件测试等功能。  * [mailcatcher.me](https://mailcatcher.me/) — 用于接收邮件并通过网页界面进行处理的工具。
  * [mailchannels.com](https://www.mailchannels.com) - 提供电子邮件API服务，支持REST API和SMTP接口，每月最多可处理3,000封电子邮件，免费使用。
  * [Mailcheck.ai](https://www.mailcheck.ai/) - 防止用户使用临时电子邮件地址进行注册，每小时可处理120个请求（每月约86,400个请求）。
  * [Mailchimp](https://mailchimp.com/) — 提供500个订阅者和每月1,000封电子邮件的免费服务。
  * [Maildroppa](https://maildroppa.com) - 提供多达100个订阅者和无限数量的电子邮件处理服务，同时支持自动化功能，免费使用。
  * [MailerLite.com](https://www.mailerlite.com) — 每月可处理1,000个订阅者和12,000封电子邮件，免费使用。
  * [MailerSend.com](https://www.mailersend.com) — 提供电子邮件API和SMTP服务，每月可处理3,000封电子邮件，适用于事务性邮件，免费使用。
  * [mailinator.com](https://www.mailinator.com/) — 免费的公共电子邮件系统，用户可以自由使用任何他们想要的收件箱。  * [Mailjet](https://www.mailjet.com/) — 每月免费发送6,000封电子邮件（每日发送限制为200封电子邮件）
  * [mailsac.com](https://mailsac.com) - 提供免费API，可用于临时电子邮件测试，免费提供公共电子邮件托管服务，支持邮件转发功能，同时支持将电子邮件发送到Slack/WebSocket/WebHook服务器（每月API调用限制为1,500次）
  * [Mailtrap.io](https://mailtrap.io/) — 提供电子邮件API和SMTP服务，每月免费发送3,500封用于事务性和营销目的的电子邮件。该平台还提供电子邮件沙盒功能，可使用假的SMTP服务器进行开发测试，免费计划包含一个收件箱、100条消息，无需团队成员参与，发送速度可达每秒两封电子邮件，且不支持邮件转发规则
  * [Mutant Mail](https://www.mutantmail.com/) – 提供免费10个电子邮件地址、1个域名、1个邮箱空间。所有电子邮件地址共享同一个邮箱空间
  * [OneSignal](https://onesignal.com/) — 每月可发送10,000封电子邮件，无需使用信用卡即可使用
  * [Parsio.io](https://parsio.io) — 提供免费电子邮件解析服务（如转发邮件、提取数据并将其发送到您的服务器）
  * [Plunk](https://useplunk.com) - 每月免费发送3,000封电子邮件  * [Postmark](https://postmarkapp.com/) - 每月免费发送100封电子邮件，每周可发送无限量的DMARC摘要。
  * [Proton Mail](https://proton.me/mail) - 提供免费且安全的电子邮件账户服务，内置端到端加密功能。每月免费提供1GB存储空间。
  * [Resend.com](https://resend.com) - 为开发者提供的交易型电子邮件API服务。每月可发送3000封电子邮件，每天免费发送100封电子邮件，支持自定义域名。
  * [Sender.net](https://www.sender.net) - 每月最多可发送15000封电子邮件，最多可拥有2500名订阅者。
  * [Sendpulse.com](https://sendpulse.com) - 每月可免费发送15000封电子邮件，最多可拥有500名订阅者。
  * [SimpleLogin.io](https://simplelogin.io/) - 开源的自行托管电子邮件别名/转发解决方案。免费提供10个别名，无限带宽，无限回复/发送功能。适用于教育工作者（学生、研究人员等）的免费服务。
  * [Substack.com](https://substack.com) - 提供无限量的免费通讯服务。需付费后才能享受此服务。  * [Sweego](https://www.sweego.io/) - 为开发者提供的欧洲事务性电子邮件API服务。每天可免费发送100封电子邮件。
  * [temp-mail.io](https://temp-mail.io) — 免费的一次性临时电子邮件服务，可同时发送多封电子邮件并进行转发。
  * [Temp-Mail.org](https://temp-mail.org/en/) - 使用多种域名提供的临时/一次性电子邮件服务。电子邮件地址在页面重新加载时自动更新。该服务完全免费，且不包含任何服务费用。
  * [TempMailDetector.com](https://tempmaildetector.com/) - 每月可免费检测多达200封电子邮件，判断这些电子邮件是否为临时邮件。
  * [trashmail.com](https://www.trashmail.com) - 提供免费的一次性电子邮件地址，支持转发功能，且地址自动失效。  * [Tuta](https://tuta.com/) - 提供免费且安全的电子邮件账户服务，内置端到端加密功能，无广告，无追踪行为。提供免费的1GB存储空间，以及一个日历功能。Tuta还提供付费计划。(https://tuta.com/pricing)。Tuta的部分代码是开源的，因此也可以自行部署。
  * [Verifalia](https://verifalia.com/email-verification-api) — 提供实时电子邮件验证服务，包含邮箱确认功能以及一次性电子邮件地址检测器；每天可免费进行25次电子邮件验证。
  * [verimail.io](https://verimail.io/) — 提供批量和API级别的电子邮件验证服务。每月可免费进行100次验证。

**[⬆️ 返回顶部](#目录)

## 功能开关管理平台

  * [Abby](https://www.tryabby.com) - 采用开源方式管理功能开关，支持A/B测试。支持通过代码配置，并拥有完全用TypeScript编写的开发工具。与Next.js和React等框架有着良好的集成。提供丰富的免费功能，并具备灵活的扩展选项。  * [ConfigCat](https://configcat.com) - ConfigCat 是一款以开发者为中心的功能标志服务，支持无限团队规模、优质的支持服务以及合理的价格。免费计划最多支持10个功能标志、两种环境、1个产品，且每月请求次数上限为500万次。
  * [Flagsmith](https://flagsmith.com) - 能够自信地发布功能；可管理跨网页、移动端和服务器端应用程序的功能标志。可以使用我们的托管API，部署到自己的私有云中，或直接在本地运行。
  * [GrowthBook](https://growthbook.io) - 开源的功能标志和A/B测试工具提供商，内置贝叶斯统计分析引擎。最多支持3个用户使用，功能标志和实验数量不受限制。
  * [Hypertune](https://www.hypertune.com) - 功能标志安全、A/B测试、分析以及应用程序配置功能。支持Git风格的版本控制，以及同步、内存中的本地标志评估。最多支持5名团队成员使用，功能标志和A/B测试数量不受限制。  * [Statsig](https://www.statsig.com) - 一个功能强大的平台，适用于功能管理、A/B测试、数据分析等场景。其免费的套餐提供无限数量的席位、标志、实验以及动态配置，每月最多支持100万次事件记录。
  * [Toggled.dev](https://www.toggled.dev) - 适用于企业级应用的、可扩展的多地区功能开关管理平台。免费套餐支持最多10个标志、两种环境，且请求数量无限制。免费套餐包含SDK、分析仪表板、发布日历、Slack通知以及所有其他功能。


**[⬆️ 返回顶部](#目录)

## 字体

  * [Befonts](https://befonts.com/) - 提供多种独特的字体，适用于个人或商业用途。
  * [Bunny](https://fonts.bunny.net) - 注重隐私保护的Google字体。
  * [dafont](https://www.dafont.com/) - 本网站上使用的字体属于其作者所有，可能是免费软件、共享软件、演示版本，或是公共领域字体。  * [Everything Fonts](https://everythingfonts.com/) - 提供多种工具，包括 @font-face、Units Converter、Font Hinter 和 Font Submitter。
  * [Font of web](https://fontofweb.com/) - 可识别网站上使用的所有字体及其使用方式。
  * [Font Squirrel](https://www.fontsquirrel.com/) - 提供免费字体，适用于商业用途。这些字体经过精心挑选，并以易于使用的格式呈现。
  * [FontGet](https://www.fontget.com/) - 提供多种可下载的字体，并附有标签，方便用户查找。
  * [fonts.xz.style](https://fonts.xz.style/) - 提供免费且开源的服务，可通过 CSS 将字体族传递给网站。
  * [Fontsensei](https://fontsensei.com/) - 提供由用户标记的开源 Google 字体，包含 CJK（中文、日文、韩文）字体标签。
  * [Fontshare](https://www.fontshare.com/) - 提供免费的字体服务。该平台拥有大量专业级字体，完全适用于个人和商业用途。* [Google Fonts](https://fonts.google.com/) – 许多免费字体可以通过下载或链接到Google的CDN轻松快速地应用于网站。

**[返回顶部](#目录)

## 表单

* [FabForm](https://fabform.io/) – 适用于智能开发者的表单后端平台。免费计划每月允许提交250个表单。拥有友好的现代图形用户界面。可集成到Google Sheets、Airtable、Slack、电子邮件等工具中。
* [Feathery](https://feathery.io) – 功能强大、易于使用的表单构建工具。可用于构建注册、登录、用户引导、支付流程、复杂的财务应用程序等。免费计划每月最多允许提交250个表单，并支持五个活跃的表单。
* [feedback.fish](https://feedback.fish/) – 免费计划允许收集总共25份反馈意见。可以轻松地与React和Vue组件集成。* [Form.taxi](https://form.taxi/) — 用于HTML表单提交的端点。具备通知功能、垃圾邮件拦截功能，并且符合GDPR数据处理规范。基础使用计划免费。
* [Formcarry.com](https://formcarry.com) — HTTP POST表单端点。免费计划允许每月提交100份表单。
* [Formester.com](https://formester.com) — 可在网站上分享和嵌入外观独特的表单。无需限制创建的表单数量或功能使用。每月可免费提交多达100份表单。
* [FormKeep.com](https://www.formkeep.com/) — 无限数量的表单，每月可提交50份表单。具备垃圾邮件防护、电子邮件通知功能，还拥有可导出HTML的拖放设计工具。其他功能包括自定义字段规则、团队功能，以及与Google Sheets、Slack、ActiveCampaign和Zapier的集成。
* [formlets.com](https://formlets.com/) — 在线表单服务，每月可创建无限数量的单页表单，每月可提交100份表单，并提供电子邮件通知功能。* [forms.app](https://forms.app/) — 创建具有强大功能的在线表单，如条件逻辑、自动评分计算器以及人工智能功能。免费计划可收集多达100份反馈，可将表单嵌入到网站中，或通过链接使用表单。

* [formspark.io](https://formspark.io/) — 表单到电子邮件的服务，免费计划支持无限数量的表单，每月最多可提交250份反馈，并配有客户支持团队提供协助。

* [Formspree.io](https://formspree.io/) — 通过HTTP POST请求发送电子邮件。免费计划每月每个表单最多可提交50份反馈。

* [Formsubmit.co](https://formsubmit.co/) — 为您的HTML表单提供简单的表单端点功能。完全免费，无需注册。

* [HeroTofu.com](https://herotofu.com/) — 具有机器人检测和加密归档功能的表单后端服务。可通过用户界面将反馈转发到电子邮件、Slack或Zapier。可以使用自己的前端界面，无需编写服务器代码。免费计划支持无限数量的表单，每月最多可提交100份反馈。  * [HeyForm.net](https://heyform.net/) - 在线表单构建工具。免费版允许您创建无限数量的表单，并收集无限数量的提交数据。该工具提供预构建的模板、反垃圾功能以及100MB的文件存储空间。
  * [Kwes.io](https://kwes.io/) - 功能丰富的表单接口。非常适合与静态网站结合使用。免费计划允许在一个网站中创建一个表单，每月最多可收集50个提交数据。
  * [Pageclip](https://pageclip.co/) - 免费计划仅允许一个网站、一个表单，每月最多可收集1,000个提交数据。
  * [SimplePDF.eu](https://simplepdf.eu/embed) - 可将PDF编辑器嵌入到您的网站上，并将任何PDF文件转换为可填写的表单。免费计划允许无限数量的PDF文件，每个PDF文件每月最多可提交3次。
  * [smartforms.dev](https://smartforms.dev/) - 功能强大且易于使用的表单后端。永久免费计划允许每月最多提交50次数据，具有250MB的文件存储空间、Zapier集成、CSV/JSON导出功能、自定义重定向、自定义响应页面、Telegram和Slack机器人功能以及单邮件通知功能。  * [staticforms.xyz](https://www.staticforms.xyz/) — 无需任何服务器端代码，即可轻松集成HTML表单。用户提交表单后，会向您的注册地址发送包含表单内容的电子邮件。
  * [Survicate](https://survicate.com/) — 通过一个工具，从各种来源收集反馈并发送后续调查。系统能够自动分析反馈并提取洞察力。提供免费电子邮件、网站调查、应用内或移动端调查、AI调查创建工具，以及每月25次调查机会。
  * [Tally.so](https://tally.so/) — 所有功能中有99%都是免费的。免费版允许您创建无限数量的表单、无限次提交表单、接收电子邮件通知、设置表单逻辑、收集付款、上传文件、自定义感谢页面等更多功能。
  * [Typeform.com](https://www.typeform.com/) — 可在网站上添加设计精美的表单。免费计划每个表单最多只能包含10个字段，并且每月只能进行100次调查。  * [Vidhook](https://vidhook.io/) - 通过设计精美的调查问卷收集反馈，响应率很高。免费计划包含1个活跃的调查问卷，每个调查问卷可接收25条回复，并且支持自定义模板。
  * [WaiverStevie.com](https://waiverstevie.com) - 带有REST API的电子签名平台。可以通过Web钩子接收通知。免费计划下，签名后的文档会带有水印，但允许无限数量的信封和签名。
  * [Web3Forms](https://web3forms.com) - 适用于静态网站和JAMStack网站的联系方式表单，无需编写后端代码。免费计划支持无限数量的表单、无限数量的域名，以及每月250次提交。
  * [Wufoo](https://www.wufoo.com/) - 可在网站上快速创建表单的工具。免费计划每月提交次数有限，为100次。

**[⬆️ 返回顶部](#目录)

## 生成式AI* [Arize AX](https://arize.com) - 一款AI工程平台，帮助AI工程师/项目经理评估并监控AI应用程序和智能体。该平台内置了Alyx智能体。免费套餐包含25,000次评估次数，每月数据摄取量为1GB。
* [Audio Enhancer](https://voice-clone.org/tools/audio-enhancer) - 一款由AI驱动的音频增强SaaS工具，能够去除噪音和回声，同时保留自然的语音清晰度。完全免费：无限次一键式增强功能，无需登录，支持MP3/WAV/FLAC格式。
* [Braintrust](https://www.braintrustdata.com/) - 用于评估、提示生成和数据管理的平台，专为通用人工智能设计。免费计划可每周进行多达1,000次私有评估。
* [Clair](https://askclair.ai/) - 临床AI参考工具。用户可免费使用专业工具套件，包括Open Search、临床总结、医学评论、药物相互作用分析、ICD-10编码以及管理功能。此外，该平台还提供专业套件的免费试用版。  * [Comet Opik](https://www.comet.com/site/products/opik/) - 可在开发周期和生产环境中评估、测试并部署大语言模型应用。 [#opensource](https://github.com/comet-ml/opik/)
  * [Keywords AI](https://keywordsai.co) - 最佳的大语言模型监控平台。只需两行代码即可调用200多个大语言模型。每月可免费使用10,000次请求，平台功能完全免费！
  * [Langfuse](https://langfuse.com/) - 开源的大语言模型工程平台，帮助团队协作调试、分析并改进大语言模型应用。永久免费计划包含每月5万次观测操作以及所有平台功能。 [#opensource](https://github.com/langfuse/langfuse)  * [Langtrace](https://langtrace.ai) - 为开发者提供追踪、评估、管理提示词和数据集的功能，并解决与大型语言模型应用性能相关的问题。它为任何大型语言模型生成开放的遥测标准追踪数据，有助于观察系统的运行状况，并可与任何观察性客户端配合使用。免费计划每月提供50,000条追踪数据。
  * [LangWatch](https://langwatch.ai) - 一款LLMOps平台，帮助AI团队测量、监控和优化大型语言模型应用，以提高可靠性、成本效益和性能。凭借强大的DSPy组件，我们能够实现工程师与非技术团队之间的无缝协作，从而完善和投产生成式人工智能产品。免费计划包含所有平台功能，每月可生成1,000条追踪数据，并拥有1个工作流程的DSPy优化工具。 [#opensource](https://github.com/langwatch/langwatch)  * [Mediaworkbench.ai](https://mediaworkbench.ai) - MediaWorkbench.ai为Azure OpenAI、DeepSeek和Google Gemini模型提供100,000个免费词汇，使用户能够使用强大的工具进行代码生成、深度研究以及图像创作。
  * [OpenRouter](https://openrouter.ai/models?q=free) - 提供多种免费AI模型，包括DeepSeek R1、V3、Llama和Moonshot AI等。这些模型在自然语言处理方面表现出色，适用于各种开发需求。需要注意的是，虽然这些模型可以免费使用，但会受到速率限制。此外，OpenRouter还提供付费模型，以满足更高级的需求，例如Claude、OpenAI、Grok、Gemini和Nova等。* [Othor AI](https://othor.ai/) – 一种基于人工智能的、快速、简单且安全的商业智能解决方案替代方案，可替代像 Tableau、Power BI 和 Looker 这样的流行商业智能工具。Othor 利用大型语言模型，在几分钟内就能提供定制化的商业智能解决方案。免费 forever 计划提供一个工作区，每个用户可连接五个数据源，且分析功能没有限制。[#开源项目](https://github.com/othorai/othor.ai)

* [Pollinations.AI](https://pollinations.ai/) – 易于使用的免费图像生成人工智能工具，提供免费 API。无需注册或获取 API 密钥，并且有多种方式可以将其集成到网站或工作流程中。[#开源项目](https://github.com/pollinations/pollinations)

* [Portkey](https://portkey.ai/) – 用于 Gen AI 应用程序的控制面板，包含可观察性套件和人工智能网关。每月可免费发送和记录多达 10,000 个请求。  * [ReportGPT](https://ReportGPT.app) - 由人工智能驱动的写作助手。只要您提供自己的API密钥，整个平台都是免费的。
  * [Zenable](https://zenable.io) - 能够自动修复来自Cursor、Windsurf和Copilot等工具的输出结果，以符合您公司的质量和合规标准。免费级别包括每天向MCP服务器调用100个工具，以及每天通过GitHub应用程序进行25次免费自动化拉取请求审核。

**[⬆️ 返回顶部](#目录)

## 内容分发网络与保护

  * [bootstrapcdn.com](https://www.bootstrapcdn.com/) — 用于bootstrap、bootswatch和fontawesome.io的内容分发网络
  * [CacheFly](https://portal.cachefly.com/signup/free2023) - 每月最多可使用5TB的免费内容分发网络流量，包含19个核心网站、1个域名以及通用SSL支持。  * [cdnjs.com](https://cdnjs.com/) — 简洁、快速、可靠的内容分发服务。cdnjs是一项免费且开源的内容分发服务，被超过11%的网站所信赖，由Cloudflare提供技术支持。
  * [developers.google.com/speed/libraries/](https://developers.google.com/speed/libraries/) — Google托管库库是一项针对最受欢迎的开源JavaScript库的内容分发服务。
  * [Gcore](https://gcorelabs.com/) — 全球内容分发服务网络，每月提供1TB的数据流量和1百万次免费请求，同时提供免费的DNS服务。
  * [jsdelivr.com](https://www.jsdelivr.com/) — 免费、快速且可靠的开源内容分发服务。支持npm、GitHub、WordPress、Deno等平台。
  * [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — Microsoft Ajax内容分发服务为诸如jQuery这样的第三方JavaScript库提供托管服务，使您能够轻松地将这些库添加到您的Web应用程序中。  * [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) — 免费DDoS防护服务  
  * [ovh.ie](https://www.ovh.ie/ssl-gateway/) — 提供免费DDoS防护和SSL证书  
  * [PromoProxy](https://promoproxy.net/) — 免费云安全Web代理服务。免费计划支持最多5个用户，每日流量限制为1GB。  
  * [raw.githack.com](https://raw.githack.com/) — 是**rawgit.com**的现代替代方案，仅通过Cloudflare进行文件托管。  
  * [Skypack](https://www.skypack.dev/) — 100%原生ES Module JavaScript内容分发网络。每个域名每月免费调用次数上限为100万次。  
  * [statically.io](https://statically.io/) — 为Git仓库（GitHub、GitLab、Bitbucket）、WordPress相关资源以及图片提供内容分发服务。  
  * [Stellate](https://stellate.co/) — 速度极快且可靠的GraphQL API内容分发网络，两项服务均可免费使用。  
  * [toranproxy.com](https://toranproxy.com/) — 为Packagist和GitHub提供代理服务。个人使用或单个开发者使用均可免费，但不支持技术支持。  * [UNPKG](https://unpkg.com/) — npm上所有资源的CDN服务
  * [weserv](https://images.weserv.nl/) — 图像缓存与调整大小服务。通过全球缓存快速处理图像。

**[⬆️ 返回顶部](#目录)

## PaaS

  * [ampt.dev](https://getampt.com/) - Ampt让团队能够在AWS上构建、部署和扩展JavaScript应用程序，而无需复杂的配置或管理基础设施。免费预览计划包含每小时500次调用、每天2,500次调用以及每月50,000次调用。仅付费计划允许使用自定义域名。
  * [anvil.works](https://anvil.works) - 仅使用Python进行Web应用开发。免费计划允许无限次应用运行，且存在30秒的超时时间限制。
  * [Apply.build](https://apply.build/) — 免费构建和部署您的GitHub应用，使用0.5个CPU核心/512 MiB内存，使用欧洲服务器，具备自动防火墙功能，以及实时性能监测功能。支持运行Node.js、Python、Go、Java、静态网站、微服务等。  * [AppWrite](https://appwrite.io) - 无限项目数量，无需暂停项目（支持websockets）以及身份验证服务。免费版中每个项目可拥有1个数据库、3个数据桶以及5个函数。
  * [Choreo](https://wso2.com/choreo/) - 基于AI的内置开发平台服务。免费版最多可创建5个组件，并每月提供100美元信用额度。
  * [CodenameOne.com](https://www.codenameone.com/) — 开源的跨平台移动应用开发工具链，适用于Java/Kotlin开发者。商业用途免费使用，项目数量不受限制。
  * [Daestro](https://daestro.com) - 可在云服务提供商和本地环境中运行计算任务。免费版最多可同时运行10个任务、2个计算资源、自托管的计算环境、1个云服务提供商、1个容器注册表以及1个定时任务。  * [Deno Deploy](https://deno.com/deploy) - 一种分布式系统，可在全球边缘环境中运行JavaScript、TypeScript和WebAssembly。免费套餐包含每天100,000次请求以及每月100 GiB的数据传输额度。
  * [domcloud.co](https://domcloud.co) – 提供Linux主机服务，支持与GitHub、SSH以及MariaDB/Postgres数据库结合的CI/CD流程。免费版本每月有1 GB的存储空间和1 GB的网络带宽限制，且仅支持免费域名。
  * [encore.dev](https://encore.dev/) — 采用静态分析技术的后端框架，提供自动化的基础设施、无需编写样板代码的解决方案等。为爱好项目提供免费的云主机服务。
  * [flightcontrol.dev](https://flightcontrol.dev/) - 允许用户通过Git推送方式在自己的AWS账户上部署Web服务、数据库等。对于拥有1名开发人员的用户，在个人GitHub仓库上可以免费使用服务。AWS的收费通过AWS进行结算，但用户可以同时使用积分和AWS的免费套餐。  * [gigalixir.com](https://gigalixir.com/) - Gigalixir提供一款免费的实例，该实例永不休眠，还提供免费的PostgreSQL数据库，限制为2个连接、10,000行数据，且不支持Elixir/Phoenix应用程序的备份功能。
  * [Koyeb](https://www.koyeb.com) - Koyeb是一个面向开发者的无服务器平台，可帮助在全球范围内部署应用程序。能够无缝运行Docker容器、Web应用程序和API，采用基于Git的部署方式，具备原生自动扩展功能、全球边缘网络，以及内置的服务网格和发现机制。免费实例允许您在德国法兰克福或美国华盛顿特区部署Web服务。提供免费的托管Postgres数据库，适用于德国法兰克福、美国华盛顿特区以及新加坡地区。内存512MB、存储2GB、CPU性能0.1。
  * [leapcell](https://leapcell.io/) - Leapcell是一个可靠的分布式应用平台，提供一切所需的功能，以支持您的快速成长。免费计划包含100k次服务调用、10k个异步任务以及100k条Redis命令。  * [Northflank](https://northflank.com) — 通过强大的用户界面、API和命令行工具，构建和部署微服务、作业以及托管数据库。可以从版本控制系统和外部Docker注册表中无缝扩展容器。免费套餐包含两项服务、两个定时任务和1个数据库。
  * [pipedream.com](https://pipedream.com) - 为开发者打造的集成平台。可以根据任何触发器开发任何工作流程。这些工作流程是你可以[免费](https://docs.pipedream.com/pricing/)运行的代码。无需管理服务器或云资源。
  * [Railway](https://railway.app/) - 通过基于Git的部署、自动CI/CD以及内置数据库来部署任何项目。免费套餐每月包含5美元的积分。
  * [pythonanywhere.com](https://www.pythonanywhere.com/) — 云端的Python应用托管服务。初学者账户是免费的，可创建1个Python Web应用，存储路径为your-username.pythonanywhere.com，拥有512MB的私有文件存储空间和1个MySQL数据库。  * [WunderGraph](https://cloud.wundergraph.com) - 一个开源平台，可让您快速构建、发布和管理现代API。内置的CI/CD功能、GitHub集成以及自动HTTPS配置。[免费计划](https://wundergraph.com/pricing)下，最多可管理3个项目，每月外链流量不超过1GB，构建时间不超过300分钟。
  * [YepCode](https://yepcode.io) - 一个一体化平台，用于在无服务器环境中连接API和服务。它带来了NoCode工具的所有灵活性和优势，同时具备使用编程语言的所有功能。免费级别包含[1,000个yeps](https://yepcode.io/pricing/)。
  * [Zeabur](https://zeabur.com) - 一键部署您的服务。三个服务免费使用，每月可免费使用5美元信用额度。

**[⬆️ 返回顶部](#目录)

## 企业服务  * [Activepieces](https://www.activepieces.com) - 用于构建自动化流程，以便在应用程序的后端将多个应用程序连接在一起。例如，在应用程序中发生某个事件时，可以发送Slack消息或添加Google Sheet行。每月最多可免费处理5,000个任务。
  * [back4app.com](https://www.back4app.com) - Back4App是一个易于使用、灵活且可扩展的后端服务，基于Parse平台构建。
  * [backendless.com](https://backendless.com/) — 移动和Web后端服务，提供1GB的文件存储免费使用权限，每月可发送50,000条推送通知，并且支持在表中存储1000个数据对象。
  * [bismuth.cloud](https://www.bismuth.cloud/) — 我们的AI技术将在我们的函数运行环境和托管存储中支持您的Python API，您可以在我们的在线编辑器中进行免费构建和托管，或者选择使用您喜欢的工具进行本地构建。  * [Claw.cloud](https://run.claw.cloud) - 一个PaaS平台，为拥有超过180天有效期的GitHub账户的用户提供每月5美元的免费额度。非常适合托管应用程序、数据库等。([使用免费额度的注册链接](https://ap-southeast-1.run.claw.cloud/signin))。
  * [connectycube.com](https://connectycube.com) - 无限聊天消息、点对点语音和视频通话、文件附件以及推送通知功能。适用于最多1000用户的项目，免费使用。
  * [convex.dev](https://convex.dev/) - 响应式后端服务，可托管您的数据（具有关系性的文档以及可序列化的ACID事务），无服务器函数，以及用于向各种客户端传输更新的WebSockets。适用于小型项目，最多支持100万条记录，每月可调用500万次函数。* [ETLR](https://etlr.io) – 使用 YAML 定义、版本控制及部署自动化脚本。这是专为开发者设计的、替代拖放工具的解决方案。可用于定时任务、AI 代理以及基础设施监控。免费套餐每月包含 100 个积分。*
* [Flutter Flow](https://flutterflow.io) – 无需编写一行代码即可构建 Flutter 应用界面。同时支持 Firebase 集成。免费计划包含完整的 UI 构建工具和免费模板。*
* [getstream.io](https://getstream.io/) – 在几小时内即可构建可扩展的应用内聊天、消息传递、视频及音频功能，而无需花费数周时间。*
* [IFTTT](https://ifttt.com) – 自动化你喜爱的应用程序和设备操作。免费提供 2 个应用程序。*
* [Integrately](https://integrately.com) – 只需一次点击即可自动化繁琐任务。免费提供 100 个任务，时长 15 分钟。*  * [LeanCloud](https://leancloud.app/) — 移动端后端服务。提供1GB的数据存储空间、256MB的实例资源，每天可处理3K个API请求，并且每天可发送10K条推送消息。其API功能与Parse平台非常相似。
  * [nhost.io](https://nhost.io) — 适用于网页和移动应用的无服务器后端服务。免费套餐包含PostgreSQL、GraphQL（Hasura）、身份验证、存储功能以及无服务器函数。
  * [onesignal.com](https://onesignal.com/) — 提供无限量的免费推送通知服务。每月可发送10,000封电子邮件，支持无限数量的联系人，并且可以访问自动预热功能。
  * [paraio.com](https://paraio.com) — 后端服务API，具备灵活的身份验证、全文搜索和缓存功能。仅适用于一个应用程序，提供1GB的应用数据存储空间。
  * [pubnub.com](https://www.pubnub.com/) — 提供每月最多1百万条消息的免费推送通知服务，同时支持100个活跃的设备。
  * [pushbots.com](https://pushbots.com/) — 推送通知服务。每月最多可发送1.5百万条推送消息，且免费使用。  * [pusher.com](https://pusher.com/beams) — 为2000名月活跃用户提供免费、无限制的推送通知服务。适用于iOS和Android设备的单一API。
  * [simperium.com](https://simperium.com/) — 可即时自动将数据传输至任何地方，支持多平台，可无限发送和存储结构化数据，每月最多支持2,500名用户。
  * [Supabase](https://supabase.com) — 开源版的Firebase解决方案，用于构建后端服务。免费计划包含身份验证、实时数据库和对象存储功能。
  * [tyk.io](https://tyk.io/) — 提供API管理、身份验证、配额管理、监控与分析功能。提供免费云服务。
  * [zapier.com](https://zapier.com/) — 可连接您使用的应用程序，实现任务自动化。每15分钟自动执行一次任务，每月可执行100个任务。
  更新时间、五个活跃自动化任务、Web钩子功能。

**[⬆️ 返回目录顶部](#table-of-contents)**

## 低代码平台  * [AppSmith](https://www.appsmith.com/) — 一款低代码项目，用于构建管理面板、内部工具和仪表板。可集成15个以上的数据库以及任何API。
  * [BudiBase](https://budibase.com/) — Budibase是一个开源的低代码平台，可快速创建内部应用程序。支持PostgreSQL、MySQL、MSSQL、MongoDB、REST API、Docker、K8s等数据库。
  * [Clappia](https://www.clappia.com) — 一款低代码平台，专为构建业务流程应用程序而设计，支持可自定义的移动端和网页应用。提供拖放界面，具备离线支持、实时位置跟踪等功能，并可与各种第三方服务集成。
  * [Lil Bots](https://www.lilbots.io/) — 在线编写和运行脚本的平台，利用诸如OpenAI、Anthropic、Firecrawl等内置API。非常适合构建AI代理/内部工具，并可与团队共享。免费套餐包含完整的API访问权限、AI编码助手以及每月10,000次执行额度。  * [manubes](https://www.manubes.com) - 强大的无代码云平台，专注于工业生产管理。每月限一个用户使用，每月可处理100万条工作流操作（[德语版本也可提供](https://www.manubes.de)）。
  * [Mendix](https://www.mendix.com/) — 企业级快速应用开发平台，提供无限访问的沙盒环境，支持无限用户数、0.5GB存储空间和每个应用程序1GB内存。免费版还支持使用Studio和Studio Pro开发环境。
  * [outsystems.com](https://www.outsystems.com/) — 企业级Web开发PaaS平台，适用于本地或云环境，免费提供的“个人环境”允许无限代码编写和高达1GB的数据库空间。
  * [ReTool](https://retool.com/) — 用于构建内部应用的低代码平台。ReTool具有极高的可定制性。如果你能用JavaScript和API编写代码，那么就可以在ReTool中实现。免费版每月允许最多5个用户使用，并支持无限的应用程序与API连接。* [ToolJet](https://www.tooljet.com/) — 可扩展的低代码框架，用于构建商业应用程序。可以连接数据库、云存储、GraphQL、API端点、Airtable等，并通过拖放式应用程序构建工具来创建应用程序。
* [UI Bakery](https://uibakery.io) — 低代码平台，可更快地构建自定义Web应用程序。支持通过JavaScript、Python和SQL进行拖放式UI构建，具有高度的定制性。提供云部署和自托管解决方案。最多5个用户可免费使用。

**[⬆️ 返回顶部](#目录)

## 网站托管

* [Alwaysdata](https://www.alwaysdata.com/) — 提供1GB免费网站托管服务，支持MySQL、PostgreSQL、RabbitMQ、.NET、Deno、Elixir、Go、Java、Lua、Node.js、PHP、Python、Ruby、Rust等数据库。可自定义Web服务器，通过FTP、WebDAV和SSH访问。包含邮箱、邮件列表和应用程序安装工具。免费计划不支持自定义域名。  * [Awardspace.com](https://www.awardspace.com) — 免费网络托管服务，附带一个免费的短域名、PHP、MySQL功能、应用程序安装器、邮件发送功能，且无广告。
  * [Bubble](https://bubble.io/) — 无需编写代码即可构建网页和移动应用程序的可视化编程工具，使用Bubble品牌标识，免费使用。
  * [dAppling Network](https://www.dappling.network/) — 去中心化的网络托管平台，专注于提高网站的运行时间和安全性，为用户提供额外的访问点。
  * [DigitalOcean](https://www.digitalocean.com/pricing) — 在App Platform Starter层免费构建和部署三个静态网站。
  * [FreeFlarum](https://freeflarum.com/) — 由社区参与的免费Flarum托管服务，最多支持250个用户（捐赠后可去除页脚中的水印）。
  * [Kinsta静态网站托管](https://kinsta.com/static-site-hosting/) — 免费托管最多100个静态网站，提供自定义域名、SSL安全连接、每月100GB的带宽，以及260多个Cloudflare CDN位置。  * [MDB GO](https://mdbgo.com/) – 为单个项目提供免费托管服务，容器 TTL 为两周，每个项目可使用的内存为 500 MB，SFTP 支持，磁盘空间为 1GB。
  * [Neocities](https://neocities.org) – 静态网站托管服务，免费存储空间为 1GB，带宽达 200GB。
  * [Netlify](https://www.netlify.com/) – 为静态网站和应用程序提供免费构建、部署和托管服务，每月可获取 300 个积分（相当于 30GB 的带宽）。
  * [Oaysus](https://oaysus.com) – 为开发者提供的可视化页面构建工具，支持 React、Vue 或 Svelte 组件。免费套餐包括一个网站，可创建无限数量的页面、处理表单提交，并拥有全球内容分发网络托管服务。
  * [PandaStack](https://www.pandastack.io/) – 为开发者提供完整的生态系统，包括不同格式的网站托管服务（静态网站托管、基于容器的网站托管、WordPress 托管等，只需几次点击即可完成）。提供一个免费网站托管服务（静态或基于容器的），以及一个免费数据库，带有的带宽为 100GB，每月构建时间限制为 300分钟。  * [pantheon.io](https://pantheon.io/) — 提供 Drupal 和 WordPress 的托管服务，采用自动化的 DevOps 流程，具备可扩展的基础设施。开发者及代理机构均可免费使用，无需自定义域名。
  * [Qoddi](https://qoddi.com) — 提供类似 Heroku 的 PaaS 服务，以开发者为中心的设计和全面的功能。适用于静态资源、测试环境以及开发者应用程序的免费套餐。
  * [readthedocs.org](https://readthedocs.org/) — 提供免费的文件托管服务，包含版本控制、PDF 生成等功能。
  * [render.com](https://render.com) — 提供统一的云服务平台，用于构建和运行应用程序和网站。提供免费的 SSL 证书、全球内容分发网络、私有网络、基于 Git 的自动部署功能，以及完全免费的 Web 服务、数据库和静态网页服务。  * [Serv00.com](https://serv00.com/) — 提供3GB的免费网站托管服务，包含每日备份功能（支持7天）。支持Crontab任务、SSH访问、仓库管理（GIT、SVN和Mercurial），并支持MySQL、PostgreSQL、MongoDB、PHP、Node.js、Python、Ruby、Java、Perl、TCL/TK、Lua、Erlang、Rust、Pascal、C、C++、D、R等多种编程语言。
  * [SourceForge](https://sourceforge.net/) — 免费查找、创建和发布开源软件。
  * [surge.sh](https://surge.sh/) — 为前端开发者提供静态网站发布服务。支持无限数量的网站，并支持自定义域名。
  * [tilda.cc](https://tilda.cc/) — 一个网站，50个页面，50MB的存储空间。仅提供预定义的模块，没有字体、图标以及自定义域名的功能。
  * [Vercel](https://vercel.com/) — 用于构建、部署和托管Web应用程序的工具。提供免费的SSL证书、全球CDN服务，每次执行`git push`时都会生成唯一的预览URL。非常适合Next.js和其他静态网站生成器。* [Versoly](https://versoly.com/) —— 以SaaS模式运营的网站构建工具，提供无限数量的网站创建选项、70多种模板、自定义CSS、Favicon、SEO功能以及表单功能。无需使用自定义域名。*

**[⬆️ 返回目录顶部](#目录内容)**

## DNS

* [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/) —— 由Cloudflare提供的免费公共DNS解析器，速度快且安全（会加密您的DNS查询）。可用于绕过互联网提供商的DNS封锁、防止DNS查询被监视，以及[屏蔽成人内容和恶意软件内容](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families)。还可以通过API使用：[https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests)。注意：仅提供DNS解析服务，而非DNS主机服务。
* [1984.is](https://www.1984.is/product/freedns/) —— 提供免费的DNS服务，包含API和其他多种免费DNS功能。
* [cloudns.net](https://www.cloudns.net/) —— 提供免费DNS服务，最多可托管1个域名，并支持50条记录。  * [deSEC](https://desec.io) - 提供免费DNS托管服务，支持API接口，注重安全性。基于开源软件运行，并由[SSE](https://www.securesystems.de/)提供支持。
  * [dns.he.net](https://dns.he.net/) — 提供免费DNS托管服务，支持动态DNS功能。
  * [dnspod.com](https://www.dnspod.com/) — 提供免费DNS托管服务。
  * [duckdns.org](https://www.duckdns.org/) — 提供免费DDNS服务，在免费套餐下最多可支持5个域名。提供多种配置指南，方便用户进行设置。
  * [Dynv6.com](https://dynv6.com/) — 提供免费DDNS服务，支持[API接口](https://dynv6.com/docs/apis)，并能够管理多种DNS记录类型（如CNAME、MX、SPF、SRV、TXT等）。
  * [freedns.afraid.org](https://freedns.afraid.org/) — 提供免费DNS托管服务。此外，还提供基于众多公共用户[贡献的域名](https://freedns.afraid.org/domain/registry/)的免费子域名。注册后可通过“子域名”菜单获取免费子域名。  * [Glauca](https://docs.glauca.digital/hexdns/) – 提供免费DNS托管服务，支持最多3个域名，并具备DNSSEC功能。
  * [Hetzner](https://www.hetzner.com/dns-console) – Hetzner提供的免费DNS托管服务，支持API接口。
  * [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) – 由华为提供的免费DNS托管服务。
  * [LocalCert](https://localcert.net) – 提供免费的`.localcert.net`子域名服务，可与公共CA证书兼容，适用于私有网络环境。
  * [luadns.com](https://www.luadns.com/) – 提供免费DNS托管服务，支持3个域名，各项功能齐全，且限制较为合理。
  * [namecheap.com](https://www.namecheap.com/domains/freedns/) – 提供免费DNS服务，对域名数量无限制。
  * [nextdns.io](https://nextdns.io) – 提供基于DNS的防火墙服务，每月可免费查询30万次。
  * [noip.at](https://noip.at/) – 提供免费的DDNS服务，无需注册、跟踪、日志记录或广告推送，对域名数量也无限制。  * [noip](https://www.noip.com/) — 一种动态DNS服务，最多可免费使用3个主机名，且每30天需要确认一次。
  * [sslip.io](https://sslip.io/) — 免费DNS服务，当查询带有嵌入式IP地址的主机名时，会返回该IP地址。
  * [VolaryDDNS](https://volaryddns.net) — 免费且性能高的DDNS服务，无需订阅或广告。
  * [zilore.com](https://zilore.com/en/dns) — 为5个域名提供免费DNS托管服务。
  * [zoneedit.com](https://www.zoneedit.com/free-dns/) — 提供免费DNS托管服务，并支持动态DNS功能。
  * [Zonomi](https://zonomi.com/) — 提供免费DNS托管服务，并具备即时DNS传播功能。免费方案：最多支持1个DNS区域（域名），并包含最多10条DNS记录。

**[⬆️ 返回顶部](#目录内容)**

## 域名

  * [DigitalPlat](https://domain.digitalplat.org) — 提供免费子域名服务。
  * [pp.ua](https://nic.ua/) — 提供免费的pp.ua子域名服务。

**[⬆️ 返回顶部](#目录内容)**

## 基础设施即服务 (IaaS)* [4EVERLAND](https://www.4everland.org/) — 与AWS S3的API、接口操作、CLI以及其他上传方式兼容。能够安全、便捷且高效地上传和存储来自IPFS和Arweave网络的文件。注册用户可免费获得6GB的IPFS存储空间和300MB的Arweave存储空间。任何小于150KB的Arweave文件上传都是免费的。*
* [backblaze.com](https://www.backblaze.com/b2/) — Backblaze B2云存储服务。免费提供10GB的存储空间（类似Amazon S3），且无需限制使用时间。
* [C2 Object Storage](https://c2.synology.com/en-us/pricing/object-storage) — 支持S3协议的对象存储服务。免费提供15GB的存储空间，并且每月可免费下载15GB的数据。
* [filebase.com](https://filebase.com/) — 基于区块链技术的S3兼容对象存储服务。免费提供5GB的存储空间，使用期限无限制。

**[⬆️ 返回顶部](#目录)

## 托管数据服务  * [8base.com](https://www.8base.com/) - 8base是一个面向JavaScript开发者的全栈低代码开发平台，基于MySQL、GraphQL和无服务器后端服务构建。它允许您使用UI应用构建工具快速开始构建Web应用程序，并且可以迅速扩展。免费套餐包括：行数2,500条，存储空间500GB，无服务器计算能力1Gb/小时，客户端应用程序用户数5个。
  * [airtable.com](https://airtable.com/) — 看起来像电子表格，但实际上是一个关系型数据库平台，具有无限的行数限制，每基础行数1,200条，每月API请求次数1,000次。
  * [Aiven](https://aiven.io/) - Aiven在其开源数据平台上提供免费的PostgreSQL、MySQL和Valkey（兼容Redis）服务。单节点配置，1个CPU，1GB内存；对于PostgreSQL和MySQL，存储限制为1GB。易于迁移到更全面的服务或跨云部署。  * [CockroachDB Cloud](https://www.cockroachlabs.com/pricing/) — 免费套餐每月提供5000万请求单位以及10 GiB的存储空间（相当于15美元的优惠）。([关于请求单位的信息](https://www.cockroachlabs.com/docs/cockroachcloud/metrics-request-units.html))
  * [codehooks.io](https://codehooks.io/) — 易于使用的JavaScript服务器less API/后端服务以及NoSQL数据库服务，包含函数、类似MongoDB的查询功能、键/值查找、任务系统、实时消息传递、工作队列、强大的CLI界面以及基于Web的数据管理器。免费套餐提供5GB的存储空间，每分钟可调用60次API。包含2名开发者使用权限，无需信用卡信息。
  * [Couchbase Capella](https://www.couchbase.com/products/capella/) — 可部署永久免费套餐，提供完全管理的数据库集群，包含1个节点和8GB的存储空间。该数据库集群专为开发者设计，可用于开发从物联网到人工智能领域的新一代应用程序。  * [CrateDB](https://crate.io/) - 用于实时分析的分布式开源SQL数据库。[免费层CRFREE](https://crate.io/lp-crfree)：单节点配置，配备2个CPU、2 GiB内存和8 GiB存储空间。每个组织只能拥有一个集群，无需支付任何费用。
  * [filess.io](https://filess.io) - filess.io是一个平台，用户可以在该平台上免费创建两个数据库，每个数据库的最大容量可达10 MB。用户可以免费使用以下数据库管理系统：MySQL、MariaDB、MongoDB和PostgreSQL。
  * [InfluxDB](https://www.influxdata.com/) — 时间序列数据库。免费情况下，写入数据的上限为3 MB，写入时间为5分钟；读取数据的上限为30 MB，读取时间也为5分钟。此外，该数据库支持10,000种不同种类的数据表结构。
  * [MemCachier](https://www.memcachier.com/) — 托管的内存缓存服务。免费情况下，最大存储容量为25 MB，仅支持1个代理服务器，并提供基本的数据分析功能。
  * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) — 免费层可使用的内存容量为512 MB。  * [Neo4j Aura](https://neo4j.com/cloud/aura/) — 一种托管式的原生图数据库管理系统/分析平台，支持Cypher查询语言及REST API。对图结构的大小有限制：最多支持50,000个节点和175,000个关系。
  * [Neon](https://neon.tech/) — 托管式的PostgreSQL平台，总存储容量为0.5GB，可创建1个项目，支持10个分支，数据库数量无限制，主分支始终可用（5分钟后自动暂停），非主分支分支的活跃时间每月总计20小时。
  * [Nile](https://www.thenile.dev/) — 适用于B2B应用的Postgres平台。数据库数量无限制，始终可用且无需关闭服务器，总存储容量为1GB，可分配5000万个查询令牌，支持自动扩展，向量嵌入功能也无限制。
  * [Prisma Postgres](https://prisma.io/postgres) — 基于unikernel技术构建的超快速托管Postgres平台，运行在裸机上，存储容量为1GB，可管理10个数据库，与Prisma ORM集成。  * [restdb.io](https://restdb.io/) - 一款快速且简单的NoSQL云数据库服务。使用restdb.io，您可以享受模式设计、关系管理、自动REST API接口（支持类似MongoDB的查询功能），以及高效的多用户管理界面，方便数据操作。免费计划支持3个用户、2500条记录，以及每秒1次API请求。
  * [scalingo.com](https://scalingo.com/) — 主要提供PaaS服务，但提供128MB至192MB的免费MySQL、PostgreSQL或MongoDB存储空间。
  * [SeaTable](https://seatable.io/) — 由Seafile团队开发的灵活、类似电子表格的数据库。支持无限数量的表、2000行数据，具有1个月的版本管理功能，最多支持25个团队成员同时使用。
  * [skyvia.com](https://skyvia.com/) — Cloud Data Platform提供免费计划，所有计划在测试阶段都是完全免费的。  * [StackBy](https://stackby.com/) — 一款结合了电子表格的灵活性、数据库的强大功能，以及与您喜爱的商业应用程序的集成功能的工具。免费计划包含无限用户数、十个存储集，以及每个存储集2GB的附件空间。
  * [Tinybird](https://tinybird.co) — 一款基于服务器less技术的ClickHouse数据库服务，通过HTTP协议进行无连接的数据导入，并允许您将SQL查询作为管理的HTTP API进行发布。免费计划没有时间限制，包含10GB的存储空间，以及每天1000次API调用权限。
  * [Turso by ChiselStrike](https://chiselstrike.com/) — Turso是一款基于SQLite的边缘数据库服务。Turso提供永久免费的启动计划，总存储容量为9GB，最多支持500个数据库，最多支持3个位置，每月可处理10亿条记录，并提供基于SQLite的本地开发支持。
  * [Upstash](https://upstash.com/) — 一款基于服务器less技术的Redis数据库服务，免费计划下每月可执行多达50万条命令，数据库最大存储容量为256MB，同时支持20个并发连接。* [Xata Lite](https://lite.xata.io/) – Xata Lite是一款无服务器数据库，内置强大的搜索和分析功能。一个API接口，多种类型安全的客户端库，专为您的开发工作流程而优化。免费计划提供10个分支和15GB的存储空间，且不会中断服务或产生冷启动现象。

**[⬆️ 返回顶部](#目录)**

## 隧道传输、WebRTC、Web Socket服务器及其他路由器

* [btunnel](https://www.btunnel.in/)——将本地主机和本地TCP服务器暴露到互联网上。免费计划包含文件服务器、自定义HTTP请求和响应头、基本认证保护以及1小时的隧道超时时间。
* [cname.dev](https://cname.dev/)——免费且安全的动态反向代理服务。
* [conveyor.cloud](https://conveyor.cloud/)——Visual Studio扩展，可将IIS Express暴露到本地网络或通过隧道传输到公共URL。  * [Expose](https://expose.dev/) — 通过安全隧道公开本地服务器。免费计划包含欧盟服务器、随机子域名，以及单用户使用权限。
  * [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi是一种托管式VPN服务，可让您安全地将类似局域网的网络扩展到分布式团队。免费计划允许无限数量的网络成员，最多可达5人。
  * [Hookdeck](https://hookdeck.com/pricing) — 随时随地开发、测试和监控您的Web钩子。每月可处理10万次请求和10万次尝试，数据保留时间为三天。
  * [localhost.run](https://localhost.run/) — 通过隧道将本地运行的服务器公开到公共URL。
  * [localtunnel](https://theboroer.github.io/localtunnel-www/) — 通过隧道将本地运行的服务器公开到公共URL。提供免费托管版本，且为[开源项目](https://github.com/localtunnel/localtunnel)。  * [LocalXpose](https://localxpose.io) — 一款反向代理服务，可让您将本地服务器暴露到互联网上。免费计划的有效隧道时长为15分钟。
  * [ngrok.com](https://ngrok.com/) — 通过隧道将本地运行的服务器暴露到公共URL上。
  * [Pinggy](https://pinggy.io) — 通过单一命令即可为本地主机生成公共URL，无需下载。支持HTTPS、TCP和TLS隧道。免费计划的有效隧道时长为60分钟。
  * [Radmin VPN](https://www.radmin-vpn.com/) — 通过VPN将多台计算机连接在一起，形成类似局域网的网络。支持无限数量的连接伙伴。（相当于Hamachi的替代品）
  * [serveo](https://serveo.net/) — 将本地服务器暴露到互联网上。无需安装或注册。提供免费的子域，且无使用限制。
  * [stun:global.stun.twilio.com:3478?transport=udp](stun:global.stun.twilio.com:3478?transport=udp) — Twilio STUN服务
  * [stun:stun.l.google.com:19302](stun:stun.l.google.com:19302) — Google STUN服务  * [Tailscale](https://tailscale.com/) — 无需配置即可实现VPN连接，采用开源的WireGuard协议。适用于MacOS、iOS、Windows、Linux和Android设备。个人使用免费计划，支持100台设备和3个用户。
  * [webhookrelay.com](https://webhookrelay.com) — 可管理、调试、分派和代理所有Web钩子事件，可以将Web钩子事件发送到公共或内部目标（例如localhost）。此外，还可以通过获取公共HTTP端点，将运行在私有网络中的服务器暴露出来（`https://yoursubdomain.webrelay.io <----> http://localhost:8080`）。
  * [Xirsys](https://www.xirsys.com/pricing/) — 无限制的使用STUN功能，每月可使用的TURN带宽达到500MB，带宽上限为特定地理区域。
  * [ZeroTier](https://www.zerotier.com) — 基于开源技术的虚拟以太网服务。免费计划下可创建无限制端到端加密网络，最多支持25台客户端。提供适用于桌面/移动设备的客户端，以及用于配置自定义路由规则和批准私有网络中新客户端节点的Web界面。**[返回顶部](#table-of-contents)

## 问题跟踪与项目管理

  * [acunote.com](https://www.acunote.com/) — 适用于最多5名成员的项目管理和SCRUM工具
  * [asana.com](https://asana.com/) — 适用于与协作者合作的个人项目的免费服务
  * [Backlog](https://backlog.com) — 一个平台，可帮助您的团队在一个地方完成出色的项目。免费计划提供1个项目、10个用户以及100MB的存储空间
  * [Basecamp](https://basecamp.com/personal) - 用于任务列表、里程碑管理、类似论坛的消息传递、文件共享以及时间跟踪。最多支持3个项目、20个用户以及1GB的存储空间
  * [bitrix24.com](https://www.bitrix24.com/) — 用于内网和项目管理的工具。免费计划提供5GB存储空间，适用于无限个用户
  * [cacoo.com](https://cacoo.com/) — 在线实时图表工具：流程图、UML图、网络图等。免费情况下，最多支持15个用户/图表，以及25张图表模板  * [clickup.com](https://clickup.com/) — 项目管理工具。提供免费版和带云存储的付费版。支持移动应用和Git集成。
  * [Clockify](https://clockify.me) — 时间跟踪和工时报表应用程序，可跨项目记录工作时间。支持无限用户，永久免费使用。
  * [Cloudcraft](https://cloudcraft.co/) — 使用Cloudcraft可视化设计工具，可在几分钟内创建专业的架构图。针对AWS优化，包含智能组件，可实时显示数据。免费版支持单个用户使用，拥有无限数量的私有图稿。
  * [Confluence](https://www.atlassian.com/software/confluence) — Atlassian的内容协作工具，帮助团队高效协作和共享知识。免费版支持最多10个用户使用。
  * [Crosswork](https://crosswork.app/) — 多用途项目管理平台。免费版支持最多3个项目，支持无限用户，存储容量达1GB。  * [diagrams.net](https://app.diagrams.net/) — 在线图表工具，图表数据可本地存储在 Google Drive、OneDrive 或 Dropbox 中。所有功能及存储级别均免费使用。
  * [easyretro.io](https://www.easyretro.io/) — 简单且直观的迭代回顾工具。免费计划包含三个公共看板，每个看板每月可进行一次调查。
  * [freedcamp.com](https://freedcamp.com/) — 任务管理、讨论、里程碑跟踪、时间跟踪、日历、文件管理及密码管理器。免费计划支持无限项目、用户及文件存储。
  * [GForge](https://gforge.com) — 适用于复杂项目的项目管理与问题跟踪工具，提供自有服务器及 SaaS 版本。SaaS 免费计划适用于前五个用户，开源项目也可享受免费服务。
  * [gleek.io](https://www.gleek.io) — 开发者使用的免费描述到图表工具。可使用关键词创建非正式的 UML 类图、对象图或实体关系图。  * [GraphQL Inspector](https://github.com/marketplace/graphql-inspector) - GraphQL Inspector能够输出两个 GraphQL模式之间的变更列表。每个差异都得到了详细的说明，并标记为“破坏性”、“非破坏性”或“危险”。
  * [Helploom](https://helploom.com) - 一款客户支持软件，在免费永久计划下提供实时聊天功能。界面简单、轻量级且美观。安装过程只需简单的复制粘贴操作。该软件由一位开发者开发。
  * [Hygger](https://hygger.io) — 项目管理平台。免费计划支持无限用户、项目及看板，并拥有100MB的存储空间。
  * [Ilograph](https://www.ilograph.com/) — 交互式图表工具，允许用户从多个角度和细节级别查看他们的基础设施。图表可以用代码表示。免费级别允许无限数量的私密图表，最多可支持3位观众。  * [Jira](https://www.atlassian.com/software/jira) — 先进的软件开发项目管理工具，广泛应用于各种企业环境中。免费计划适用于最多10名用户。
  * [kan.bn](https://kan.bn/) - 功能强大、灵活多用的看板管理工具，可帮助您组织工作、跟踪进度并交付成果——所有功能都在一个平台上。免费计划适用于最多1名用户，可创建无限数量的工作板、列表和卡片。
  * [kanbanflow.com](https://kanbanflow.com/) — 基于看板的项目管理工具。免费版和高级版提供更多功能。
  * [kanbantool.com](https://kanbantool.com/) — 基于看板的项目管理工具。免费计划包含两个工作板以及两名用户，无需附加文件或附件。
  * [Kitemaker.co](https://kitemaker.co) - 在整个产品开发过程中进行协作，并通过Slack、Discord、Figma和GitHub等平台跟踪工作进度。支持无限用户和无限空间。免费计划最多可处理250个任务项。  * [Kiter.app](https://www.kiter.app/) - 让任何人都能组织他们的求职过程，并跟踪面试、机会和人际关系。功能强大的网页应用和Chrome扩展程序。完全免费。
  * [Kumu.io](https://kumu.io/) — 带有动画、装饰、滤镜、聚类、电子表格导入等功能的关系图谱工具。免费版允许无限数量的公开项目。图表大小无限制。学生可以使用免费私人项目。如果您不想让文件公开在线上，还可以选择使用沙盒模式（上传、编辑、下载、丢弃文件）。
  * [leiga.com](https://www.leiga.com/) — Leiga是一款SaaS产品，利用人工智能技术自动管理您的项目，帮助您的团队保持专注，释放巨大潜力，确保项目按计划进行。免费服务适用于最多10个用户，支持20个自定义字段，存储空间为2GB。AI录制的视频长度限制为5分钟，自动化操作的费用为20元/用户/月。  * [Linear](https://linear.app/) — 具有简洁界面的问题跟踪工具。免费使用，支持无限数量的成员，文件上传大小上限为10MB，可创建250个问题（不包括归档问题）。
  * [Lucidchart](https://www.lucidchart.com/) - 一款具有协作功能的在线图表工具。免费版包含三个可编辑文档、100种专业模板，以及基本的协作功能。
  * [MeisterTask](https://www.meistertask.com/) — 适用于团队的在线任务管理工具。免费使用，最多可创建3个项目，且项目成员数量不受限制。
  * [MeuScrum](https://www.meuscrum.com/en) - 免费的在线Scrum工具，包含看板功能。
  * [nTask](https://www.ntaskmanager.com/) — 项目管理软件，帮助团队进行协作、规划、分析以及管理日常任务。基础版免费使用，存储容量可达100MB，支持5个用户/团队。支持无限的工作空间、会议、任务、工时表以及问题跟踪功能。  * [Plane](https://plane.so/) – Plane是一个简单、可扩展且开源的项目和产品管理工具。免费使用，支持无限数量的成员，文件上传大小上限为5MB，可创建1000个待办事项。
  * [planitpoker.com](https://www.planitpoker.com/) – 免费的在线规划扑克工具（估算工具）。
  * [point.poker](https://www.point.poker/) – 在线规划扑克工具（基于共识的估算工具）。免费使用，支持无限用户、团队、会议、轮次和投票。无需注册。
  * [Pulse.red](https://pulse.red) – 免费的项目时间跟踪和工时表应用程序。
  * [ScrumFast](https://www.scrumfast.com) – 界面非常直观的Scrum看板工具，免费使用，最多支持5个用户。
  * [Sflow.io](https://sflow.io) – sflow.io是一款专为敏捷软件开发、市场营销、销售以及客户支持而设计的项目管理工具，特别适用于外包和跨组织协作项目。免费使用，最多支持3个项目和5名成员。  * [Shake](https://www.shakebugs.com/) - 适用于移动应用的漏洞报告和反馈工具。免费计划，每月每个应用最多可报告10个漏洞。
  * [Shortcut](https://shortcut.com/) - 项目管理平台。无限期免费使用，最多可支持10个用户。
  * [taiga.io](https://taiga.io/) — 面向初创企业和敏捷开发者的项目管理平台，开源版本免费使用。
  * [taskade.com](https://www.taskade.com/) — 实时协作任务列表和团队规划工具。免费计划包含一个工作区，任务与项目数量无限制；文件存储容量达1GB；项目历史记录为期1周；视频会议中最多可容纳5名参与者。
  * [Teaminal](https://www.teaminal.com) - 适用于远程团队的站立会议、回顾会议和冲刺计划工具。无限期免费使用，最多可支持15个用户。
  * [teamwork.com](https://teamwork.com/) — 项目管理和团队聊天工具。免费使用，最多可支持5个用户和2个项目。提供高级计划选项。  * [teleretro.com](https://www.teleretro.com/) — 一款简单有趣的回顾工具，包含破冰活动、动图以及表情符号。免费计划包含三次回顾功能，且会员数量无限制。
  * [Tenzu](https://tenzu.net/) — 适用于敏捷团队的轻量级项目管理工具。该工具基于免费贡献模式运行；用户可以选择不进行任何贡献，且工具没有付费功能限制。{[更多详情](https://tenzu.net/pricing/)})
  * [titanapps.io](https://titanapps.io/) — 为Jira和monday.com提供的工作效率工具，包含结构化清单、模板以及任务/问题中的审批功能。小型团队可以使用免费计划。
  * [todoist.com](https://todoist.com/) — 支持协作和个人任务管理。免费计划包含：5个活跃项目、每个项目5名用户、最大5MB的文件上传限制、三种过滤选项，以及一周的活动历史记录。* [Toggl](https://toggl.com/) — 提供两种免费的生产力工具。[Toggl Track](https://toggl.com/track/)用于时间管理和跟踪，免费版功能齐全，专为自由职业者设计，支持无限次的时间跟踪和报告功能。此外，[Toggl Plan](https://toggl.com/plan/)则用于任务规划，免费版可支持单打开发者的无限任务、里程碑和时间表。*
* [trello.com](https://trello.com/) — 基于看板的项目管理工具。支持无限个人看板以及10个团队看板。
* [Tweek](https://tweek.so/) — 简单的每周任务日历与任务管理工具。
* [Wikifactory](https://wikifactory.com/) — 产品设计服务，包含项目、版本控制系统和问题管理功能。免费版支持无限项目和合作者，并拥有3GB的存储空间。
* [Yodiz](https://www.yodiz.com/) — 敏捷开发与问题跟踪工具。免费版可支持最多3个用户，无限个项目。*  * [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud) — 适用于FOSS项目和私有项目的免费托管工具（InCloud），三个用户免费使用。包含时间跟踪和敏捷项目管理功能。
  * [zenhub.com](https://www.zenhub.com) — 唯一一款集成在GitHub中的项目管理工具。适用于公共仓库、开源项目以及非营利组织，免费使用。
  * [zenkit.com](https://zenkit.com) — 项目管理和协作工具，最多5个成员免费使用，支持5GB的附件存储。
  * [Zube](https://zube.io) — 项目管理工具，免费计划支持4个项目及4名用户。支持与GitHub集成。

**[⬆️ 返回顶部](#目录)

## 存储与媒体处理

  * [AndroidFileHost](https://androidfilehost.com/) — 免费的文件共享平台，具有无限的速度、带宽、文件数量、下载次数等特性。主要面向与Android开发相关的文件，如APK构建、自定义ROM等。不过，似乎也接受其他类型的文件。  * [borgbase.com](https://www.borgbase.com/) — 为Borg Backup提供简单且安全的异地备份服务。提供10GB的免费备份空间以及两个存储库。
  * [cloudinary.com](https://cloudinary.com/) — 提供图片上传、强大的图像处理功能、存储服务以及网站和应用程序的交付服务。支持Ruby、Python、Java、PHP、Objective-C等多种语言。免费套餐包含25个月的月度积分。1个积分可用来进行1000次图片处理、1GB的存储空间或1GB的CDN使用量。
  * [degoo.com](https://degoo.com/) – 基于AI的云存储服务，免费存储空间上限为20GB，支持三台设备共享，以及5GB的推荐奖励（账户闲置90天）。
  * [Dropshare](https://dropsha.re) – 零知识文件共享服务。采用AES-256-GCM加密技术，实现端到端加密的文件共享。客户端处理数据，且完全不访问服务器端数据。免费上传的文件大小上限为1GB，且不会收集任何数据。  * [embed.ly](https://embed.ly/) — 提供用于在网页中嵌入媒体的API，支持响应式图片缩放，以及从网页中提取元素的功能。每月最多可处理5,000个URL，每秒最多可发起15次请求，免费使用。
  * [Ente](https://ente.io/) — Ente是一种端到端加密的云存储服务，适用于照片、视频和双因素认证密钥的存储。也可以选择自行托管，并享受永久免费的10GB存储空间。免费用户仅会保留数据的一个副本。
  * [file.io](https://www.file.io) — 提供2GB的存储空间。下载后文件会自动删除。可通过REST API与存储服务进行交互，每分钟最多可发起一次请求。
  * [freetools.site](https://freetools.site/) — 免费在线工具，可用于转换或编辑文档、图片、音频、视频等。
  * [getpantry.cloud](https://getpantry.cloud/) — 简单的JSON数据存储API，非常适合个人项目、黑客马拉松和移动应用等场景！  * [GoFile.io](https://gofile.io/) - 免费的文件共享和存储平台，可通过网页界面或API使用。支持无限的文件大小、带宽、下载次数等。但是，当文件超过十天没有被下载时，该文件将被删除。
  * [gumlet.com](https://www.gumlet.com/) — 图片和视频的托管服务，通过CDN进行处理和流媒体播放。提供每月250GB的图片存储空间和30GB的视频存储空间的免费套餐。
  * [icedrive.net](https://www.icedrive.net/) - 简单的云存储服务。提供10GB的免费存储空间。
  * [image-charts.com](https://www.image-charts.com/) — 支持无限量的图片图表生成，并带有水印。
  * [ImageEngine](https://imageengine.io/) – ImageEngine是一个易于使用的全球图片CDN服务。设置时间不到60秒。支持AVIF和JPEGXL格式，还支持WordPress、Magento、React、Vue等插件。可在此处申请免费的开发者账户：[https://imageengine.io/developer-program/](https://imageengine.io/developer-program/)  * [imagekit.io](https://imagekit.io) – 提供图像CDN服务，具备自动优化、实时转换及存储功能，可轻松与现有系统集成。免费计划每月带宽上限为20GB。
  * [ImgBB](https://imgbb.com/) — 无限量的图像托管服务。可将图像拖放到屏幕上的任意位置。每幅图像大小上限为32MB。上传后可获取直接图像链接、BBCode以及HTML缩略图。登录后可查看上传历史记录。
  * [Imgbot](https://github.com/marketplace/imgbot) — 一款智能机器人，可优化您的图像，为您节省时间。经过优化的图像文件体积更小，且质量不受影响。该服务为开源项目，完全免费。
  * [imgen](https://www.jitbit.com/imgen/) - 免费提供无限量的社交封面图像生成服务，无需水印。
  * [imgix](https://www.imgix.com/) - 提供图像缓存、管理和CDN服务。免费计划包含1000张原始图像、无限次图像转换功能，以及100GB的带宽资源。  * [internxt.com](https://internxt.com) – Internxt Drive 是一种基于绝对隐私和绝对安全性的零知识文件存储服务。立即注册，即可免费获得10GB存储空间，终身有效！
  * [kraken.io](https://kraken.io/) – 提供网站性能优化服务，免费计划可处理最大1MB的文件大小
  * [LibreQR](https://libreqr.com) – 专注于隐私和无追踪的免费二维码生成工具。免费使用，不会收集任何数据。
  * [nitropack.io](https://nitropack.io/) – 通过全面的前端优化（缓存、图像和代码优化、内容分发网络）来自动提升网站速度。每月访问量不超过5,000次时免费使用。
  * [npoint.io](https://www.npoint.io/) – 支持协作模式编辑的JSON存储工具
  * [otixo.com](https://www.otixo.com/) – 可加密、共享、复制和移动所有云存储文件。基础套餐允许无限次文件传输，文件大小上限为250MB，并支持存储五个加密文件。  * [packagecloud.io](https://packagecloud.io/) — 为 YUM、APT、RubyGem 和 PyPI 提供托管仓库服务。可通过申请获得有限的免费计划或开源计划。
  * [pcloud.com](https://www.pcloud.com/) - 云存储服务。可免费使用高达 10GB 的存储空间。
  * [Pinata IPFS](https://pinata.cloud) — Pinata 是 IPFS 上上传和管理文件的最简单方式。我们友好的用户界面和 IPFS API 使 Pinata 成为平台、创作者和收藏家最易使用的 IPFS 文件管理服务。可免费使用 1GB 存储空间，并可使用 API。
  * [plot.ly](https://plot.ly/) — 用于绘制图表和共享数据。免费套餐包含无限量的公共文件和十个私有文件。
  * [podio.com](https://podio.com/) — 您可以与最多五人的团队一起使用 Podio，并试用基础计划的功能，但无需管理用户。
  * [QRME.SH](https://qrme.sh) - 快速、美观的批量二维码生成工具——无需登录、无水印、无广告。每次批量导出最多可生成 100 个 URL。  * [QuickChart](https://quickchart.io) — 生成可嵌入的图像图表、图形以及二维码。
  * [redbooth.com](https://redbooth.com) — P2P文件同步服务，最多可支持2个用户免费使用。
  * [resmush.it](https://resmush.it) — reSmush.it是一个免费的API，提供图片优化服务。该服务已应用于最常见的内容管理系统，如WordPress、Drupal或Magento。reSmush.it是使用最广泛的图片优化API，已有超过70亿张图片得到处理，且仍然保持免费状态。
  * [sirv.com](https://sirv.com/) — 智能图片CDN服务，支持即时图片优化和缩放。免费套餐包含500MB的存储空间和2GB的带宽。* [SlingSite](https://slingsite.github.io) – 免费为您的图片和视频创建优化版本。您可以批量处理。对于每张图片，您将获得以下格式：AVIF、WEBP和JPG，分别针对桌面、平板和移动设备三种分辨率。对于视频，您将获得：WebM（编码格式：VP9）、MP4（编码格式：HEVC，即H.265）和MP4（编码格式：AVC，即H.264）。此外，您还可以获得带有首帧画面的封面图片。*
* [sync.com](https://www.sync.com/) – 端到端的云存储服务。提供5GB的免费存储空间。*
* [tinypng.com](https://tinypng.com/) – 提供PNG和JPEG图片的压缩与尺寸调整服务。每月可免费压缩500次图片。*
* [transloadit.com](https://transloadit.com/) – 负责视频、音频、图片和文档的上传及编码处理。对于开源项目、慈善机构和学生，可免费使用。商业应用可获2GB的免费测试空间。*  * [twicpics.com](https://www.twicpics.com) - 提供响应式图片服务。该服务包含图片CDN、媒体处理API以及自动化图片优化的前端库。每月流量不超过3GB的情况下，该服务是免费的。
  * [uploadcare.com](https://uploadcare.com/hub/developers/) — Uploadcare提供基于尖端算法的媒体处理工具包。所有功能对开发者完全免费：文件上传API和用户界面、图片CDN和原始服务、自适应传输方式以及智能压缩功能。免费套餐包含3000次上传、3GB流量和3GB存储空间。
  * [VaocherApp二维码生成器](https://www.vaocherapp.com/qr-code-generator) – 可轻松生成用于礼品卡、赠品券和促销活动的自定义二维码。支持自定义样式、颜色、标志等设置。
  * **[⬆️ 返回顶部](#table-of-contents)**

## 设计与用户界面  * [AllTheFreeStock](https://allthefreestock.com) - 一个精选的免费股票图片、音频和视频资源列表。
  * [Ant Design 着陆页](https://landing.ant.design/) - Ant Design 着陆页提供了一个由 Ant Motion 的运动组件构建的模板。它拥有丰富的首页模板，可以下载模板代码包，并可以快速使用。您还可以使用编辑器快速构建自己的专属页面。
  * [Backlight](https://backlight.dev/) — 以开发者与设计师之间的紧密合作为核心，Backlight 是一个完整的编码平台，团队可以在这里构建、记录、发布、扩展和维护设计系统。免费计划允许最多3名编辑同时在一个设计系统上工作，且拥有无限数量的查看者。
  * [BoxySVG](https://boxy-svg.com/app) — 一款可免费安装的网页应用程序，用于绘制 SVG 图形，并将图形导出为 SVG、PNG、JPEG 等格式。
  * [Branition](https://branition.com/colors) - 精心挑选的适合品牌的色彩调色板。  * [Calendar Icons Generator](https://calendariconsgenerator.app/) -- 只需点击一次，即可生成一整年的独特图标，完全免费。
  * [Canva](https://canva.com) - 免费的在线设计工具，可用于创建视觉内容。
  * [Carousel Hero](https://carouselhero.com/) - 免费的在线工具，可用于创建社交媒体轮播图。
  * [Circum Icons](https://circumicons.com) - 提供一致的开源图标，如适用于React、Vue和Svelte的SVG图标。
  * [clevebrush.com](https://www.cleverbrush.com/) — 免费的图形设计/照片拼贴应用。此外，他们还提供付费整合服务，可将该应用作为组件使用。
  * [cloudconvert.com](https://cloudconvert.com/) — 可将任何格式的内容转换为其他格式。支持208种格式，包括视频和GIF图。
  * [CMYK Pantone](https://www.cmyktopantone.com/) - 可轻松将CMYK值转换为最接近的Pantone颜色以及其他颜色模型，且完全免费。  * [CodedThemes](https://codedthemes.com/) - 提供设计精良的管理面板及用户界面组件，旨在简化和加快现代网页开发的过程。
  * [CodeMyUI](https://codemyui.com) - 精选的网页设计与用户界面灵感素材，附带代码片段。
  * [ColorKit](https://colorkit.co/) - 在线创建颜色调色板，或从顶级调色板中获取灵感。
  * [colorr.me](https://colorr.me/) - 颜色和渐变生成器。
  * [coolors](https://coolors.co/) - 颜色调色板生成器。免费使用。
  * [css-gradient.com](https://www.css-gradient.com/) - 免费工具，可快速生成自定义跨浏览器CSS渐变效果，支持RGB和HEX格式。
  * [css.glass](https://css.glass/) -- 免费的网络应用，用于使用CSS创建玻璃质设计。
  * [DaisyUI](https://daisyui.com/) -- 免费使用。其特点为“使用Tailwind CSS但编写更少的类名”，提供按钮等组件。  * [easyvectors.com](https://easyvectors.com/) —— EasyVectors.com 是一个免费的 SVG 矢量图形资源库。您可以完全免费下载最佳的矢量图形。
  * [Excalidraw](https://excalidraw.com/) —— 一个免费的在线绘图工具，支持免费保存为本地文件以及导出功能。
  * [figma.com](https://www.figma.com) —— 一款在线协作设计工具，适用于团队使用；免费版本包含无限的文件存储空间，最多可同时编辑 2 个文件，并支持 3 个项目。
  * [Float UI](https://floatui.com/) —— 一款免费的网页开发工具，即使非设计师也能轻松创建现代、响应式的网站，设计风格非常优雅。
  * [Flows](https://flows.sh/) —— 一款完全可定制的产品采用平台，用于构建用户导入和互动体验。免费使用，最多可支持 250 个每月跟踪用户。
  * [Flyon UI](https://flyonui.com/)- 最适合 Tailwind CSS 的组件库。  * [framer.com](https://www.framer.com/) – Framer帮助您为下一个应用程序、网站或产品进行界面设计的迭代和动画效果处理，从强大的布局开始。对于将Framer作为专业原型工具的人来说：拥有无限数量的查看者、最多2位编辑人员以及最多3个项目。
  * [freeforcommercialuse.net](https://freeforcommercialuse.net/) – FFCU提供无需担心的模型/属性发布的库存照片。
  * [Glyphs](https://glyphs.fyi/) – 免费的、网络上最强大的图标系统，完全可编辑且真正开源的设计系统。
  * [Gradientos](https://www.gradientos.app) – 让选择渐变效果变得快速而简单。
  * [Grapedrop](https://grapedrop.com/) – 基于GrapesJS框架的响应式、强大的、符合SEO优化的网页构建工具。前五页免费使用，可无限使用自定义域名，包含所有功能，且使用简单。  * [haikei.app](https://www.haikei.app/) – Haikei是一款用于生成独特SVG形状、背景和图样的网络应用，生成后的内容可以直接与您的设计工具和工作流程结合使用。
  * [hypercolor.dev](https://hypercolor.dev/) – 这里收集了Tailwind CSS颜色渐变资源，同时提供了多种生成器，帮助您创建属于自己的颜色渐变效果。
  * [HyperUI](https://www.hyperui.dev/) – 免费的开源Tailwind CSS组件库。
  * [Icon Horse](https://icon.horse) – 通过我们的简单API，可以为任何网站获取最高分辨率的标准图标。
  * [iconify.design](https://icon-sets.iconify.design/) – 包含超过100种图标的集合，拥有统一的界面设计。您可以跨集合搜索图标，并将单个图标导出为SVG文件，或者导出为流行的Web框架所需的格式。
  * [Iconoir](https://iconoir.com) – 一个开源的图标库，包含数千种图标，支持React、React Native、Flutter、Vue、Figma和Framer等平台。  * [Icons8](https://icons8.com) — 提供图标、插图、照片、音乐以及设计工具。免费计划提供有限格式的低分辨率版本。使用我们的素材时，请访问Icons8网站。
  * [Image BG Blurer](https://imagebgblurer.com/) — 为图片生成模糊背景框架，使用该图片作为模糊背景，适用于Notion、Trello、Jira等工具。
  * [landen.co](https://www.landen.co) — 为您的初创企业生成、编辑并发布精美的网站和着陆页。完全无需编程。免费计划允许您拥有一个完全可自定义且发布在网上的网站。
  * [lensdump.com](https://lensdump.com/) — 免费云图片托管服务。
  * [Logo.dev](https://www.logo.dev) — 公司标志API服务，拥有4400万份品牌信息，调用URL即可使用。前10000次API调用是免费的。* [Lorem Picsum](https://picsum.photos/) – 一款免费且易于使用的工具，提供时尚的占位符图片。在您的网址后面添加您想要的图片尺寸（宽度和高度），即可获得随机生成的图片。
* [LottieFiles](https://lottiefiles.com/) – 全球最大的在线平台，提供设计师和开发者所需的微型动画格式。您可以访问适用于Android、iOS和网页的Lottie动画工具和插件。
* [Lucide](https://lucide.dev) – 一款免费、可自定义且功能一致的SVG图标工具包。
* [Lunacy](https://icons8.com/lunacy) – 一款免费的图形设计工具，支持离线使用，内置资源（图标、照片、插图），并具备实时协作功能。免费版包含10个云文档、30天的历史记录、低分辨率资源以及基本的设计工具。
* [MagicPattern](https://www.magicpattern.design/tools) – 一套用于生成CSS和SVG背景、渐变、图案以及点状元素的工具集。  * [marvelapp.com](https://marvelapp.com/) — 设计、原型制作和协作工具，免费计划仅限一名用户和一个项目。
  * [Mastershot](https://mastershot.app) - 完全免费的基于浏览器的视频编辑器。无需水印，支持最高1080p分辨率导出。
  * [MDBootstrap](https://mdbootstrap.com/) - 适用于个人和商业用途的免费Bootstrap、Angular、React和Vue UI组件库，包含700多个组件，拥有精美的模板，安装只需1分钟，并提供丰富的教程和庞大的社区支持。
  * [Mindmup.com](https://www.mindmup.com/) — 可免费创建无限量的思维导图，并将它们存储在云端。你的思维导图可以在任何设备上即时访问。
  * [Mockplus iDoc](https://www.mockplus.com/idoc) - Mockplus iDoc是一款强大的设计协作与资料交接工具。免费计划包含三名用户和五个项目，所有功能均可使用。  * [mockupmark.com](https://mockupmark.com/create/free) — 为社交媒体和电子商务创建逼真的T恤和服装设计图，提供40张免费模板。
  * [Modeldraw.com](https://modeldraw.com) — 完整的图表制作平台，包含UML、系统架构图、流程图、思维导图以及敏捷工作流程。支持实时协作，可连接无限数量的团队成员，无需信用卡即可使用。
  * [Mossaik](https://mossaik.app) - 免费SVG图像生成工具，支持创建波浪、博客和图案等多种效果。
  * [movingpencils.com](https://movingpencils.com) — 基于浏览器的快速矢量编辑工具，完全免费。
  * [Nappy](https://nappy.co/) -- 提供精美的黑人及棕色人种照片，可免费使用，适用于商业和个人用途。
  * [NextUI](https://nextui.org/) -- 免费、美观、快速且现代的React和Next.js UI库。
  * [NSPolygon](https://nspolygon.com) — 提供免费的图片、图标和插图资源。  * [Octopus.do](https://octopus.do) —— 可视化网站结构构建工具。可以实时构建你的网站结构，并快速分享给团队或客户进行协作。
  * [OKLCH](https://oklch.net/) —— 为网页设计师和开发者提供的免费OKLCH颜色选择器和转换器工具。
  * [okso.app](https://okso.app) —— 极简风格的在线绘图应用。可以快速创建草图和视觉笔记。将草图导出为PNG、JPG、SVG和WEBP格式。也可以作为PWA应用程序安装使用。完全免费，无需注册。
  * [Pencil](https://github.com/evolus/pencil) —— 使用Electron技术的开源设计工具。
  * [Penpot](https://penpot.app) —— 基于网页的、开源的设计和原型工具。支持SVG格式。完全免费。
  * [pexels.com](https://www.pexels.com/) —— 商业用途的免费图片库。提供免费API，可按关键词搜索图片。  * [photopea.com](https://www.photopea.com) — 一款免费的、高级的在线设计编辑器，拥有类似Adobe Photoshop的用户界面，支持PSD、XCF和Sketch格式的文件格式。
  * [Pixelixe](https://pixelixe.com/) — 在线创建和编辑引人入胜、独特的图形和图像。
  * [pixlr.com](https://pixlr.com/) — 一款免费的在线浏览器编辑器，其功能与商业产品相当。
  * [Plasmic](https://www.plasmic.app/) — 一款快速、易用且功能强大的网页设计工具与页面构建工具，可以集成到您的代码库中。您可以构建响应式页面或复杂的组件；也可以通过代码进行扩展；最终可以将设计发布到生产网站和应用程序中。
  * [PNG to WebP Converter](https://pngtowebpconverter.com/) — 可在浏览器中直接将PNG图片转换为WebP图片。无需上传文件，完全采用客户端处理方式，确保最大程度的隐私和安全。
  * [Pravatar](https://pravatar.cc/) — 生成随机或占位符头像，其URL可以直接在您的网页应用中进行热链接。* [Proto.io](https://www.proto.io) - 无需编程即可创建完全交互式的UI原型。免费版在免费试用期结束后可用。免费版包含一名用户、一个项目、五个原型、100MB的在线存储空间，以及Proto.io应用程序的预览功能。
* [Quant Ux](https://quant-ux.com/) - Quant Ux是一款原型设计和工具。完全免费且采用开源方式开发。
* [resizeappicon.com](https://resizeappicon.com/) - 一个用于调整和管理应用程序图标的简单服务。
* [Responsively App](https://responsively.app) - 一款免费的开发工具，可更快、更精确地开发响应式网页应用程序。
* [Rive](https://rive.app) - 可创建并发布适用于任何平台的精美动画。个人用户可永久免费使用。该服务不仅是一个编辑器，还托管了所有的图形资源。他们还为多种平台提供了运行使用Rive制作的动画的运行时环境。* [SceneLab](https://scenelab.io) – 在线模版图形编辑器，拥有不断扩展的免费设计模板库。
* [Scrollbar.app](https://scrollbar.app) – 一款简单的免费网络应用，可用于为网页设计自定义滚动条。
* [Shadcn Studio](https://shadcnstudio.com/theme-editor) – 可预览不同组件和布局中的主题更改效果。
* [ShadcnUI](https://ui.shadcn.com/) – 设计精美的组件，可复制粘贴到您的应用程序中。易于使用，可自定义，且为开源软件。
* [smartmockups.com](https://smartmockups.com/) – 可创建产品模版，提供200个免费模版。
* [storyset.com](https://storyset.com/) – 使用此工具可为您的项目创建精美的免费自定义插图。
* [Superdesigner](https://superdesigner.co) – 一系列免费设计工具，只需几次点击即可创建独特的背景、图案、形状、图片等。  * [SVG转换器](https://svgconverter.online/)——免费将JPG/PNG格式转换为SVG格式的工具，支持自定义颜色调色板。
  * [SVGmix.com](https://www.svgmix.com/)——拥有3万多个免费SVG图标、集合及品牌标志的丰富资源库。该网站还提供了简单的矢量编辑工具，可在浏览器中快速编辑文件。
  * [svgrepo.com](https://www.svgrepo.com/)——可使用各种矢量库来探索、搜索并找到最适合您项目的图标或矢量图形。可下载用于商业用途的免费SVG矢量图形。
  * [tabler-icons.io](https://tabler-icons.io/)——拥有1500多个免费可复制粘贴的SVG可编辑图标。
  * [Tailark](https://tailark.com/)——一系列现代、响应式、预先构建好的UI组件，专为营销网站设计。
  * [Tailcolors](https://tailcolors.com/)——精美的Tailwind CSS v4颜色调色板。可即时预览并复制完美的Tailwind CSS颜色类。  * [Tailkits](https://tailkits.com/)—— 一个精心策划的Tailwind模板、组件和工具的集合，还包括用于代码、网格、阴影等内容的实用生成器。
  * [TeleportHQ](https://teleporthq.io/)—— 一种低代码前端设计与开发平台。TeleportHQ是一个协作式的前端平台，可即时创建和发布无框架的静态网站。提供三个免费项目，无限数量的合作者，以及免费的代码导出功能。
  * [TW Elements](https://tw-elements.com/)—— 使用Tailwind CSS重新设计的免费Bootstrap组件，但设计更出色，功能也更丰富。
  * [tweakcn](https://tweakcn.com/)—— 为shadcn/ui提供的美观主题。可以实时自定义颜色、字体等参数。
  * [UI Avatars](https://ui-avatars.com/)—— 根据名字的首字母生成头像。生成的头像可以直接在您的网页应用中使用。支持通过URL传递配置参数。  * [unDraw](https://undraw.co/) - 一个不断更新精美的SVG图片集，您可以完全免费地使用，无需署名。
  * [Unicorn Platform](https://unicornplatform.com/) - 无需繁琐操作的 Landing Page 构建工具，附带托管服务。免费使用一个网站。
  * [unsplash.com](https://unsplash.com/) - 适用于商业和非商业用途的免费静态图片资源（采用“任意使用”许可协议）。
  * [Updrafts.app](https://updrafts.app) - 基于 tailwindcss 的网站构建工具，支持所见即所得的设计效果。非商业用途可免费使用。
  * [vector.express](https://vector.express) — 快速轻松地将 AI、CDR、DWG、DXF、EPS、HPGL、PDF、PLT、PS 和 SVG 等矢量文件转换为其他格式。
  * [vectr.com](https://vectr.com/) — 适用于网页和桌面的免费设计工具。
  * [Vertopal](https://www.vertopal.com) - Vertopal 是一个免费的在线平台，可以将文件转换为多种格式。包括将 JPG 转换为 SVG、GIF 转换为 APNG、PNG 转换为 WEBP、JSON 转换为 XML 等功能的开发者专用转换器。  * [Volume](https://volumecolor.io) — OKLCH颜色选择器和颜色调色板生成工具。  
  * [walkme.com](https://www.walkme.com/) — 企业级指导与互动平台，免费套餐包含3个关于5个步骤/行走的指南。  
  * [Wdrfree SVG](https://wdrfree.com/free-svg) - 黑白免费SVG文件。  
  * [Webflow](https://webflow.com) - 具有动画效果和网站托管功能的所见即所得网站构建工具。两个项目免费使用。  
  * [Webstudio](https://webstudio.is/) -- Webflow的开源替代品。免费套餐允许在域名上创建无限数量的网站。五个带有自定义域名的网站。每月一万人次浏览量。2GB的资产存储空间。  
  * [whimsical.com](https://whimsical.com/) - 支持协作的流程图、线框图、便签和思维导图工具。最多可创建4个免费板。  * [xLayers](https://xlayers.dev) - 预览并将Sketch设计文件转换为Angular、React、Vue、LitElement、Stencil、Xamarin等格式（免费且采用开源方式，网址：https://github.com/xlayers/xlayers）
  * [Zeplin](https://zeplin.io/) — 设计师与开发者的协作平台。展示设计稿、素材以及风格指南。单个项目免费使用。

**[⬆️ 返回目录顶部](#table-of-contents)**

## 设计灵感来源

  * [awwwards.com.](https://www.awwwards.com/) - [顶级网站] 展示所有设计精美的网站，这些网站由设计师们投票选出。
  * [Behance.net.](https://www.behance.net/) - [设计展示平台] 设计师们展示自己作品的平台。可根据UI/UX项目分类进行筛选。
  * [Dribbble.com.](https://dribbble.com/) - [设计灵感来源] 提供独特的设计灵感，通常并非来自实际应用。
  * [Landings.dev.](https://landings.dev/) - [网页截图平台] 根据您的偏好找到最适合的设计灵感页面。  * [Lapa Ninja](https://www.lapa.ninja/) - [着陆页设计 / 用户界面组件 / 网页截图] Lapa Ninja 是一个展示最佳着陆页设计的画廊，提供设计师免费书籍以及来自网络的免费用户界面组件。
  * [LovelyLanding.net](https://www.lovelylanding.net/) - [着陆页设计] 经常更新的着陆页截图，包括桌面版、平板版和移动版截图。
  * [Mobbin](https://mobbin.design/) - [移动端截图] 通过我们的包含50,000多份可完全搜索的移动应用截图的库，节省数小时的时间来研究用户界面和用户体验。
  * [Mobile Patterns](https://www.mobile-patterns.com/) - [移动端截图] 一个设计灵感库，提供最优秀的用户界面和用户体验模式（适用于iOS和Android），供设计师、开发者和产品制作者参考。
  * [Page Flows](https://pageflows.com/) - [移动端/网页视频和截图] 许多移动应用和网页的完整流程视频，同时包含截图。支持高度搜索和索引功能。  * [Refero](https://refero.design/) - [网页截图] 汇集了来自优秀网页应用程序的设计参考，支持标签分类和搜索。
  * [Screenlane](https://screenlane.com/) - [移动端截图] 获取灵感，了解最新的网页和移动应用UI设计趋势。可根据模式和应用进行筛选。
  * [scrnshts](https://scrnshts.club/) - [移动端截图] 精选了最优秀的应用商店设计截图。
  * [Uiland Design](https://uiland.design/) - [移动端截图] 探索来自非洲及全球领先公司的移动端和网页UI设计。

**[⬆️ 返回顶部](#目录)

## 地图上的数据可视化

  * [Clockwork Micro](https://clockworkmicro.com/) — 类似时钟运转的地图工具。每月可免费查询五万次数据（地图瓦片、db2vector、海拔信息等）。
  * [Foursquare](https://developer.foursquare.com/) - 通过 Places API 和 Pilgrim SDK 进行位置发现、场所搜索以及上下文感知的内容呈现。  * [geoapify.com](https://www.geoapify.com/) - 矢量地图和栅格地图瓦片、地理编码、地点查询、路线规划、等值线数据API。每天可免费调用三千次。
  * [geocod.io](https://www.geocod.io/) — 通过API或CSV文件进行地理编码。每天可免费调用两千五百次。
  * [geocodify.com](https://geocodify.com/) — 通过API或CSV文件进行地理编码和地理数据解析。每月可免费调用一万次。
  * [geojs.io](https://www.geojs.io/) - 提供高可用性的REST/JSON/JSONP接口，用于地理定位查询。
  * [Geokeo api](https://geokeo.com) - 具有语言校正功能的地理编码API。全球覆盖，每天可免费调用2500次。
  * [graphhopper.com](https://www.graphhopper.com/) - 提供路由、路线优化、距离矩阵、地理编码和地图匹配功能的免费开发包。
  * [here](https://developer.here.com/) — 为地图和位置感知应用程序提供的API和SDK。每月可免费调用25万次。  * [IP地理定位服务](https://ipgeolocation.io/) — 提供免费的开发者计划，每月请求上限为30,000次。
  * [ipstack.com](https://ipstack.com/) - 通过IP地址定位并识别网站访问者。
  * [locationiq.com](https://locationiq.com/) — 提供地理编码、地图和路由API服务。每日免费请求上限为5,000次。
  * [mapbox.com](https://www.mapbox.com/) — 提供地图、地理空间服务以及用于显示地图数据的SDK。
  * [maps.stamen.com](http://maps.stamen.com/) - 提供免费的地图瓦片及瓦片托管服务。
  * [maptiler.com](https://www.maptiler.com/cloud/) — 提供矢量地图、地图服务及地图可视化SDK。提供免费的矢量瓦片，并每周更新四种地图样式。
  * [nominatim.org](https://nominatim.org/) — 提供免费的OpenStreetMap地理编码服务，具备全球地址搜索功能及反向地理编码功能。  * [opencagedata.com](https://opencagedata.com) — 地理编码API，整合了OpenStreetMap及其他开源地理数据。每天可免费查询2500次。
  * [osmnames.org](https://osmnames.org/) — 地理编码服务，搜索结果会根据相关维基页面的受欢迎程度进行排名。
  * [positionstack.com](https://positionstack.com/) — 全球地点和坐标的免费地理编码服务。个人使用每月可请求25,000次。
  * [stadiamaps.com](https://stadiamaps.com/) — 地图瓦片、路线规划、导航功能以及其他地理空间API。非商业用途和测试用途每天可免费查看2500张地图，并请求2500次API。

**[⬆️ 返回顶部](#目录)

## 软件包构建系统

  * [build.opensuse.org](https://build.opensuse.org/) — 适用于多种发行版的软件包构建服务（如SUSE、EL、Fedora、Debian等）。
  * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — 基于Mock的RPM构建服务，适用于Fedora和EL发行版。* [help.launchpad.net](https://help.launchpad.net/Packaging) — 适用于Ubuntu和Debian的构建服务。

**[⬆️ 返回顶部](#目录)

## 集成开发环境和代码编辑

* [Android Studio](https://developer.android.com/studio) — Android Studio提供了在各类Android设备上构建应用程序的最快工具。这款开源的集成开发环境对所有人免费开放，是开发最佳Android应用程序的最佳选择。支持Windows、Mac、Linux，甚至ChromeOS系统！
* [AndroidIDE](https://m.androidide.com/) — 一款开源的集成开发环境，用于在Android设备上开发基于Gradle的Android应用程序。
* [Apache NetBeans](https://netbeans.apache.org/) — 开发环境、工具平台和应用程序框架。
* [apiary.io](https://apiary.io/) — 协作设计API，提供即时API模拟和生成的文档。免费提供无限数量的API蓝图，且只需一个管理员账号即可管理无限数量的用户，文档也由托管服务提供。  * [BBEdit](https://www.barebones.com/) - BBEdit是一款流行且功能丰富的macOS编辑器。免费模式提供了[强大的核心功能集](https://www.barebones.com/products/bbedit/comparison.html)，并可通过升级获得更多高级功能。
  * [Binder](https://mybinder.org/) - 可将Git仓库转换为一系列交互式笔记本。这是一个免费的公共服务。
  * [BlueJ](https://bluej.org) — 一款为初学者设计的免费Java开发环境，全球有数百万用户使用。由Oracle公司提供支持，拥有简单的图形用户界面，方便初学者使用。
  * [Bootify.io](https://bootify.io/) - 一款Spring Boot应用程序生成器，支持自定义数据库和REST API。
  * [Brackets](http://brackets.io/) - Brackets是一款专为网页开发设计的开源文本编辑器。它轻量级、易于使用，且可高度定制。
  * [cacher.io](https://www.cacher.io) — 一款代码片段管理工具，支持100多种编程语言，并带有标签功能。  * [cocalc.com](https://cocalc.com/) — （原名为SageMathCloud，网址为cloud.sagemath.com）在云端进行协作计算。可通过浏览器访问，支持完整的Ubuntu环境，内置协作功能，并提供了大量适用于数学、科学、数据科学领域的免费软件，预装了Python、LaTeX、Jupyter Notebooks、SageMath、scikitlearn等工具。
  * [code.cs50.io](https://code.cs50.io/) — 针对CS50课程的Visual Studio Code，是一款在code.cs50.io上运行的网络应用，可将GitHub Codespaces功能适配给学生和教师使用。
  * [Code::Blocks](https://codeblocks.org) — 免费的Fortran与C/C++集成开发环境。开源代码，可在Windows、macOS和Linux上运行。
  * [codepen.io](https://codepen.io/) — CodePen是一个用于前端开发的编程平台。
  * [codesandbox.io](https://codesandbox.io/) — 适用于React、Vue、Angular、Preact等框架的在线编程平台。  * [codiga.io](https://codiga.io/) — 编码助手，可让您直接在IDE中搜索、定义和复用代码片段。适用于个人用户及小型组织，免费使用。
  * [Components.studio](https://webcomponents.dev/) — 以独立组件的形式提供代码，可通过故事形式进行可视化、测试，并发布到npm上。
  * [Eclipse Che](https://www.eclipse.org/che/) — 基于Web的、支持Kubernetes的开发者团队IDE，支持多语言环境。开源项目，由社区驱动开发。Red Hat提供的在线实例可在[workspaces.openshift.com](https://workspaces.openshift.com/)获取。
  * [ForgeCode](https://forgecode.dev/) — 支持Claude、GPT4系列、Grok、Deepseek、Gemini等前沿模型的AI辅助编程工具。可直接与您的命令行工具集成，并与任何IDE无缝协作。免费版包含基本的AI模型访问权限及本地处理功能。  * [GetVM](https://getvm.io) — 即时免费的Linux环境和IDE，包含Chrome侧边栏。免费套餐每天可使用5台虚拟机。
  * [JDoodle](https://www.jdoodle.com) — 提供超过60种编程语言的在线编译器和编辑器，免费套餐每天可编译REST API代码，最多可累计获得200点积分。
  * [jetbrains.com](https://jetbrains.com/products.html) — 提供生产力工具、IDE以及部署工具（如[IntelliJ IDEA](https://www.jetbrains.com/idea/)、[PyCharm](https://www.jetbrains.com/pycharm/等）。学生、教师、开源项目以及用户团体均可免费使用。
  * [JSONPlaceholder](https://jsonplaceholder.typicode.com/) — 提供一些REST API接口，返回假的JSON数据。如果需要本地运行服务器，源代码也可以获取。
  * [Lazarus](https://www.lazarus-ide.org/) — Lazarus是一款兼容Delphi的跨平台快速应用程序开发IDE。
  * [MarsCode](https://www.marscode.com/) — 一款基于云技术的免费AI驱动IDE。  * [micro-jaymock](https://micro-jaymock.now.sh/) - 一种用于生成虚假JSON数据的微型API模拟工具。
  * [mockable.io](https://www.mockable.io/) — Mockable是一个可配置的服务，用于模拟RESTful API或SOAP Web服务。该在线服务允许您快速定义REST API或SOAP端点，并让它们返回JSON或XML数据。
  * [mockaroo](https://mockaroo.com/) — Mockaroo能够生成真实的测试数据，数据格式包括CSV、JSON、SQL和Excel。您还可以为后端API创建模拟。
  * [Mocklets](https://mocklets.com) - 一种基于HTTP的模拟API模拟器，有助于加快并行开发和更全面的测试，且提供终身免费服务。
  * [OneCompiler](https://onecompiler.com/) - 免费的在线编译器，支持70多种语言，包括Java、Python、C++和JavaScript。  * [Paiza](https://paiza.cloud/en/) — 无需任何配置即可开发浏览器中的Web应用程序。免费计划提供一台服务器，拥有24小时的运行时间，每天运行4小时，配备2个CPU核心、2GB内存和1GB存储空间。
  * [PHPSandbox](https://phpsandbox.io/) — PHP的在线开发环境。
  * [Replit](https://replit.com/) — 适用于多种编程语言的云编程环境。
  * [SoloLearn](https://code.sololearn.com) — 适合运行代码片段的云编程平台。支持多种编程语言。运行代码无需注册，但在平台上保存代码时需要注册。还提供针对初学者和中级编程者的免费课程。  * [stackblitz.com](https://stackblitz.com/) — 在线/云代码集成开发环境，用于创建、编辑和部署全栈应用程序。支持多种流行的基于Node.js的前端和后端框架。创建新项目的快捷链接：[https://node.new](https://node.new)。
  * [Sublime Text](https://www.sublimetext.com/) —— Sublime Text是一款受欢迎且功能丰富的文本编辑器，适用于编码和文本编辑任务。
  * [Visual Studio Code](https://code.visualstudio.com/) —— 代码编辑器，为构建和调试现代网络和云应用程序而重新定义并进行了优化。由微软开发。
  * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) —— 功能齐全的集成开发环境，拥有数千种扩展程序，支持跨平台应用程序开发（微软为iOS和Android提供了相关扩展程序），适用于桌面、网络和云开发，支持多种语言（C#、C++、JavaScript、Python、PHP等）。  * [VSCodium](https://vscodium.com/) - 由社区驱动开发的编辑器，无需遥测/跟踪功能，且采用免费许可的二进制分发格式，适用于微软的编辑器VSCode。
  * [wakatime.com](https://wakatime.com/) — 通过文本编辑器插件提供关于您的编码活动的量化自我评估数据，免费试用有限计划。
  * [Wave Terminal](https://waveterm.dev/) - 开源的跨平台终端工具，可实现无缝工作流程。可以内联渲染任何内容，保存会话和历史记录。基于开放网络标准构建，适用于MacOS和Linux系统。
  * [WebComponents.dev](https://webcomponents.dev/) — 浏览器内IDE，可用于独立编码Web组件，提供58种模板，支持故事和测试功能。
  * [Zed](https://zed.dev/) - Zed是一款高性能的多人代码编辑器，由Atom和Tree-sitter的开发者团队开发。

**[⬆️ 返回顶部](#目录)

## 分析、事件和统计信息

  * [amplitude.com](https://amplitude.com/) — 每月有100万个事件记录，最多支持2个应用程序。* [AppFit](https://appfit.io) – AppFit是一款全面的分析与产品管理工具，旨在实现跨平台的、无缝的分析与产品更新管理。免费套餐每月包含10,000个事件记录、产品日志以及每周分析数据。*
* [Aptabase](https://aptabase.com) – 开源、注重隐私保护且功能简单的分析工具，适用于移动和桌面应用。提供Swift、Kotlin、React Native、Flutter、Electron等多种语言的SDK。每月最多可处理20,000个事件记录，免费使用。*
* [Avo](https://avo.app/) – 简化了分析版本的发布流程。采用单一来源跟踪机制、类型安全的分析跟踪库、应用内调试工具，以及数据观察功能，可在发布前发现所有数据问题。两个工作空间成员可免费使用，数据观察的回查时间限制为1小时。*
* [Beampipe.io](https://beampipe.io) – Beampipe是一款简单且注重隐私保护的网页分析工具。最多可支持5个域名，每月最多处理10,000次页面访问，免费使用。** [Census](https://www.getcensus.com/) — 反向ETL与运营分析平台。可将数据仓库中的10个字段同步到60多个类似Salesforce、Zendesk或Amplitude的SaaS平台。
* [Clicky](https://clicky.com) — 网站分析平台。适用于单个网站且访问量不超过3000次的分析服务，免费提供。
* [counter.dev](https://counter.dev) — 简化的网站分析工具，注重隐私保护。免费使用，或可通过捐款支付费用。
* [DocBeacon](https://docbeacon.io) — 安全的文档共享工具，包含文档跟踪及互动分析功能。免费计划最多支持20个PDF文档（每个文档最大10MB），10个联系人，每个文档最多可共享2次，并提供基本的查看次数、下载次数、使用时间及互动情况的分析。
* [Dwh.dev](https://dwh.dev) — 数据云可观测性解决方案（基于Snowflake）。个人使用免费。
* [Expensify](https://www.expensify.com/) — 费用报告工具，个人使用免费，并提供费用报告的审批流程。  * [getinsights.io](https://getinsights.io) - 注重隐私，无需使用Cookie，每月最多可分析3,000个事件，且完全免费。
  * [GoatCounter](https://www.goatcounter.com/) — GoatCounter是一个开源的网页分析平台，可作为托管服务提供（非商业用途免费），或作为自托管应用程序使用。它旨在提供易于使用且注重隐私的网页分析服务，作为Google Analytics或Matomo的替代方案。免费版适用于非商业用途，包含无限数量的网站、六个月的数据保留期限，以及每月10万次页面浏览量。
  * [Google Analytics](https://analytics.google.com/) — Google Analytics
  * [heap.io](https://heap.io) — 自动捕获iOS或网页应用程序中的每一次用户操作。每月最多可记录10,000个会话，免费使用。
  * [Hightouch](https://hightouch.com/) — Hightouch是一个逆向ETL平台，可以帮助您将客户数据从数据仓库同步到CRM、营销和支持工具中。免费版仅提供一个数据同步目的地。* [Hotjar](https://hotjar.com)——网站分析和报告工具。免费计划支持每天2000次页面访问量，每天可生成100个快照（最大容量：300个）。最多可存储3个快照热图，保存期限可达365天。支持无限数量的团队成员。该平台还支持应用程序和独立调查功能，以及带有截图的反馈组件。免费计划允许用户创建3个调查、3个反馈组件，每月可收集20份反馈数据。*

*[LogSpot](https://logspot.io]*——全合一的网页和产品分析平台，包含可嵌入的分析组件以及自动化的机器人程序（如Slack、Telegram和Webhook）。免费计划每月包含10,000个事件记录。*

*[MetricsWave](https://metricswave.com)*——专为开发者设计的、注重隐私保护的Google Analytics替代方案。免费计划允许每月访问1百万次页面，无需使用信用卡即可使用。*

*[Mixpanel](https://mixpanel.com/)*——每月可追踪100,000名用户，数据历史记录和数据存储位置不受限制，支持美国或欧洲的数据隐私保护。  * [Moesif](https://www.moesif.com) — 提供REST和GraphQL的API分析服务。每月最多可调用500,000次API。
  * [PostHog](https://posthog.com) - 提供完整的产品分析服务，每月最多可处理1百万条记录。同时提供无限次数的应用内调查功能，每月最多可回复250条数据。
  * [Repohistory](https://repohistory.com) - 提供美观的仪表盘，用于跟踪超过14天的GitHub仓库访问记录。免费计划允许用户监控单个仓库的访问情况。
  * [Row Zero](https://rowzero.io) - 速度极快的连接式电子表格工具。可直接连接数据数据库、S3以及API。可即时导入、分析、绘制图表并分享数百万行数据。提供3个免费（永久使用）的工作表。
  * [Rybbit](https://rybbit.io) - 开源且无cookie的替代方案，相比Google Analytics更加直观易用。免费计划支持每月最多3,000条数据记录。  * [Seline](https://seline.so) - Seline是一个简单且私密的网络平台，用于进行网站和产品分析。该平台无需使用Cookie，设计轻量级，且完全独立运行。免费计划包含每月3000次数据分析，用户可以访问所有功能，如控制面板、用户行为追踪等。
  * [StatCounter](https://statcounter.com/) — 网站浏览数据分析平台。免费计划适用于分析500名最新访问者的数据。
  * [Statsig](https://statsig.com) - 一个集成了数据分析、功能标记和A/B测试功能的综合平台。免费计划适用于每月最多1百万次事件的数据分析。
  * [TraceLog](https://tracelog.io/) - 电子商务领域的AI数据分析工具。用户可以用自然语言提出关于数据分析的问题，并获得基于AI的实用建议，从而通过AI技术提升收入。免费计划适用于每月最多1万次事件的数据分析。  * [Trackingplan](https://www.trackingplan.com/) - 自动检测数字分析、营销数据及像素问题，维护最新的跟踪计划，并促进无缝协作。可将其部署到实际运行的环境中，或在不编写代码的情况下为回归测试添加分析功能。
  * [TrackWith Dicloud](https://dicloud.net/trackwith-privacy-focused-analytics/) - 免费的、注重隐私的谷歌分析替代方案。提供无限页面浏览量、无限访客数、无限页面热图及目标跟踪功能。适用于最多3个域名，每个域名可免费进行600次会话回放测试。
  * [Umami](https://umami.is/) - 简单、快速、注重隐私的谷歌分析替代方案，采用开源技术。
  * [usabilityhub.com](https://usabilityhub.com/) — 在真实用户身上测试设计和原型图，并跟踪访客行为。适用于一个用户，不限次数地进行测试。* [Userbird](https://userbird.com) – 一款替代Google Analytics的分析工具，支持热力图、会话记录以及收入跟踪功能。

**[⬆️ 返回顶部](#目录)

## 访客会话记录

* [FullStory.com](https://www.fullstory.com) – 每月可记录1,000个会话，数据保留时间为一个月，提供3个用户席位。更多信息请访问：[https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition)

* [howuku.com](https://howuku.com) – 可记录用户互动、参与情况及事件。每月最多可记录5,000次访问记录，免费使用。

* [inspectlet.com](https://www.inspectlet.com/) – 每月可记录2,500个会话记录，适用于单个网站，免费使用。

* [LogRocket.com](https://www.logrocket.com) – 每月可记录1,000个会话记录，数据保留时间为30天，支持错误跟踪和实时模式。

* [Microsoft Clarity](https://clarity.microsoft.com/) – 完全免费的会话记录功能，无需限制流量、项目数量，且无需采样数据。  * [mouseflow.com](https://mouseflow.com/) — 单个网站每月可免费使用500次会话记录
  * [OpenReplay.com](https://www.openreplay.com) - 开源会话回放功能，包含用于复现错误的开发工具，实时支持的交互会话，以及产品分析工具包。单个网站每月可访问1000次会话记录，并享有所有功能及7天数据保留权限。
  * [Reactflow.com](https://www.reactflow.com/) — 每个网站每天可记录1000次页面浏览，提供三个热图分析工具、三个小工具，并支持免费的错误追踪功能。
  * [smartlook.com](https://www.smartlook.com/) — 为网页和移动应用提供免费服务（每月1500次会话记录），提供三个热图分析工具、一个漏斗图分析工具，以及1个月的数据历史记录。
  * [UXtweak.com](https://www.uxtweak.com/) — 记录并观察访客如何使用您的网站或应用。小型项目可免费使用无限次会话记录功能。

**[⬆️ 返回顶部](#目录)

## 国际手机号码验证API与SDK* [numverify](https://numverify.com/) —— 全球电话号码验证与查询的JSON API。每月可调用100次API。
* [veriphone](https://veriphone.io/) —— 提供免费、快速、可靠的全球电话号码验证服务，使用JSON API。每月可调用1000次API。

**[⬆️ 返回顶部](#目录)**

## 支付与账单集成

* [Adapty.io](https://adapty.io/) —— 提供一站式解决方案，包含开源的移动应用订阅集成SDK，适用于iOS、Android、React Native、Flutter、Unity或Web应用。每月收入上限为1万美元。
* [CoinMarketCap](https://coinmarketcap.com/api/) —— 提供加密货币市场数据，包括最新的加密货币与法定货币汇率。免费套餐每月可使用1万次调用权限。
* [Currencyapi](https://currencyapi.com) —— 提供免费的外币兑换和汇率数据API。每月可免费调用300次，每次调用需等待10分钟，仅限私人使用。  * [CurrencyApi](https://currencyapi.net/) — 提供实物货币和加密货币的最新汇率信息，支持JSON和XML格式。免费套餐每月可调用1,250次API。
  * [CurrencyFreaks](https://currencyfreaks.com/) — 提供当前和历史货币汇率信息。免费开发者计划每月可调用1,000次API。
  * [currencylayer](https://currencylayer.com/) — 为您的业务提供可靠的汇率和货币转换服务，免费套餐每月可调用100次API。
  * [exchangerate-api.com](https://www.exchangerate-api.com) — 易于使用的货币转换JSON API。免费套餐每天更新一次汇率数据，每月调用次数上限为1,500次。
  * [FraudLabsPRO](https://www.fraudlabspro.com) — 帮助商家防止支付诈骗和退款问题。免费微计划每月可查询500次数据。
  * [FxRatesAPI](https://fxratesapi.com) — 提供实时和历史汇率数据。免费套餐需要注明来源。  * [Moesif API  monetization](https://www.moesif.com/) – 通过基于使用量的计费方式，从 API 中获取收入。可连接 Stripe、Chargebee 等支付平台。免费套餐每月提供 30,000 次调用次数。
  * [ParityVend](https://www.ambeteco.com/ParityVend/) – 根据访问者的位置自动调整价格，从而在全球范围内扩展业务并进入新的市场（购买力平价）。免费套餐每月可调用 7,500 次 API。
  * [Qonversion](http://qonversion.io/) – 一站式跨平台订阅管理平台，提供分析功能、A/B 测试、Apple Search Ads、远程配置功能以及优化应用内购买和货币化的工具。支持 iOS、Android、React Native、Flutter、Unity、Cordova、Stripe 以及网页版。免费套餐每月可追踪收入不超过 10,000 美元。
  * [RevenueCat](https://www.revenuecat.com/) – 提供应用内购买和订阅服务的托管后端服务（适用于 iOS 和 Android）。免费套餐每月可追踪收入不超过 2,500 美元。  * [vatlayer.com](https://vatlayer.com/) — 提供即时增值税号码验证服务及欧盟增值税税率API，每月可免费调用100次API

**[⬆️ 返回顶部](#目录)

## 与Docker相关的服务

  * [Container Registry服务](https://container-registry.com/) — 基于Harbor的容器管理解决方案。免费层可提供1GB的存储空间用于私有仓库的存储。
  * [Docker Hub](https://hub.docker.com) — 可免费创建一个私有仓库，并可无限创建和存储Docker镜像。
  * [Play with Docker](https://labs.play-with-docker.com/) — 一个简单、互动且有趣的Docker学习平台。
  * [quay.io](https://quay.io/) — 可构建和存储容器镜像，拥有无限数量的免费公共仓库。
  * [ttl.sh](https://ttl.sh/) - 匿名且临时的Docker镜像注册中心

**[⬆️ 返回顶部](#目录)

## 开发博客网站  * [AyeDot](https://ayedot.com/) — 以现代多媒体短格式迷你博客的形式，免费与全世界分享你的想法、知识和故事。
  * [BearBlog](https://bearblog.dev/) - 以 Markdown格式设计的简约博客和网站构建工具。
  * [Dev.to](https://dev.to/) - 程序员们分享想法、互相学习成长的平台。
  * [Hashnode](https://hashnode.com/) — 为开发者提供的无需繁琐操作的博客软件！
  * [Medium](https://medium.com/) — 让你更深入地思考那些对你来说重要的事情。
  * [JustBlogged](https://justblogged.com) — 提供免费博客平台，支持自定义域名，并拥有快速的全球性能。

**[⬆️ 返回目录顶部](#目录内容)**

## 评论平台

  * [GraphComment](https://graphcomment.com/) - GraphComment是一个评论平台，可以帮助你从网站的用户群中建立活跃的社区。  * [IntenseDebate](https://intensedebate.com/) - 一个功能丰富的评论系统，适用于WordPress、Tumblr、Blogger以及许多其他网站平台。
  * [Remarkbox](https://www.remarkbox.com/) - 开源的托管评论平台，可根据实际需求付费使用，可在一个域名上设置“一名管理员”，拥有完全的控制权。
  * [Utterances](https://utteranc.es/) - 基于GitHub Issues构建的轻量级评论组件。可用于博客评论、维基页面等多种场景！

**[⬆️ 返回顶部](#目录)

## 截图API

  * [ApiFlash](https://apiflash.com) — 基于AWS Lambda和Chrome的截图API。可以处理整页截图，记录截图时间以及视区尺寸。
  * [microlink.io](https://microlink.io/) – 可将任何网站转换为数据，如元标签标准化、美观的链接预览、抓取功能，或提供截图服务。每天免费调用250次。  * [PhantomJsCloud](https://PhantomJsCloud.com) — 浏览器自动化与页面渲染服务。免费套餐可每日处理多达500页页面。该服务自2017年起提供免费服务。
  * [screenshotbase.com](https://screenshotbase.com) — 每月可免费获取300张截图。可从任意网址截取截图。速度快、免费且可扩展。
  * [screenshotlayer.com](https://screenshotlayer.com/) — 可生成高度可定制的网站截图。每月免费提供100张截图。
  * [screenshotmachine.com](https://www.screenshotmachine.com/) — 每月可生成100张截图，支持PNG、GIF和JPG格式，包括完整页面截图，不仅限于首页。
  * [thumbnail.ws](https://thumbnail.ws) — 用于生成网站缩略图的API服务。每月免费调用1000次。

**[⬆️ 返回目录顶部](#目录内容)**

## 与Flutter相关的内容以及无需Mac即可构建iOS应用程序  * [CodeMagic](https://codemagic.io/) - CodeMagic是一款完全托管且由企业管理的移动应用持续集成/持续交付工具。您可以使用基于GUI的CI/CD工具进行构建、测试和部署。免费套餐每月提供500分钟的使用时间，并附带一台配备2.3 GHz处理器和8 GB内存的Mac Mini实例。
  * [FlutLab](https://flutlab.io/) - FlutLab是一款现代化的Flutter在线IDE，是创建、调试和构建跨平台项目的理想场所。您可以使用Flutter构建iOS和Android应用（无需Mac）。
  * [FlutterFlow](https://flutterflow.io/) - FlutterFlow是一款基于浏览器的拖放界面，用于使用Flutter构建移动应用。

**[⬆️ 返回顶部](#目录)

## 基于JavaScript的浏览器硬件仿真

  * [Jor1k](https://s-macke.github.io/jor1k/demos/main.html) — 一款OpenRISC虚拟机，能够运行支持网络功能的Linux系统。
  * [JsLinux](https://bellard.org/jslinux) — 一款非常快速的x86虚拟机，能够运行Linux和Windows 2k系统。* [v86](https://copy.sh/v86) — 一款能够直接在浏览器中运行Linux及其他操作系统的x86虚拟机。

**[返回顶部](#目录)

## 隐私管理

* [Bearer](https://www.bearer.sh/) — 通过审计和持续工作流程来帮助实现设计上的隐私保护，使组织能够遵守GDPR及其他相关法规。免费版仅适用于小型团队，且仅提供SaaS版本。
* [Concord](https://www.concord.tech/) — 完整的隐私管理平台，包括同意管理、隐私请求处理以及数据映射功能。免费版包含核心的同意管理功能，同时为经过验证的开源项目提供更高级别的免费服务。
* [Cookiefirst](https://cookiefirst.com/) — 提供Cookie banner、审计以及多语言同意管理解决方案。免费版仅提供一次性扫描和单个Cookie banner的功能。* [Iubenda](https://www.iubenda.com/) – 隐私与cookie政策及同意管理。免费版提供有限的隐私和cookie政策，以及cookie信息。
* [Ketch](https://www.ketch.com/) – 同意管理及隐私框架工具。免费版提供大部分功能，但访问量有限。

**[⬆️ 返回顶部](#目录)

## 其他

* [BackgroundStyler.com](https://backgroundstyler.com) – 创建美观的截图，用于分享到社交媒体。
* [Base64解码/编码工具](https://devpal.co/base64-decode/)——在线免费工具，用于数据的解码与编码。
* [BinShare.net](https://binshare.net) – 创建并分享代码或二进制文件。可以以美观的图片形式分享，例如用于Twitter/Facebook帖子，或者作为链接分享，例如用于聊天或论坛。  * [Blynk](https://blynk.io) — 一款基于SaaS的软件，具有API功能，可用于控制、构建和评估物联网设备。提供免费的开发者计划，包含5台设备，同时提供免费的云存储服务。也有相应的移动应用。
  * [Bricks Note Calculator](https://free.getbricks.app/) — 一款笔记应用（PWA），内置了强大的多行计算器功能。
  * [Carbon.now.sh](https://carbon.now.sh) — 能够以美观的截图格式创建和分享代码片段。通常用于在Twitter或博客文章中展示代码片段。
  * [Code Time](https://www.software.com/code-time) — 一款用于跟踪时间及评估编码效率的扩展程序，适用于VS Code、Atom、IntelliJ、Sublime Text等编辑器。
  * [Codepng](https://www.codepng.app) — 可根据源代码生成精美的截图，方便在社交媒体上分享。
  * [CodeToImage](https://codetoimage.com/) — 可将代码或文本截图制作成图片，以便在社交媒体上分享。  * [cron-job.org](https://cron-job.org) - 在线任务调度服务。无限量的任务可以免费使用。
  * [Cronhooks](https://cronhooks.io/) - 可定时执行或定期重复的Web钩子功能。免费计划支持5个临时调度任务。
  * [datelist.io](https://datelist.io) - 在线预订/预约系统。每月最多可预订5次，包含1个日历功能。
  * [Domain Forward](https://domain-forward.com/) - 用于转发任意URL或域名的简单工具。每月最多可处理5个域名，请求次数不超过20万次。
  * [Exif Editor](https://exifeditor.io/) — 可在浏览器中即时查看、编辑、过滤和分析图片/照片的元数据，包括GPS位置信息及元数据内容。
  * [Format Express](https://www.format-express.dev) - 即时在线JSON/XML/SQL格式转换工具。
  * [FOSSA](https://fossa.com/) - 可扩展的端到端管理工具，用于管理第三方代码、许可证合规性以及漏洞处理。  * [Hook Relay](https://www.hookrelay.dev/) - 为您的应用程序添加Webhook支持，无需自行处理队列、重试机制以及日志记录等问题。免费计划每天可处理100个任务，数据保存周期为14天，并支持3个Hook端点。
  * [Hosting Checker](https://hostingchecker.co) - 可检查任何域名、网站或IP地址的托管信息，如ASN、ISP、位置等。此外，还包含多种与托管和DNS相关的工具。
  * [newreleases.io](https://newreleases.io/) - 可接收来自GitHub、GitLab、Bitbucket、Python PyPI、Java Maven、Node.js NPM、Node.js Yarn、Ruby Gems、PHP Packagist、.NET NuGet、Rust Cargo以及Docker Hub等平台的新发布通知，可通过电子邮件、Slack、Telegram、Discord以及自定义Web钩子来接收通知。
  * [OnlineExifViewer](https://onlineexifviewer.com/) — 可在线即时查看照片的EXIF数据，包括GPS位置和元数据。  * [PDFMonkey](https://www.pdfmonkey.io/) — 通过仪表板管理PDF模板，调用带有动态数据的API，并下载您的PDF文件。每月提供300份免费文档。
  * [Pika Code截图](https://pika.style/templates/code-image) — 使用该扩展程序，从代码片段和VSCode中生成美观、可定制的截图。
  * [QuickType.io](https://quicktype.io/) — 能够快速从JSON、模式以及GraphQL中自动生成模型、类、类型、接口以及序列化器，以便在任何编程语言中快速且安全地处理数据。可以将JSON转换为任何语言下的美观且类型安全的代码。
  * [RandomKeygen](https://randomkeygen.com/) — 一款免费的、适用于移动设备的工具，提供多种随机生成的密钥和密码，可用于保护任何应用程序、服务或设备。
  * [ray.so](https://ray.so/) — 为您的代码片段创建美观的图像。
  * [readme.com](https://readme.com/) — 美观的文档制作工具，开源且免费。  * [redirect.pizza](https://redirect.pizza/) — 支持HTTPS的便捷重定向管理工具。免费计划包含10个重定向源，每月可处理100,000次重定向请求。
  * [redirection.io](https://redirection.io/) — 用于企业、营销和SEO的HTTP重定向管理SaaS工具。
  * [Renamer.ai](https://renamer.ai) — 基于AI的文件重命名工具，具备OCR功能、元数据提取功能，并支持多语言操作。免费套餐：每月可处理15个文件，包含桌面应用程序、批量重命名功能、自动重命名功能以及常规支持。
  * [ReqBin](https://reqbin.com/) — 在线发送HTTP请求的工具。支持的请求方法包括GET、POST、PUT、DELETE和HEAD等。支持头部信息和令牌认证。还包含基本的登录系统，可用于保存您的请求信息。
  * [Smartcar API](https://smartcar.com) — 用于汽车定位、获取燃油箱状态、电池电量、里程表信息、解锁/锁定车门等功能的应用程序接口。  * [Snappify](https://snappify.com) - 帮助开发者创建精美的视觉效果。从优美的代码片段到完整的技术演示。免费计划支持一次最多3个项目的创建，且可无限下载，每月还有5次由人工智能驱动的代码解释功能。
  * [Sunrise and Sunset](https://sunrisesunset.io/api/) - 提供特定经纬度位置的日出和日落时间信息。
  * [superfeedr.com](https://superfeedr.com/) — 提供实时符合PubSubHubbub标准的订阅服务，支持导出和分析数据。免费使用，但定制功能较少。
  * [SurveyMonkey.com](https://www.surveymonkey.com) — 在线创建调查问卷，并可在线上分析结果。免费计划仅允许创建10个问题和100个回答。
  * [UUID Generator](https://newuuid.com/) - 可即时生成UUID v1、UUID v4、UUID v7、GUID、Nil UUIDs、CUID v1/v2、NanoID以及ULID，性能达到企业级标准。  * [Versionfeeds](https://versionfeeds.com) — 为您喜爱的软件发布版本提供自定义的RSS订阅源。只需在一个订阅源中即可获取您编程语言、库或常用工具的最新版本。（前3个订阅源是免费的）
  * [videoinu](https://videoinu.com) — 在线创建和编辑屏幕录像及其他视频。
  * [Volume Shader BM](https://volumeshaderbm.org) — 免费的基于浏览器的GPU性能测试工具（WebGL）。帮助开发者跨浏览器和设备进行可重复性的着色器性能测试与比较。
  * [Webacus](https://webacus.dev) — 提供丰富的免费开发工具，用于编码、解码和数据处理。
  * [XKit](https://xkit.io) — 一系列免费在线工具，旨在为开发者、学生和日常用户带来便利。包括各种开发工具、差异比较工具、计算器、转换器和生成器。
 性能与安全

**[⬆️ 返回顶部](#目录)

## 远程桌面工具  * [AnyDesk](https://anydesk.com) — 适用于3台设备，无需限制会话数量及持续时间，免费使用。
  * [Getscreen.me](https://getscreen.me) — 适用于2台设备，同样无需限制会话数量及持续时间，免费使用。
  * [RemSupp](https://remsupp.com) — 提供按需支持服务，并允许永久访问设备，每天可免费进行2次会话。
  * [RustDesk](https://rustdesk.com/) — 开源虚拟/远程桌面基础设施，适用于所有人！

**[⬆️ 返回顶部](#目录)

## 游戏开发

  * [3Dassets.one](https://3dassets.one/) — 提供超过8,000个免费/付费3D模型以及PBR材质，可用于制作纹理。
  * [ArtStation](https://www.artstation.com/) — 提供免费/付费2D、3D素材、音频、图标、瓦片集、游戏套件等。也可用于展示您的艺术作品集。
  * [CraftPix](https://craftpix.net) — 提供免费/付费的2D、3D素材、音频、GUI、背景、图标、瓦片集、游戏套件等。  * [Freesound](https://freesound.org/) - 提供免费且可协作使用的声音库，采用不同的CC许可证。
  * [Game Icons](https://game-icons.net/) - 提供可自由编辑的SVG/PNG图标，采用CC-BY许可证。
  * [GameDevMarket](https://gamedevmarket.net) — 提供免费或付费的游戏素材，包括2D、3D、音频、GUI等。
  * [Gamefresco.com](https://gamefresco.com/) — 供人们发现、收集并分享来自游戏艺术家的免费游戏素材。
  * [itch.io](https://itch.io/game-assets) — 提供免费或付费的游戏素材，如精灵图、瓦片集、角色包等。
  * [Kenney](https://www.kenney.nl/assets/) - 提供免费（CC0 1.0通用许可证）的2D、3D、音频和UI游戏素材。
  * [LoSpec](https://lospec.com/) — 提供在线工具，用于创建像素艺术及其他限制性数字艺术，并提供大量教程和素材列表，可供游戏使用。
  * [OpenGameArt](https://opengameart.org) — 提供开源的游戏素材，如音乐、声音、精灵图、GIF等。  * [Poliigon](https://www.poliigon.com/) - 提供免费和付费的纹理、模型、HDRI以及画笔资源。还提供免费插件，可导出至Blender等软件。
  * [Poly Pizza](https://poly.pizza/) - 提供免费的低多边形3D素材。

**[⬆️ 返回顶部](#目录)

## 其他免费资源

  * [360Converter](https://www.360converter.com/) - 提供免费服务，可用于将视频转换为文本、音频转换为文本、语音转换为文本、实时音频转换为文本，以及将YouTube视频转换为文本，并添加视频字幕。在短视频转换或简短的YouTube教程制作中可能会非常有用。)
  * [AdminMart](https://adminmart.com/) — 提供高质量的自由版和高级版管理面板及网站模板，采用Angular、Bootstrap、React、VueJs、NextJS和NuxtJS技术构建！
  * [Buttons Generator](https://markodenic.com/tools/buttons-generator/) — 提供100多种可用于项目的按钮模板。  * [ElevateAI](https://www.elevateai.com) - 每月可免费获得高达200小时的音频转录服务。
  * [Framacloud](https://degooglisons-internet.org/en/) — 由法国非营利组织[Framasoft](https://framasoft.org/en/)提供的免费/开源软件及SaaS服务列表。
  * [Free Code Tools](https://freecodetools.org/) — 完全免费的实用代码工具。包括Markdown编辑器、代码压缩美化工具、二维码生成器、Open Graph生成器、Twitter卡片生成器等。
  * [get.localhost.direct](https://get.localhost.direct) — 为本地主机开发设计的更好的`*.localhost.direct`通配符公共SSL证书，支持子域名。
  * [GitHub Education](https://education.github.com/pack) — 为学生提供的免费服务集合。需要注册。
  * [Glob tester](https://globster.xyz/) — 一个可以设计和测试glob模式的网站。还提供了学习glob模式的资源。  * [It Tools](https://it-tools.tech/) – 适用于开发者和IT行业工作者的实用工具。
  * [JSON Viewer Tool](https://jsonviewertool.com/) – 可在浏览器中直接查看、格式化、验证、压缩和转换JSON数据（无需API密钥）。
  * [Killer Coda](https://killercoda.com/) – 在浏览器中提供的互动式学习平台，可用于学习Linux、Kubernetes、容器技术、编程、DevOps以及网络相关技能。
  * [Kody Tools](https://www.kodytools.com/dev-tools) – 包含多种开发工具，如格式化工具、压缩工具和转换工具等。
  * [Markdown Tools](https://markdowntools.com) – 用于将HTML、CSV、PDF、JSON和Excel文件转换为Markdown格式的工具。  * [Microsoft 365 开发者计划](https://developer.microsoft.com/microsoft-365/dev-program) — 获取免费的沙盒、工具以及其他资源，以便为 Microsoft 365 平台构建解决方案。该订阅是 90 天的 [Microsoft 365 E5 订阅](https://www.microsoft.com/microsoft-365/enterprise/e5)（Windows 系统除外），且可续订。如果您在开发过程中保持活跃（通过遥测数据和算法进行衡量），则仍可续订该订阅）。
  * [MySQL 可视化解释工具](https://mysqlexplain.com) — 易于理解且免费的 MySQL EXPLAIN 输出可视化工具，可用于优化慢查询。
  * [PageTools](https://pagetools.co/) — 提供一系列永久免费的 AI 驱动工具，帮助您生成必要的网站模板、创建社交媒体个人简介、帖子以及网页，只需简单的一键式操作即可完成。
  * [Pyrexp](https://pythonium.net/regex) — 免费的基于 Web 的正则表达式测试器和可视化工具，可用于调试正则表达式。  * [RedHat for Developers](https://developers.redhat.com) — 专为开发者提供的Red Hat产品免费访问服务，包括RHEL、OpenShift、CodeReady等。仅限个人使用。还提供免费电子书以供参考。
  * [regex101.com](https://regex101.com/) — 该网站可免费测试与调试正则表达式。提供正则表达式编辑器与测试工具，以及有助于学习正则表达式的文档和资源。
  * [sandbox.httpsms.com](https://sandbox.httpsms.com) — 可免费发送和接收测试短信。
  * [SimpleBackups.com](https://simplebackups.com/) — 为服务器和数据库（MySQL、PostgreSQL、MongoDB）提供自动备份服务，备份数据直接存储于云存储提供商（AWS、DigitalOcean和Backblaze）中。提供免费备份服务，最多可备份1个数据。
  * [SimpleRestore.io](https://simplerestore.io) — 无需繁琐操作即可恢复MySQL备份。无需编写代码或拥有服务器，即可将MySQL备份恢复到任何远程数据库。  * [SnapShooter](https://snapshooter.com/) — 适用于DigitalOcean、AWS、LightSail、Hetzner和Exoscale的备份解决方案，支持直接对数据库、文件系统和应用程序进行备份，并将备份数据存储在s3存储中。提供免费方案，每天可备份一个资源。
  * [Table Format Converter](https://www.tableformatconverter.com) - 一款免费工具，可将表格数据转换为多种格式，如CSV、HTML、JSON、Markdown等。
  * [Themeselection](https://themeselection.com/) — 精选的高质量、现代设计、专业且易于使用的免费管理面板模板。
  * [ToolsHref](https://toolshref.com) - 一套免费的开发工具集，包括Java代码生成（JSON转POJO、cURL转Java）、静态分析以及DevOps配置构建工具（Docker、K8s、Nginx）。  * [Utils.fun](https://utils.fun/en) — 所有基于浏览器计算能力的离线日常及开发工具，包括水印生成、屏幕录制、编码解码、加密解密以及代码格式处理等功能，全部免费，且不会将数据上传到云端进行处理。
  * [Wikimint开发者工具](https://developer.wikimint.com/p/tools.html) — 专为网页开发者设计的免费工具，包括CSS压缩与解压缩、图片优化、图片调整大小、大小写转换、CSS验证、JavaScript编译器、HTML编辑器等。
  * [WrapPixel](https://www.wrappixel.com/) — 下载由Angular、React、VueJs、NextJS和NuxtJS构建的高质量免费及高级管理面板模板！HTML主题和UI组件可帮助您更快地创建应用程序！
**[⬆️ 返回顶部](#table-of-contents)**