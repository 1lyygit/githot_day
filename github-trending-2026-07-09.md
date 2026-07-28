# GitHub 热门项目日报 - 2026-07-09

> 每日精选 GitHub 上最受关注的开源项目，助你紧跟技术前沿。

## 今日概览

今天 GitHub 热门榜呈现三大亮点：一是 **AI Agent 垂直场景加速落地**——从求职（ai-job-search 日增 5k+）、视频理解（claude-video）、办公自动化（OfficeCLI 日增 1.7k+）到科研工作台（openscience），Agent 正从"通用助手"转向"垂直专才"；二是 **大厂基础设施开源继续加码**——腾讯同时推出 Agent 记忆层（TencentDB-Agent-Memory）和安全沙箱（CubeSandbox），阿里开源轻量向量库 zvec，构建 Agent 全栈底座；三是 **WiFi 感知计算异军突起**——RuView 用 WiFi 信号实现无摄像头空间感知，79k stars 说明开发者对"非视觉 AI"兴趣浓厚。

## 热门项目精选

### 1. iOfficeAI/OfficeCLI ⭐ 12,764
- **链接**：https://github.com/iOfficeAI/OfficeCLI
- **简介**：专为 AI Agent 打造的 Office 套件——读写编辑 Word/Excel/PPT，无需安装 Office
- **语言**：C#
- **今日增星**：+1,717
- **亮点**：首个面向 AI Agent 而非人类用户的 Office 工具，单二进制文件、免费开源、零 Office 安装依赖。Agent 可直接调用 API 操作文档，是"Agent 吃饭"的基础设施——如果 Agent 要处理真实世界文档，这是刚需。
- **适合人群**：构建文档自动化流程的 AI Agent 开发者、RPA/办公自动化团队

### 2. MadsLorentzen/ai-job-search ⭐ 16,761
- **链接**：https://github.com/MadsLorentzen/ai-job-search
- **简介**：基于 Claude Code 的 AI 驱动求职框架——自动评估岗位、定制简历、撰写求职信、准备面试
- **语言**：TypeScript
- **今日增星**：+5,079（本周 +9,677）
- **亮点**：不是普通求职网站，而是让 Claude Code 成为你的"求职 Agent"。Fork 后填入个人资料，Agent 全程代劳——从筛选匹配岗位到生成针对性简历和求职信，堪称"AI 求职管家"。日增 5k stars 说明求职焦虑与 AI 赋能的碰撞引爆了关注。
- **适合人群**：求职者、Claude Code 用户、对 Agent 垂直场景感兴趣的开发者

### 3. bradautomates/claude-video ⭐ 6,361
- **链接**：https://github.com/bradautomates/claude-video
- **简介**：让 Claude 能"看"视频——下载、提取帧、转录后交给 Claude 分析
- **语言**：Python
- **今日增星**：+951
- **亮点**：一条 `/watch` 命令，Claude 就能理解视频内容——自动下载视频、提取关键帧、音频转录为文字，然后让 Claude 基于帧+文字做综合分析。把视频这个"Agent 黑箱"变成了可处理的文本+图片组合。
- **适合人群**：需要视频内容分析的 Claude Code 用户、多模态 AI 应用开发者

### 4. TencentCloud/CubeSandbox ⭐ 9,186
- **链接**：https://github.com/TencentCloud/CubeSandbox
- **简介**：面向 AI Agent 的即时、并发、安全、轻量沙箱
- **语言**：Rust
- **今日增星**：+564（本周 +2,106）
- **亮点**：腾讯开源的 Agent 安全隔离方案——用 Rust 构建轻量沙箱，让 AI Agent 在受控环境中执行代码，不污染宿主系统。随着 Agent 越来越多地"动手操作"，安全隔离从可选变成必选，CubeSandbox 正好填补这个空白。
- **适合人群**：AI Agent 平台开发者、关注 Agent 安全执行的 DevOps 工程师

