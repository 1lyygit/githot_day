# GitHub 热门项目日报 - 2026-07-06

> 每日精选 GitHub 上最受关注的开源项目，助你紧跟技术前沿。

## 今日概览

今日 GitHub 热门榜单呈现出 **AI Agent 生态全面深化** 的态势——从安全攻防（strix/T3MP3ST）、Agent 编排（herdr/orca）、代码智能（codebase-memory-mcp/codex-plugin-cc）、多媒体创作（OpenMontage/video-use）到投资研究（ai-berkshire），AI Agent 已经渗透到几乎每一个垂直领域。Meta 的开源设计系统 **Astryx** 正式提出"面向 Agent 设计"的新范式，标志着 Agent 交互从"命令行对话"走向"结构化 UI"。另一大趋势是 **本地化回归**——meetily 的 100% 本地 AI 会议助手、local-llm 的本地 LLM 终极指南，都反映了社区对隐私与离线能力的高度关注。

## 热门项目精选

### 1. usestrix/strix ⭐ 37,590
- **链接**：https://github.com/usestrix/strix
- **简介**：开源的 AI 渗透测试工具，自动发现并修复应用安全漏洞
- **语言**：Python
- **今日增星**：+1,114（本周 +10,338）
- **亮点**：Strix 用 AI 替代传统渗透测试工具，能自动化扫描 Web 应用漏洞、生成修复建议，支持 CI/CD 集成。本周以破万增速强势登顶，成为 AI 安全赛道的新标杆。它不仅是安全工程师的利器，更让普通开发者也能在发版前做自动化安全检查。
- **适合人群**：安全工程师、DevSecOps 团队、对应用安全感兴趣的全栈开发者

### 2. elder-plinius/T3MP3ST ⭐ 2,100
- **链接**：https://github.com/elder-plinius/T3MP3ST
- **简介**：自主化红队攻击平台，多 Agent 协同的安全测试元框架
- **语言**：TypeScript
- **今日增星**：新创建（仅约 3 天，已 +2,100）
- **亮点**：T3MP3ST 是本周最亮眼的新项目——一个多 Agent 协同的进攻性安全测试平台。不同于 strix 的防御视角，T3MP3ST 从攻击方出发，用多智能体模拟真实攻击链。创建仅 3 天即破 2,000 星，AI+安全赛道正在裂变出攻防双极。
- **适合人群**：红队安全研究员、渗透测试工程师、安全自动化团队

### 3. facebook/astryx ⭐ 6,202
- **链接**：https://github.com/facebook/astryx
- **简介**：Meta 开源的面向 Agent 的设计系统，可完全自定义
- **语言**：TypeScript
- **今日增星**：+522
- **亮点**：Meta 亲自下场，将内部沉淀的 Agent UI 组件库开源。Astryx 不是传统设计系统——它专为 AI Agent 交互场景而生：流式输出展示、工具调用可视化、多轮对话管理。这标志着"面向 Agent 设计（Design for Agent）"从社区探索升级为大厂标准。
- **适合人群**：前端开发者、AI 产品设计师、构建 Agent 交互界面的团队

### 4. ogulcancelik/herdr ⭐ 12,419
- **链接**：https://github.com/ogulcancelik/herdr
- **简介**：终端里的 Agent 多路复用器，一个窗口管理多个 AI Agent
- **语言**：Rust
- **今日增星**：+651（本周 +3,937）
- **亮点**：herdr 把 tmux 的多窗口哲学引入 AI Agent——你可以在一个终端里同时与 Claude Code、Codex、Gemini 等多个 Agent 交互，无缝切换上下文。Rust 实现保证了极致性能，Agent 编排赛道正从"选一个 Agent"走向"同时用多个 Agent"。
- **适合人群**：日常使用多个 AI 编码助手的开发者、追求终端效率的极客

### 5. browser-use/video-use ⭐ 15,248
- **链接**：https://github.com/browser-use/video-use
- **简介**：用编程 Agent 编辑视频——让 AI 帮你剪片
- **语言**：Python
- **今日增星**：本周 +4,288
- **亮点**：video-use 是 browser-use 团队的新作品，把 Agent 的能力从浏览器扩展到了视频编辑。你只需用自然语言描述想要的剪辑效果，Agent 会调用 FFmpeg 等工具执行。不需要学习 Premiere 或 DaVinci Resolve，开发者也能快速产出高质量视频。
- **适合人群**：内容创作者、需要批量处理视频的运营团队、想做 AI 视频自动化的开发者

