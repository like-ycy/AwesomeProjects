# AwesomeProjects

AwesomeProjects 收集整理工作及生活中看到的高质量、有趣的开源项目，并将他们进行归类。省的浏览器一堆收藏。

### ChatGPT 相关

- [openai-translator](https://github.com/yetone/openai-translator) 

  一个基于 OpenAI 的翻译插件 + 桌面端应用，支持翻译、润色和总结三种模式，以及 55 种语言的互相翻译。

- [ChatGPT 快捷键](https://github.com/rockbenben/ChatGPT-Shortcut) 

  当你想问 ChatGPT 一些问题，却得不到你想要的答案，此时你可以试一试 ChatGPT Shortcut。这是一个让你使用 ChatGPT 时生产力翻倍的快捷指令网站。

  你只需在该开源项目中复制提示词，稍加修改后发送给 ChatGPT，就能获得你期望的输出，让你的生产力加倍！

- [wukong-robot](https://github.com/liuhaogui/wukong-robot)

  一个智能语音对话机器人，可以以语音或文本方式与用户进行对话。其特点是支持个性化定制和插件扩展，可以根据用户的需求进行灵活定制和扩展。

  比如可以集成 Open AI、腾讯、百度、科大讯飞等语音识别技术，同时还能和 ChatGPT、Siri、小爱同学进行联动。

- [ChatPaper](https://github.com/kaixindelele/ChatPaper) 

  该项目可根据用户关键词下载 arXiv 上的最新论文，利用 ChatGPT3.5 API 强大的归纳能力，将其浓缩成固定格式，文字少且易读。

- [川虎 ChatGPT](https://github.com/GaiZhenbiao/ChuanhuChatGPT)  

  该项目为 ChatGPT API 提供了一个 Web 图形界面，在本地部署后，你只需填上自己的 Key，便能直接使用。

- [roomGPT](https://github.com/Nutlope/roomGPT) 

  你只需要给你的房间拍一张照，或是房间的 3D 效果图，并将其上传，即可用 AI 生成对应的梦幻房间效果图。

- [DocsGPT](https://github.com/arc53/DocsGPT) 

  是一种尖端的开源解决方案，可简化在项目文档中查找信息的过程。通过集成强大的 **GPT** 模型，开发人员可以轻松提出有关项目的问题并获得准确的答案。

- [chatgpt-on-wechat](https://github.com/zhayujie/chatgpt-on-wechat) 

  基于 ChatGPT 的微信聊天机器人，通过 [ChatGPT](https://github.com/openai/openai-python) 接口生成对话内容，使用 [itchat](https://github.com/littlecodersh/ItChat) 实现微信消息的接收和自动回复

### 云原生

- [sealer](https://github.com/sealerio/sealer)  

  sealer[ˈsiːlər]是一款分布式应用打包交付运行的解决方案，通过把分布式应用及其数据库中间件等依赖一起打包以解决应用整个集群整体交付问题。 sealer构建出来的产物我们称之为"集群镜像", 集群镜像里内嵌了一个kubernetes, 解决了分布式应用的交付一致性问题。 集群镜像可以push到registry中共享给其他用户使用，也可以在官方仓库中找到非常通用的分布式软件直接使用。

- [sealos](https://github.com/labring/sealos) 

  一条命令部署 Kubernetes 高可用集群

- [KubeGems](https://github.com/kubegems/kubegems)  

  一款超强大面向云原生的通用开源 PaaS 管理平台，支持 Argo CD、Istio 等 30+ 开源服务

- [Porter](https://github.com/porter-dev/porter) 

  一个由 Kubernetes 驱动的 PaaS 系统（Heroku 开源平替版)

- [Crane](https://gocrane.io/)  

  一个基于 FinOps 的云资源分析与成本优化平台，它的愿景是在保证客户应用运行质量的前提下实现极致的降本。
  
- [skaffol](https://github.com/GoogleContainerTools/skaffold)

  Skaffold 是一个命令行工具，有助于持续开发 Kubernetes 应用程序。您可以迭代应用程序源代码 在本地，然后部署到本地或远程 Kubernetes 集群。脚手架手柄 用于构建、推送和部署应用程序的工作流。它还 提供构建基块并描述 CI/CD 管道的自定义项。

### Git

- [git-cliff](https://github.com/orhun/git-cliff)  

  一款**基于 Git 历史记录**自动生成日志变更文件。

### Docker

- [static](https://github.com/chainguard-images/static)

  static 与 `busybox`、`alpine` 和 `google/distroless` 类似，都属于基础镜像范畴，不过它是专门用来运行静态编译二进制文件的。
  
- [Copacetic](https://github.com/project-copacetic/copacetic)  

  Copacetic 是一个使用 Go 语言编写的 CLI 工具，它可以根据 Trivy 等工具的漏洞扫描结果直接修补正在运行的容器，不需要上游重新构建完整的镜像。

### eBPF

- [Caretta](https://github.com/groundcover-com/caretta)  

  这个项目可以在 Grafana 监控面板中显示 K8s Service 之间的依赖关系。底层使用的是 eBPF，对应用无侵入。

- [NetWorth](https://github.com/ShubhamPalriwala/NetWorth)  

  这个项目使用 eBPF 与 XDP 来监控主机的入站流量，包含地理位置、网络协议类型或数量、CPU 使用率等等，并使用 Grafana 监控面板来展示监控数据。

### Kubernetes

- [Lens](https://k8slens.dev/)  

  Lens 是一个**Kubernetes IDE**，在桌面环境下使用它，来开发、调试、DevOps、运维和监控。

  它有很多强大的功能，其中：Catalog、Hotbar、命令面板、监控、智能终端、资源模板、Helm Chart 管理和插件 这些功能一定要试一试，体验飞升！

- [krew](https://github.com/kubernetes-sigs/krew)  

  Krew 是 `kubectl` 命令行工具的插件管理器。

  Krew 可以帮助你:

  •发现 kubectl 插件•将它们安装到您的机器上•并保持安装的插件是最新的

- [Kubermetrics](https://github.com/oslabs-beta/kubermetrics)  

  提供`Kubernetes`集群监视以及数据可视化在一个简单和容易理解的用户接口。

- [kubectl-debug](https://github.com/aylei/kubectl-debug)  

  kubectl 插件, 能够帮助你便捷地进行 Kubernetes 上的 Pod 排障诊断。

- [kubecolor](https://github.com/dty1er/kubecolor)  

  对kubectl命令输出进行着色。

- [regclient](https://github.com/regclient/regclient)

  regclient 是一个 CLI 工具库，用来操作 Docker 镜像和 OCI 镜像，无需下载镜像即可对其重新打 tag，还可以查看 tag 和 manifests 等信息。它总共包含了 3 个 CLI 工具，功能各不相同，非常强大。

- [Buildpacks](https://buildpacks.io/)  

  新型镜像构建技术

- [containerd-shim-systemd-v1](https://github.com/cpuguy83/containerd-shim-systemd-v1)

  containerd-shim-systemd-v1 这个项目实现了 containerd shim，可以使用 Systemd 来管理容器。与标准的 runc shim (io.containerd.runc.v2)，具有以下优势：

  - 可以使用 systemd 管理容器。
  - 如果使用标准的 runc shim，则每个容器（或 Pod）都需要一个 shim；而 containerd-shim-systemd-v1 每个节点只需一个 shim，运行时开销为 O(1)。
  - Shim 可以随意重启，不会影响容器正常运行。

- [Kustomizer](https://github.com/stefanprodan/kustomizer)

  Kustomizer 是一个比较有新意的软件包管理器，用于将 Kubernetes 的配置清单打包成 OCI 镜像，然后推送到 OCI 镜像仓库。还可以在线修改配置更新镜像。

- [Kubectl-Ice](https://github.com/NimbleArchitect/kubectl-ice/releases)  

  一款超强大的 Kubernetes Pod 资源终端管理工

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
  
- [Kueue](https://github.com/kubernetes-sigs/kueue)  

  Kueue 是开源的云原生作业队列控制器，它充分利用了 Kubernetes 现有组件的各种成熟的功能，比如节点自动伸缩由 cluster-autoscaler 负责，Pod 调度由 kube-scheduler 负责，作业生命周期管理由 kube-controller-manager 负责。同时提供了扩展 API 来合理分配资源配额，还提供了 hooks 用来集成其他定制的批处理作业 API。

- [kconf](https://github.com/simontheleg/konf-go)  

  Konf 是一个轻量级 kubeconfig 管理工具，可以同时在不同的终端窗口中使用不同的 kubeconfig，也不会创建子 shell，速度很快。

- [mirrord](https://github.com/metalbear-co/mirrord)  

  mirrord 可以让你的本地应用直接对接到 Kubernetes 中，看起来就像是直接运行在 Kubernetes 中一样，但实际上不需要部署到 Kubernetes 中。还提供了 VS Code 插件与 IntelliJ 插件。

- [Paralus](https://github.com/paralus/paralus)  

  Paralus 是开源的零信任解决方案，可以自定义角色、身份提供商，以及创建不同权限的自定义规则等功能，支持 Kubernetes 多集群环境，可以控制所有集群的访问权限。

- [Depot](https://depot.dev)  

  这个工具可以在云端远程构建 Docker 镜像，比 docker build 的构建速度更快，支持 Apple M1。

- [Dockle](https://github.com/goodwithtech/dockle)   

  Dockle 是用于安全的容器镜像 Linter，可以帮助我们构建最佳实践的安全 Docker 镜像，易于上手。

- [buildg](https://github.com/ktock/buildg)  

  这是一个基于 Buildkit 的 Dockerfile 实时调试工具，支持断点调试，提供了交互式 shell，同时还提供了 VS Code 等 IDE 插件，可以直接在 IDE 中调试。

- [KubeGateway](https://github.com/kubewharf/kubegateway)  

  KubeGateway 是字节跳动针对 kube-apiserver 流量特征专门定制的七层网关，它彻底解决了 kube-apiserver 负载不均衡的问题，同时在社区范围内首次实现了对 kube-apiserver 请求的完整治理，包括请求路由、分流、限流、降级等，显著提高了 Kubernetes 集群的可用性。

- [Helm-Dashboard](https://github.com/komodorio/helm-dashboard)  

  Helm Dashboard 插件提供了一种 UI 驱动的方式来查看已安装的 Helm Chart、查看其修订历史记录和相应的 K8s 资源。此外，你还可以执行简单的操作，例如回滚到修订版或升级到新版本。

- [mizu](https://github.com/up9inc/mizu) 

  强大的 Kubernetes API 流量查看工具。如果把 k8s 比作操作系统，那它就是 k8s 上的 tcpdump，使用起来就像 Chrome 开发者工具一样简单直接，能够让 k8s 上微服务之间的网络通信一览无遗。

- [trivy](https://github.com/aquasecurity/trivy) 

  一款全面的容器安全扫描工具。目前最流行的开源容器镜像漏洞扫描工具，拥有速度快、精准度高、依赖检测、机密检查、对 CI 友好等特点。它不仅安装简单而且容易上手，仅需一条命令，即可发现镜像存在的安全漏洞。

- [Kubernetes-Volume-Autoscaler](https://github.com/DevOps-Nirvana/Kubernetes-Volume-Autoscaler) 

  这是一个 Kubernetes 控制器，它会在 PVC 的容量即将被消耗殆尽时自动对其进行动态扩容，支持任意 Kubernetes 集群和云厂商托管集群。

- [vcluster](https://www.vcluster.com)  

  虚拟集群（virtual cluster, 简称 vcluster）是在常规的 Kubernetes 集群之上运行的一个功能齐全，轻量级，隔离性良好的 Kubernetes 集群。虚拟集群的核心思想是提供运行在“真实”Kubernetes 集群之上隔离的 Kubernetes 控制平面（例如 API Server）。与完全独立的“真实“集群相比，虚拟集群没有自己的工作节点或者网络，工作负载实际上还是在底层宿主集群上调度。

- [k9s](https://github.com/derailed/k9s)  

  K9s 是一个可以和 K8s 集群进行交互的终端 UI 。它可以轻松浏览你的 namespace、services 、 deployments 等，并持续监视 Kubernetes 的变化，使得管理应用程序变得更加容易。

- [Popeye](https://github.com/derailed/popeye)  

  Popeye 是一个开源工具，可以扫描实时的 Kubernetes 集群，并且可以报告部署过的资源及配置的潜在问题。它根据部署的内容来清理群集。通过扫描集群检测出配置错误，并帮助我们保证最佳实践。此外，如果我们的 Kubernetes 集群过载，它会报告分配过多/分配不足的资源，在集群容量不足时发出警告。

- [Kube-bench](https://github.com/aquasecurity/kube-bench)  

  Kube-bench 也是一个方便使用的工具，通过 CIS Kubernetes Benchmark 测试中的记录，检查 Kubernetes 集群是否安全部署。

- [Kubectx、Kubens、fzf ](https://github.com/ahmetb/kubectx) 

  通常情况下，你可能会拥有多套集群，开发/测试/生产，本地或云集群。我们可以使用 Kubectx 和 Kubens 快速地在不同的集群和 namespace 直接切换。除此之外， fzf 提供了交互的方式来切换上下文，因此你不必记住任何集群或 namespace。

- [Stern](https://github.com/wercker/stern)  

  Stern 允许我们在 Kubernetes 上使用多个 Pod ，帮助我们从不同的 Pod 收集日志，并通过颜色进行区分。

- [Nocalhost](https://nocalhost.dev/)

  Nocalhost 是一个用于云原生应用程序开发的开源 IDE 插件：

  - **直接在 Kubernetes 中构建、测试和调试应用程序**
  - **IDE 支持 ：**提供与 IDE 中使用的相同的调试和开发体验，即使在远程 Kubernetes 群集中也是如此
  - **使用即时文件同步进行开发：**即时将代码更改同步到远程容器，而无需重新生成映像或重新启动容器。

- [kt-connect](https://github.com/alibaba/kt-connect/blob/master/README_CN.md)

  KtConnect（Kt为Kubernetes Toolkit集群工具包的简写）是一款基于Kubernetes环境用于提高本地测试联调效率的小工具。

  ✅ 特性

  - `Connect`：建立数据代理通道，实现本地服务直接访问Kubernetes集群内网（包括Pod IP和Service域名）
  - `Exchange`：让集群服务流量重定向到本地，实现快速验证本地版本和调试排查问题
  - `Mesh`：创建路由规则重定向特定流量，实现多人协作场景下互不影响的本地调试
  - `Preview`：暴露本地服务到集群，实现无需发布即可在线预览集成效果
  
- [KubeShark](https://github.com/kubeshark/kubeshark)

  适用于 Kubernetes 的 API 流量查看器，可深入了解 Kubernetes 集群内容器和 Pod 之间的所有 API 流量和有效负载

  Kubeshark 是 kubernetes 的 API Traffic Viewer，它提供对进出 Kubernetes 集群内容器和 Pod 的所有 API 流量和有效负载的深度可见性和监控。

  想想 Chrome Dev Tools，TCPDump 和 Wireshark 的组合，它们为 Kubernetes 重新发明。
  
- [kubernetes-chatgpt-bot](https://github.com/robusta-dev/kubernetes-chatgpt-bot) 

  这是一个适用于 Slack 的 ChatGPT 机器人，只要有监控告警发送到 Slack 频道中，你就可以通过机器人向 ChatGPT 咨询如何解决这个告警，ChatGPT 将会给出一个较为详细的解决方案。

- [Pluto](https://github.com/FairwindsOps/pluto)  

  这是一个命令行工具，用来查找 Kubernetes 集群中已弃用的 API 版本。

- [k8z](https://github.com/gotomicro/k8z)

  k8z 意在 K8s 业务层面，提供一个方便好用的 K8s 集群可视化工具集。目前包含以下功能：

  - 终端：连接到集群任意 Pod 容器上，方便调试
  - Tcpdump：对集群内容器进行 tcpdump 抓包，可直接展示抓包信息，也可拉起 wireshark 实时分析
  - Files：可将本机文件上传至集群 Pod 里或从集群 Pod 上下载文件
  - Profiling：对开启了 pprof 的 go 服务进行 profile，请求 profile 并绘制火焰图方便分析
  - Pod HTTP proxy: 代理 http 请求到集群内 Pod 上，方便一些本地网络和集群 Pod 网络不通的场景调试接口使用
  - Debug：复制一个 Pod 并新建一个终端连接上去，方便针对 crash 的 Pod 手动调试故障
  - ConfigMap：提供方便的编辑器来管理集群内的 ConfigMap

- [vesta](https://github.com/kvesta/vesta)  

  vesta 是一款集容器扫描，Docker 和 Kubernetes 配置基线检查于一身的工具。检查内容包括镜像或容器中包含漏洞版本的组件，同时根据云上实战渗透经验检查 Docker 以及 Kubernetes 的危险配置。

- [kubescape](https://github.com/kubescape/kubescape)

  Kubescape 是一个开源的 Kubernetes 安全平台。它的功能包括 `风险分析`、`安全合规性` 和 `错误配置扫描`。针对 DevSecOps 从业者或平台工程师，提供易于使用的 CLI 界面、灵活的输出格式和自动扫描功能。同时对于小集群提供了免费的 在线 面板工具，它为 Kubernetes 用户和管理员节省了宝贵的时间、精力和资源。
  
- [ContainerSSH](https://github.com/ContainerSSH/ContainerSSH)  

  ContainerSSH 是一个为容器环境设计的 SSH 服务器，它提供了一种连接到容器的简单方法，以及在容器中执行命令和脚本的机制。

### Kubectl 插件

安装方式：kubectl krew install [插件名称]

- [krew plugins](https://krew.sigs.k8s.io/plugins/)  kubectl 插件列表

- [access-matrix](https://github.com/corneliusweig/rakkess) 

  显示服务器资源的 RBAC 访问矩阵。

  您是否曾经想过您对所提供的 kubernetes 集群拥有哪些访问权限?对于单个资源，您可以使用`kubectl auth can-i` 列表部署，但也许您正在寻找一个完整的概述?这就是它的作用。它列出当前用户和所有服务器资源的访问权限，类似于`kubectl auth can-i --list`。

- [ca-cert](https://github.com/ahmetb/kubectl-extras)   

  打印当前集群的 PEM CA 证书

- [cert-manager](https://github.com/jetstack/cert-manager)  

  用来管理集群内的证书资源

- [cost](https://github.com/kubecost/kubectl-cost)  

  查看集群成本信息。

  `kubectl-cost` 是一个 kubectl 插件，通过 kubeccost api 提供简单的 CLI 访问 Kubernetes 成本分配指标。它允许开发人员、devops 和其他人快速确定 Kubernetes 工作负载的成本和效率。

- [ctx](https://github.com/ahmetb/kubectx) 

  在 kubeconfig 中切换上下文

- [deprecations](https://github.com/rikatz/kubepug)  

  检查集群中已经弃用的对象。一般用在升级 K8S 之前做检查。又叫 **KubePug**

- [df-pv](https://github.com/yashbhutwala/kubectl-df-pv)  

  查看 pv 使用情况

- [get-all](https://github.com/corneliusweig/ketall)  

  真正能 get 到 Kubernetes 的所有资源

- [images](https://github.com/chenjiandongx/kubectl-images)  

  显示集群中使用的容器镜像

- [kubesec-scan](https://github.com/controlplaneio/kubectl-kubesec)  

  使用 kubesec.io 扫描 Kubernetes 资源

- [neat](https://github.com/itaysk/kubectl-neat)  

  从Kubernetes显示中删除杂乱以使其更具可读性

- [node-shell](https://github.com/kvaps/kubectl-node-shell) 

  通过 kubectl 在一个 node 上生成一个 root shell

- [ns](https://github.com/ahmetb/kubectx)  

  切换 Kubernetes 的 ns

- [outdated](https://github.com/replicatedhq/outdated) 

  查找集群中运行的过时容器镜像。

- [popeye](https://popeyecli.io/) 

  扫描集群以发现潜在的资源问题。就是 K9S 也在使用的 popeye

- [resource-capacity](https://github.com/robscott/kube-capacity)  

  提供资源请求、限制和使用率的概览。

- [score](https://github.com/zegl/kube-score) 

  Kubernetes 静态代码分析

- [sniff](https://github.com/eldadru/ksniff) 

  强烈推荐，之前有次 POD 网络出现问题就是通过这个帮助来进行分析的。它会使用 tcpdump 和 wireshark 在 pod 上启动远程抓包

- [starboard](https://github.com/aquasecurity/starboard) 

  是一个安全扫描工具，

- [tail](https://github.com/boz/kail)

  将所有匹配 pod 的所有容器的日志流。按 service、replicaset、deployment 等匹配 pod。调整到变化的集群 —— 当 pod 落入或退出选择时，将从日志中添加或删除它们

- [trace](https://github.com/iovisor/kubectl-trace) 

  使用系统工具跟踪 Kubernetes pod 和 node

- [tree](https://github.com/ahmetb/kubectl-tree)

  一个 `kubectl` 插件，通过对 Kubernetes 对象的 `ownersReferences` 来探索它们之间的所有权关系

- [tunnel](https://github.com/omrikiei/ktunnel) 

  集群和你自己机器之间的反向隧道.

  它允许您将计算机作为集群中的服务公开，或者将其公开给特定的部署。这个项目的目的是为这个特定的问题提供一个整体的解决方案 (从 kubernetes pod 访问本地机器)

- [warp](https://github.com/ernoaapa/kubectl-warp)

  在 Pod 中同步和执行本地文件

  它创建临时 Pod，并将本地文件同步到所需的容器，并执行任何命令。

  例如，这可以用于在 Kubernetes 中构建和运行您的本地项目，其中有更多的资源、所需的架构等，同时在本地使用您的首选编辑器。

- [who-can](https://github.com/aquasecurity/kubectl-who-can)  

  显示谁具有访问 Kubernetes 资源的 RBAC 权限



###  prometheus

- [karma](https://github.com/prymitive/karma)  

  一款超高颜值的 Alertmanager 可视化面板


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

- [github-x](https://github.com/riskers/GithubX)  

  一款增强 Github 体验的 Chrome 插件

- [Bilibili-Evolved](https://github.com/the1812/Bilibili-Evolved)  

  强大的哔哩哔哩增强脚本, 供了非常多开箱即用的功能比如广告删除、夜间模式.

- [Automa ](https://github.com/Kholid060/automa)  

  一个用于 Chrome 浏览器自动化的插件，从自动填写表格、执行重复性任务、截屏、抓取网站数据等等，完全可以根据你自己的需求来决定如何使用。

- [HackBrowserData](https://github.com/moonD4rk/HackBrowserData)  

  一个浏览器数据，能够导出本地浏览器的密码、历史记录、Cookie、书签、下载记录、localStorage 等数据的命令行工具，支持多平台下的多种主流浏览器。

### Redis

- [Another Redis Desktop Manager](https://gitee.com/qishibo/AnotherRedisDesktopManager)  

  redis桌面管理工具，可以运行于Linux、Windows、Mac三大平台。

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

- [bob](https://github.com/ripperhe/Bob)  

  一款免费的 Mac 端翻译软件，支持划词翻译和截图翻译，甚至还有语音合成功能，现在支持很多翻译引擎。
  
- [LocalSend](https://github.com/localsend/localsend)

  `localsend` 是一个使用 Flutter 开发的 `AirDrop` 开源跨平台替代品，可以将文件共享到附近的设备，该应用允许你通过本地 LAN 网络发送文件和消息。不需要互联网，不需要外部服务器。一切都在 wifi 网络中本地发生。

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
  
- [gum](https://github.com/charmbracelet/gum)  

  用于制作迷人 shell 脚本的工具。在您的脚本和别名中利用[Bubbles](https://github.com/charmbracelet/bubbles)和[Lip GLoss](https://github.com/charmbracelet/lipgloss)的强大功能，而无需编写任何 Go 代码！
  
- [erdtree](https://github.com/solidiquis/erdtree) 

  一个支持可视化文件树和磁盘使用量的多线程资源分析器

- [zellij](https://github.com/zellij-org/zellij) 

  一个面向开发人员，面向运维的人以及任何喜欢终端的人的工作空间。类似的程序有时被称为“终端多路复用器”。

### 终端

- [vhs](https://github.com/charmbracelet/vhs)  

  记录终端命令，生成 gif动态图。

- [Codex-CLI](https://github.com/microsoft/Codex-CLI) 

  让终端理解自然语言命令的工具。该项目使用 GPT-3 Codex 可将自然语言命令，转换为 PowerShell、Zsh 和 Bash 中的命令，比如输入 what‘s my IP？就能得到本机 IP。

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

- [github 趋势](https://www.githubtrends.io)  

  统计过去一年中你的代码贡献趋势及编程语言趋势，并在README中展示。

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

- [打印 GitHub issue 小票](https://aschmelyun.com/blog/i-built-a-receipt-printer-for-github-issues/) https://github.com/yihong0618/blue

  借助树莓派与 GitHub Action, 每次当有人给你提交一个 GitHub issue 时，就会跟在超市买东西一样，在打印机弹出一张小票

- [shields](https://github.com/badges/shields)  

  输入项目的链接即可定制属于自己的徽章。

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
  
- [Foresight](https://github.com/marketplace/thundra-foresight) 

  Foresight 是一个 GitHub App，它会通过可视化监控面板来展示 Workflow 的状态、持续时间和成本，以及消耗的 CPU、内存、存储和网络 I/O 资源。同时还会提供相应的 Workflow 优化建议。


### 工具

- [rembg](https://github.com/danielgatis/rembg)

  Rembg 是一个去除图像背景的工具。开发者已经封装好了，用法非常简单，可以进入下方的链接查看。
  
- [sysbench](https://github.com/akopytov/sysbench) 

  基于 LuaJIT 的可编写脚本的多线程基准测试工具。多用于数据库基准测试的命令行工具，经常出现在各种知名数据库的性能对比报告中。支持丰富的测试选项，比如表数量、数据条数、生成只读 SQL 等。

- [masscan](https://github.com/robertdavidgraham/masscan) 

  超快的 IP 端口扫描工具。异步的 TCP 端口扫描器，特点就是快。最快能在 5 分钟内扫描完整个互联网，但要小心别把本机打挂了。

### 博客相关

- [一言](https://hitokoto.cn/#)  

  为网站提供一句话服务，一句话，可以是动漫中的台词，也可以是网络上的各种小段子。

- [Astro](https://github.com/withastro/astro) 

  Astro 是一款现轻量级的静态网站生成器，在 GitHub 上已经斩获 18K 的 Star。该项目可以提供详细的中文教程，只要你具备基本的前端编程基础，就能快速搭建一个属于自己的静态网站。

- [kbar](https://github.com/timc1/kbar)  

  为你的站点提供命令面板界面的组件。这是一个即插即用的 React 组件，可以快速地为站点增加命令面板功能。让用户可以通过快捷键，灵活、交互式地访问网站。
  
- [mdBook](https://github.com/rust-lang/mdBook) Rust 官方开源的制作 Markdown 电子书工具，功能上类似 Gitbook。它可以将 Markdown 文件制作成在线书籍，支持代码高亮、可集成搜索、多主题等功能，简单易用非常适合创建教程、API 文档、开源书籍等。

### 其他

- [后盾人](https://doc.houdunren.com/)  后盾人在线文档，前端学习及vscode插件推荐
- [猫爪导航🐱](https://v2fy.com/)  各种工具及资源的推荐
- [正则大全](https://any86.github.io/any-rule/)  提供常见的正则匹配
- [BT下载Tracker](https://trackerslist.com/#/zh)  提高BT下载速度

### Go相关项目

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

- [pikepdf](https://github.com/pikepdf/pikepdf) 

  用于读取和写入 PDF 文件的 Python 库

- [docker-py](https://github.com/docker/docker-py) 

  用 Python 操作 Docker 的库。Docker 官方出品的 Python 库，可以用来批量、自动管理镜像

- [memray](https://github.com/bloomberg/memray)

  Python 的内存分析器。帮你分析 Python 应用的内存使用情况，找到内存泄漏的原因、占用内存多的代码、内存使用率高的原因。支持生成内存报告（火焰图、表格、树状图）和实时报告等模式，以及统计结果等功能

- [Geopandas](https://geopandas.readthedocs.io/)

  一行代码算出每个省面积的神器

- [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)  

  百度飞桨ocr识别

- [PPOCRLabel](https://github.com/PaddlePaddle/PaddleOCR/tree/release/2.5/PPOCRLabel)  

  OCR半自动数据标注工具

- [APIFlask](https://github.com/apiflask/apiflask)  

  APIFlask是一个基于[Flask](https://github.com/pallets/flask)和 [marshmallow-code](https://github.com/marshmallow-code)项目的轻量级Python Web API框架。它易于使用，高度可定制，ORM / ODM不可知，并且与Flask生态系统100%兼容。

- [stylecloud](https://github.com/minimaxir/stylecloud)  

  stylecloud 是一位数据科学家叫 Max Woolf 的大神做出来的 wordcloud 词云包的升级版

### 其他 Github 项目

- [AppMap](https://github.com/getappmap) 

  AppMap 是一款开源的运行时代码分析工具，支持 Ruby、Java、Python 和 Javascript。它会跟踪代码的运行流程，并统计所有收集到的信息，最终将这些信息以交互式图表的形式呈现，通过可视化图表可以直观地看到函数、网络服务、数据存储、安全、I/O 和依赖服务是如何一起工作的。
