# GitHub 热门项目日报 - 2026-07-07

> 每日精选 GitHub 上最受关注的开源项目，助你紧跟技术前沿。

## 今日概览

今天的 GitHub 热门榜几乎被 **AI Agent 基础设施**和**AI 编码工具**全面占领。从本地会议助手到安全渗透、从提示词工程到视频编辑，开源社区正在围绕"AI 代理能做什么"快速扩张。**Rust** 在本地/隐私型 Agent 基础设施中表现亮眼，而 **JavaScript/TypeScript** 依然是 Skill 经济和插件生态的主力军。大厂（OpenAI、阿里巴巴）与社区项目同台竞技，Agent 生态正从"单点工具"走向"系统级基础设施"。

## 热门项目精选

### 1. meetily ⭐ 19,965
- **链接**：https://github.com/Zackriya-Solutions/meetily
- **简介**：隐私优先的本地 AI 会议助手
- **语言**：Rust
- **今日增星**：+2,494 today
- **亮点**：基于 Rust 构建，支持 4 倍速 Parakeet/Whisper 实时转录、说话人分离和 Ollama 摘要，100% 本地处理无需云端。被誉为 macOS 和 Windows 上排名第一的自托管开源 AI 会议笔记工具。
- **适合人群**：注重隐私的远程团队、需要对会议内容进行本地化处理的用户、Rust 和边缘 AI 开发者

### 2. strix ⭐ 38,240
- **链接**：https://github.com/usestrix/strix
- **简介**：开源 AI 渗透测试工具
- **语言**：Python
- **今日增星**：本周 +10,759
- **亮点**：用于自动发现和修复应用漏洞，将大模型能力引入安全攻防实战。本周增星最高，显示出 AI+安全赛道的强劲热度。
- **适合人群**：安全工程师、DevSecOps 团队、白帽黑客、对 AI 安全攻防感兴趣的开发者

### 3. agent-skills ⭐ 71,448
- **链接**：https://github.com/addyosmani/agent-skills
- **简介**：面向 AI 编码代理的生产级工程技能
- **语言**：JavaScript
- **今日增星**：+1,112 today
- **亮点**：提供可在 Claude Code、Codex 等 Agent 中直接使用的工程技能模板，帮助开发者把 AI 代理真正用于生产级软件开发。
- **适合人群**：使用 AI 编码代理的开发者、希望提升 Agent 输出质量与一致性的工程团队

### 4. caveman ⭐ 85,973
- **链接**：https://github.com/JuliusBrussee/caveman
- **简介**：让 Claude 用"原始人"方式说话以减少 token
- **语言**：JavaScript
- **今日增星**：本周 +7,780
- **亮点**：Claude Code 技能，通过极简语言风格沟通，据说能减少 65% 的 token 消耗。在成本敏感、需要大规模调用 Agent 的场景下极具吸引力。
- **适合人群**：高频使用 Claude API 的开发者、关注 LLM 调用成本的团队、Prompt 工程师

### 5. taste-skill ⭐ 59,659
- **链接**：https://github.com/Leonxlnx/taste-skill
- **简介**：赋予 AI 良好品味，阻止生成低质内容
- **语言**：JavaScript
- **今日增星**：+1,458 today
- **亮点**：一套针对 AI 生成内容的"品味"约束技能，让模型减少无聊、通用、低质量输出。对内容创作型 Agent 非常有价值。
- **适合人群**：内容创作者、AI 写作工具开发者、营销团队、对生成内容质量有高要求的用户

### 6. codebase-memory-mcp ⭐ 27,681
- **链接**：https://github.com/DeusData/codebase-memory-mcp
- **简介**：高性能代码智能 MCP 服务器
- **语言**：C
- **今日增星**：本周 +6,309
- **亮点**：将代码库索引到持久知识图谱，支持 158 种语言、亚毫秒级查询，号称能减少 99% token。是 Agent 记忆层基础设施的重要拼图。
- **适合人群**：构建 AI 编码助手的团队、需要大代码库上下文理解能力的开发者、MCP 生态研究者

### 7. T3MP3ST ⭐ 2,900
- **链接**：https://github.com/elder-plinius/T3MP3ST
- **简介**：自主红队测试平台
- **语言**：TypeScript
- **今日增星**：本周新创建，约 2.9k stars
- **亮点**：多 Agent 攻击安全元框架，将 AI 能力用于红队测试和漏洞挖掘。与 strix 共同反映 AI 安全实战化的趋势。
- **适合人群**：安全研究员、红队工程师、AI 安全爱好者、企业安全团队

### 8. codex-plugin-cc ⭐ 26,488
- **链接**：https://github.com/openai/codex-plugin-cc
- **简介**：在 Claude Code 中调用 Codex
- **语言**：JavaScript
- **今日增星**：+906 today
- **亮点**：OpenAI 官方出品，让开发者可以直接在 Claude Code 里使用 Codex 审查代码或委派任务。代表大厂在 Agent 工具链上的深度博弈。
- **适合人群**：Claude Code 和 Codex 双栖用户、AI 辅助编程早期采用者、追求多模型协同的开发者

