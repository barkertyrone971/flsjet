最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 rest http 方法使用原则
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.gjizlyk.asia/blog/2385613.sHtMl

原标题：golang 系统设计序列化性能选型对比
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://book.gjizlyk.asia/blog/9356713.sHtMl

原标题：快速入门环境区分：开发、测试、生产环境
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.gjizlyk.asia/blog/9424498.sHtMl

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.gjizlyk.asia/blog/1288311.sHtMl

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://book.gjizlyk.asia/blog/1166059.sHtMl

原标题：从零搭建简单定时任务demo
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.gjizlyk.asia/blog/2305065.sHtMl

原标题：极简方式搭建个人技术文档站点
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.gjizlyk.asia/blog/0148344.sHtMl

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.gjizlyk.asia/blog/7355188.sHtMl

原标题：前端大文件分片上传完整方案
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://book.gjizlyk.asia/blog/4835397.sHtMl

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.gjizlyk.asia/blog/7234523.sHtMl

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.gjizlyk.asia/blog/3259665.sHtMl

原标题：golang goroutine 池任务调度
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.gjizlyk.asia/blog/2273887.sHtMl

原标题：golang 系统设计故障演练简单落地思路方法论
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.gjizlyk.asia/blog/4998259.sHtMl

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.gjizlyk.asia/blog/8709782.sHtMl

原标题：golang 系统设计高可用服务架构梳理
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.gjizlyk.asia/blog/1186296.sHtMl

原标题：vue pinia 状态管理实战教程
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.gjizlyk.asia/blog/0537656.sHtMl

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.gjizlyk.asia/blog/5861829.sHtMl

原标题：部署实践：告警收敛避免告警风暴配置
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.gjizlyk.asia/blog/0892483.sHtMl

原标题：golang 优雅停机服务关闭实现
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.gjizlyk.asia/blog/3200809.sHtMl

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://book.gjizlyk.asia/blog/5101346.sHtMl

原标题：读懂开源项目 README 实用技巧
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.gjizlyk.asia/blog/5829147.sHtMl

原标题：端口占用释放资源重启服务
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.gjizlyk.asia/blog/2650422.sHtMl

原标题：golang 系统设计接口返回格式统一规范
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.gjizlyk.asia/blog/5460847.sHtMl

原标题：极简方式搭建个人技术文档站点
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.gjizlyk.asia/blog/5100189.sHtMl

原标题：golang 系统设计监控告警阈值设置思路
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.gjizlyk.asia/blog/9710067.sHtMl

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.gjizlyk.asia/blog/2172842.sHtMl

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://book.gjizlyk.asia/blog/0770458.sHtMl

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.gjizlyk.asia/blog/7068006.sHtMl

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://book.gjizlyk.asia/blog/2478752.sHtMl

原标题：golang 系统设计 README 开源文档模板
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.gjizlyk.asia/blog/3105020.sHtMl

原标题：语义化版本依赖管理防错乱
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.gjizlyk.asia/blog/7050339.sHtMl

原标题：nodejs 全局异常捕获进程防护
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.gjizlyk.asia/blog/0151906.sHtMl

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.gjizlyk.asia/blog/0571573.sHtMl

原标题：golang k8s 监控 prometheus 部署
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.gjizlyk.asia/blog/1456731.sHtMl

原标题：Practice：实现异步任务结果查询回调实践
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.gjizlyk.asia/blog/1197925.sHtMl

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://book.gjizlyk.asia/blog/5830617.sHtMl

原标题：OpenSource：开源项目贡献者协作流程规范
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.gjizlyk.asia/blog/0417412.sHtMl

原标题：Security：Web常见安全漏洞原理与修复清单
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.gjizlyk.asia/blog/0978631.sHtMl

原标题：入门实践：简单错误码设计与使用规范
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.gjizlyk.asia/blog/7474067.sHtMl

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://book.gjizlyk.asia/blog/7122689.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.gjizlyk.asia/blog/0499842.sHtMl

原标题：golang 系统设计排行榜几种实现
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.gjizlyk.asia/blog/8802190.sHtMl

原标题：golang 系统设计 csrf 接口防护实现
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.gjizlyk.asia/blog/6007996.sHtMl

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.gjizlyk.asia/blog/3660649.sHtMl

原标题：安全复盘：业务接口越权测试与修复实践
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.gjizlyk.asia/blog/2133224.sHtMl

原标题：AI实践：大模型生成测试用例实践与校验
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.gjizlyk.asia/blog/6100498.sHtMl

原标题：golang github actions 多平台构建
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.gjizlyk.asia/blog/8809513.sHtMl

