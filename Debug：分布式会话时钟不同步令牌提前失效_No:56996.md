最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8508028.shtml

原标题：golang 系统设计 changelog 变更日志维护
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8587758.shtml

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/7451476.shtml

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/2405931.shtml

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/1678778.shtml

原标题：缓存过期策略优化防业务故障
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8508738.shtml

原标题：集成测试业务流程编写示例
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4014548.shtml

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0166857.shtml

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8985900.shtml

原标题：golang minio 存储桶权限管控配置
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4510318.shtml

原标题：golang es 聚合统计查询实现
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/1969148.shtml

原标题：nodejs 跨域中间件配置细节
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8728176.shtml

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5237861.shtml

原标题：性能笔记：线程池参数调优任务队列策略
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0541583.shtml

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0793443.shtml

原标题：golang 系统设计高可用服务架构梳理
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/2164837.shtml

原标题：golang gin 路由分组权限管控
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0912897.shtml

原标题：golang 系统设计分库分表 id 全局生成策略
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/2095453.shtml

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4196680.shtml

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3565899.shtml

原标题：新手向：看懂项目README的正确阅读姿势
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5091373.shtml

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/2375027.shtml

原标题：YAML 配置文件语法快速上手
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8026873.shtml

原标题：部署复盘：数据库主从备份恢复演练实践
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0944438.shtml

原标题：golang http grpc 全链路埋点示例
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/9291856.shtml

原标题：WebSocket 断线重连稳定优化
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6155988.shtml

原标题：golang gitlab ci 配置自动构建镜像
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3607947.shtml

原标题：golang 系统设计重试退避策略业务落地
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0049534.shtml

原标题：开发复盘：批量任务进度持久化实现方案
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5987793.shtml

原标题：golang 系统设计缓存故障降级处理方案
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6117680.shtml

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/9868713.shtml

原标题：JSON XML 数据解析处理示例
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5569913.shtml

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5416762.shtml

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/7602079.shtml

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/2980456.shtml

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5872170.shtml

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0135840.shtml

原标题：golang 系统设计消息体序列化选型对比
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/1220610.shtml

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0597560.shtml

原标题：golang 系统设计日志系统架构思路
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0712292.shtml


二、踩坑排错｜Troubleshooting
原标题：从零学习基础的接口请求与参数处理
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/2374587.shtml

原标题：优化实践：预加载与懒加载业务场景取舍
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3049017.shtml

原标题：golang 系统设计文件存储选型对比
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6218499.shtml

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/2483236.shtml

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6648040.shtml

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3862412.shtml

原标题：nodejs 集成测试业务流程编写
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/1820015.shtml

原标题：Practice：实现数据库事务消息最终一致性demo
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/2404124.shtml

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/9907547.shtml

原标题：方案设计：异步解耦业务架构边界识别
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6070562.shtml

原标题：golang 系统设计日志脱敏防止信息泄露
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/7248656.shtml

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8949899.shtml

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6165864.shtml

原标题：死信队列处理消息阻塞业务
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3594977.shtml

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4962988.shtml

原标题：golang redis 缓存更新策略讲解
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4901132.shtml

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/9421809.shtml

原标题：golang docker compose 部署 minio
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/2500508.shtml

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6452914.shtml

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3744133.shtml

原标题：golang goroutine 池任务调度
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/2614681.shtml

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4898957.shtml

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/7237197.shtml

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/7376195.shtml

原标题：golang 系统设计排行榜几种实现
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3265281.shtml

原标题：排错：打包后资源路径，开发生产行为不一致
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8586917.shtml

原标题：从零搭建简单Mock接口服务
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0042135.shtml

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/2490716.shtml

原标题：nodejs 多进程任务分发处理
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8613534.shtml

原标题：数值 key 浮点匹配异常规避
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/1705255.shtml

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6483973.shtml

原标题：golang pprof 线上采集性能数据
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/9505909.shtml

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8159190.shtml

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6383279.shtml

原标题：程序信号中断退出处理逻辑
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8646973.shtml

原标题：无用对象回收抑制内存上涨
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5077774.shtml

原标题：部署实践：容器时区统一配置解决方案
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8935698.shtml

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0193279.shtml

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8380467.shtml

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4427894.shtml

三、实战开发｜Practice
原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5499638.shtml

原标题：Hands‑on：简易代理服务器开发实践
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/9837838.shtml

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/2341971.shtml

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/9067631.shtml

原标题：Practice：实现接口防重提交组件实践
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/9823238.shtml

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3931904.shtml

原标题：开发环境变量配置全平台教程
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0762901.shtml

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0446861.shtml

原标题：golang html 模板渲染简单示例
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8711960.shtml

原标题：项目依赖安全扫描漏洞防范
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6099204.shtml

原标题：正则表达式文本处理实战案例
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/1509239.shtml

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/1779794.shtml

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4095365.shtml

原标题：方案对比：几种分布式限流算法架构适用性
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8094183.shtml

原标题：上传接口跨域配置特殊适配
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5704384.shtml

原标题：golang es 查询语句 DSL 实操
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8909426.shtml

原标题：跨平台换行符统一异常修复
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/1660758.shtml

原标题：golang 系统设计 rest 资源命名规范汇总
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3316274.shtml

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4999490.shtml

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5789008.shtml

原标题：golang minio 分片上传断点续传
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4251306.shtml

原标题：Architecture：链路追踪架构核心组件与埋点
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/1081617.shtml

原标题：设计思考：消息队列重复消费架构层防御手段
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4862460.shtml

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/7165201.shtml

原标题：golang 系统设计开源项目协作流程梳理
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5057004.shtml

原标题：新手教程：Gittag版本标签打标签实操
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/7272354.shtml

原标题：全量回归测试提升代码质量
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3935574.shtml

原标题：Git LFS 大文件推送失败解决
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6154760.shtml

原标题：golang 系统设计消息发送确认机制配置实操
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/9377075.shtml

原标题：开源源码阅读拆解学习思路
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5877222.shtml

原标题：快速入门消息队列基础概念模型
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4904905.shtml

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6049768.shtml

原标题：前端组件库按需加载性能优化
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6479151.shtml

原标题：Debug：多线程共享可变变量产生脏数据
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/7634027.shtml

原标题：golang 系统设计限流算法原理代码实现
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8649584.shtml

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5124302.shtml

原标题：开发复盘：超时参数统一治理线上服务实践
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8614869.shtml

原标题：多操作系统开发兼容处理
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6710702.shtml

原标题：Hands‑on：简易链路追踪原型开发实践
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8830508.shtml

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8930887.shtml

四、架构设计｜Architecture
原标题：golang 错误包装 errors.wrap 用法
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3880187.shtml

原标题：golang docker 多阶段构建 go 镜像
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/7967902.shtml

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4319146.shtml

原标题：golang mysql 主从同步延迟兼容
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3776454.shtml

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/9061203.shtml

原标题：golang 系统设计回调重试幂等完整处理
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/6722058.shtml

原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5940052.shtml

原标题：HelloShell：入门常用shell脚本编写
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3575132.shtml

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/5695154.shtml

原标题：Practice：实现定时任务动态启停管理接口
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/7593842.shtml

原标题：nodejs 跨域中间件配置细节
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/9378251.shtml

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3596083.shtml

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3780317.shtml

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/4465920.shtml

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/9361450.shtml

原标题：运维笔记：系统文件句柄数调整生产配置
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/3505050.shtml

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/0142049.shtml

原标题：Security：Docker镜像安全扫描漏洞修复
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://www.blog.wanrenzuji.cn/Article/details/8378258.shtml

?
