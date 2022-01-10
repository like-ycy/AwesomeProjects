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


## 项目

- [JustAuth](https://github.com/justauth/JustAuth)

  JustAuth，如你所见，它仅仅是一个**第三方授权登录**的**工具类库**，它可以让我们脱离繁琐的第三方登录 SDK，让登录变得 **So easy!**

  JustAuth 集成了诸如：Github、Gitee、支付宝、新浪微博、微信、Google、Facebook、Twitter、StackOverflow 等国内外数十家第三方平台。更多请参考[已集成的平台](https://justauth.wiki/)

- [代码安全指南](https://github.com/Tencent/secguide)

  面向开发人员梳理的代码安全指南，旨在梳理 API 层面的风险点并提供详实可行的安全编码方案。

