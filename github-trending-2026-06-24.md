# GitHub 热门项目日报 - 2026-06-24

> 每日精选 GitHub 上最受关注的开源项目，助你紧跟技术前沿。

## 今日概览

今天是 2026 年 6 月 24 日，GitHub Trending 几乎被 **AI 智能体（Agent）生态** 全面占领：从字节跳动的 `deer-flow` 长周期 SuperAgent，到 Anthropic 官方的 `claude-plugins-official` 插件目录，再到 `codebase-memory-mcp`、`gstack`、`Agent-Reach` 等垂直工具，开发者正在围绕 Claude Code、Codex、Cursor 构建一个"技能 + 工具 + 记忆"的完整智能体工具链。与此同时，**AI 视频/语音创作工具**（OpenMontage、Palmier、Voicebox）和 **大厂官方项目**（Google TimesFM、NVIDIA SkillSpector、Cloudflare security-audit-skill）持续霸榜，显示基础模型 + 行业落地 + 安全审查的三角格局正在快速形成。

---

## 热门项目精选

### 1. calesthio/OpenMontage ⭐ 17.4k
- **链接**：https://github.com/calesthio/OpenMontage
- **简介**：全球首个开源的智能体视频制作系统
- **语言**：Python
- **今日增星**：+3,592 ⬆️(今日第一)
- **亮点**：内置 12 条流水线、52 个工具、500+ 智能体技能，可将 Claude Code、Cursor 等 AI 编程助手直接改造为完整的视频生产工作流，覆盖脚本、分镜、剪辑、特效全流程。
- **适合人群**：短视频创作者、AI 视频自动化团队、需要批量生成营销视频的运营人员。

### 2. DeusData/codebase-memory-mcp ⭐ 13.7k
- **链接**：https://github.com/DeusData/codebase-memory-mcp
- **简介**：高性能代码智能 MCP 服务器，把代码库索引成知识图谱
- **语言**：C
- **今日增星**：+1,300 / 本周 +8,536
- **亮点**：单文件静态二进制，零依赖，毫秒级完成代码库索引，支持 158 种语言，亚毫秒级查询，可减少 99% 的 LLM token 消耗，让 AI 编码助手"读懂"大型项目。
- **适合人群**：重度使用 Claude Code / Cursor / Copilot 的全栈工程师，需要在不泄漏代码的前提下让 AI 理解大型私有仓库的团队。

### 3. garrytan/gstack ⭐ 114.6k
- **链接**：https://github.com/garrytan/gstack
- **简介**：YC 总裁 Garry Tan 的 Claude Code 完整工作流配置
- **语言**：TypeScript
- **今日增星**：+1,011
- **亮点**：包含 23 个具备"角色"的工具（CEO、设计师、工程经理、发布经理、文档工程师、QA），把 Claude Code 打造成一支虚拟产品团队，是学习"AI 团队协作"的标杆项目。
- **适合人群**：独立开发者、初创公司创始人、希望用 AI 模拟完整产研流程的工程师。

### 4. jamiepine/voicebox ⭐ 33.6k
- **链接**：https://github.com/jamiepine/voicebox
- **简介**：开源 AI 语音工作室
- **语言**：TypeScript
- **今日增星**：+1,045
- **亮点**：集成了语音克隆、听写、AI 配音创作能力，可作为 ElevenLabs 的开源替代方案，支持本地部署，避免语音数据上传到云端。
- **适合人群**：播客主、有声内容创作者、需要定制 AI 配音的企业开发团队。

### 5. mukul975/Anthropic-Cybersecurity-Skills ⭐ 20.2k
- **链接**：https://github.com/mukul975/Anthropic-Cybersecurity-Skills
- **简介**：817 个结构化网络安全技能集合
- **语言**：Python
- **今日增星**：+1,041
- **亮点**：映射到 MITRE ATT&CK、NIST CSF 2.0、MITRE ATLAS、D3FEND 等 6 大安全框架，覆盖 29 个安全领域，兼容 Claude Code、Copilot、Cursor 等 20+ AI 平台。
- **适合人群**：安全工程师、渗透测试团队、需要在 AI 助手中嵌入安全审查能力的企业。

### 6. palmier-io/palmier-pro ⭐ 8.7k
- **链接**：https://github.com/palmier-io/palmier-pro
- **简介**：专为 AI 时代打造的 macOS 视频编辑器
- **语言**：Swift
- **今日增星**：+1,630
- **亮点**：原生 Swift 性能，深度集成大模型能力（脚本生成、智能剪辑、口播同步），主打"AI 优先"的桌面级剪辑体验，定位为 Final Cut + CapCut 的 AI 替代品。
- **适合人群**：macOS 视频创作者、追求原生性能的设计与剪辑从业者。

