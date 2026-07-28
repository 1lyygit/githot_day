# GitHub 热门项目日报 - 2026-07-13

> 每日精选 GitHub 上最受关注的开源项目，助你紧跟技术前沿。

## 今日概览

今日 GitHub 趋势呈现三大亮点：**AI 基础设施全面成熟化**（从沙箱隔离到命令防护的全栈安全）、**大厂开源策略深度博弈**（OpenAI、阿里巴巴、腾讯、Meta 纷纷下场）、**垂直场景 Agent 百花齐放**（交易、会议、视频、办公等场景全面 AI 化）。TypeScript 和 Rust 继续主导 Agent 基础设施层，Python 则在应用层保持强势。

---

## 热门项目精选

### 1. OpenCut-app/OpenCut ⭐ 64,021
- **链接**：https://github.com/OpenCut-app/OpenCut
- **简介**：开源 CapCut 替代品，跨平台视频编辑器
- **语言**：TypeScript / Rust
- **今日增星**：+1,077
- **亮点**：正处于全面重写阶段，将基于 Rust 核心构建插件优先架构，支持 Web、桌面和移动端统一代码库。内置 MCP 服务器支持 AI 代理直接操控视频编辑流程，还规划了 Headless 模式用于自动化批量渲染。对创作者工具和 AI 工作流结合感兴趣的前端/桌面开发者值得密切关注。
- **适合人群**：视频创作者、前端开发者、对 AI+创意工具感兴趣的开发者

---

### 2. Graphify-Labs/graphify ⭐ 83,680
- **链接**：https://github.com/Graphify-Labs/graphify
- **简介**：AI 编码助手技能，将代码/文档/媒体转为可查询知识图谱
- **语言**：Python
- **今日增星**：+1,028
- **亮点**：支持把任何文件夹（代码、SQL 模式、R 脚本、文档、论文、图片、视频）统一转换为查询式知识图谱。应用代码 + 数据库模式 + 基础设施可以在一个图谱中关联分析。支持 Claude Code、Codex、OpenCode、Cursor、Gemini CLI 等主流 AI 工具。对于需要理解大型复杂代码库或进行跨系统数据分析的开发者是利器。
- **适合人群**：需要处理大型代码库的团队、数据工程师、AI 辅助开发者

---

### 3. Zackriya-Solutions/meetily ⭐ 23,826
- **链接**：https://github.com/Zackriya-Solutions/meetily
- **简介**：隐私优先的本地 AI 会议助手
- **语言**：Rust
- **本周增星**：+7,440（本周最高）
- **亮点**：基于 Rust 构建，100% 本地处理无需任何云服务。采用 Parakeet/Whisper 实现 4 倍速实时转录，支持说话人分离和 Ollama 本地 LLM 摘要。当前自托管 AI 会议工具中排名第一，对隐私敏感的企业和团队极具吸引力。5,556 次提交显示项目处于高度活跃状态。
- **适合人群**：隐私敏感型企业、远程工作团队、需要本地部署的合规场景

---

### 4. asgeirtj/system_prompts_leaks ⭐ 56,972
- **链接**：https://github.com/asgeirtj/system_prompts_leaks
- **简介**：系统性地提取和记录主流 AI 产品的系统提示词
- **语言**：JavaScript
- **本周增星**：+7,155
- **亮点**：覆盖 Anthropic、OpenAI、Google、xAI、Microsoft、Perplexity 等主流厂商的 Claude、GPT、Gemini、Grok、Copilot 等产品的系统提示词。被《华盛顿邮报》引用报道。提供版本对比、官方发布与提取版本区分、工具提示词分类等结构化归档。对于研究 AI 安全、提示词工程和模型行为的开发者是宝贵的参考资料。
- **适合人群**：AI 安全研究员、提示词工程师、对模型行为机制感兴趣的开发者

---

### 5. iOfficeAI/OfficeCLI ⭐ 15,797
- **链接**：https://github.com/iOfficeAI/OfficeCLI
- **简介**：专为 AI 智能体设计的 Office 套件
- **语言**：C# / .NET
- **本周增星**：+6,978
- **亮点**：全球首个专为 AI Agent 设计的 Office 工具，单二进制文件无需安装 Office。支持 Word/Excel/PowerPoint 的完整读写改操作，内置 350+ Excel 公式自动求值引擎和高保真 HTML 渲染引擎。提供确定性 JSON 输出、路径寻址、渐进式复杂度分级。支持 MCP 协议，Claude Code/Cursor 可一键接入。5,784 次提交，非常活跃。
- **适合人群**：需要自动化处理 Office 文档的开发者、AI Agent 构建者、办公自动化场景