### 6. DeusData/codebase-memory-mcp ⭐ 27,047
- **链接**：https://github.com/DeusData/codebase-memory-mcp
- **简介**：高性能代码智能 MCP 服务器，将代码库索引为持久化知识图谱
- **语言**：C
- **今日增星**：本周 +7,945
- **亮点**：这个项目解决了 AI Agent 最大的痛点——代码上下文丢失。它用纯 C 实现（单静态二进制、零依赖），支持 158 种语言，能在毫秒级完成索引构建和查询。作为 MCP 服务器，它让 Claude Code / Codex 等 Agent 获得"代码库长期记忆"，token 消耗减少 99%。本周增星近 8,000，是 Agent 基础设施层的现象级项目。
- **适合人群**：使用 AI 编码助手的大型代码库维护者、关注 Agent 上下文管理的平台团队

### 7. calesthio/OpenMontage ⭐ 33,987
- **链接**：https://github.com/calesthio/OpenMontage
- **简介**：全球首个开源的 Agent 驱动视频制作系统
- **语言**：Python
- **今日增星**：本周 +7,353
- **亮点**：OpenMontage 拥有 12 条制作管线、52 个工具、500+ Agent 技能，能把你的 AI 编码助手直接变成一套完整的视频工作室。从脚本撰写、素材搜索、剪辑合成到字幕生成，全流程 Agent 驱动。连续多周稳居趋势榜前列，是 AI × 多媒体创作融合的标杆项目。
- **适合人群**：视频内容创作者、需要自动化视频生产的营销团队、AI 多媒体创业者

### 8. Zackriya-Solutions/meetily ⭐ 18,104
- **链接**：https://github.com/Zackriya-Solutions/meetily
- **简介**：隐私优先的本地 AI 会议助手，100% 本地处理，无需云端
- **语言**：Rust
- **今日增星**：+1,409（今日第二）
- **亮点**：Meetily 解决了企业级 AI 会议记录的核心痛点——数据隐私。基于 Rust 构建，使用 Parakeet/Whisper 实现 4 倍速实时转录，支持说话人分离和 Ollama 本地摘要。完全离线运行，所有数据处理都在本地完成。macOS 和 Windows 双平台支持，是 Zoom AI Companion 的开源替代。
- **适合人群**：对数据隐私敏感的企业用户、远程团队管理者、需要会议记录的开发者

### 9. diegosouzapw/OmniRoute ⭐ 12,188
- **链接**：https://github.com/diegosouzapw/OmniRoute
- **简介**：免费 AI 网关——一个端点连接 231+ 提供商（含 50+ 免费）
- **语言**：TypeScript
- **今日增星**：本周 +4,411
- **亮点**：OmniRoute 是 AI API 的"万能路由器"——统一端点连接 Claude、GPT、Gemini 等 231+ 提供商。内置 RTK+Caveman 堆叠压缩可节省 15-95% token 消耗，支持智能自动故障转移、MCP/A2A 协议和多模态 API。对于不想被单一 AI 厂商锁定的团队，这是性价比最优的网关选择。
- **适合人群**：需要多模型接入的 AI 应用开发者、关注成本优化的团队、Agent 平台构建者

### 10. HUANGCHIHHUNGLeo/claude-real-video ⭐ 1,100
- **链接**：https://github.com/HUANGCHIHHUNGLeo/claude-real-video
- **简介**：让 Claude（或任何 LLM）真正"看懂"视频
- **语言**：Python
- **今日增星**：新创建（约 3 天，已 +1,100）
- **亮点**：这个项目的创意非常棒——它通过场景感知帧去重 + 转录文本，让 LLM 能真正理解视频内容，而不只是读视频标题。支持 URL 和本地文件，完全本地运行，MIT 协议。解决了 LLM 只能"读图"不能"看视频"的根本局限，是多模态 Agent 的重要基础设施。
- **适合人群**：多模态 AI 应用开发者、需要视频内容分析的团队、AI 研究员

### 11. jamesob/local-llm ⭐ 975
- **链接**：https://github.com/jamesob/local-llm
- **简介**：本地运行大语言模型的终极指南——一切你需要知道的
- **语言**：Shell
- **今日增星**：新创建（约 4 天，已 +975）
- **亮点**：这不是一个工具，而是一部"本地 LLM 百科全书"。从硬件选择、模型下载、推理框架对比到性能调优，jamesob 将自己多年本地运行 LLM 的经验系统整理成文档。在当前 AI 隐私焦虑背景下，这份指南成为开发者转向本地方案的"圣经"级资料。
- **适合人群**：想在本地运行 LLM 的开发者、关注 AI 隐私的技术决策者、AI 基础设施学习者