### 7. bytedance/deer-flow ⭐ 74.3k
- **链接**：https://github.com/bytedance/deer-flow
- **简介**：字节跳动开源的长周期 SuperAgent 框架
- **语言**：Python
- **今日增星**：+739
- **亮点**：通过沙箱、记忆、工具、技能、子智能体和消息网关的组合，可处理从分钟级到小时级的复杂任务，覆盖研究、编码、创作三大场景，是国内大厂对 Agent 框架的最新答卷。
- **适合人群**：研究型开发者、需要 AI 完成多步深度任务的工程师、AI 应用架构师。

### 8. JCodesMore/ai-website-cloner-template ⭐ 18.9k
- **链接**：https://github.com/JCodesMore/ai-website-cloner-template
- **简介**：用一条命令让 AI 智能体克隆任意网站
- **语言**：TypeScript
- **今日增星**：+826
- **亮点**：把"截图 + 视觉理解 + 代码生成 + 资源抓取"流水线封装成单一 CLI 指令，让 Claude Code / Codex 等 Agent 复刻任意目标站点，是学习多模态 Agent 编排的绝佳模板。
- **适合人群**：前端工程师、想学习 Agent 工程化的开发者、需要快速搭原型的产品经理。

### 9. koala73/worldmonitor ⭐ 59.4k
- **链接**：https://github.com/koala73/worldmonitor
- **简介**：实时全球情报仪表板
- **语言**：TypeScript
- **今日增星**：+294 / 本周 +2,309
- **亮点**：整合 AI 驱动的新闻聚合、地缘政治监测、关键基础设施追踪，提供统一态势感知界面，可自定义数据源与告警规则。
- **适合人群**：行业研究员、新闻机构、关注全球风险的投资与运营人员。

### 10. shanraisshan/claude-code-best-practice ⭐ 59.9k
- **链接**：https://github.com/shanraisshan/claude-code-best-practice
- **简介**：从 Vibe Coding 到 Agentic Engineering 的最佳实践
- **语言**：HTML
- **今日增星**：+344
- **亮点**：以可视化的方式梳理 Claude Code 的进阶使用技巧，覆盖提示工程、上下文管理、子任务拆分、技能复用等核心议题，是中文圈学习 Claude Code 的高人气教程。
- **适合人群**：Claude Code 新手到中级用户、希望规范化使用 AI 编程助手的团队。

### 11. NousResearch/hermes-agent ⭐ 201.5k
- **链接**：https://github.com/NousResearch/hermes-agent
- **简介**：与你共同成长的智能体
- **语言**：Python
- **今日增星**：+936
- **亮点**：NousResearch 出品的开源 Agent 框架，强调长期记忆、持续学习和个性化适配，定位于"会进化的 AI 助手"，在所有 trending 项目中总 Star 数最高之一。
- **适合人群**：Agent 框架研究者、想打造长期记忆 AI 应用的开发者。

### 12. bytedance/deer-flow ⭐ 74.3k *(本周补强)*
- **链接**：https://github.com/bytedance/deer-flow
- **简介**：字节跳动开源的长周期 SuperAgent
- **语言**：Python
- **亮点**：参见第 7 项；本周持续维持高增长，是国内大厂 Agent 框架的代表项目。

### 13. mattpocock/skills ⭐ 144.1k
- **链接**：https://github.com/mattpocock/skills
- **简介**：TypeScript 名师 Matt Pocock 的工程师技能集
- **语言**：Shell
- **本周增星**：+11,784 ⬆️(本周第一)
- **亮点**：直接来自 Matt Pocock 自己的 `.claude` 配置目录，包含大量面向真实工程场景的 Claude Code 技能，被视为"生产级工程师技能模板"标杆。
- **适合人群**：TypeScript 工程师、Claude Code 用户、希望借鉴顶级工程师工作流的开发者。

### 14. Panniantong/Agent-Reach ⭐ 39.2k
- **链接**：https://github.com/Panniantong/Agent-Reach
- **简介**：让 AI Agent 拥有"看见"整个互联网的能力
- **语言**：Python
- **本周增星**：+6,915
- **亮点**：单一 CLI 工具即可让 Agent 读取并搜索 Twitter、Reddit、YouTube、GitHub、B 站、小红书等平台，**完全零 API 费用**，是降低 Agent 数据采集成本的关键工具。
- **适合人群**：AI Agent 开发者、需要低成本抓取社交平台数据的团队。

