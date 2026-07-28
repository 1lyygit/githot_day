# GitHub 热门项目日报 - 2026-07-14

> 每日精选 GitHub 上最受关注的开源项目，助你紧跟技术前沿。

## 今日概览

今天的 GitHub 趋势延续了 AI Agent 基础设施全面繁荣的主线，同时出现了几个亮眼的新方向：**开源视频创作工具**继续高歌猛进，**AI 安全护栏**成为开发者刚需，**规范驱动开发（SDD）**获得 GitHub 官方背书。大厂与开源社区并驱：腾讯、阿里巴巴、GitHub 官方纷纷推出面向 Agent 的底座工具；而个人开发者的垂直场景项目（求职、会议、交易、设计）则以极高的 star 增速占据榜单前列。

## 热门项目精选

### 1. OpenCut-app/OpenCut ⭐ 68,335
- **链接**：https://github.com/OpenCut-app/OpenCut
- **简介**：开源的 CapCut 替代品，面向 Web、桌面和移动端的免费视频编辑器
- **语言**：TypeScript
- **今日增星**：+1,229
- **亮点**：项目正在用 Rust 核心彻底重写，未来将支持插件优先架构、MCP Server、Headless 批量渲染和内置脚本编辑；现有经典版已可在 opencut.app 体验，是开源创作者工具赛道的重要玩家
- **适合人群**：视频创作者、开源创作者工具爱好者、希望自建视频编辑工作流的开发者

### 2. Dicklesworthstone/destructive_command_guard ⭐ 4,019
- **链接**：https://github.com/Dicklesworthstone/destructive_command_guard
- **简介**：为 AI 编程代理设计的高性能命令护栏，防止误执行破坏性操作
- **语言**：Rust
- **今日增星**：+1,295
- **亮点**：Rust 实现的亚毫秒级命令钩子，能在 `git reset --hard`、`rm -rf`、`DROP TABLE` 等危险命令执行前拦截；内置 50+ 安全规则包，覆盖数据库、Kubernetes、Docker、云平台等场景，支持 Claude Code、Codex、Gemini CLI、Cursor 等主流 AI 代理
- **适合人群**：经常使用 AI 编程代理的开发者、DevOps/SRE 工程师、安全敏感团队

### 3. HKUDS/Vibe-Trading ⭐ 22,347
- **链接**：https://github.com/HKUDS/Vibe-Trading
- **简介**：香港大学数据科学实验室出品的个人交易智能体
- **语言**：Python
- **今日增星**：+1,153
- **亮点**："一条命令赋能你的交易智能体"；集成 461 个预构建量化因子、10 家券商连接、18+ 数据源、多智能体 Swarm，支持研究自动驾驶闭环；提供 CLI、Web UI、REST API 和 MCP Server 四种交互方式，且已完成外部安全审计
- **适合人群**：量化研究者、个人交易者、金融开发者、AI/LLM 应用开发者

### 4. Shubhamsaboo/awesome-llm-apps ⭐ 120,180
- **链接**：https://github.com/Shubhamsaboo/awesome-llm-apps
- **简介**：100+ 可实际运行的 AI Agent 与 RAG 应用合集
- **语言**：Python
- **今日增星**：+996
- **亮点**：收录 100 多个可直接克隆、定制并部署的 AI Agent 和 RAG 应用，覆盖客服、研究、自动化、多 Agent 协作等场景；每个项目都提供完整代码和说明，是快速学习 Agent 落地的宝藏仓库
- **适合人群**：AI 应用开发者、学习者、希望快速搭建原型的产品经理和创业者

### 5. Graphify-Labs/graphify ⭐ 85,459
- **链接**：https://github.com/Graphify-Labs/graphify
- **简介**：将代码、文档、图片、视频等构建为可查询知识图谱的 AI 编程助手技能
- **语言**：Python
- **今日增星**：+1,095
- **亮点**：AI coding assistant skill，能把任意文件夹的代码、SQL schema、R 脚本、文档、论文、图片、视频统一构建成可查询知识图谱；支持 Claude Code、Codex、OpenCode、Cursor、Gemini CLI 等主流 AI 编码工具，实现 App 代码+数据库 schema+基础设施的一体化理解
- **适合人群**：需要理解复杂代码库和文档的开发者、AI 增强编程用户、知识图谱爱好者

