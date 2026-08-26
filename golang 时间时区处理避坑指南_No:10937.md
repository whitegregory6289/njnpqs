最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 时间时区处理避坑指南
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.rrrh6i.asia/arts/957567.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.rrrh6i.asia/arts/080580.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.rrrh6i.asia/arts/837002.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.rrrh6i.asia/arts/562835.Doc

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.rrrh6i.asia/arts/756304.Doc

原标题：接口签名校验防篡改实现
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.rrrh6i.asia/arts/387241.Doc

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.rrrh6i.asia/arts/200464.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.rrrh6i.asia/arts/559245.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.rrrh6i.asia/arts/088522.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.rrrh6i.asia/arts/029739.Doc

原标题：接口签名验签完整安全方案
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.rrrh6i.asia/arts/130059.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.rrrh6i.asia/arts/441101.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.rrrh6i.asia/arts/424055.Doc

原标题：golang lru 缓存淘汰算法编写
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.rrrh6i.asia/arts/184468.Doc

原标题：golang 协程泄露问题排查方法
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.rrrh6i.asia/arts/967242.Doc

原标题：入门实践：简单图片上传预览本地demo
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.rrrh6i.asia/arts/725567.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.rrrh6i.asia/arts/780621.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.rrrh6i.asia/arts/199767.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.rrrh6i.asia/arts/601013.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.rrrh6i.asia/arts/953509.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.rrrh6i.asia/arts/270506.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.rrrh6i.asia/arts/417547.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.rrrh6i.asia/arts/326834.Doc

原标题：golang 系统设计字符串拼接性能优化技巧
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.rrrh6i.asia/arts/029492.Doc

原标题：空指针异常判空容错处理
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.rrrh6i.asia/arts/106793.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.rrrh6i.asia/arts/799126.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.rrrh6i.asia/arts/365044.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.rrrh6i.asia/arts/816050.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.rrrh6i.asia/arts/256231.Doc

原标题：入门实践：实现简单文件读写功能
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.rrrh6i.asia/arts/671012.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.rrrh6i.asia/arts/153261.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.rrrh6i.asia/arts/050042.Doc

原标题：golang mock 单元测试编写技巧
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.rrrh6i.asia/arts/920467.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.rrrh6i.asia/arts/423646.Doc

原标题：golang prometheus histogram 指标
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.rrrh6i.asia/arts/005280.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.rrrh6i.asia/arts/618702.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.rrrh6i.asia/arts/480346.Doc

原标题：服务器时钟同步任务错乱修复
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.rrrh6i.asia/arts/599370.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.rrrh6i.asia/arts/473940.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.rrrh6i.asia/arts/212159.Doc


二、踩坑排错｜Troubleshooting
原标题：零基础学习简单正则表达式实战案例
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.rrrh6i.asia/arts/929868.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.rrrh6i.asia/arts/926142.Doc

原标题：golang ci 流水线环境变量管理方案
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.rrrh6i.asia/arts/160317.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.rrrh6i.asia/arts/414242.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.rrrh6i.asia/arts/964485.Doc

原标题：golang kafka 核心概念分区副本
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.rrrh6i.asia/arts/156331.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.rrrh6i.asia/arts/478888.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.rrrh6i.asia/arts/468862.Doc

原标题：系统时间同步定时任务偏移
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.rrrh6i.asia/arts/231498.Doc

原标题：程序信号中断退出处理逻辑
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.rrrh6i.asia/arts/617658.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.rrrh6i.asia/arts/461451.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.rrrh6i.asia/arts/556055.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.rrrh6i.asia/arts/923838.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.rrrh6i.asia/arts/030041.Doc

原标题：零基础理解读写分离基础思想
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.rrrh6i.asia/arts/053271.Doc

原标题：文件句柄耗尽资源泄露处理
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.rrrh6i.asia/arts/565067.Doc

原标题：golang 单例模式实现几种方式
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.rrrh6i.asia/arts/106082.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.rrrh6i.asia/arts/272727.Doc

原标题：Debug：多线程共享可变变量产生脏数据
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.rrrh6i.asia/arts/475628.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.rrrh6i.asia/arts/624471.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.rrrh6i.asia/arts/103478.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.rrrh6i.asia/arts/739624.Doc

原标题：nodejs 消息队列消费服务开发
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.rrrh6i.asia/arts/518891.Doc

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.rrrh6i.asia/arts/607356.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.rrrh6i.asia/arts/990321.Doc

原标题：react 状态管理方案选型对比
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.rrrh6i.asia/arts/944947.Doc

原标题：RPC 报文大小上限调优大请求
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.rrrh6i.asia/arts/066426.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.rrrh6i.asia/arts/147202.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.rrrh6i.asia/arts/293118.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.rrrh6i.asia/arts/513421.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.rrrh6i.asia/arts/751055.Doc