### 15. NVIDIA/SkillSpector ⭐ 10.1k
- **链接**：https://github.com/NVIDIA/SkillSpector
- **简介**：AI 智能体技能安全扫描器
- **语言**：Python
- **本周增星**：+2,849
- **亮点**：由 NVIDIA 出品，专门检测 AI Agent 技能中的漏洞、恶意模式与安全风险，是 Agent 生态走向成熟期"安全基建"的代表性项目。
- **适合人群**：Agent 平台运营、企业安全团队、关注 AI 供应链安全的开发者。

### 16. addyosmani/agent-skills ⭐ 66.2k
- **链接**：https://github.com/addyosmani/agent-skills
- **简介**：Google 工程师 Addy Osmani 出品的生产级 AI 编码技能
- **语言**：Shell
- **本周增星**：+5,073
- **亮点**：聚焦"生产级"工程实践，覆盖代码审查、性能优化、测试与发布等真实工作流，是大厂视角下 AI 编码智能体技能的最佳示范。
- **适合人群**：资深工程师、技术 Lead、追求工程严谨性的 AI 编程助手用户。

### 17. baidu/Unlimited-OCR ⭐ 5.1k 🆕
- **链接**：https://github.com/baidu/Unlimited-OCR
- **简介**：百度开源的"一次性长跨度解析"OCR 系统
- **语言**：Python
- **亮点**：本周新晋热门项目，专为超长文档、复杂版式设计，号称"一次性解析整个文档"，是中文 OCR 领域少有的面向长文本场景的开源方案。
- **适合人群**：文档数字化团队、法律/金融/医疗等长文档处理场景的开发者。

### 18. cloudflare/security-audit-skill 🆕
- **链接**：https://github.com/cloudflare/security-audit-skill
- **简介**：Cloudflare 开源的"多阶段安全审计"编码 Agent 技能
- **语言**：JavaScript
- **亮点**：以独立可验证、机器可读的方式输出审计结果，可直接集成到 AI 编程助手中，是大厂"AI 安全工程"实践的代表。
- **适合人群**：安全工程团队、DevSecOps 从业者、AI 编程工具链开发者。

### 19. sums001/Windows-Copilot-API 🆕
- **链接**：https://github.com/sums001/Windows-Copilot-API
- **简介**：将 Windows Copilot 逆向为 OpenAI 兼容 API
- **语言**：Python
- **亮点**：在没有 Azure 账户的前提下，通过本地 REST 接口调用 GPT-4 / GPT-5 模型，对个人开发者与本地化部署非常友好。
- **适合人群**：Windows 平台独立开发者、想在本地跑 GPT 模型的极客。

---

## 趋势洞察

1. **AI 智能体（Agent）生态进入"全栈化"阶段**：从字节 `deer-flow`、YC 总裁 `gstack`、Anthropic 官方 `claude-plugins-official`，到 `codebase-memory-mcp`、`Agent-Reach` 等垂直工具，"技能 + 工具 + 记忆 + 安全"四件套基本成型，Agent 已从"对话玩具"演变为"工程化平台"。

2. **大厂"亲自下场"成为新的流量密码**：Google（TimesFM）、NVIDIA（SkillSpector）、字节（deer-flow）、Cloudflare（security-audit-skill）、百度（Unlimited-OCR）本周齐刷刷登榜，说明基础模型 + 行业落地 + 安全的三角格局正在快速形成，巨头把开源当作"标准制定权"来打。

3. **AI 创作工具继续分化**：视频方向出现 `OpenMontage`（智能体管线）、`palmier-pro`（原生 macOS）、`OpenCut`（剪映替代）三足鼎立；语音方向 `voicebox` 持续走高；图片/网站方向则有 `ai-website-cloner-template`。创作者工具的"开源 + AI 重构"窗口期仍在。

4. **"技能（Skill）经济"开始崛起**：`claude-plugins-official`、`Anthropic-Cybersecurity-Skills`、`agent-skills`、`mattpocock/skills`、`cloudflare/security-audit-skill` 等项目密集出现，预示着 Agent 时代的"应用商店"正在形成，谁先积累高质量技能库，谁就掌握入口。

5. **基础设施层（性能 + 内存 + 网络）重新被关注**：`codebase-memory-mcp`（C 写的毫秒级索引）、`iroh`（Rust 写的 P2P 网络栈）提醒我们：当 AI 智能体规模扩大，对底层性能与去中心化网络的需求正在回归。
