# GitHub 热门项目日报 - 2026-07-08

> 每日精选 GitHub 上最受关注的开源项目，助你紧跟技术前沿。

## 今日概览

今日 AI 安全赛道进入「双极对决」——红队攻击自动化 strix 与多智能体进攻平台 T3MP3ST 同时霸榜，分别代表「企业级渗透」和「自主攻击编排」两条路线。Agent 基础设施继续深化，腾讯一口气贡献了 Agent 记忆（TencentDB-Agent-Memory）和沙箱（CubeSandbox）两层关键组件，Facebook 的 Astryx 则在「面向 Agent 的设计系统」方向上建立新标准。一个值得关注的新趋势是 **WiFi 感知计算**——RuView 今日获得 1,100+ stars，将普通 WiFi 信号转化为空间智能和生命体征监测，开辟了一个全新的应用领域。

## 热门项目精选

### 1. usestrix/strix ⭐ 38,836
- **链接**：https://github.com/usestrix/strix
- **简介**：开源 AI 渗透测试工具，自动发现并修复应用安全漏洞
- **语言**：Python
- **本周增星**：+10,741
- **亮点**：将 AI 能力注入安全测试流程，自动执行渗透测试、生成漏洞报告并给出修复建议。以本周超万星的增速成为当前最火的开源 AI 安全项目，填补了「AI + 红队」的生态空白。
- **适合人群**：安全工程师、DevSecOps 团队、需要自动化安全审计的开发者

### 2. MadsLorentzen/ai-job-search ⭐ 13,282
- **链接**：https://github.com/MadsLorentzen/ai-job-search
- **简介**：基于 Claude Code 的 AI 求职框架——评估职位、定制简历、撰写求职信、模拟面试
- **语言**：TypeScript
- **今日增星**：+2,514
- **亮点**：Fork 即用的求职 Agent 框架，只需填入个人信息，Claude Code 就能自动完成从筛选职位到面试准备的完整求职流程。今日以 2,500+ stars 领跑日榜，AI 在垂直场景的落地典范。
- **适合人群**：求职者、职业规划师、HR 工具开发者

### 3. elder-plinius/T3MP3ST ⭐ 3,600
- **链接**：https://github.com/elder-plinius/T3MP3ST
- **简介**：多智能体自主红队攻击平台——进攻性安全元编排框架
- **语言**：TypeScript
- **本周增星**：+1,700（7月2日创建，仅6天）
- **亮点**：与 strix 的「防守修复」定位不同，T3MP3ST 是纯粹的「攻击模拟」平台，支持多 Agent 协同执行复杂的进攻性安全任务。新建仅 6 天即获 3.6k stars，与 strix 形成攻防互补的 AI 安全双极格局。
- **适合人群**：红队安全研究员、渗透测试工程师、攻防演练团队

### 4. ruvnet/RuView ⭐ 78,838
- **链接**：https://github.com/ruvnet/RuView
- **简介**：将普通 WiFi 信号转化为实时空间智能、生命体征监测和存在感知——不需要摄像头
- **语言**：Rust
- **今日增星**：+1,129
- **亮点**：利用商用 WiFi 信号实现无摄像头的空间感知，可检测人体存在、监测呼吸频率和心率。纯软件方案，无需额外硬件，代表了「无感感知计算」的前沿方向。Rust 实现保证了性能和安全性。
- **适合人群**：IoT 开发者、智慧家居/健康监测领域、隐私保护技术研究者

### 5. facebook/astryx ⭐ 7,027
- **链接**：https://github.com/facebook/astryx
- **简介**：面向 AI Agent 的开源设计系统，完全可定制
- **语言**：TypeScript
- **本周增星**：+5,247
- **亮点**：Meta 开源的首个「Agent-Ready」设计系统，提供了一套完整的 UI 组件和交互模式，专门为 AI Agent 生成和操控界面而设计。标志着前端从「面向人类设计」向「面向 Agent 设计」的范式转移。
- **适合人群**：前端开发者、Agent 工具链开发者、UI/UX 设计师

