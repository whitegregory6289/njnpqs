最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计高可用服务架构梳理
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.lg6lyk.asia/arts/810587.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.lg6lyk.asia/arts/917143.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.lg6lyk.asia/arts/559827.Doc

原标题：golang 协程泄露问题排查方法
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.lg6lyk.asia/arts/941658.Doc

原标题：线程调度优化减少上下文切换
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.lg6lyk.asia/arts/937151.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.lg6lyk.asia/arts/049156.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.lg6lyk.asia/arts/456540.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.lg6lyk.asia/arts/028818.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.lg6lyk.asia/arts/438111.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.lg6lyk.asia/arts/040059.Doc

原标题：golang redis 过期策略内存淘汰
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.lg6lyk.asia/arts/563055.Doc

原标题：多套环境灵活切换配置方案
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.lg6lyk.asia/arts/610069.Doc

原标题：golang redis 主从复制哨兵原理
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.lg6lyk.asia/arts/536293.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.lg6lyk.asia/arts/319432.Doc

原标题：数据库排序规则统一结果一致
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.lg6lyk.asia/arts/891999.Doc

原标题：浏览器内存泄漏排查前端页面
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.lg6lyk.asia/arts/040545.Doc

原标题：语义化版本依赖管理防错乱
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.lg6lyk.asia/arts/798783.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.lg6lyk.asia/arts/126330.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.lg6lyk.asia/arts/789929.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.lg6lyk.asia/arts/823993.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.lg6lyk.asia/arts/741849.Doc

原标题：开源项目构建失败排查步骤
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.lg6lyk.asia/arts/600744.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.lg6lyk.asia/arts/937353.Doc

原标题：golang 系统设计技术文档编写最佳实践
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.lg6lyk.asia/arts/218815.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.lg6lyk.asia/arts/562659.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.lg6lyk.asia/arts/902115.Doc

原标题：golang alertmanager 钉钉告警推送
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.lg6lyk.asia/arts/592218.Doc

原标题：golang docker 容器资源限制设置
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.lg6lyk.asia/arts/203734.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.lg6lyk.asia/arts/273184.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/522852.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.lg6lyk.asia/arts/892830.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/576309.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.lg6lyk.asia/arts/118401.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.lg6lyk.asia/arts/604595.Doc

原标题：golang k8s liveness readiness 探针
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.lg6lyk.asia/arts/254090.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.lg6lyk.asia/arts/710451.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.lg6lyk.asia/arts/084402.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.lg6lyk.asia/arts/238352.Doc

原标题：前端防抖节流高频事件处理
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.lg6lyk.asia/arts/469242.Doc

原标题：包管理器依赖冲突解决方案
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.lg6lyk.asia/arts/540176.Doc


二、踩坑排错｜Troubleshooting
原标题：项目实践：搭建监控大盘查看系统关键指标
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.lg6lyk.asia/arts/043867.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.lg6lyk.asia/arts/554206.Doc

原标题：golang redis 计数器防超卖示例
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.lg6lyk.asia/arts/236324.Doc

原标题：JWT 工具封装令牌刷新过期
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.lg6lyk.asia/arts/868770.Doc

原标题：浮点计算精度错误处理方案
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.lg6lyk.asia/arts/427677.Doc

原标题：日志驱动异常日志不输出修复
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.lg6lyk.asia/arts/076373.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.lg6lyk.asia/arts/963746.Doc

原标题：golang redis 客户端业务使用
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.lg6lyk.asia/arts/305810.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.lg6lyk.asia/arts/673663.Doc

原标题：前端虚拟列表大数据渲染优化
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.lg6lyk.asia/arts/522117.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.lg6lyk.asia/arts/026469.Doc

原标题：golang etcd 分布式锁实现原理
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.lg6lyk.asia/arts/465195.Doc

原标题：快速上手简单性能监控指标查看
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.lg6lyk.asia/arts/306896.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.lg6lyk.asia/arts/607861.Doc

原标题：正则表达式优化 CPU 占满问题
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.lg6lyk.asia/arts/097143.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.lg6lyk.asia/arts/600093.Doc

原标题：golang 链路追踪简易实现方案
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.lg6lyk.asia/arts/683169.Doc

原标题：golang github actions 发布 release 包
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.lg6lyk.asia/arts/644137.Doc

原标题：golang dockerfile 多阶段构建详解
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.lg6lyk.asia/arts/986259.Doc

原标题：golang 系统设计 mq 消息积压解决方案
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.lg6lyk.asia/arts/073746.Doc

原标题：端口占用访问失败排查方案
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.lg6lyk.asia/arts/569000.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.lg6lyk.asia/arts/240357.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.lg6lyk.asia/arts/509339.Doc

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.lg6lyk.asia/arts/243187.Doc

原标题：golang kafka 批量发送消费优化
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/000635.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.lg6lyk.asia/arts/868660.Doc