### 6. github/spec-kit ⭐ 120,945
- **链接**：https://github.com/github/spec-kit
- **简介**：GitHub 官方推出的规范驱动开发（Spec-Driven Development）工具包
- **语言**：Python
- **今日增星**：+543
- **亮点**：围绕"规范先行、AI 辅助实现"理念，提供 `spec.md`、`plan.md`、`tasks.md` 等全套 SDD 脚手架；支持角色化套件管理（产品经理/业务分析师/安全研究员/开发者）、代码库与规范差距评估，以及 GitHub Copilot 等 AI 代理集成
- **适合人群**：采用规范驱动开发的团队、需要为 AI 编码代理创建结构化上下文的开发者、追求工程规范化的技术负责人

### 7. Nutlope/hallmark ⭐ 5,614
- **链接**：https://github.com/Nutlope/hallmark
- **简介**：反"AI 味"设计技能，让 Claude Code、Cursor、Codex 生成更精致的 UI
- **语言**：CSS
- **今日增星**：+794
- **亮点**：为 AI 编程工具提供的设计技能包，帮助开发者摆脱千篇一律的"AI slop"界面；通过 CSS 和设计系统约束，引导 AI 输出更有质感、更符合设计规范的 UI/UX
- **适合人群**：前端开发者、全栈开发者、AI 辅助设计的独立开发者

### 8. MadsLorentzen/ai-job-search ⭐ 22,164
- **链接**：https://github.com/MadsLorentzen/ai-job-search
- **简介**：基于 Claude Code 构建的本地 AI 求职申请框架
- **语言**：TypeScript
- **本周增星**：+15,420
- **亮点**：本周增星冠军；支持职位评估、简历定制、求职信撰写、面试准备全流程；采用 Drafter-Reviewer 双代理架构和 PDF 验证循环，作者亲测 69 份定制申请 → 20 次初面 → 1 份 AI 工程师 offer
- **适合人群**：求职者、职业转型者、希望用 AI 自动化求职流程的专业人士

### 9. iOfficeAI/OfficeCLI ⭐ 16,417
- **链接**：https://github.com/iOfficeAI/OfficeCLI
- **简介**：首个专为 AI Agent 构建的 Office 套件
- **语言**：C#
- **本周增星**：+7,596
- **亮点**：单二进制零依赖，无需安装 Office 即可读取、编辑和自动化 Word、Excel、PowerPoint；内置高保真 HTML 渲染引擎让 AI "看见"文档效果；支持 MCP Server 一键接入 Claude Code/Cursor，并提供 Python 和 Node.js SDK
- **适合人群**：AI Agent 开发者、需要自动化文档处理的开发者、企业办公自动化团队

### 10. Zackriya-Solutions/meetily ⭐ 24,399
- **链接**：https://github.com/Zackriya-Solutions/meetily
- **简介**：隐私优先的本地 AI 会议助手
- **语言**：Rust
- **本周增星**：+5,392
- **亮点**：100% 本地处理，无需上传云端；基于 Rust + Tauri 构建，支持 4 倍速实时转录、说话人分离、Ollama 本地摘要；对数据合规和隐私要求高的团队极具吸引力
- **适合人群**：注重隐私的职场人士、企业合规团队、自托管爱好者、远程办公团队

### 11. stablyai/orca ⭐ 18,738
- **链接**：https://github.com/stablyai/orca
- **简介**：管理并行 Agent 集群的 Agent 开发环境（ADE）
- **语言**：TypeScript
- **本周增星**：+5,263
- **亮点**：面向桌面和移动端的 Agent Development Environment，支持管理大规模并行 Agent 集群；为多 Agent 协作、编排和状态追踪提供基础设施，是 Agent 操作系统方向的代表项目
- **适合人群**：AI Agent 开发者、多 Agent 系统研究者、需要编排复杂 Agent 工作流的团队