### 6. openai/codex-plugin-cc ⭐ 26,760
- **链接**：https://github.com/openai/codex-plugin-cc
- **简介**：让 Claude Code 使用 OpenAI Codex——代码审查与任务委托
- **语言**：JavaScript
- **本周增星**：+4,725
- **亮点**：OpenAI 官方出品，在 Claude Code 中无缝集成 Codex 能力。OpenAI 为竞争对手的编码 Agent 开发插件，这种「开放式博弈」姿态本身就是一个标志性事件，也侧面印证了 Claude Code 在开发者中的主导地位。
- **适合人群**：Claude Code 用户、需要多模型协同开发的团队

### 7. alibaba/zvec ⭐ 14,203
- **链接**：https://github.com/alibaba/zvec
- **简介**：轻量级、极速的进程内向量数据库
- **语言**：C++
- **今日增星**：+685
- **亮点**：阿里巴巴开源的嵌入式向量数据库，主打「零依赖、毫秒级响应」，可直接嵌入应用进程，无需独立部署。相比 Pinecone/Milvus 等重量级方案，zvec 更适合边缘设备和轻量级 AI 应用的向量检索场景。
- **适合人群**：边缘 AI 开发者、嵌入式系统工程师、需要轻量级向量搜索的应用开发者

### 8. TencentCloud/TencentDB-Agent-Memory ⭐ 7,315
- **链接**：https://github.com/TencentCloud/TencentDB-Agent-Memory
- **简介**：AI Agent 全本地长期记忆系统——四层渐进式流水线，零外部 API 依赖
- **语言**：TypeScript
- **今日增星**：+610
- **亮点**：腾讯出品的 Agent 记忆方案，采用「会话级→短期→长期→归档」四层渐进式流水线，完全本地运行，不依赖任何外部 API。在 Agent 记忆成为基础设施瓶颈的当下，这个方案精准切中了隐私和延迟两大痛点。
- **适合人群**：AI Agent 开发者、需要长期会话记忆的 Chatbot 项目、企业级 Agent 应用

### 9. iOfficeAI/OfficeCLI ⭐ 10,930
- **链接**：https://github.com/iOfficeAI/OfficeCLI
- **简介**：首个为 AI Agent 量身定制的 Office 套件——读写编辑 Word/Excel/PPT，无需安装 Office
- **语言**：C#
- **今日增星**：+893
- **亮点**：单一二进制文件，无需 Microsoft Office 即可让 AI Agent 完成 Office 文件的读取、编辑和自动化。填补了「Agent 操控 Office 文档」的工具空白，对于需要批量处理文档的企业场景价值巨大。
- **适合人群**：企业自动化开发者、文档处理工作流构建者、RPA 工程师

### 10. bradautomates/claude-video ⭐ 5,665
- **链接**：https://github.com/bradautomates/claude-video
- **简介**：让 Claude 观看任意视频——下载、抽帧、转录，全部交给 Claude
- **语言**：Python
- **今日增星**：+965
- **亮点**：一键让 Claude Code 分析视频内容：自动下载视频、提取关键帧、语音转文字，然后交给 Claude 进行内容理解、摘要生成或问答。为 AI Agent 补上了「视频理解」这块重要拼图。
- **适合人群**：内容创作者、视频分析师、需要视频内容自动化处理的团队

### 11. synthetic-sciences/openscience ⭐ 1,600
- **链接**：https://github.com/synthetic-sciences/openscience
- **简介**：开源 AI 科学研究工作台——让 AI Agent 成为你的科研助手
- **语言**：TypeScript
- **本周增星**：+1,600（7月2日创建，仅6天）
- **亮点**：定位「AI 时代的科研操作系统」，支持 Agent 驱动的文献检索、实验设计、数据分析和论文辅助。新建 6 天即获 1.6k stars，反映了学术界对 AI 辅助科研工具的强烈需求。
- **适合人群**：科研人员、研究生、学术机构、AI for Science 探索者