原标题：设计思考：分布式会话架构选型对比
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.rrrh6i.asia/arts/024486.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.rrrh6i.asia/arts/790190.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.rrrh6i.asia/arts/644631.Doc

原标题：消息队列生产消费模型入门
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.rrrh6i.asia/arts/022024.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.rrrh6i.asia/arts/812550.Doc

原标题：浏览器内存泄漏排查前端页面
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.rrrh6i.asia/arts/525107.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.rrrh6i.asia/arts/091504.Doc

原标题：golang 链路 traceId 透传中间件
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.rrrh6i.asia/arts/104836.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.rrrh6i.asia/arts/237407.Doc

三、实战开发｜Practice
原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.rrrh6i.asia/arts/154125.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.rrrh6i.asia/arts/901530.Doc

原标题：eslint prettier 代码规范落地
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.rrrh6i.asia/arts/989395.Doc

原标题：新手教程：本地环境变量配置全流程
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.rrrh6i.asia/arts/732789.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.rrrh6i.asia/arts/231188.Doc

原标题：日志驱动异常日志不输出修复
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.rrrh6i.asia/arts/278618.Doc

原标题：golang 协程泄露问题排查方法
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.rrrh6i.asia/arts/589125.Doc

原标题：服务熔断防止故障级联传播
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.rrrh6i.asia/arts/104098.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.rrrh6i.asia/arts/899745.Doc

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.rrrh6i.asia/arts/167117.Doc

原标题：golang redis 位图用户签到统计
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.rrrh6i.asia/arts/949930.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.rrrh6i.asia/arts/415069.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.rrrh6i.asia/arts/837493.Doc

原标题：golang es 更新文档注意版本冲突
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.rrrh6i.asia/arts/500478.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.rrrh6i.asia/arts/085665.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.rrrh6i.asia/arts/474424.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.rrrh6i.asia/arts/520006.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.rrrh6i.asia/arts/417985.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.rrrh6i.asia/arts/343148.Doc

原标题：golang k8s rbac 权限控制配置示例
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.rrrh6i.asia/arts/234206.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.rrrh6i.asia/arts/274735.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.rrrh6i.asia/arts/704951.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.rrrh6i.asia/arts/940787.Doc

原标题：golang ci 流水线单元测试集成测试
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.rrrh6i.asia/arts/106451.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.rrrh6i.asia/arts/283255.Doc

原标题：gitignore 文件编写过滤规则
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.rrrh6i.asia/arts/470201.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.rrrh6i.asia/arts/547036.Doc

原标题：golang es 聚合统计查询实现
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.rrrh6i.asia/arts/741966.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.rrrh6i.asia/arts/107891.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.rrrh6i.asia/arts/749195.Doc

原标题：golang redis zset 延时队列实现
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.rrrh6i.asia/arts/477758.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.rrrh6i.asia/arts/101703.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.rrrh6i.asia/arts/327089.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.rrrh6i.asia/arts/023934.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.rrrh6i.asia/arts/920884.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.rrrh6i.asia/arts/483335.Doc

原标题：手写简易 RPC 服务通信原型
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.rrrh6i.asia/arts/625278.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.rrrh6i.asia/arts/006845.Doc

原标题：Practice：实现数据库连接池简易模拟实现
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.rrrh6i.asia/arts/211985.Doc

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.rrrh6i.asia/arts/369148.Doc

四、架构设计｜Architecture
原标题：安全实践：防止重放攻击接口签名方案
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.rrrh6i.asia/arts/687558.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.rrrh6i.asia/arts/025016.Doc

原标题：nodejs 多进程任务分发处理
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.rrrh6i.asia/arts/439821.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.rrrh6i.asia/arts/669631.Doc

原标题：golang 信号量控制并发数量
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.rrrh6i.asia/arts/308826.Doc

原标题：golang 系统设计防重复提交实现
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.rrrh6i.asia/arts/083150.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.rrrh6i.asia/arts/705022.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.rrrh6i.asia/arts/422072.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.rrrh6i.asia/arts/946383.Doc

原标题：缓存过期策略优化防业务故障
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.rrrh6i.asia/arts/476216.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.rrrh6i.asia/arts/848319.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.rrrh6i.asia/arts/051297.Doc

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.rrrh6i.asia/arts/500016.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.rrrh6i.asia/arts/433048.Doc

原标题：前端 pdf 预览渲染方案对比
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.rrrh6i.asia/arts/264345.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.rrrh6i.asia/arts/954271.Doc

原标题：golang redis 布隆过滤器安装使用
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.rrrh6i.asia/arts/789850.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.rrrh6i.asia/arts/803904.Doc

?