---

### 6. HKUDS/Vibe-Trading ⭐ 21,127
- **链接**：https://github.com/HKUDS/Vibe-Trading
- **简介**：你的个人 AI 交易代理
- **语言**：Python / React
- **今日增星**：+768
- **亮点**：香港大学数据科学实验室出品，将 LLM 与金融交易全流程结合。内置 461 个预构建 Alpha 因子，支持 18 个免费数据源（A股/美股/港股/印度股/加密货币），连接 10 个券商。支持多智能体协作（投资委员会、量化团队、风控委员会），提供 68+ 工具覆盖数据获取到实盘执行。5,191+ 测试用例，5 种语言文档。
- **适合人群**：量化交易者、金融科技开发者、对 AI+金融感兴趣的开发者

---

### 7. Shubhamsaboo/awesome-llm-apps ⭐ 119,124
- **链接**：https://github.com/Shubhamsaboo/awesome-llm-apps
- **简介**：100+ 可立即运行的 AI Agent & RAG 应用模板
- **语言**：Python
- **今日增星**：+408
- **亮点**：精心构建的 LLM 应用"菜谱库"，覆盖 15 个类别：Agent 技能、入门 Agent、高级生产级 Agent、Always-on Agent、多 Agent 团队、语音 Agent、生成式 UI、MCP Agent、RAG 教程、记忆型应用、Chat with X 等。每个模板均为原创手写、端到端测试通过。3 条命令即可运行，支持多厂商模型切换。
- **适合人群**：AI 应用开发者、快速原型验证者、LLM 技术学习者

---

### 8. Dicklesworthstone/destructive_command_guard ⭐ 3,567
- **链接**：https://github.com/Dicklesworthstone/destructive_command_guard
- **简介**：阻止 AI 代理执行破坏性命令的安全守卫
- **语言**：Rust
- **今日增星**：+444
- **亮点**：高性能钩子工具，拦截 Claude Code、Codex、Cursor 等 AI 编程代理执行危险命令。50+ 模块化安全包覆盖数据库、容器、K8s、云平台、CI/CD 等。支持 Heredoc/内联脚本扫描、上下文感知、子毫秒延迟。原生支持 11 种 AI 代理协议。Fail-Open 设计哲学确保安全不阻塞工作流。从 175ms 优化到 3.1ms（56 倍提升）。
- **适合人群**：使用 AI 编程代理的开发者、DevOps 工程师、关注 AI 安全落地的团队

---

### 9. diegosouzapw/OmniRoute ⭐ 16,475
- **链接**：https://github.com/diegosouzapw/OmniRoute
- **简介**：免费 AI 网关，连接 231+ 供应商到主流编程工具
- **语言**：TypeScript
- **本周增星**：+4,506
- **亮点**：统一端点连接 Claude Code、Codex、Cursor、Cline、Copilot 到 231+ 供应商（50+ 免费）。RTK + Caveman 堆叠压缩节省 15-95% tokens。智能自动故障转移、MCP/A2A 协议支持、多模态 API。4,550+ 提交，21,153+ 测试用例，Turbopack 构建优化。42+ 语言国际化，社区活跃（27+ 外部贡献者）。
- **适合人群**：需要聚合多模型 API 的开发者、AI 工具链整合者、成本控制敏感用户

---

### 10. stablyai/orca ⭐ 17,656
- **链接**：https://github.com/stablyai/orca
- **简介**：并行代理舰队的 ADE（Agent 开发环境）
- **语言**：TypeScript
- **本周增星**：+4,481
- **亮点**：支持同时运行和管理多个编码代理（fleet of parallel agents），可用自己的订阅运行任意 coding agent。桌面端 + 移动端双平台支持。近期大量提交集中在终端性能深度优化（"Terminal Performance Initiative"），8x512KB/s 负载下 p50 打字延迟从 293ms 降至 15ms。支持 SSH 远程连接、多工作区管理、休眠/恢复机制。
- **适合人群**：需要同时运行多个 AI 编码代理的开发者、团队效率工具爱好者

