最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计分布式任务调度
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.5mcbj6.asia/arts/643902.Doc

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.5mcbj6.asia/arts/345504.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.5mcbj6.asia/arts/312532.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.5mcbj6.asia/arts/961049.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.5mcbj6.asia/arts/119528.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.5mcbj6.asia/arts/779849.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.5mcbj6.asia/arts/617660.Doc

原标题：golang 系统设计埋点数据上报方案
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.5mcbj6.asia/arts/797708.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.5mcbj6.asia/arts/803850.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.5mcbj6.asia/arts/026565.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.5mcbj6.asia/arts/021929.Doc

原标题：golang docker 私有仓库搭建使用
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.5mcbj6.asia/arts/223585.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.5mcbj6.asia/arts/483657.Doc

原标题：批量异步处理系统业务落地
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.5mcbj6.asia/arts/685779.Doc

原标题：系统字符集统一乱码修复
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.5mcbj6.asia/arts/578331.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/751060.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.5mcbj6.asia/arts/555074.Doc

原标题：golang es 查询语句 DSL 实操
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/411704.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.5mcbj6.asia/arts/963262.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.5mcbj6.asia/arts/649725.Doc

原标题：golang 批量任务协程控制防雪崩
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.5mcbj6.asia/arts/305228.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.5mcbj6.asia/arts/226301.Doc

原标题：golang 日志 zap 结构化日志实践
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.5mcbj6.asia/arts/046636.Doc

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.5mcbj6.asia/arts/752808.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.5mcbj6.asia/arts/004473.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.5mcbj6.asia/arts/818532.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.5mcbj6.asia/arts/908046.Doc

原标题：Security：服务器最小权限账号运维实践
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.5mcbj6.asia/arts/946832.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.5mcbj6.asia/arts/527442.Doc

原标题：golang 系统设计开发环境本地调试最佳实践
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.5mcbj6.asia/arts/677714.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.5mcbj6.asia/arts/458400.Doc

原标题：消息消费重试次数限制防爆炸
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.5mcbj6.asia/arts/894728.Doc

原标题：golang 系统设计消息消费 offset 管理策略
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.5mcbj6.asia/arts/041430.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.5mcbj6.asia/arts/715496.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.5mcbj6.asia/arts/866055.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.5mcbj6.asia/arts/788136.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.5mcbj6.asia/arts/430077.Doc

原标题：golang grafana 监控面板简单配置
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.5mcbj6.asia/arts/534486.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.5mcbj6.asia/arts/594189.Doc

原标题：文件分片上传断点续传功能
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.5mcbj6.asia/arts/134079.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计故障预案编写模板参考示例
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.5mcbj6.asia/arts/905527.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/641541.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/603313.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.5mcbj6.asia/arts/254802.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.5mcbj6.asia/arts/592945.Doc

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.5mcbj6.asia/arts/786662.Doc

原标题：golang etcd watch 监听配置变更
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.5mcbj6.asia/arts/720435.Doc

原标题：golang aes 对称加密解密示例
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.5mcbj6.asia/arts/906917.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.5mcbj6.asia/arts/078745.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.5mcbj6.asia/arts/059961.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.5mcbj6.asia/arts/059998.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.5mcbj6.asia/arts/678524.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.5mcbj6.asia/arts/403173.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.5mcbj6.asia/arts/614733.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.5mcbj6.asia/arts/823694.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.5mcbj6.asia/arts/611750.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.5mcbj6.asia/arts/574875.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.5mcbj6.asia/arts/866615.Doc

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.5mcbj6.asia/arts/788302.Doc

原标题：golang md5 sha 加密工具实现
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.5mcbj6.asia/arts/493737.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.5mcbj6.asia/arts/077435.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.5mcbj6.asia/arts/790807.Doc

原标题：golang 告警推送钉钉机器人实现
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.5mcbj6.asia/arts/171104.Doc

原标题：golang http client 连接池调优
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.5mcbj6.asia/arts/078776.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.5mcbj6.asia/arts/425285.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.5mcbj6.asia/arts/712387.Doc

原标题：异步异常捕获避免进程崩溃
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.5mcbj6.asia/arts/426912.Doc

原标题：部署实践：数据库迁移脚本版本管理实践
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.5mcbj6.asia/arts/686107.Doc

原标题：golang 系统信号信号量处理
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.5mcbj6.asia/arts/334906.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.5mcbj6.asia/arts/381030.Doc

