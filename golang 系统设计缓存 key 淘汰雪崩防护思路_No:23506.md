最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.hounr8.asia/arts/365592.Doc

原标题：golang 系统设计分表字段选择路由规则设计
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.hounr8.asia/arts/125998.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.hounr8.asia/arts/281547.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.hounr8.asia/arts/420732.Doc

原标题：golang redis 五种数据结构实战
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.hounr8.asia/arts/717066.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.hounr8.asia/arts/302029.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.hounr8.asia/arts/951428.Doc

原标题：golang 布隆过滤器实现去重
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.hounr8.asia/arts/784749.Doc

原标题：golang mysql 长连接短连接对比
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.hounr8.asia/arts/073970.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.hounr8.asia/arts/635480.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.hounr8.asia/arts/409900.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.hounr8.asia/arts/839679.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.hounr8.asia/arts/306258.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.hounr8.asia/arts/598903.Doc

原标题：前端骨架屏提升页面体验
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.hounr8.asia/arts/294758.Doc

原标题：极简 API 网关路由转发实现
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.hounr8.asia/arts/503678.Doc

原标题：golang minio 存储桶权限管控配置
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.hounr8.asia/arts/313643.Doc

原标题：重复提交幂等防护再次讲解
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.hounr8.asia/arts/180069.Doc

原标题：多套环境灵活切换配置方案
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.hounr8.asia/arts/376787.Doc

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.hounr8.asia/arts/107471.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.hounr8.asia/arts/306276.Doc

原标题：从零学习简单分布式ID生成思路
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.hounr8.asia/arts/151169.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.hounr8.asia/arts/039015.Doc

原标题：排错：前端缓存304异常更新不及时
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.hounr8.asia/arts/714830.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.hounr8.asia/arts/451277.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.hounr8.asia/arts/017709.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.hounr8.asia/arts/972140.Doc

原标题：时间精度统一业务判断修复
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.hounr8.asia/arts/647869.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.hounr8.asia/arts/345277.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.hounr8.asia/arts/083066.Doc

原标题：Nginx 请求头大小上限调整
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.hounr8.asia/arts/638619.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.hounr8.asia/arts/698116.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.hounr8.asia/arts/779192.Doc

原标题：Debug日志：生产环境偶发空指针异常排查
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.hounr8.asia/arts/122584.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.hounr8.asia/arts/928281.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.hounr8.asia/arts/868270.Doc

原标题：Git 混乱提交历史清理方法
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.hounr8.asia/arts/717108.Doc

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.hounr8.asia/arts/300073.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.hounr8.asia/arts/232358.Doc

原标题：Shell 运维脚本服务器效率提升
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.hounr8.asia/arts/017695.Doc


二、踩坑排错｜Troubleshooting
原标题：网关集成鉴权限流日志一体化
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.hounr8.asia/arts/609388.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.hounr8.asia/arts/680463.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.hounr8.asia/arts/834974.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.hounr8.asia/arts/817833.Doc

原标题：代理 HTTPS 证书访问异常处理
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.hounr8.asia/arts/489214.Doc

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.hounr8.asia/arts/340136.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.hounr8.asia/arts/087830.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.hounr8.asia/arts/302847.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.hounr8.asia/arts/915158.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.hounr8.asia/arts/742519.Doc

原标题：golang redis stream 消息队列实践
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.hounr8.asia/arts/239101.Doc

原标题：日志驱动异常日志不输出修复
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.hounr8.asia/arts/150049.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.hounr8.asia/arts/153101.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.hounr8.asia/arts/351663.Doc

原标题：代码格式化工具团队统一风格
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.hounr8.asia/arts/318429.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.hounr8.asia/arts/851657.Doc

原标题：项目依赖安全扫描漏洞防范
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.hounr8.asia/arts/030368.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.hounr8.asia/arts/673780.Doc

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.hounr8.asia/arts/057739.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.hounr8.asia/arts/963693.Doc

原标题：数据库索引重建提升查询速度
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.hounr8.asia/arts/561902.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.hounr8.asia/arts/858060.Doc

原标题：前端权限路由动态生成实现
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.hounr8.asia/arts/246397.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.hounr8.asia/arts/283732.Doc

原标题：golang mysql limit 大分页优化
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.hounr8.asia/arts/028878.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.hounr8.asia/arts/795815.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.hounr8.asia/arts/102155.Doc

原标题：全局本地依赖隔离冲突规避
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.hounr8.asia/arts/747538.Doc