原标题：golang 系统设计热点数据缓存处理
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.gjizlyk.asia/blog/9690251.sHtMl

原标题：单元测试用例编写入门实操
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.gjizlyk.asia/blog/8333360.sHtMl

原标题：Docker 网络模式容器互通设置
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.gjizlyk.asia/blog/8172061.sHtMl

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.gjizlyk.asia/blog/7022736.sHtMl

原标题：golang 系统设计开源项目协作流程梳理
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://book.gjizlyk.asia/blog/1498865.sHtMl

原标题：golang redis 事务 multi exec 使用
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://book.gjizlyk.asia/blog/3782030.sHtMl

原标题：golang 系统设计接口向前兼容改造实操
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.gjizlyk.asia/blog/6390116.sHtMl

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.gjizlyk.asia/blog/7247933.sHtMl

原标题：golang 系统设计热点数据缓存处理
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.gjizlyk.asia/blog/4534967.sHtMl

原标题：方案对比：单体、微服务、模块化单体取舍
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.gjizlyk.asia/blog/4301803.sHtMl

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.gjizlyk.asia/blog/7601922.sHtMl

原标题：调优方案：服务实例扩容，水平扩展性能
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.gjizlyk.asia/blog/2547801.sHtMl

原标题：golang 系统设计字段命名类型选择最佳实践
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.gjizlyk.asia/blog/0713594.sHtMl

原标题：排错：静态资源404，打包路径配置错误
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.gjizlyk.asia/blog/0417758.sHtMl

原标题：golang 系统设计熔断降级架构讲解
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.gjizlyk.asia/blog/2046409.sHtMl

原标题：记一次字符集编码不一致乱码问题全排查
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://book.gjizlyk.asia/blog/0942384.sHtMl

原标题：部署实践：Nginx高可用配置方案实践
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.gjizlyk.asia/blog/3504576.sHtMl

原标题：排错：GitLFS大文件推送失败完整排障
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.gjizlyk.asia/blog/2177294.sHtMl

原标题：Practice：实现接口防重提交组件实践
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.gjizlyk.asia/blog/1080624.sHtMl

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.gjizlyk.asia/blog/9102378.sHtMl

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://book.gjizlyk.asia/blog/9389913.sHtMl

原标题：零基础理解内存溢出基础现象与表现
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.gjizlyk.asia/blog/5449905.sHtMl

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.gjizlyk.asia/blog/1115187.sHtMl

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.gjizlyk.asia/blog/7549049.sHtMl

原标题：批量操作分批处理防止 OOM
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.gjizlyk.asia/blog/6610456.sHtMl

原标题：nodejs redis 缓存业务实战
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.gjizlyk.asia/blog/4916290.sHtMl

原标题：golang gin 框架接口开发实战
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.gjizlyk.asia/blog/7904313.sHtMl

原标题：多线程线程安全脏数据规避
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.gjizlyk.asia/blog/7346044.sHtMl

原标题：golang k8s 镜像拉取密钥配置
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.gjizlyk.asia/blog/8168048.sHtMl

原标题：golang 系统设计代码仓库权限管理方案
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://book.gjizlyk.asia/blog/2956531.sHtMl

原标题：nodejs 脚手架工具开发完整教程
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.gjizlyk.asia/blog/2728900.sHtMl

原标题：nodejs 信号处理优雅关闭服务
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.gjizlyk.asia/blog/0672973.sHtMl

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://book.gjizlyk.asia/blog/7020570.sHtMl

三、实战开发｜Practice
原标题：golang mysql limit 大分页优化
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.gjizlyk.asia/blog/4059298.sHtMl

原标题：多版本开发环境共存配置
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.gjizlyk.asia/blog/3147688.sHtMl

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.gjizlyk.asia/blog/8194534.sHtMl

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.gjizlyk.asia/blog/0820294.sHtMl

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.gjizlyk.asia/blog/3621010.sHtMl

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.gjizlyk.asia/blog/8025615.sHtMl

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.gjizlyk.asia/blog/3965850.sHtMl

原标题：golang mysql 索引失效常见场景
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.gjizlyk.asia/blog/3489446.sHtMl

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.gjizlyk.asia/blog/6721653.sHtMl

原标题：快速入门：API接口调试完整实操步骤
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.gjizlyk.asia/blog/7155827.sHtMl

原标题：golang 系统设计文件存储选型对比
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.gjizlyk.asia/blog/7860448.sHtMl

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.gjizlyk.asia/blog/5792436.sHtMl

