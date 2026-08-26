最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计雪花算法 id 原理剖析
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.298awn.asia/arts/892915.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.298awn.asia/arts/971356.Doc

原标题：零基础学习简单正则表达式实战案例
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.298awn.asia/arts/344034.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.298awn.asia/arts/277063.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.298awn.asia/arts/362718.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.298awn.asia/arts/944221.Doc

原标题：新手教程：本地环境变量配置全流程
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.298awn.asia/arts/423573.Doc

原标题：golang csv 读写批量数据处理
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.298awn.asia/arts/115587.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.298awn.asia/arts/453407.Doc

原标题：monorepo 项目多包管理最佳实践
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.298awn.asia/arts/500840.Doc

原标题：golang http 代理客户端配置
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.298awn.asia/arts/119466.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.298awn.asia/arts/595000.Doc

原标题：新手参与开源社区贡献指南
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.298awn.asia/arts/237284.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.298awn.asia/arts/922434.Doc

原标题：hosts 配置本地回环访问修复
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.298awn.asia/arts/256950.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.298awn.asia/arts/862288.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.298awn.asia/arts/715036.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.298awn.asia/arts/594682.Doc

原标题：Performance：批量导入数据性能优化实践
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.298awn.asia/arts/018228.Doc

原标题：golang 文件上传下载接口开发
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.298awn.asia/arts/126047.Doc

原标题：golang docker compose 部署 minio
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.298awn.asia/arts/307983.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.298awn.asia/arts/472461.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.298awn.asia/arts/712330.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.298awn.asia/arts/612709.Doc

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.298awn.asia/arts/711625.Doc

原标题：golang 协程泄露问题排查方法
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.298awn.asia/arts/723877.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.298awn.asia/arts/605732.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.298awn.asia/arts/896874.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.298awn.asia/arts/448144.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.298awn.asia/arts/755066.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.298awn.asia/arts/716574.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.298awn.asia/arts/909098.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.298awn.asia/arts/494351.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.298awn.asia/arts/334060.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.298awn.asia/arts/262732.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.298awn.asia/arts/294323.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.298awn.asia/arts/181407.Doc

原标题：快速入门简单签名校验实现思路
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.298awn.asia/arts/441969.Doc

原标题：golang 协程泄露问题排查方法
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.298awn.asia/arts/260872.Doc

原标题：大事务拆分防止连接池耗尽
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.298awn.asia/arts/241663.Doc


二、踩坑排错｜Troubleshooting
原标题：golang docker 私有仓库搭建使用
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.298awn.asia/arts/521010.Doc

原标题：RPC 接口字段增减兼容处理
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.298awn.asia/arts/158026.Doc

原标题：golang 雪花 id 重复问题排查
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.298awn.asia/arts/263912.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.298awn.asia/arts/604998.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.298awn.asia/arts/412730.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.298awn.asia/arts/023696.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.298awn.asia/arts/384058.Doc

原标题：图片上传预览格式大小处理
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.298awn.asia/arts/385047.Doc

原标题：golang 结构体深拷贝几种实现
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.298awn.asia/arts/120373.Doc

原标题：golang 系统设计 id 生成器选型对比
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.298awn.asia/arts/786405.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.298awn.asia/arts/894687.Doc

原标题：golang prometheus 指标暴露实现
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.298awn.asia/arts/900554.Doc

原标题：本地运行正常线上报错排查
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.298awn.asia/arts/518174.Doc

原标题：Nginx 请求头大小上限调整
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.298awn.asia/arts/930226.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.298awn.asia/arts/343947.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.298awn.asia/arts/906946.Doc

原标题：nodejs 日志轮转生产环境配置
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.298awn.asia/arts/596868.Doc

原标题：express 请求参数校验处理
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.298awn.asia/arts/031854.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.298awn.asia/arts/163329.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.298awn.asia/arts/371779.Doc

原标题：从零搭建简单定时任务demo
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.298awn.asia/arts/822499.Doc

原标题：nodejs 中间件模式原理剖析
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.298awn.asia/arts/865433.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.298awn.asia/arts/338573.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.298awn.asia/arts/118313.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.298awn.asia/arts/559494.Doc