### 12. huggingface/speech-to-speech ⭐ 5,637
- **链接**：https://github.com/huggingface/speech-to-speech
- **简介**：用开源模型构建本地语音 Agent——端到端语音对话
- **语言**：Python
- **本周增星**：+645
- **亮点**：HuggingFace 官方出品的语音 Agent 构建套件，支持 ASR→LLM→TTS 全链路本地部署，无需云端 API。在隐私敏感场景和离线环境下，这套方案是目前最完整的选择。
- **适合人群**：语音应用开发者、智能硬件团队、需要本地语音交互的产品经理

### 13. TencentCloud/CubeSandbox ⭐ 8,712
- **链接**：https://github.com/TencentCloud/CubeSandbox
- **简介**：即时的、并发的、安全的轻量级 AI Agent 沙箱
- **语言**：Rust
- **今日增星**：+664
- **亮点**：腾讯为 AI Agent 执行代码提供安全隔离沙箱，支持毫秒级启动、高并发执行。与 Agent-Memory 形成「记忆+执行」的完整基础设施矩阵，是目前 Agent 安全执行层最成熟的方案之一。Rust 实现保证了零运行时开销的隔离性。
- **适合人群**：Agent 平台开发者、需要安全执行不受信代码的 SaaS 服务、AI DevOps 团队

### 14. diegosouzapw/OmniRoute ⭐ 13,423
- **链接**：https://github.com/diegosouzapw/OmniRoute
- **简介**：免费 AI 网关——一个端点接入 231+ AI 提供商（50+ 免费），连接 Claude Code/Codex/Cursor/Copilot
- **语言**：TypeScript
- **本周增星**：+4,797
- **亮点**：统一 API 网关聚合了 231+ 个 AI 模型提供商，其中 50+ 提供免费额度。开发者无需管理多个 API Key 和端点格式，一次配置即可在不同编码 Agent 之间自由切换模型。当前 Agent 工具链生态中路由层的标杆项目。
- **适合人群**：AI 应用开发者、需要灵活切换模型的团队、成本敏感型个人开发者

## 趋势洞察

**1. AI 安全进入「攻防双极」时代**  
strix（防御修复）和 T3MP3ST（自主攻击）同时上榜，标志着 AI 安全赛道从「单点工具期」进入「攻防体系化」阶段。两者的结合意味着完整的红蓝对抗流程即将被 AI 全自动化。

**2. Agent 基础设施「记忆层」成为新战场**  
腾讯 TencentDB-Agent-Memory 的爆发说明，Agent 的「长期记忆」已经从锦上添花变成刚需。与上周的 cognee 形成竞争态势，各家在记忆架构（分层/向量/图谱）上开始差异化。

**3. 大厂「开放式博弈」常态化**  
OpenAI 为 Claude Code 开发插件、Meta 开源 Agent 设计系统、腾讯/阿里持续输出基础设施——大厂不再执着于「全栈闭环」，而是选择在各自优势层开放并嵌入对手生态。这种「竞合」模式对开发者极为有利。

**4. WiFi 感知计算——潜藏的「下一个风口」**  
RuView 的爆发是个信号：利用现有 WiFi 信号实现无摄像头感知的技术正在走向成熟。结合 AI 的信号处理能力，这可能催生智能家居、健康监测、安防等领域的新一代「无感感知」产品。

**5. 垂直场景 Agent 化加速**  
从求职（ai-job-search）到视频（claude-video）到科研（openscience）到办公（OfficeCLI），AI Agent 正在教条式地渗透每一个垂直场景。「通用 Agent + 领域知识 + 工具链」的公式已经验证，下一个爆点可能在医疗、法律、教育等尚未被充分覆盖的领域。

---

*报告生成时间：2026-07-08 20:08 | 数据来源：GitHub Trending Daily/Weekly & Search API*