### 9. herdr ⭐ 13,159
- **链接**：https://github.com/ogulcancelik/herdr
- **简介**：终端里的 Agent 多路复用器
- **语言**：Rust
- **今日增星**：+779 today
- **亮点**：驻留在终端中的多 Agent 管理器，让多个 AI Agent 可以协同工作。是 Agent 编排层基础设施的有趣探索。
- **适合人群**：终端党、喜欢命令行工作流的开发者、多 Agent 系统研究者

### 10. page-agent ⭐ 24,770
- **链接**：https://github.com/alibaba/page-agent
- **简介**：JavaScript 页面内 GUI Agent
- **语言**：TypeScript
- **今日增星**：本周 +3,989
- **亮点**：阿里巴巴开源，用自然语言控制 Web 界面。代表"面向 Agent 设计"的新范式，让 AI 可以直接操作网页。
- **适合人群**：前端开发者、自动化测试工程师、RPA 开发者、浏览器自动化爱好者

### 11. Firecrawl ⭐ 146,840
- **链接**：https://github.com/firecrawl/firecrawl
- **简介**：大规模搜索、抓取和与网络交互的 API
- **语言**：TypeScript
- **今日增星**：+867 today
- **亮点**：将任意网站转换为 LLM 可用的结构化数据，支持大规模抓取。是 Agent 获取外部知识的事实标准工具之一。
- **适合人群**：构建 RAG/Agent 的开发者、需要网页数据抓取的工程师、知识库构建者

### 12. video-use ⭐ 15,679
- **链接**：https://github.com/browser-use/video-use
- **简介**：用编码 Agent 编辑视频
- **语言**：Python
- **今日增星**：本周 +3,706
- **亮点**：让 AI 编码代理接管视频编辑工作流，将多模态创作能力交给 Agent。代表 AI 在创意生产领域的进一步渗透。
- **适合人群**：视频创作者、多媒体开发者、AI 创作工具研究者、内容生产团队

### 13. claude-skills ⭐ 21,411
- **链接**：https://github.com/alirezarezvani/claude-skills
- **简介**：345 个 Claude Code 技能和插件
- **语言**：Python
- **今日增星**：+610 today
- **亮点**：涵盖工程、营销、产品、研究等多领域的 Claude Code 技能集合，含 30+ 代理和 330+ 技能，适配 Claude Code、Codex、Gemini CLI、Cursor 等 8+ 编码代理。
- **适合人群**：Claude Code 用户、希望快速扩展 Agent 能力的知识工作者、跨职能团队

### 14. OpenScience ⭐ 1,000
- **链接**：https://github.com/synthetic-sciences/openscience
- **简介**：开源 AI 科学研究工作台
- **语言**：TypeScript
- **今日增星**：新创建，约 1k stars
- **亮点**：专为科学研究设计的开源 AI 工作台，尝试将 Agent 能力引入实验设计、文献分析和科研工作流。新兴项目，值得关注。
- **适合人群**：科研人员、学术工作者、科学计算开发者、AI for Science 爱好者

### 15. zvec ⭐ 13,767
- **链接**：https://github.com/alibaba/zvec
- **简介**：轻量级、闪电般快速的进程内向量数据库
- **语言**：C++
- **今日增星**：+382 today
- **亮点**：阿里巴巴开源的进程内向量数据库，主打极低延迟。适合需要本地嵌入向量检索的 AI 应用。
- **适合人群**：AI 应用开发者、需要本地向量检索的工程师、RAG 系统开发者

## 趋势洞察

1. **Agent 基础设施三层架构成型**：记忆层（codebase-memory-mcp）、编排层（herdr）、工具层（page-agent / video-use）协同发力，说明社区已经从"做一个 Agent"转向"做一个 Agent 能用的世界"。

2. **AI 安全双赛道并行**：strix（防御/漏洞发现）与 T3MP3ST（红队/攻击测试）同时火热，反映企业对 AI 驱动的安全能力需求快速升温。

3. **Skill 经济持续繁荣**：agent-skills、taste-skill、caveman 等"技能"型项目大量上榜，表明开发者正在把最佳实践封装为可复用的 Agent 能力单元，Prompt/Skill 工程正在成为新的生产力杠杆。

4. **大厂开源常态化**：OpenAI（codex-plugin-cc）、阿里巴巴（page-agent、zvec）等持续贡献核心基础设施，开源已成为 Agent 生态竞争的主战场。

5. **本地与隐私回归**：meetily 强调 100% 本地处理，加上 herdr、zvec 等本地优先项目，反映出后云端时代用户对数据主权和延迟敏感的重新重视。

---

*数据来源：GitHub Trending（Daily / Weekly）及 GitHub 搜索 `created:>2026-06-30`，整理时间：2026-07-07 18:25 GMT+8*
