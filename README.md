# AwesomeProjects

AwesomeProjects 收集整理工作及生活中看到的高质量、有趣的开源项目，并将他们进行归类。省的浏览器一堆收藏。

### 云原生

- [sealer](https://github.com/sealerio/sealer)  sealer[ˈsiːlər]是一款分布式应用打包交付运行的解决方案，通过把分布式应用及其数据库中间件等依赖一起打包以解决应用整个集群整体交付问题。 sealer构建出来的产物我们称之为"集群镜像", 集群镜像里内嵌了一个kubernetes, 解决了分布式应用的交付一致性问题。 集群镜像可以push到registry中共享给其他用户使用，也可以在官方仓库中找到非常通用的分布式软件直接使用。
- [sealos](https://github.com/labring/sealos) **一条命令部署 Kubernetes 高可用集群**
- [KubeGems](https://github.com/kubegems/kubegems)  一款超强大面向云原生的通用开源 PaaS 管理平台，支持 Argo CD、Istio 等 30+ 开源服务
- [Porter](https://github.com/porter-dev/porter) 一个由 Kubernetes 驱动的 PaaS 系统（Heroku 开源平替版)

### Git

- [git-cliff](https://github.com/orhun/git-cliff)  一款**基于 Git 历史记录**自动生成日志变更文件。

### Kubernetes

- [Kubermetrics](https://github.com/oslabs-beta/kubermetrics)  提供`Kubernetes`集群监视以及数据可视化在一个简单和容易理解的用户接口。

- [kubectl-debug](https://github.com/aylei/kubectl-debug)  kubectl 插件, 能够帮助你便捷地进行 Kubernetes 上的 Pod 排障诊断。

- [kubecolor](https://github.com/dty1er/kubecolor)  对kubectl命令输出进行着色。

- [regclient](https://github.com/regclient/regclient)

  regclient 是一个 CLI 工具库，用来操作 Docker 镜像和 OCI 镜像，无需下载镜像即可对其重新打 tag，还可以查看 tag 和 manifests 等信息。它总共包含了 3 个 CLI 工具，功能各不相同，非常强大。

- [Buildpacks](https://buildpacks.io/)  新型镜像构建技术

- [containerd-shim-systemd-v1](https://github.com/cpuguy83/containerd-shim-systemd-v1)

  containerd-shim-systemd-v1 这个项目实现了 containerd shim，可以使用 Systemd 来管理容器。与标准的 runc shim (io.containerd.runc.v2)，具有以下优势：

  - 可以使用 systemd 管理容器。
  - 如果使用标准的 runc shim，则每个容器（或 Pod）都需要一个 shim；而 containerd-shim-systemd-v1 每个节点只需一个 shim，运行时开销为 O(1)。
  - Shim 可以随意重启，不会影响容器正常运行。

- [Kustomizer](https://github.com/stefanprodan/kustomizer)

  Kustomizer 是一个比较有新意的软件包管理器，用于将 Kubernetes 的配置清单打包成 OCI 镜像，然后推送到 OCI 镜像仓库。还可以在线修改配置更新镜像。

- [Kubectl-Ice](https://github.com/NimbleArchitect/kubectl-ice/releases)  一款超强大的 Kubernetes Pod 资源终端管理工

- [Kube-capacity CLI](https://github.com/robscott/kube-capacity)

  `Kube-capacity` 是一个简单而强大的 `CLI`，它提供了`Kubernetes`集群中资源请求、限制和利用率的概览。它将输出的最佳部分结合`kubectl top`到`kubectl describe`一个易于使用的集中于集群资源的 `CLI` 中。
  
- [klock](https://github.com/robert-nemet/klock)

  klock 是一个资源锁，通过 CRD 来锁定 Kubernetes 中的资源，以防止被误删除或者误更新。例如：

  ```yaml
  apiVersion: klock.rnemet.dev/v1
  kind: Lock
  metadata:
    name: lock-sample
    namespace: test
  spec:
    operations:
      - UPDATE
      - DELETE
    matcher:
      test: test
  ```

  这样你就无法对打了标签 `test: test` 的资源执行更新或者删除操作。

### prometheus

- [karma](https://github.com/prymitive/karma)  一款超高颜值的 Alertmanager 可视化面板


### 浏览器插件

- [Neverinstall](https://neverinstall.com/)

  Neverinstall 是一个云平台，可将任何桌面应用程序带入浏览器，不用在本地安装，不受硬件限制，真正可以从任何地方访问。免费用户一次只能运行一个应用。

- [omni](https://github.com/alyssaxuu/omni)

  Chrome 最强大的界面 🔥，一款浏览器插件。

  借助 Omni，您可以像专业人士一样使用 Chrome。使用简单的命令界面管理选项卡、书签、浏览器历史记录、执行各种操作等等。

  🗄 切换、打开、关闭和搜索您的标签
  📚 浏览和管理您的书签
  🔍 搜索您的浏览历史记录
  ⚡️ 50 多项提高生产力的措施
  🔮 用于过滤和执行更多操作的特殊命令
  🧩 与 Notion、Figma、Docs、Asana 的集成......
  ⌨️ 静音、固定、书签等操作的快捷方式...
  ⚙️ 有助于解决浏览问题的高级设置
  🌙黑暗模式
  ...... 以及更多 - 全部免费且无需登录！

- [github-x](https://github.com/riskers/GithubX)  款增强 Github 体验的 Chrome 插件

- [Bilibili-Evolved](https://github.com/the1812/Bilibili-Evolved)  强大的哔哩哔哩增强脚本, 供了非常多开箱即用的功能比如广告删除、夜间模式.

- [Automa ](https://github.com/Kholid060/automa)  一个用于 Chrome 浏览器自动化的插件，从自动填写表格、执行重复性任务、截屏、抓取网站数据等等，完全可以根据你自己的需求来决定如何使用。



### Redis

- [Another Redis Desktop Manager](https://gitee.com/qishibo/AnotherRedisDesktopManager)  redis桌面管理工具，可以运行于Linux、Windows、Mac三大平台。

### 文档

- [Mark text](https://github.com/marktext/marktext)  另一款markdown编辑器

### Mac软件

- [MenubarX](https://menubarx.app/)

  MenubarX 是一款强大的 Mac 菜单栏浏览器，可以在菜单栏固定任何网页，就像原生 App 一样使用，支持调整窗口大小。

- [touchbar-systemmonitor](https://github.com/spagnuolocarmine/touchbar-systemmonitor)

  touchbar 系统监视器, 可以在 touchbar 上显示 CPU, 内存，网络流量，磁盘使用量，电池信息等。

- [Raycast ](https://www.raycast.com/)

  Raycast 是一款类似 Spotlight 和 Alfred 的启动器, 提供了更多功能。

- [wrap 很棒的终端软件](https://www.warp.dev/)

  WARP 是一个速度极快、基于 RUST 的终端，从头开始重新构想，可以像现代应用程序一样工作。

- [Tart](https://github.com/cirruslabs/tart)

  Tart 是一个虚拟化工具集，用于构建、运行和管理 Apple Silicon 芯片 macOS 上的虚拟机，主要目的是为 CI 流水线的特殊任务提供运行环境。主要亮点：

  - 使用 macOS 最新的虚拟化框架 `Virtualization.Framework` 来创建虚拟机。
  - 可以从 OCI 镜像仓库中拉取/推送虚拟机镜像。
  - 可以使用 Tart 的 Packer 插件来自动化虚拟机创建流程。
  - 内置 CI 集成。

- [bob](https://github.com/ripperhe/Bob)  一款免费的 Mac 端翻译软件，支持划词翻译和截图翻译，甚至还有语音合成功能，现在支持很多翻译引擎。

### Linux

- [Tmux](https://github.com/tmux/tmux)

  Tmux 可用于在一个终端窗口中运行多个终端会话。不仅如此，还可以通过 Tmux 使终端会话运行于后台或是按需接入、断开会话，这个功能非常实用。

- [HeySpace](https://github.com/louisun/HeySpace)

  HeySpace 是一款帮你优化排版，提升阅读体验的「命令行工具」。

  - 核心功能：**中英文之间添加空格**
  - 去除连续两个以上的空行
  - 兼容 Markdown 格式
  - 支持剪贴板输入输出，复制内容处理后可直接粘贴
  - **支持文件、目录的输入和输出**；支持文件备份

- [oh my zsh](https://github.com/ohmyzsh/ohmyzsh)

  美化shell

- [asciinema ](https://asciinema.org/)

  是一个免费的开源解决方案，用于记录终端会话并在网络上共享它们。对终端命令进行录制并分享，不是录屏哈。

- [Atuin](https://github.com/ellie/atuin)

  shell 历史记录工具

  Atuin 🐢 使用 SQLite 数据库取代了你现有的 shell 历史，并为你的命令记录了额外的内容，可以通过一个非常美观的 UI 界面进行操作。此外，它还通过 Atuin 服务器，在节点之间提供可选的、完全加密的历史记录同步功能。
  
- [gum](https://github.com/charmbracelet/gum)  用于制作迷人 shell 脚本的工具。在您的脚本和别名中利用[Bubbles](https://github.com/charmbracelet/bubbles)和[Lip GLoss](https://github.com/charmbracelet/lipgloss)的强大功能，而无需编写任何 Go 代码！

### 抓包工具

- Fiddler

- wireshark

- Charles

- [Proxyman](https://proxyman.io/)

### 接口

- [API Hub](apifox.cn/apihub/)

  **API Hub** 是国产 API 管理工具 Apifox 里面相对独立的模块。

  API Hub 收录了国内各大厂商热门的 API 开放项目，如企业微信 API, 快手开放 API，抖音开放 API，目前还在持续收录中；另一方面它依托于 Apifox，能提供对开放 api 进行调试、mock 等功能。

### 个人网站

- [vcard-personal-portfolio](https://github.com/codewithsadee/vcard-personal-portfolio)  用来展示个人信息的网站

### 项目

- [JustAuth](https://github.com/justauth/JustAuth)

  JustAuth，如你所见，它仅仅是一个**第三方授权登录**的**工具类库**，它可以让我们脱离繁琐的第三方登录 SDK，让登录变得 **So easy!**

  JustAuth 集成了诸如：Github、Gitee、支付宝、新浪微博、微信、Google、Facebook、Twitter、StackOverflow 等国内外数十家第三方平台。更多请参考[已集成的平台](https://justauth.wiki/)

- [代码安全指南](https://github.com/Tencent/secguide)

  面向开发人员梳理的代码安全指南，旨在梳理 API 层面的风险点并提供详实可行的安全编码方案。

### github相关

- 指定某张图片在 Dark 模式下的显示效果

  ```html
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
    <img alt="Shows an illustrated sun in light color mode and a moon with stars in dark color mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  </picture>
  ```



- [Repobeats](https://repobeats.axiom.co/)

  Repobeats 是一种将贡献者分析嵌入到 GitHub 项目的 README.md 中的方法

  使用 Repobeats，您的项目的贡献者和用户可以清楚、漂亮地了解您的项目如何随着时间的推移而发展。

- [github 趋势](https://www.githubtrends.io)  统计过去一年中你的代码贡献趋势及编程语言趋势，并在README中展示。

- [awesome-github-profile-readme](https://github.com/abhisheknaiidu/awesome-github-profile-readme)

  里面有很多优质有趣的github主页装扮案例😄，可以参考源代码，快速装扮自己的主页。

  配套网站: https://awesomegithubprofile.tech/

  网站示例：技术大佬型	 https://github.com/thmsgbrt

  ​		二次元程序员   https://github.com/edisonlee55

  ​		递归调用型	 https://github.com/vanshkapoor

  ​		忙碌打码型	 https://github.com/alwinw

  ​		简简单单挺好	https://github.com/alwinw

  ​					  https://github.com/Volcano-Yang

- [打印 GitHub 贡献图](https://github.com/djyde/ossart)

  将 Github 的贡献图打印出来

- [打印 GitHub issue 小票](https://aschmelyun.com/blog/i-built-a-receipt-printer-for-github-issues/)

  借助树莓派与 GitHub Action, 每次当有人给你提交一个 GitHub issue 时，就会跟在超市买东西一样，在打印机弹出一张小票

- [shields](https://github.com/badges/shields)  输入项目的链接即可定制属于自己的徽章。

  https://shields.io/

- [probot](https://github.com/probot/probot)

  用于构建 GitHub 应用程序以自动化和改进您的工作流程的框架

- [octicons](https://github.com/primer/octicons)

  Octicons 是一款开源免费字体图标库，也是 GitHub 目前使用的图标库，GitHub 已将这个图标开源分享给广大的开发者使用，Octicons 包含多种形式的图标文件，包括字体图标、SVG 文件等。

- [all-contributors](https://github.com/all-contributors/all-contributors)

  这是一个用于认可开源项目贡献者的规范，不仅仅是代码，它感谢每一个贡献。

  基本想法是：

  > 使用项目README (或者项目中其他重要的公开文档页) 来认可项目社区成员的贡献。

  人们花费自己的空闲时间，以各种方式为开源项目努力，因此每个人的贡献，不管是不是代码，都应该受到赞扬。

- [starter-workflows](https://github.com/actions/starter-workflows)

  从构思到生产的工作流程自动化

  GitHub Actions 可让您轻松自动化所有软件工作流程，现在使用世界一流的 CI/CD。

  直接从 GitHub 构建、测试和部署您的代码。让代码审查、分支管理和问题分类以您想要的方式工作。

- [metrics](https://github.com/lowlighter/metrics)

  具有 30 多个插件和 200 多个选项的信息图表生成器，用于显示有关您的 GitHub 帐户的统计信息并将它们呈现为 SVG、Markdown、PDF 或 JSON！

- [github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy)

  GitHub 个人资料奖杯 🏆在您的自述文件中添加动态生成的 GitHub Stat Trophies


### 工具

- [rembg](https://github.com/danielgatis/rembg)

  Rembg 是一个去除图像背景的工具。开发者已经封装好了，用法非常简单，可以进入下方的链接查看。



### 博客相关

- [一言](https://hitokoto.cn/#)  为网站提供一句话服务，一句话，可以是动漫中的台词，也可以是网络上的各种小段子。
- [Astro](https://github.com/withastro/astro) Astro 是一款现轻量级的静态网站生成器，在 GitHub 上已经斩获 18K 的 Star。该项目可以提供详细的中文教程，只要你具备基本的前端编程基础，就能快速搭建一个属于自己的静态网站。

### 其他

- [后盾人](https://doc.houdunren.com/)  后盾人在线文档，前端学习及vscode插件推荐
- [猫爪导航🐱](https://v2fy.com/)  各种工具及资源的推荐
- [正则大全](https://any86.github.io/any-rule/)  提供常见的正则匹配
- [BT下载Tracker](https://trackerslist.com/#/zh)  提高BT下载速度



### Go相关项目

?> 为以后转行做准备

- [gotests](https://github.com/cweill/gotests)

  自动生成 Go 语言测试代码的工具。该项目基于表驱动测试法（TableDrivenTests）自动生成测试代码，表驱动测试法是创建一张数据表格，每一行为输入和预期输出值，然后用这张表格的数据测试代码

- [Sharingan ](https://github.com/didi/sharingan)

  Sharingan 是一个基于 Golang 的流量录制回放工具，录制线上真实请求流量进行回放测试，适合项目重构、回归测试等。

- [GoAdmin](https://gitee.com/go-admin/go-admin)

  GoAdmin 可以帮助你的golang应用快速实现数据可视化，搭建一个数据管理平台。10 分钟内做一个好看的管理后台，开箱即用的 rbac 认证系统。

- [go学习库](https://github.com/hwholiday/learning_tools)

  这个开源项目包含 Go 学习资料、Go 进阶资料、实用工具类、DDD 项目落地、Go-kit 、Go-Micro 、Go 推送平台、微服务实践等相关内容。

- [monitoror](https://github.com/monitoror/monitoror)

  平铺的监控工具。安装简单配置方便的“监控墙”，所有监控指标以平铺的方式展示，美观且一目了然。支持 Linux、macOS 和 Windows 主流操作系统

- [casdoor](https://github.com/casdoor/casdoor)

  提供登陆界面的身份访问管理平台。提供中文界面的用户管理后台，支持多种第三方登录、单点登录以及手机/邮箱验证码、找回密码等功能

- [GoFound ](https://gitee.com/tompeppa/gofound)

​	一个golang实现的全文检索引擎 基于平衡二叉树+正排索引、倒排索引实现 可支持亿级数据，毫秒级查询。使用简单，使用	http接口，任何系统都可以使用。



### Python项目

- [pikepdf](https://github.com/pikepdf/pikepdf) 用于读取和写入 PDF 文件的 Python 库

- [docker-py](https://github.com/docker/docker-py) 用 Python 操作 Docker 的库。Docker 官方出品的 Python 库，可以用来批量、自动管理镜像

- [memray](https://github.com/bloomberg/memray)

  Python 的内存分析器。帮你分析 Python 应用的内存使用情况，找到内存泄漏的原因、占用内存多的代码、内存使用率高的原因。支持生成内存报告（火焰图、表格、树状图）和实时报告等模式，以及统计结果等功能

- [Geopandas](https://geopandas.readthedocs.io/)一行代码算出每个省面积的神器

- [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)  百度飞桨ocr识别

- [PPOCRLabel](https://github.com/PaddlePaddle/PaddleOCR/tree/release/2.5/PPOCRLabel)  OCR半自动数据标注工具

- [APIFlask](https://github.com/apiflask/apiflask)  APIFlask是一个基于[Flask](https://github.com/pallets/flask)和 [marshmallow-code](https://github.com/marshmallow-code)项目的轻量级Python Web API框架。它易于使用，高度可定制，ORM / ODM不可知，并且与Flask生态系统100%兼容。