---

### 11. bradautomates/claude-video ⭐ 7,950
- **链接**：https://github.com/bradautomates/claude-video
- **简介**：赋予 Claude 观看视频的能力
- **语言**：Python
- **本周增星**：+4,353
- **亮点**：通过 `/watch` 命令让 Claude 分析视频内容。自动下载视频（yt-dlp 覆盖数百平台）、提取关键帧、生成带时间戳的转录文本。三种细节模式（transcript/efficient/balanced/token-burner）满足不同 token 预算。感知帧去重避免静态画面浪费 token。支持时间段聚焦和精确时间点抓取。支持 50+ AI 平台集成。
- **适合人群**：需要 AI 分析视频内容的用户、内容创作者、竞品分析师

---

### 12. ruvnet/RuView ⭐ 80,353
- **链接**：https://github.com/ruvnet/RuView
- **简介**：将 WiFi 信号转为实时空间智能的隐私优先平台
- **语言**：Rust
- **本周增星**：+3,763
- **亮点**：无需摄像头，通过 WiFi CSI 信号实现人体姿态推断、生命体征监测（呼吸/心率）和存在检测。BFLD PrivacyGate 分级隐私控制在每一层边界强制执行。Apple HomeKit 原生集成、MCP 智能代理支持。96+ ADR 架构决策记录，自我纠偏的透明度文化（主动撤回过度声明）。1,055 次提交，真实 ESP32-C6 硬件验证。
- **适合人群**：物联网开发者、隐私技术爱好者、智能家居开发者

---

### 13. openai/codex-plugin-cc ⭐ 28,231
- **链接**：https://github.com/openai/codex-plugin-cc
- **简介**：在 Claude Code 中调用 Codex 进行代码审查和任务委派
- **语言**：JavaScript
- **本周增星**：+2,803
- **亮点**：OpenAI 官方出品，允许在 Claude Code 内直接调用 Codex。提供 `/codex:review` 代码审查、`/codex:adversarial-review` 对抗性审查、`/codex:rescue` 任务委派、`/codex:transfer` 会话迁移等斜杠命令。支持后台任务管理、可选审查门控。复用本地 Codex 配置和环境，无需独立运行时。仅需 ChatGPT 订阅或 OpenAI API key。
- **适合人群**：同时使用 Claude Code 和 Codex 的开发者、需要多模型代码审查的团队

---

### 14. alibaba/page-agent ⭐ 26,334
- **链接**：https://github.com/alibaba/page-agent
- **简介**：网页内 GUI Agent，一行脚本赋予网页 AI 能力
- **语言**：TypeScript
- **本周增星**：+2,666
- **亮点**：阿里巴巴开源，无需浏览器扩展、Python 或无头浏览器。纯 JavaScript 在网页内运行，基于文本式 DOM 操作（不依赖截图/多模态模型）。支持大多数主流 LLM（含本地部署）。一行 `<script>` 标签即可接入，CDN 直引。适合 SaaS 产品快速集成 AI Copilot、智能表单填写、无障碍访问等场景。基于 browser-use 构建。
- **适合人群**：前端开发者、SaaS 产品经理、需要快速集成 AI Copilot 的团队

---

### 15. TencentCloud/CubeSandbox ⭐ 9,892
- **链接**：https://github.com/TencentCloud/CubeSandbox
- **简介**：为 AI Agent 设计的极速安全沙箱
- **语言**：Rust
- **本周增星**：+2,490
- **亮点**：腾讯云开源，基于 RustVMM + KVM 构建。60ms 以内创建硬件隔离的完整沙箱环境，单实例内存开销 < 5MB。单台物理机数分钟内启动数万个沙箱。CubeCoW 写时复制引擎支持百毫秒级快照、即时克隆和任意状态回滚。凭据保险vault确保密钥不进入沙箱。eBPF 内核级网络隔离。原生兼容 E2B SDK，替换 URL 即可迁移。
- **适合人群**：AI Agent 基础设施开发者、需要隔离执行环境的平台、云原生开发者

---