### 5. TencentCloud/TencentDB-Agent-Memory ⭐ 7,933
- **链接**：https://github.com/TencentCloud/TencentDB-Agent-Memory
- **简介**：为 AI Agent 提供全本地长期记忆的四层渐进式管线，零外部 API 依赖
- **语言**：TypeScript
- **今日增星**：+318
- **亮点**：Agent 的"记忆力"一直是痛点——会话结束就失忆。腾讯用四层渐进管线（短期→中期→长期→归档）解决 Agent 长期记忆问题，全部本地运行，不依赖任何外部 API。Agent 生态从"技能层"向"记忆层"纵深发展的重要一步。
- **适合人群**：构建长期运行 AI Agent 的开发者、对话系统工程师

### 6. ruvnet/RuView ⭐ 79,476
- **链接**：https://github.com/ruvnet/RuView
- **简介**：将普通 WiFi 信号转化为实时空间智能、体征监测和存在感知——无需任何摄像头
- **语言**：Rust
- **今日增星**：+799
- **亮点**：不用摄像头就能"看见"房间里有人、在做什么、甚至监测心率呼吸。利用 WiFi 信号扰动进行空间感知，是"非视觉 AI"的代表性项目。79k stars 说明开发者对隐私友好、无侵入的感知方案需求巨大。
- **适合人群**：智能家居/IoT 开发者、隐私感知技术研究者、嵌入式工程师

### 7. alibaba/zvec ⭐ 14,590
- **链接**：https://github.com/alibaba/zvec
- **简介**：轻量、极速的进程内向量数据库
- **语言**：C++
- **今日增星**：+395
- **亮点**：阿里开源的嵌入式向量数据库——不走网络调用，直接在进程内运行，延迟极低。适合 AI Agent 本地检索、RAG 场景中小规模向量搜索。跟 Pinecone/Milvus 等重型方案比，zvec 是"能用就行"的极简选择。
- **适合人群**：需要轻量向量检索的 AI 应用开发者、嵌入式 RAG 构建者

### 8. asgeirtj/system_prompts_leaks ⭐ 54,632
- **链接**：https://github.com/asgeirtj/system_prompts_leaks
- **简介**：各大 AI 产品的系统提示词泄露合集——Claude、GPT、Gemini、Grok、Cursor、Copilot 等
- **语言**：JavaScript
- **今日增星**：+1,218（本周 +6,182）
- **亮点**：持续更新的"AI 提示词考古"项目——收录了 Anthropic (Claude Fable 5/Opus 4.8/Claude Code)、OpenAI (ChatGPT 5.5/Codex)、Google (Gemini 3.5)、xAI (Grok)、Cursor、Copilot 等的完整系统提示词。对研究 AI 行为、理解模型边界、优化自己的提示词都有极高参考价值。
- **适合人群**：提示词工程师、AI 安全研究者、对 AI 产品内部逻辑好奇的开发者

### 9. obra/superpowers ⭐ 250,381
- **链接**：https://github.com/obra/superpowers
- **简介**：Agent 技能框架与软件开发方法论——让 AI Agent 系统化地完成复杂工程任务
- **语言**：Shell
- **今日增星**：+1,116
- **亮点**：250k stars 的"技能方法论"巨无霸——不只是技能集合，而是完整的 Agent 开发方法论：如何规划、如何拆解任务、如何验证、如何协作。定义了"Agent 怎么工作"而非"Agent 能做什么"。
- **适合人群**：所有使用 AI 编码 Agent 的开发者、团队负责人

### 10. addyosmani/agent-skills ⭐ 75,270
- **链接**：https://github.com/addyosmani/agent-skills
- **简介**：面向 AI 编码 Agent 的生产级工程技能集
- **语言**：JavaScript
- **今日增星**：+1,297
- **亮点**：Google 工程师 Addy Osmani 精选的 Agent 工程技能——涵盖代码审查、性能优化、安全扫描、调试、重构等真实工程场景。不是玩具 demo，而是可直接用于生产环境的专业技能库。
- **适合人群**：使用 Claude Code / Codex / Cursor 等 Agent 的前端/全栈工程师

### 11. Diolinux/PhotoGIMP ⭐ 15,253
- **链接**：https://github.com/Diolinux/PhotoGIMP
- **简介**：让 GIMP 3+ 变成 Photoshop 体验的补丁——快捷键、界面、工具栏全面适配
- **语言**：CSS
- **今日增星**：+1,125
- **亮点**：不是新项目，但今天突然爆发 +1.1k。GIMP 3 发布后 Photoshop 用户迁移需求激增，PhotoGIMP 把 GIMP 的快捷键、布局、工具名全部改成 Photoshop 习惯，降低迁移门槛。开源替代商业软件的"体验桥接"思路值得关注。
- **适合人群**：从 Photoshop 迁移到 GIMP 的设计师、Linux 桌面用户