原标题：项目脚手架模板生成工具
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.hounr8.asia/arts/360228.Doc

原标题：echarts 大数据渲染性能调优
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.hounr8.asia/arts/340311.Doc

原标题：上传接口跨域配置特殊适配
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.hounr8.asia/arts/569299.Doc

原标题：方案设计：分布式分页查询架构难点处理
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.hounr8.asia/arts/685044.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.hounr8.asia/arts/375084.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.hounr8.asia/arts/542069.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.hounr8.asia/arts/303847.Doc

原标题：golang 系统设计内存高占用排查思路
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.hounr8.asia/arts/691228.Doc

原标题：golang 项目 go mod 依赖管理
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.hounr8.asia/arts/810761.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.hounr8.asia/arts/116090.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.hounr8.asia/arts/643730.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.hounr8.asia/arts/852559.Doc

三、实战开发｜Practice
原标题：设计思考：分布式会话架构选型对比
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.hounr8.asia/arts/409277.Doc

原标题：Nginx 丢失请求头配置修正
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.hounr8.asia/arts/691751.Doc

原标题：空指针异常判空容错处理
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.hounr8.asia/arts/858463.Doc

原标题：Docker 网络模式容器互通设置
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.hounr8.asia/arts/813935.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.hounr8.asia/arts/265176.Doc

原标题：golang 系统设计故障演练简单思路
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.hounr8.asia/arts/631740.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.hounr8.asia/arts/662319.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.hounr8.asia/arts/400374.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.hounr8.asia/arts/002991.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.hounr8.asia/arts/562249.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.hounr8.asia/arts/691078.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.hounr8.asia/arts/990326.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.hounr8.asia/arts/319553.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.hounr8.asia/arts/897464.Doc

原标题：GitHub 项目提交推送完整流程讲解
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.hounr8.asia/arts/275684.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.hounr8.asia/arts/744468.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.hounr8.asia/arts/191967.Doc

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.hounr8.asia/arts/676320.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.hounr8.asia/arts/819910.Doc

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.hounr8.asia/arts/010225.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.hounr8.asia/arts/815483.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.hounr8.asia/arts/156954.Doc

原标题：css 动画性能优化 GPU 加速
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.hounr8.asia/arts/693873.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.hounr8.asia/arts/119393.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.hounr8.asia/arts/205131.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.hounr8.asia/arts/849884.Doc

原标题：golang k8s 基础概念 pod deployment
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.hounr8.asia/arts/443726.Doc

原标题：项目实践：分布式会话Redis存储落地实践
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.hounr8.asia/arts/121105.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.hounr8.asia/arts/362000.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.hounr8.asia/arts/069870.Doc

原标题：跨平台换行符统一异常修复
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.hounr8.asia/arts/933707.Doc

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.hounr8.asia/arts/970625.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.hounr8.asia/arts/890331.Doc

原标题：nestjs 权限守卫鉴权实现方案
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.hounr8.asia/arts/697336.Doc

原标题：Git commit 钩子提交规范校验
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.hounr8.asia/arts/444869.Doc

原标题：限流组件计数器令牌桶模式实现
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.hounr8.asia/arts/747839.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.hounr8.asia/arts/211381.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.hounr8.asia/arts/557373.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.hounr8.asia/arts/739163.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.hounr8.asia/arts/716427.Doc

四、架构设计｜Architecture
原标题：项目实践：搭建监控大盘查看系统关键指标
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.hounr8.asia/arts/883679.Doc

原标题：多实例部署 Session 共享方案
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.hounr8.asia/arts/076734.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.hounr8.asia/arts/086472.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.hounr8.asia/arts/438905.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.hounr8.asia/arts/960725.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.hounr8.asia/arts/254243.Doc

原标题：前端工程化 webpack 打包优化
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.hounr8.asia/arts/273939.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.hounr8.asia/arts/820314.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.hounr8.asia/arts/397072.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.hounr8.asia/arts/563107.Doc

原标题：ICMP 放通网络丢包问题修复
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.hounr8.asia/arts/070357.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.hounr8.asia/arts/679228.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.hounr8.asia/arts/075508.Doc

原标题：不必要字符转义关闭业务异常
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.hounr8.asia/arts/787423.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.hounr8.asia/arts/124249.Doc

原标题：echarts 大数据渲染性能调优
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.hounr8.asia/arts/783025.Doc

原标题：不必要字符转义关闭业务异常
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.hounr8.asia/arts/752983.Doc

原标题：golang 分库分表简单路由实现
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.hounr8.asia/arts/932419.Doc

?