### 16. facebook/astryx ⭐ 8,402
- **链接**：https://github.com/facebook/astryx
- **简介**：Meta 开源的"面向 Agent 设计"设计系统
- **语言**：TypeScript / React / StyleX
- **本周增星**：+2,397
- **亮点**：Meta 内部发展 8 年，支撑 13,000+ 应用。150+ 可访问组件，7 个现成主题（neutral/butter/chocolate/matcha/stone/gothic/y2k）。组件可在任意层级组合，swizzle 功能可将源码弹出到项目中。无样式锁定，可用 Tailwind/CSS Modules 覆盖。人机共建：API、文档和 CLI 统一设计，确保人类和 AI 使用相同工具。零构建配置接入。
- **适合人群**：前端开发者、设计系统工程师、使用 AI 辅助开发的设计师

---

### 17. Nutlope/hallmark ⭐ 4,672
- **链接**：https://github.com/Nutlope/hallmark
- **简介**：让 AI 生成的设计不再"一眼 AI"
- **语言**：CSS / JavaScript
- **今日增星**：+155
- **亮点**：反 AI 设计套话（anti-AI-slop）技能，为 Claude Code、Cursor、Codex 提供设计规范。20 个主题、4 个动词（build/audit/redesign/study）、58 个 slop-test 检测门。为不同 brief 生成不同结构的页面，而非同一模板的换色。每个生成页面都是自包含 HTML+CSS，带有结构指纹。由 Together AI 出品，MIT 协议。
- **适合人群**：前端开发者、需要高质量 AI 生成设计的团队、对 AI 设计质量有要求的设计师

---

### 18. github/spec-kit ⭐ 120,190
- **链接**：https://github.com/github/spec-kit
- **简介**：GitHub 官方推出的规格驱动开发（SDD）工具包
- **语言**：Python
- **今日增星**：+508
- **亮点**：通过 `specify` CLI 实现结构化开发工作流：规格编写 → 计划制定 → 研究分析 → 数据建模 → 任务分解。支持 bundle 打包管理（search/install/update/validate/build）。离线优先 catalog 解析、HTTPS 强制、路径约束防逃逸。可重现构建（字节级一致）。提供 product-manager、business-analyst、security-researcher、developer 四个开箱即用角色 bundle。1,373 次提交，43 个依赖排序任务。
- **适合人群**：需要规范化开发流程的团队、项目经理、技术负责人、AI 辅助开发实践者

---

## 趋势洞察

### 🔥 核心趋势总结

1. **Agent 基础设施全面成熟化**：从单纯的代码生成工具到完整的三层架构（安全层/编排层/执行层）已成行业共识。destructive_command_guard（安全）、herdr（编排）、CubeSandbox（执行）分别代表了三个层面的成熟方案，且均采用 Rust 构建以确保性能。

2. **大厂开源策略深度博弈**：OpenAI（codex-plugin-cc 为 Claude Code 开发插件）、阿里巴巴（page-agent 网页内 Agent）、腾讯（CubeSandbox 沙箱）、Meta（astryx 设计系统）、GitHub（spec-kit 规格驱动）纷纷以不同角度切入 Agent 生态，形成"开放式博弈"格局。

3. **垂直场景 Agent 百花齐放**：交易（Vibe-Trading）、会议（meetily）、视频（claude-video）、办公（OfficeCLI）、安全（strix/pentagi）等场景全面 AI 化。每个场景都在从"工具"向"代理"升级。

4. **隐私与本地化回归**：meetily（100% 本地 Rust）、RuView（WiFi 感知零摄像头）、system_prompts_leaks（AI 透明度研究）反映了对隐私和透明度的关注持续升温。

5. **TypeScript 与 Rust 双主导**：Agent 基础设施层几乎被 TypeScript（编排/工具）和 Rust（性能/安全）瓜分，Python 在应用层保持强势，C# 在 Office 自动化领域异军突起。

6. **Skill 经济持续繁荣**：hallmark（反 AI slop 设计）、marketingskills（40 个营销技能）、awesome-llm-apps（100+ 应用模板）表明"技能即代码"的生态系统持续扩展，AI 工具的可组合性成为核心竞争力。

---

*本报告数据采集时间：2026-07-13 19:30 GMT+8*
*数据来源：GitHub Trending Daily / Weekly / Search*