### 12. huxingyi/autoremesher ⭐ 2,171
- **链接**：https://github.com/huxingyi/autoremesher
- **简介**：自动四边形重网格化工具——将任意 3D 模型转为高质量四边形网格
- **语言**：C++
- **今日增星**：+296
- **亮点**：小众但精准的 3D 工具——自动把三角网格转为四边形网格（对动画、仿真、CAD 都很关键）。独立 C++ 工具，不依赖大型库，体积小速度快。3D/游戏/工业设计领域少见的实用开源工具。
- **适合人群**：3D 动画师、游戏开发者、CAD/CAE 工程师

### 13. mvanhorn/last30days-skill ⭐ 51,073
- **链接**：https://github.com/mvanhorn/last30days-skill
- **简介**：AI Agent 技能——自动跨 Reddit/X/YouTube/HN/Polymarket/Web 研究任意话题并综合摘要
- **语言**：Python
- **今日增星**：+352
- **亮点**：给 Agent 装上"研究员"能力——一条命令就能跨 6 个信息源做深度调研，综合输出有据可查的摘要。不是简单搜索，而是结构化研究：多源交叉验证、去噪、综合。对需要快速了解某个领域动态的人特别实用。
- **适合人群**：需要快速调研的研究者、投资分析师、内容创作者

### 14. Zackriya-Solutions/meetily ⭐ 21,905
- **链接**：https://github.com/Zackriya-Solutions/meetily
- **简介**：隐私优先的本地 AI 会议助手——Rust 构建，4x 速实时转录+说话人分离+Ollama 摘要
- **语言**：Rust
- **本周增星**：+8,366
- **亮点**：100% 本地处理的会议纪要方案——用 Rust + Parakeet/Whisper 做 4 倍速实时转录，Ollama 本地模型做摘要，数据不出机器。在企业隐私合规日益严格的背景下，"本地化会议助手"正成为刚需。
- **适合人群**：重视隐私的企业团队、远程办公者、Rust 语言爱好者

## 趋势洞察

### 1. Agent 垂直场景"百花齐放"
今天的日榜几乎被 Agent 垂直应用占领：求职（ai-job-search）、视频理解（claude-video）、办公自动化（OfficeCLI）、会议纪要（meetily）、话题研究（last30days-skill）。Agent 正从"万能助手"走向"专业工匠"——每个场景都需要专精的技能+工具+记忆组合。

### 2. 大厂构建 Agent 全栈底座
腾讯本周同时推出三层 Agent 基础设施：安全沙箱（CubeSandbox，隔离层）、长期记忆（TencentDB-Agent-Memory，记忆层），加上此前已有的编排能力，形成了"隔离→记忆→编排"完整栈。阿里则用 zvec 补齐了向量检索层。大厂不再只是"开源一个模型"，而是在构建 Agent 时代的"操作系统"。

### 3. WiFi 感知计算成为新赛道
RuView 用 WiFi CSI 信号做空间感知和体征监测，79k stars 证明开发者对"非视觉感知"的热情。隐私焦虑+IoT 部署需求正在催生一个不同于摄像头方案的全新赛道——信号感知 AI。

### 4. "系统提示词考古"成为研究热点
system_prompts_leaks 本周增 6k+ stars，说明开发者对"理解 AI 产品内部逻辑"的需求在增长。从逆向工程到安全研究到提示词优化，这个方向正在从猎奇走向严肃研究。

### 5. Rust 在 Agent 基础设施中的地位持续上升
CubeSandbox、RuView、herdr、meetily——四个本周热门项目都用 Rust 构建 Agent 底座。性能+安全+轻量的组合使 Rust 成为 Agent 基础设施的"首选语言"。

---

*数据来源：GitHub Trending (Daily/Weekly) + GitHub Search (created:>2026-07-02)*
*报告时间：2026-07-09 18:25*