原标题：多规则数据脱敏组件开发
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.gjizlyk.asia/blog/9276873.sHtMl

原标题：golang 系统设计接口幂等架构设计
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://book.gjizlyk.asia/blog/0641428.sHtMl

原标题：业务幂等键设计防重复逻辑
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.gjizlyk.asia/blog/9199023.sHtMl

原标题：CORS 跨域问题多种解决方案
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://book.gjizlyk.asia/blog/6996262.sHtMl

原标题：golang 系统设计短信发送限流降级
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.gjizlyk.asia/blog/9185260.sHtMl

原标题：部署复盘：数据库主从备份恢复演练实践
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.gjizlyk.asia/blog/1100164.sHtMl

原标题：golang 系统设计网关性能压测优化简单思路
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.gjizlyk.asia/blog/1192129.sHtMl

原标题：实践：消息队列死信处理业务落地实践
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://book.gjizlyk.asia/blog/9603080.sHtMl

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.gjizlyk.asia/blog/5996349.sHtMl

原标题：golang minio 预签名 url 临时访问
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.gjizlyk.asia/blog/5142409.sHtMl

原标题：架构笔记：数据库连接池架构参数调优思路
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://book.gjizlyk.asia/blog/4577251.sHtMl

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.gjizlyk.asia/blog/7746196.sHtMl

原标题：全平台系统环境变量配置
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.gjizlyk.asia/blog/1823257.sHtMl

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.gjizlyk.asia/blog/9920955.sHtMl

原标题：日志驱动异常日志不输出修复
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.gjizlyk.asia/blog/1490564.sHtMl

原标题：新手向：开源项目依赖安装失败排查
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.gjizlyk.asia/blog/7361963.sHtMl

原标题：看懂报错日志快速定位问题
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.gjizlyk.asia/blog/8401422.sHtMl

原标题：Docker 容器网络不通排查
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.gjizlyk.asia/blog/3240898.sHtMl

原标题：golang 系统设计消息消费 offset 管理策略
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.gjizlyk.asia/blog/8192777.sHtMl

原标题：golang kafka 死信队列业务落地
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.gjizlyk.asia/blog/8659455.sHtMl

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.gjizlyk.asia/blog/8337971.sHtMl

原标题：安全实践：备份文件访问权限安全管控
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.gjizlyk.asia/blog/7500608.sHtMl

原标题：Hands‑on：简易代理服务器开发实践
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.gjizlyk.asia/blog/6506924.sHtMl

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.gjizlyk.asia/blog/0485712.sHtMl

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.gjizlyk.asia/blog/6490364.sHtMl

原标题：API 接口调试与异常处理实战
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.gjizlyk.asia/blog/3974017.sHtMl

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.gjizlyk.asia/blog/1191909.sHtMl

原标题：CPU 亲和性配置负载均衡调度
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://book.gjizlyk.asia/blog/4163128.sHtMl

四、架构设计｜Architecture
原标题：golang 分布式上下文传递方案
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://book.gjizlyk.asia/blog/7789362.sHtMl

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://book.gjizlyk.asia/blog/2242301.sHtMl

原标题：golang 项目环境变量加载方案
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.gjizlyk.asia/blog/7160782.sHtMl

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.gjizlyk.asia/blog/5162298.sHtMl

原标题：golang 分布式锁 redis 实现
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.gjizlyk.asia/blog/6426821.sHtMl

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.gjizlyk.asia/blog/2918980.sHtMl

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.gjizlyk.asia/blog/2505423.sHtMl

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.gjizlyk.asia/blog/6618713.sHtMl

原标题：Docker 多阶段构建镜像瘦身
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.gjizlyk.asia/blog/2971365.sHtMl

原标题：不必要字符转义关闭业务异常
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.gjizlyk.asia/blog/5271780.sHtMl

原标题：超大数据集分页性能优化方案
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.gjizlyk.asia/blog/9211406.sHtMl

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.gjizlyk.asia/blog/5389286.sHtMl

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.gjizlyk.asia/blog/9266595.sHtMl

原标题：Nginx 透传真实客户端 IP 配置
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://book.gjizlyk.asia/blog/3735960.sHtMl

原标题：消息队列重复消费业务处理
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.gjizlyk.asia/blog/9137000.sHtMl

原标题：从零搭建本地开发环境完整教程
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://book.gjizlyk.asia/blog/8428962.sHtMl

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.gjizlyk.asia/blog/6644289.sHtMl

原标题：方案设计：多租户系统架构三种实现模式对比
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.gjizlyk.asia/blog/2593040.sHtMl

?