### 12. xbtlin/ai-berkshire ⭐ 10,836
- **链接**：https://github.com/xbtlin/ai-berkshire
- **简介**：AI 时代的伯克希尔——基于多 Agent 的价值投资研究框架
- **语言**：Python
- **今日增星**：本周 +5,038
- **亮点**：这个项目将巴菲特、芒格、段永平、李录四位投资大师的方法论编码为多 Agent 协作框架。通过对抗式 Agent 研究（一个 Agent 做多、一个做空、一个风险审计），让 AI 模拟机构级投资决策流程。中文友好的设计与金融垂直场景的深度结合，让它在华人开发者圈中快速传播。
- **适合人群**：量化投资者、金融科技开发者、对 AI+投资感兴趣的研究者

### 13. stablyai/orca ⭐ 12,612
- **链接**：https://github.com/stablyai/orca
- **简介**：并行 Agent 舰队管理——用你的订阅跑任意编码 Agent
- **语言**：TypeScript
- **今日增星**：本周 +3,783
- **亮点**：Orca 是 Agent 应用的"舰队指挥官"——它让你并行运行多个 AI 编码 Agent，各自使用你自己的 API 订阅，支持桌面端和移动端。在 herdr 提供多路复用的同时，Orca 提供并行编排，两者共同构成了"Agent 操作系统"的用户态基础设施。
- **适合人群**：需要同时管理多个 AI 任务的开发者、Agent 重度用户、团队效率工具探索者

### 14. openai/codex-plugin-cc ⭐ 25,927
- **链接**：https://github.com/openai/codex-plugin-cc
- **简介**：在 Claude Code 中使用 OpenAI Codex——代码审查和任务委托
- **语言**：JavaScript
- **今日增星**：+1,532（今日第一）
- **亮点**：OpenAI 官方出品的 Claude Code 插件，让 OpenAI Codex 和 Claude Code 双剑合璧——用 Codex 的推理能力做代码审查，用 Claude Code 的终端能力做执行。这个项目证明了即使是大厂，也不再试图用单一模型吞噬一切，而是拥抱 Agent 间的协作生态。
- **适合人群**：Claude Code 用户想引入 Codex 能力、需要跨模型代码审查的团队

### 15. topoteretes/cognee ⭐ 27,196
- **链接**：https://github.com/topoteretes/cognee
- **简介**：开源 AI Agent 记忆平台——给 Agent 装上持久化的长期记忆
- **语言**：Python
- **今日增星**：本周 +2,699
- **亮点**：Cognee 是 Agent 基础设施层的关键拼图——自托管的图数据库引擎，让 Agent 在多次对话间保持上下文连续性。与 codebase-memory-mcp 侧重"代码结构记忆"不同，cognee 提供通用的 Agent 记忆方案，支持知识图谱、语义搜索和记忆管理。为 Agent 的"人格连续性"打下基础。
- **适合人群**：构建 AI Agent 产品的团队、需要会话持久化的聊天机器人开发者、Agent 平台架构师

## 趋势洞察

1. **Agent 基础设施三层架构成型**：本周榜单清晰地呈现出 Agent 生态的三个层级——**路由层**（herdr/orca/OmniRoute 解决"怎么连"）、**记忆层**（cognee/codebase-memory-mcp 解决"记住啥"）和**安全层**（strix/T3MP3ST 解决"安全吗"）。这标志着 Agent 从"玩具"走向"生产就绪"。

2. **"面向 Agent 设计"成为新范式**：Meta 的 Astryx 正式将 Agent UI 组件化、标准化，终结了每个 Agent 应用都要从零开始搭界面的时代。预计将带动一波 Agent 前端框架的井喷。

3. **AI+安全赛道裂变**：Strix（防御侧）和 T3MP3ST（攻击侧）同日上榜，形成攻防双极。随着 Agent 越来越多地接入企业系统，安全自动化从"锦上添花"变为"必选项"。

4. **本地化与隐私优先回归**：meetily（本地会议）、local-llm（本地 LLM 指南）的走红说明在 AI 能力爆发的背景下，用户对数据主权和离线能力的需求不降反升。

5. **垂直场景 Agent 化加速**：从视频制作（OpenMontage/video-use）到投资研究（ai-berkshire）再到网站克隆（ai-website-cloner-template），Agent 正在系统性地替代传统的垂直软件工作流。

6. **大厂生态博弈进入深水区**：OpenAI 为 Claude Code 开发插件、Meta 开源 Agent UI 标准，大厂不再固守自家生态，而是通过"插件渗透"争夺开发者心智——谁的 Agent 生态更开放，谁就赢得下一波增长。
