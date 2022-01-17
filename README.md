# Awesome Tools&Projects

此项目收集了一些有趣的工具和项目，在此记录，省的浏览器一堆收藏。


## 工具

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




### 浏览器

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

### Redis

- [**Another Redis Desktop Manager**](https://gitee.com/qishibo/AnotherRedisDesktopManager)  redis桌面管理工具，可以运行于Linux、Windows、Mac三大平台。

### 文档

- [Mark text](https://github.com/marktext/marktext)  另一款markdown编辑器

### Mac

- [MenubarX](https://menubarx.app/)

  MenubarX 是一款强大的 Mac 菜单栏浏览器，可以在菜单栏固定任何网页，就像原生 App 一样使用，支持调整窗口大小。

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

- [oh my zsh](https://github.com/ohmyzsh/ohmyzsh)  美化shell

- [asciinema ](https://asciinema.org/)  是一个免费的开源解决方案，用于记录终端会话并在网络上共享它们。对终端命令进行录制并分享，不是录屏哈。


## 项目

- [JustAuth](https://github.com/justauth/JustAuth)

  JustAuth，如你所见，它仅仅是一个**第三方授权登录**的**工具类库**，它可以让我们脱离繁琐的第三方登录 SDK，让登录变得 **So easy!**

  JustAuth 集成了诸如：Github、Gitee、支付宝、新浪微博、微信、Google、Facebook、Twitter、StackOverflow 等国内外数十家第三方平台。更多请参考[已集成的平台](https://justauth.wiki/)

- [代码安全指南](https://github.com/Tencent/secguide)

  面向开发人员梳理的代码安全指南，旨在梳理 API 层面的风险点并提供详实可行的安全编码方案。

### github

- [Repobeats](https://repobeats.axiom.co/)

  Repobeats 是一种将贡献者分析嵌入到 GitHub 项目的 README.md 中的方法

  使用 Repobeats，您的项目的贡献者和用户可以清楚、漂亮地了解您的项目如何随着时间的推移而发展。

- [github 趋势](https://www.githubtrends.io)  统计过去一年中你的代码贡献趋势及编程语言趋势，并在README中展示。

## 博客

- [一言](https://hitokoto.cn/#)  为网站提供一句话服务，一句话，可以是动漫中的台词，也可以是网络上的各种小段子。

## 其他

- [后盾人](https://doc.houdunren.com/)  后盾人在线文档，前端学习及vscode插件推荐
- [猫爪导航🐱](https://v2fy.com/)  各种工具及资源的推荐
- [正则大全](https://any86.github.io/any-rule/)  提供常见的正则匹配

- [BT下载Tracker](https://trackerslist.com/#/zh)  提高BT下载速度