原标题：golang etcd watch 监听配置变更
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/352841.Doc

原标题：本地运行正常线上报错排查
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.5mcbj6.asia/arts/607445.Doc

原标题：开发记录：分布式锁超时业务安全处理实践
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/522513.Doc

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/189562.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.5mcbj6.asia/arts/902760.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.5mcbj6.asia/arts/820230.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/425518.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.5mcbj6.asia/arts/496636.Doc

原标题：golang github actions 发布 release 包
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.5mcbj6.asia/arts/927627.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.5mcbj6.asia/arts/214417.Doc

三、实战开发｜Practice
原标题：golang 优雅处理 http 超时设置
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.5mcbj6.asia/arts/856944.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.5mcbj6.asia/arts/181404.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.5mcbj6.asia/arts/278522.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.5mcbj6.asia/arts/820596.Doc

原标题：nodejs 事件循环机制完整讲解
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.5mcbj6.asia/arts/919177.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.5mcbj6.asia/arts/567838.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.5mcbj6.asia/arts/267099.Doc

原标题：Nginx 缓冲区调优大文件上传
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.5mcbj6.asia/arts/895086.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.5mcbj6.asia/arts/059925.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.5mcbj6.asia/arts/720957.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.5mcbj6.asia/arts/921566.Doc

原标题：K8s 镜像拉取网络故障修复
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.5mcbj6.asia/arts/520781.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.5mcbj6.asia/arts/488870.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.5mcbj6.asia/arts/486425.Doc

原标题：Spring 事务传播机制配置生效
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.5mcbj6.asia/arts/801435.Doc

原标题：容器软链接文件权限修复
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.5mcbj6.asia/arts/219922.Doc

原标题：golang 系统设计线程协程泄露定位方法
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.5mcbj6.asia/arts/201731.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.5mcbj6.asia/arts/890492.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.5mcbj6.asia/arts/160840.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.5mcbj6.asia/arts/381237.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.5mcbj6.asia/arts/748817.Doc

原标题：Git 误删提交代码恢复找回
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.5mcbj6.asia/arts/053663.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.5mcbj6.asia/arts/330301.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.5mcbj6.asia/arts/088992.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.5mcbj6.asia/arts/856070.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.5mcbj6.asia/arts/890726.Doc

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.5mcbj6.asia/arts/344122.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.5mcbj6.asia/arts/318818.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.5mcbj6.asia/arts/152239.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.5mcbj6.asia/arts/192155.Doc

原标题：限流规则误拦截正常请求修复
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.5mcbj6.asia/arts/534996.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.5mcbj6.asia/arts/419488.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.5mcbj6.asia/arts/888307.Doc

原标题：golang 系统设计 http 接口基准测试实操示例
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/603710.Doc

原标题：golang pprof 线上采集性能数据
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.5mcbj6.asia/arts/807477.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.5mcbj6.asia/arts/175188.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.5mcbj6.asia/arts/153369.Doc

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.5mcbj6.asia/arts/715856.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.5mcbj6.asia/arts/220058.Doc

原标题：golang 令牌桶限流中间件 gin
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.5mcbj6.asia/arts/378664.Doc

四、架构设计｜Architecture
原标题：golang 静态文件服务搭建教程
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.5mcbj6.asia/arts/782520.Doc

原标题：静态站点自动部署发布方案
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.5mcbj6.asia/arts/137634.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.5mcbj6.asia/arts/101440.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.5mcbj6.asia/arts/196256.Doc

原标题：golang yaml 解析配置加载实操
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.5mcbj6.asia/arts/997966.Doc

原标题：并发数据覆盖加锁安全处理
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.5mcbj6.asia/arts/734990.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.5mcbj6.asia/arts/194648.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.5mcbj6.asia/arts/605487.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.5mcbj6.asia/arts/522406.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.5mcbj6.asia/arts/380959.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.5mcbj6.asia/arts/423999.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.5mcbj6.asia/arts/556575.Doc

原标题：请求工具封装统一异常处理
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.5mcbj6.asia/arts/270666.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.5mcbj6.asia/arts/924695.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.5mcbj6.asia/arts/477240.Doc

原标题：极简方式搭建个人技术文档站点
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.5mcbj6.asia/arts/048358.Doc

原标题：方案设计：统一错误处理架构全链路方案
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/159688.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.5mcbj6.asia/arts/193516.Doc

?