原标题：golang gorm 预加载关联查询优化
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.lg6lyk.asia/arts/092620.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/332369.Doc

原标题：文件锁正确使用避免死锁
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.lg6lyk.asia/arts/320128.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.lg6lyk.asia/arts/793294.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/348313.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.lg6lyk.asia/arts/058273.Doc

原标题：前后端会话登录状态持久化
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.lg6lyk.asia/arts/472707.Doc

原标题：实践：静态站点自动化部署到GitHubPages
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.lg6lyk.asia/arts/865473.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.lg6lyk.asia/arts/526699.Doc

原标题：golang mysql 存储过程简单使用
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.lg6lyk.asia/arts/312328.Doc

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.lg6lyk.asia/arts/559914.Doc

原标题：golang lru 缓存淘汰算法编写
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.lg6lyk.asia/arts/459209.Doc

原标题：golang 系统设计网关路由规则动态配置实现
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.lg6lyk.asia/arts/851334.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.lg6lyk.asia/arts/071082.Doc

三、实战开发｜Practice
原标题：架构笔记：海量日志处理架构选型与实践
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.lg6lyk.asia/arts/619670.Doc

原标题：手写简易 ORM 理解对象映射
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.lg6lyk.asia/arts/501214.Doc

原标题：Docker Compose 一键搭建本地栈
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.lg6lyk.asia/arts/942341.Doc

原标题：nestjs 框架模块化项目搭建
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.lg6lyk.asia/arts/860487.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.lg6lyk.asia/arts/489589.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.lg6lyk.asia/arts/420654.Doc

原标题：golang goroutine 协程基础实操
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.lg6lyk.asia/arts/022477.Doc

原标题：nodejs 事件循环机制完整讲解
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.lg6lyk.asia/arts/053895.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/261819.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.lg6lyk.asia/arts/996979.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.lg6lyk.asia/arts/988437.Doc

原标题：golang mysql 批量导入数据实操
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.lg6lyk.asia/arts/616821.Doc

原标题：定时任务重复执行分布式锁
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.lg6lyk.asia/arts/190696.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.lg6lyk.asia/arts/159558.Doc

原标题：前端虚拟列表大数据渲染优化
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.lg6lyk.asia/arts/384138.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.lg6lyk.asia/arts/057068.Doc

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.lg6lyk.asia/arts/661425.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.lg6lyk.asia/arts/071176.Doc

原标题：golang 批量任务协程控制防雪崩
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/752584.Doc

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.lg6lyk.asia/arts/671556.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.lg6lyk.asia/arts/899370.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.lg6lyk.asia/arts/496945.Doc

原标题：golang kafka 生产者参数调优
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.lg6lyk.asia/arts/655551.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.lg6lyk.asia/arts/321947.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/704514.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.lg6lyk.asia/arts/759467.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.lg6lyk.asia/arts/722541.Doc

原标题：vite 项目配置与构建提速技巧
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.lg6lyk.asia/arts/762360.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.lg6lyk.asia/arts/636447.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.lg6lyk.asia/arts/231636.Doc

原标题：服务启动依赖顺序配置正确
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/390228.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.lg6lyk.asia/arts/888701.Doc

原标题：golang gorm 批量插入性能调优
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/786927.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.lg6lyk.asia/arts/905984.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.lg6lyk.asia/arts/388733.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.lg6lyk.asia/arts/859009.Doc

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/879285.Doc

原标题：前端图片懒加载性能优化
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.lg6lyk.asia/arts/650815.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.lg6lyk.asia/arts/268074.Doc

原标题：序列化版本不一致解析失败
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.lg6lyk.asia/arts/611104.Doc

四、架构设计｜Architecture
原标题：golang 系统设计性能瓶颈定位完整方法论
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.lg6lyk.asia/arts/612400.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.lg6lyk.asia/arts/110400.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.lg6lyk.asia/arts/755203.Doc

原标题：golang kafka 重试机制配置实操
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.lg6lyk.asia/arts/827298.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.lg6lyk.asia/arts/675725.Doc

原标题：golang 系统设计排行榜几种实现
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.lg6lyk.asia/arts/730880.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.lg6lyk.asia/arts/040547.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.lg6lyk.asia/arts/901066.Doc

原标题：golang mysql 死锁排查步骤讲解
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.lg6lyk.asia/arts/833330.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.lg6lyk.asia/arts/501453.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.lg6lyk.asia/arts/720953.Doc

原标题：golang 系统设计分布式事务几种方案
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.lg6lyk.asia/arts/785407.Doc

原标题：开发环境变量配置全平台教程
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.lg6lyk.asia/arts/748480.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.lg6lyk.asia/arts/867146.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.lg6lyk.asia/arts/771693.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.lg6lyk.asia/arts/508796.Doc

原标题：golang aes 对称加密解密示例
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.lg6lyk.asia/arts/048658.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.lg6lyk.asia/arts/088969.Doc

?
