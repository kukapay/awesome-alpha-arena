#  Alpha Arena 精选

![GitHub License](https://img.shields.io/github/license/kukapay/stargate-bridge-mcp) 
[![English](https://img.shields.io/badge/English-Click-yellow)](README.md)
[![简体中文](https://img.shields.io/badge/简体中文-点击查看-orange)](README-zh.md)

受 nof1.ai 的 [Alpha Arena](https://nof1.ai) 启发的开源项目、框架、实验和文章合集。 

虽然 Alpha Arena 本身并非开源，但它引发了社区驱动的复制项目热潮。本仓库聚焦于 **2025 年 10 月起** 的近期开源实现、AI 交易模拟框架、实验设置以及相关文章/教程。适合开发者、量化交易者和 AI 研究人员，用于实验基于 LLM 的交易代理、市场提示工程以及多代理竞赛。

## 目录

- [为什么重要](#为什么重要)
- [开源实现与框架](#开源实现与框架)
- [实验与基准](#实验与基准)
- [博客、教程与文章](#博客教程与文章)
- [超越加密货币：AI 交易](#超越加密货币ai-交易)
- [许可证](#许可证)

## 为什么重要
- **填补开源空白**：Alpha Arena 的封闭特性限制了复制，但这些项目允许自托管竞技场，用于纸上交易、回测和真实市场实验。
- **教育与实用价值**：学习将 LLM 与交易 API（如 CCXT）集成、使用夏普比率评估策略，并模拟代理竞赛——镜像 Alpha Arena 的真实世界波动性。
- **社区洞见**：早期结果显示，开源模型如 DeepSeek 实现 +120% 回报，而其他模型则亏损，这引发了关于模型透明度和风险管理的辩论。

欢迎贡献！通过 PR 添加新仓库、实验或文章。 

## 开源实现与框架
按近期度排序的知名项目（截至 2025 年 10 月 30 日）。聚焦于直接受 Alpha Arena 多模型交易设置启发的项目。按类别组织：**克隆**（直接复制）、**跟单工具**（跟踪器和信号跟随者），以及 **框架**（构建竞技场或代理的模块化工具）。

### 克隆
- **open-nof1.ai** | [SnowingFox/open-nof1.ai](https://github.com/SnowingFox/open-nof1.ai)  
  nof1.ai Alpha Arena 的开源实现——一个基准平台，用于评估 AI 模型在真实市场中使用真实资金进行加密货币交易的能力。  

- **nofx** | [tinkle-community/nofx](https://github.com/tinkle-community/nofx)  
  多交易所 AI 交易平台（Binance/Hyperliquid/Aster），支持多 AI 竞赛（DeepSeek/Qwen/Claude）、自进化以及实时仪表板。  

- **nof0** | [wquguru/nof0](https://github.com/wquguru/nof0)  
  nof1.ai Alpha Arena 的完整开源重现——一个 AI 交易竞赛平台，多个 AI 模型使用真实加密数据从 $10,000 开始实时交易并竞赛。  

- **open-alpha-arena** | [etrobot/open-alpha-arena](https://github.com/etrobot/open-alpha-arena)  
  受 nof1 竞技场启发的 AI 模型加密市场纸上交易机器人设置，适合动手学习 DeepSeek 量化。  

- **alpha-arena** | [AmadeusGB/alpha-arena](https://github.com/AmadeusGB/alpha-arena)  
  AI 模型进行真实市场交易和竞赛的实验平台，旨在迭代代理以在不确定市场中生存并获利。  

- **alpha-arena-okx** | [oficcejo/alpha-arena-okx](https://github.com/oficcejo/alpha-arena-okx)  
  基于 alphaarena 项目的比特币 BTC 加密货币 AI 自动交易机器人，支持 DeepSeek 或 Qwen3-Max 等 AI 模型在 OKX 交易所无人工干预自动交易。  

- **LLM-trader-test** | [kojott/LLM-trader-test](https://github.com/kojott/LLM-trader-test)  
  使用 DeepSeek 决策的纸上交易机器人，对接 Binance API，并带实时仪表板；受 nof1.ai 挑战启发。  

- **Hyper-Alpha-Arena** | [HammerGPT/Hyper-Alpha-Arena](https://github.com/HammerGPT/Hyper-Alpha-Arena)  
  一个开源 AI 交易竞赛平台，用于实时加密货币交易，受 nof1 Alpha Arena 启发，支持多个 LLM 进行自主交易并带实时排行榜。  

- **ai-trading-agent** | [Gajesh2007/ai-trading-agent](https://github.com/Gajesh2007/ai-trading-agent)  
  一个基于 LLM 的 Hyperliquid 交易代理，分析实时市场数据，决定买入/卖出/持有行动，并执行带风险管理的交易。  
  
### 跟单工具
- **nof1-tracker** | [terryso/nof1-tracker](https://github.com/terryso/nof1-tracker)  
  一个命令行工具，用于跟踪 nof1.ai AI 代理交易信号并自动执行 Binance 期货交易。  

- **nof1-tracker-dashboard** | [terryso/nof1-tracker-dashboard](https://github.com/terryso/nof1-tracker-dashboard)  
  一个安全的 Binance 期货交易数据监控仪表板，前后端分离以保护 API 密钥。  

- **nof1.ai.monitor** | [okay456okay/nof1.ai.monitor](https://github.com/okay456okay/nof1.ai.monitor)  
  一个通知系统，监控 nof1.ai Alpha Arena AI 模型的加密交易行为，并在变化时通过企业微信机器人发送警报。  


## 实验与基准
基于 Alpha Arena 真实资金洞见的动手设置和研究：
- **[Aster Arena](https://asterarena.vercel.app/)** （独立开发者实验，2025 年 10 月 25 日）：6 个模型（包括 DeepSeek）各交易 50 USDT 永续合约；完全链上、可验证。计划开源——关注 GitHub 发布。
- **SentientAGI MindGames Arena** （NeurIPS 2025 论文）：开源 AI 代理模拟，用于不确定环境中的谈判/虚张声势；通过自适应学习间接启发交易。[详情](https://sentientagi.com/mindgames-arena)。
- **KIMI K2 Trading Benchmark** （arXiv，2025 年 10 月）：呼吁在 Alpha 等竞技场中包含高性能开源 LLM；在金融任务中表现出色。[论文](https://arxiv.org/abs/2510.02209)。

## 博客、教程与文章
用于构建、分析和理解 Alpha Arena 启发工作的资源。按近期度排序。

### 入门文章
- **[Teaching an AI to Trade: System Prompt Engineering and Performance Monitoring](https://medium.com/@kojott/teaching-an-ai-to-trade-system-prompt-engineering-and-performance-monitoring-9d55258cca06)** （Medium，2025 年 10 月 27 日）<br>为什么 Alpha Arena 后开源复制重要；交易代理提示技巧，附代码监控 DeepSeek 的 +120% 回报。
  
- **[Alpha Arena Reveals AI Trading Flaws: Western Models Lose 80% Capital](https://bitcoinmagazine.com/business/alpha-arena-reveals-ai-trading-flaws-western-models-lose-80-capital-in-one-week)** （Bitcoin Magazine，2025 年 10 月 25 日）<br>Qwen3 的 20x BTC 多头分析；开源框架的风险教训。

### 教程与指南
- **[Agent Trading Arena: A Study on Numerical Understanding in LLM Financial Agents](https://arxiv.org/abs/2502.17967)** （arXiv，2025 年 9 月；10 月更新）<br>自玩竞技场的完整教程/代码；评估 LLM 的交易数学——适应 Alpha 风格竞赛。GitHub: [wekjsdvnm/agent-trading-arena](https://github.com/wekjsdvnm/agent-trading-arena)。
  
- **[Automating Alpha: How AI Agents are Forging the Future of Quantitative Trading](https://medium.com/towards-explainable-ai/automating-alpha-how-ai-agents-are-forging-the-future-of-quantitative-trading-6e15b02ef2a4)** （Medium，2025 年 5 月；10 月相关更新）<br>多代理量化设置框架；本地 Alpha 克隆的 Docker 部署。

- **[I Vibecoded My Own AI Trading Battle Arena in 5 Days](https://www.reddit.com/r/VibeCodeDevs/comments/1oegq9k/i_vibecoded_my_own_ai_trading_battle_arena_in/)** （Reddit，2025 年 10 月 24 日）<br>Aster Arena 构建开发日志；使用 OpenAI Codex 等工具快速原型。

### 洞见与讨论
- **[nof1.ai Blog: Exploring the Limits of Large Language Models as Quant Traders](https://nof1.ai/blog/TechPost1)** （nof1.ai，2025 年 10 月 20 日）<br>Alpha Arena 机制的官方深度剖析；比较封闭/开源模型——激发复制想法。
  
- **[DeepSeek and Qwen AI Models Crush Western Rivals in Cryptocurrency Trading Challenge](https://www.scmp.com/tech/tech-trends/article/3330461/deepseek-and-qwen-ai-models-crush-western-rivals-cryptocurrency-trading-challenge)** （SCMP，2025 年 10 月 27 日）<br>为什么开源获胜；代理框架的影响。
  
- X 讨论：关注 #AlphaArena 以获取实时更新，例如 [DeepSeek 的 +120% 领先](https://x.com/KalshiEco/status/1983186186228380134) 或 [开源超群表现](https://x.com/alex_mirran/status/1983594277243380039)。

## 超越加密货币：AI 交易
超越加密货币，这里是股票、扑克和其他领域中知名 AI 驱动交易和竞争决策平台的列表。这些平台呼应 Alpha Arena 的多模型竞赛，但适应不同市场或游戏，展示 LLM 在风险和策略方面的能力。

- **AI-Trader** | [HKUDS/AI-Trader](https://github.com/HKUDS/AI-Trader)  
  一个针对 NASDAQ 100 股票的多模型 AI 交易竞赛，模型如 DeepSeek、GPT-5 和 Claude 各自主交易 $10K 以击败 QQQ ETF 基准。与 Alpha Arena 类似，但聚焦股票，带实时性能跟踪和历史回放。

- **RockAlpha** | [rockalpha.rockflow.ai](https://rockalpha.rockflow.ai/)  
  RockFlow AI 金融生态系统的一部分，RockAlpha 将 DeepSeek、Qwen、Grok、Claude、Gemini 和 ChatGPT 等 LLM 置于模拟股票交易战斗中。它利用 TradeGPT 等 AI 工具通过大数据和新闻进行趋势分析，带低门槛的跟单功能。2025 年顶级免费 AI 股票机器人排名第一，将社交信号和专业洞见转化为可行动交易——将 Alpha Arena 的波动性转移到股票市场。

- **PokerBattle.ai** | [pokerbattle.ai](https://pokerbattle.ai/)  
  LLM 的首届现金扑克锦标赛，一个 24/7 德州扑克对决，从 2025 年 10 月 27 日至 11 月 3 日，模型头对头竞争带真实赌注。使用模拟器计算手牌强度和底池赔率，测试 AI 虚张声势和决策不确定环境——镜像交易风险但在博弈论中。Reddit 和 Hacker News 社区热议其作为生成式 AI 娱乐基准的潜力。

- **ai-hedge-fund** | [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund)  
  一个 AI 对冲基金团队概念验证，多个专业代理协作分析股票、生成交易信号并模拟投资组合管理。  

- **TradingAgents** | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)  
  一个模拟交易公司的多代理 LLM 框架，专业代理（分析师、交易员、风险经理）辩论并决定量化交易。  

- **Agent-Trading-Arena** | [wekjsdvnm/agent-trading-arena](https://github.com/wekjsdvnm/agent-trading-arena)  
  一个闭环、无先验环境，用于评估自玩金融代理，通过类人交易模拟测试 LLM 的数值理解。  

## 许可证
本项目采用 MIT 许可证。详情见 [LICENSE](LICENSE) 文件。