原标题：新手教程：本地项目初始化gitignore配置
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.298awn.asia/arts/645955.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.298awn.asia/arts/433577.Doc

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.298awn.asia/arts/821201.Doc

原标题：golang 开发环境快速搭建指南
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.298awn.asia/arts/379030.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.298awn.asia/arts/850182.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.298awn.asia/arts/429178.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.298awn.asia/arts/924456.Doc

原标题：golang dockerfile 多阶段构建详解
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.298awn.asia/arts/020956.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.298awn.asia/arts/608437.Doc

原标题：golang 分布式锁防死锁处理
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.298awn.asia/arts/047738.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.298awn.asia/arts/569893.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.298awn.asia/arts/441605.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.298awn.asia/arts/125024.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.298awn.asia/arts/219418.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.298awn.asia/arts/904332.Doc

三、实战开发｜Practice
原标题：消息队列生产消费模型入门
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.298awn.asia/arts/322722.Doc

原标题：golang mysql 索引失效常见场景
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.298awn.asia/arts/313573.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.298awn.asia/arts/152173.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.298awn.asia/arts/970431.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.298awn.asia/arts/901117.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.298awn.asia/arts/082542.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.298awn.asia/arts/052621.Doc

原标题：golang 批量任务协程控制防雪崩
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.298awn.asia/arts/267056.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.298awn.asia/arts/718390.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.298awn.asia/arts/306824.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.298awn.asia/arts/466156.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.298awn.asia/arts/552723.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.298awn.asia/arts/475573.Doc

原标题：css 动画性能优化 GPU 加速
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.298awn.asia/arts/896031.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.298awn.asia/arts/853950.Doc

原标题：golang consul 服务发现简单示例
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.298awn.asia/arts/218157.Doc

原标题：macOS 脚本执行权限开启
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.298awn.asia/arts/637549.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.298awn.asia/arts/296502.Doc

原标题：golang cpu pprof 性能分析实操
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.298awn.asia/arts/616075.Doc

原标题：golang 系统设计秒杀防超卖方案
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.298awn.asia/arts/601702.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.298awn.asia/arts/367727.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.298awn.asia/arts/165521.Doc

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.298awn.asia/arts/042740.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.298awn.asia/arts/748689.Doc

原标题：golang 系统设计创建更新时间自动维护方案
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.298awn.asia/arts/190983.Doc

原标题：golang 系统设计消息消费 offset 管理策略
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.298awn.asia/arts/777114.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.298awn.asia/arts/981271.Doc

原标题：golang csv 读写批量数据处理
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.298awn.asia/arts/996180.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.298awn.asia/arts/901335.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.298awn.asia/arts/603551.Doc

原标题：接口请求重试容错机制实现
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.298awn.asia/arts/009747.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.298awn.asia/arts/985334.Doc

原标题：golang redis 过期策略内存淘汰
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.298awn.asia/arts/129402.Doc

原标题：浏览器本地存储安全使用技巧
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.298awn.asia/arts/782113.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.298awn.asia/arts/166928.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.298awn.asia/arts/783552.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.298awn.asia/arts/708752.Doc

原标题：前端权限路由动态生成实现
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.298awn.asia/arts/634814.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.298awn.asia/arts/425554.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.298awn.asia/arts/493626.Doc

四、架构设计｜Architecture
原标题：调试工具断点调试变量查看技巧
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.298awn.asia/arts/084579.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.298awn.asia/arts/196365.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.298awn.asia/arts/243917.Doc

原标题：Git commit 钩子提交规范校验
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.298awn.asia/arts/496617.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.298awn.asia/arts/937091.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.298awn.asia/arts/124434.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.298awn.asia/arts/867508.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.298awn.asia/arts/353314.Doc

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.298awn.asia/arts/457860.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.298awn.asia/arts/593024.Doc

原标题：安全组端口开放网络访问
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.298awn.asia/arts/044195.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.298awn.asia/arts/296201.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.298awn.asia/arts/755865.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.298awn.asia/arts/629279.Doc

原标题：golang http client 连接池调优
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.298awn.asia/arts/604392.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.298awn.asia/arts/687461.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.298awn.asia/arts/123315.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.298awn.asia/arts/459877.Doc

?