### 12. diegosouzapw/OmniRoute ⭐ 17,070
- **链接**：https://github.com/diegosouzapw/OmniRoute
- **简介**：免费 AI 网关，单一端点对接 231+ AI 提供商
- **语言**：TypeScript
- **本周增星**：+4,345
- **亮点**：一个端点即可对接 231+ AI 提供商（含 50+ 免费模型），原生支持 Claude Code、Codex、Cursor 等开发工具；帮助开发者统一管理模型调用、简化配置并优化成本
- **适合人群**：AI 应用开发者、希望统一管理多个 AI API 的团队、关注成本优化的开发者

### 13. usestrix/strix ⭐ 41,340
- **链接**：https://github.com/usestrix/strix
- **简介**：开源 AI 渗透测试工具
- **语言**：Python
- **本周增星**：+3,403
- **亮点**：用 AI 自动发现应用漏洞并提供修复建议；在安全社区持续火爆，本周再次登上 Trending 榜；代表 AI 安全攻防实战化趋势
- **适合人群**：安全工程师、渗透测试人员、DevSecOps 团队、对 AI 安全攻防感兴趣的研究者

### 14. TencentCloud/CubeSandbox ⭐ 10,070
- **链接**：https://github.com/TencentCloud/CubeSandbox
- **简介**：腾讯开源的面向 AI Agent 的即时、并发、安全、轻量沙箱环境
- **语言**：Rust
- **本周增星**：+2,367
- **亮点**：为 AI Agent 提供隔离的执行环境，支持即时启动、并发运行和安全约束；让 Agent 在受控沙箱中安全地执行代码和工具调用，是 Agent 基础设施的重要底座
- **适合人群**：AI Agent 基础设施开发者、需要安全隔离 AI 执行环境的企业、云计算和容器化开发者

### 15. alibaba/page-agent ⭐ 26,541
- **链接**：https://github.com/alibaba/page-agent
- **简介**：阿里巴巴开源的 JavaScript 页面内 GUI Agent
- **语言**：TypeScript
- **本周增星**：+1,950
- **亮点**：允许用自然语言直接控制网页界面，将传统浏览器自动化升级为 AI 驱动的语义交互；为网页端 Agent 应用提供了新的交互范式
- **适合人群**：前端开发者、自动化测试工程师、RPA 开发者、需要 AI 驱动网页自动化的团队

## 趋势洞察

**1. Agent 基础设施进入"护栏时代"**

随着 Claude Code、Codex、Cursor 等 AI 编程代理的普及，如何防止 Agent 误操作成为刚需。`destructive_command_guard` 今日增星第一梯队，反映出开发者对 AI 安全护栏的强烈需求。未来围绕 Agent 的执行安全、权限隔离、审计追踪将形成完整工具链。

**2. 大厂底座开源常态化**

GitHub 官方的 `spec-kit`（规范驱动开发）、腾讯的 `CubeSandbox`（Agent 沙箱）、阿里巴巴的 `page-agent`（页面 GUI Agent）同时活跃，说明大厂正在把 Agent 开发所需的基础能力快速开源。这与社区垂直项目形成互补：大厂做底座，创业者做场景。

**3. 垂直场景 Agent 持续爆发**

求职（`ai-job-search`）、会议（`meetily`）、交易（`Vibe-Trading`）、办公（`OfficeCLI`）、设计（`hallmark`）等垂直场景的 Agent 项目增速极快。AI 不再只是聊天助手，而是深入具体工作流的"数字员工"。

**4. Rust 在 Agent 基础设施中的地位持续上升**

今日/本周榜单中 Rust 项目占据重要位置：命令护栏、会议助手、Agent 沙箱、WiFi 感知计算等都选择 Rust 作为核心语言。性能、安全和可部署性使 Rust 成为 Agent 基础设施的首选之一。

**5. MCP 协议成为 Agent 集成的"通用插头"**

越来越多的项目主动声明支持 MCP Server：OpenCut、Vibe-Trading、OfficeCLI、graphify 等。MCP（Model Context Protocol）正在成为 AI 工具与外部系统交互的事实标准，掌握 MCP 集成能力将成为 Agent 开发者的基本功。

---

*数据来源：GitHub Trending Daily / Weekly、GitHub Search（created:>2026-07-07）*  
*报告时间：2026-07-14 18:25 (GMT+8)*
