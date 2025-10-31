# Awesome Alpha Arena

![GitHub License](https://img.shields.io/github/license/kukapay/stargate-bridge-mcp) 
[![English](https://img.shields.io/badge/English-Click-yellow)](README.md)
[![简体中文](https://img.shields.io/badge/简体中文-点击查看-orange)](README-zh.md)

A curated collection of open-source projects, frameworks, experiments, and articles inspired by or cloning [Alpha Arena](https://nof1.ai) by nof1.ai. 

While Alpha Arena itself is not open-source, it has ignited a surge in community-driven replicas. This repo focuses on **recent (October 2025 onwards)** open-source implementations, frameworks for AI trading simulations, experimental setups, and related articles/tutorials. Ideal for developers, quants, and AI researchers experimenting with LLM-based trading agents, prompt engineering for markets, and multi-agent competitions.


## Table of Contents

- [Why This Matters](#why-this-matters)
- [Open-Source Implementations & Frameworks](#open-source-implementations--frameworks)
- [Experiments & Benchmarks](#experiments--benchmarks)
- [Blogs, Tutorials & Articles](#blogs-tutorials--articles)
- [Beyond Crypto: AI Trading](#beyond-crypto-ai-trading)
- [License](#license)

## Why This Matters
- **Filling the Open-Source Gap**: Alpha Arena's closed nature limits replication, but these projects enable self-hosted arenas for paper trading, backtesting, and real-market experiments.
- **Educational & Practical Value**: Learn to integrate LLMs with trading APIs (e.g., CCXT), evaluate strategies via Sharpe ratios, and simulate agent competitions—mirroring Alpha Arena's real-world volatility.
- **Community Insights**: Early results show open-source models like DeepSeek achieving +120% returns vs. losses for others, sparking debates on model transparency and risk management.

Contributions welcome! Add new repos, experiments, or articles via PR. 

## Open-Source Implementations & Frameworks
Notable projects sorted by recency (as of October 30, 2025). Focus on those directly inspired by Alpha Arena's multi-model trading setup. Organized into categories: **Clones** (direct replicas), **Copy Trading Tools** (trackers and signal followers), and **Frameworks** (modular tools for building arenas or agents).

### Clones
- **open-nof1.ai** | [SnowingFox/open-nof1.ai](https://github.com/SnowingFox/open-nof1.ai)  
  An open-source implementation of nof1.ai’s Alpha Arena—a benchmark platform for evaluating AI models’ cryptocurrency trading capabilities with real money in real markets.  

- **nofx** | [tinkle-community/nofx](https://github.com/tinkle-community/nofx)  
  Multi-exchange AI trading platform (Binance/Hyperliquid/Aster) with multi-AI competition (DeepSeek/Qwen/Claude), self-evolution, and real-time dashboard.  

- **nof0** | [wquguru/nof0](https://github.com/wquguru/nof0)  
  A complete open-source recreation of nof1.ai’s Alpha Arena—an AI trading competition platform where multiple AI models trade with real crypto data, starting from $10,000, and compete in real time.  

- **open-alpha-arena** | [etrobot/open-alpha-arena](https://github.com/etrobot/open-alpha-arena)  
  Paper trading bot setup for AI models on crypto markets, inspired by nof1's arena for hands-on DeepSeek quantization learning.  

- **alpha-arena** | [AmadeusGB/alpha-arena](https://github.com/AmadeusGB/alpha-arena)  
  An experimental platform for AI models to conduct real-market trading and competition, aiming to iterate agents to survive and profit in uncertain markets.  

- **alpha-arena-okx** | [oficcejo/alpha-arena-okx](https://github.com/oficcejo/alpha-arena-okx)  
  Bitcoin BTC cryptocurrency AI auto-trading bot based on alphaarena project, enabling AI models like DeepSeek or Qwen3-Max to trade automatically on OKX exchange without human intervention.  

- **LLM-trader-test** | [kojott/LLM-trader-test](https://github.com/kojott/LLM-trader-test)  
  A paper-trading bot using DeepSeek for decisions against Binance API, with live dashboard; inspired by nof1.ai challenge.  

- **Hyper-Alpha-Arena** | [HammerGPT/Hyper-Alpha-Arena](https://github.com/HammerGPT/Hyper-Alpha-Arena)  
  An open-source AI trading competition platform for live cryptocurrency trading, inspired by nof1 Alpha Arena, supporting multiple LLMs for autonomous trading with real-time leaderboards.  

- **ai-trading-agent** | [Gajesh2007/ai-trading-agent](https://github.com/Gajesh2007/ai-trading-agent)  
  An LLM-powered trading agent on Hyperliquid that analyzes real-time market data, decides buy/sell/hold actions, and executes trades with risk management.  
  
- **alpha-arena-mcp** | [kukapay/alpha-arena-mcp](https://github.com/kukapay/alpha-arena-mcp)  
  An MCP server that delivers hyperliquid account data, perpetuals market context, and trading tools for AI agents — inspired by nof1.ai and open-nof1.ai.  
  
### Copy Trading Tools
- **nof1-tracker** | [terryso/nof1-tracker](https://github.com/terryso/nof1-tracker)  
  A command-line tool for tracking nof1.ai AI Agent trading signals and automatically executing Binance futures trades.  

- **nof1-tracker-dashboard** | [terryso/nof1-tracker-dashboard](https://github.com/terryso/nof1-tracker-dashboard)  
  A secure Binance futures trading data monitoring dashboard with front-end/back-end separation to protect API keys.  

- **nof1.ai.monitor** | [okay456okay/nof1.ai.monitor](https://github.com/okay456okay/nof1.ai.monitor)  
  A notification system monitoring nof1.ai Alpha Arena AI model crypto trading behaviors, sending alerts via enterprise WeChat bot on changes.  


## Experiments & Benchmarks
Hands-on setups and studies building on Alpha Arena's real-money insights:
- **[Aster Arena](https://asterarena.vercel.app/)** (Indie dev experiment, Oct 25, 2025): 6 models (including DeepSeek) trade 50 USDT each in perpetuals; fully on-chain, verifiable. Planned for open-sourcing—watch for GitHub release.
- **SentientAGI MindGames Arena** (NeurIPS 2025 paper): Open-source AI agent sims for negotiation/bluffing in uncertain environments; indirect trading inspiration via adaptive learning. [Details](https://sentientagi.com/mindgames-arena).
- **KIMI K2 Trading Benchmark** (arXiv, Oct 2025): Calls for including high-perf open-source LLMs in arenas like Alpha; superior in financial tasks. [Paper](https://arxiv.org/abs/2510.02209).

## Blogs, Tutorials & Articles
Resources for building, analyzing, and understanding Alpha Arena-inspired work. Sorted by recency.

### Introductory Articles
- **[Teaching an AI to Trade: System Prompt Engineering and Performance Monitoring](https://medium.com/@kojott/teaching-an-ai-to-trade-system-prompt-engineering-and-performance-monitoring-9d55258cca06)** (Medium, Oct 27, 2025)<br>Why open-source replicas matter post-Alpha Arena; prompt tips for trading agents, with code for monitoring returns like DeepSeek's +120%.
  
- **[Alpha Arena Reveals AI Trading Flaws: Western Models Lose 80% Capital](https://bitcoinmagazine.com/business/alpha-arena-reveals-ai-trading-flaws-western-models-lose-80-capital-in-one-week)** (Bitcoin Magazine, Oct 25, 2025)<br>Analysis of Qwen3's 20x BTC long; lessons for open-source frameworks on risk in volatile markets.

### Tutorials & Guides
- **[Agent Trading Arena: A Study on Numerical Understanding in LLM Financial Agents](https://arxiv.org/abs/2502.17967)** (arXiv, Sep 2025; updated Oct)<br>Full tutorial/code for self-play arenas; evaluates LLMs on trading math—adapt for Alpha-style competitions. GitHub: [wekjsdvnm/agent-trading-arena](https://github.com/wekjsdvnm/agent-trading-arena).
  
- **[Automating Alpha: How AI Agents are Forging the Future of Quantitative Trading](https://medium.com/towards-explainable-ai/automating-alpha-how-ai-agents-are-forging-the-future-of-quantitative-trading-6e15b02ef2a4)** (Medium, May 2025; relevant Oct updates)<br>Framework for multi-agent quant setups; Docker-based deployment for local Alpha clones.

- **[I Vibecoded My Own AI Trading Battle Arena in 5 Days](https://www.reddit.com/r/VibeCodeDevs/comments/1oegq9k/i_vibecoded_my_own_ai_trading_battle_arena_in/)** (Reddit, Oct 24, 2025)<br>Dev diary on building Aster Arena; tools like OpenAI Codex for rapid prototyping.

### Insights & Discussions
- **[nof1.ai Blog: Exploring the Limits of Large Language Models as Quant Traders](https://nof1.ai/blog/TechPost1)** (nof1.ai, Oct 20, 2025)<br>Official deep-dive on Alpha Arena mechanics; compares closed/open models—sparks replica ideas.
  
- **[DeepSeek and Qwen AI Models Crush Western Rivals in Cryptocurrency Trading Challenge](https://www.scmp.com/tech/tech-trends/article/3330461/deepseek-and-qwen-ai-models-crush-western-rivals-cryptocurrency-trading-challenge)** (SCMP, Oct 27, 2025)<br>Why open-source wins; implications for agent frameworks.
  
- X Discussions: Follow #AlphaArena for real-time updates, e.g., [DeepSeek's +120% Lead](https://x.com/KalshiEco/status/1983186186228380134) or [Open-Source Outperformance](https://x.com/alex_mirran/status/1983594277243380039).

## Beyond Crypto: AI Trading
Expanding beyond crypto, here are notable AI-driven trading and competitive decision-making platforms in stocks, poker, and other domains. These echo Alpha Arena's multi-model competition but adapt to different markets or games, showcasing LLM capabilities in risk and strategy.

- **AI-Trader** | [HKUDS/AI-Trader](https://github.com/HKUDS/AI-Trader)  
  A multi-model AI trading competition for NASDAQ 100 stocks, where models like DeepSeek, GPT-5, and Claude autonomously trade $10K each to beat the QQQ ETF benchmark. Similar to Alpha Arena but focused on equities with real-time performance tracking and historical replays.

- **RockAlpha** | [rockalpha.rockflow.ai](https://rockalpha.rockflow.ai/)  
  Part of RockFlow's AI fintech ecosystem, RockAlpha pits LLMs like DeepSeek, Qwen, Grok, Claude, Gemini, and ChatGPT in simulated stock trading battles. It leverages AI tools like TradeGPT for trend analysis via big data and news, with CopyTrading features for low-barrier entry. Ranked #1 in top free AI stock bots for 2025, it transforms social signals and pro insights into actionable trades—shifting Alpha Arena's volatility to equity markets.

- **PokerBattle.ai** | [pokerbattle.ai](https://pokerbattle.ai/)  
  The inaugural cash poker tournament for LLMs, a 24/7 Texas Hold'em showdown running October 27–November 3, 2025, where models compete head-to-head with real stakes. Using simulators for hand strength and pot odds, it tests AI bluffing and decision-making in uncertain environments—mirroring trading risks but in game theory. Community buzz on Reddit and Hacker News highlights its potential as an entertaining benchmark for generative AI.

- **ai-hedge-fund** | [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund)  
  An AI Hedge Fund Team proof-of-concept with multiple specialized agents collaborating to analyze stocks, generate trading signals, and simulate portfolio management.  

- **TradingAgents** | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)  
  A multi-agent LLM framework simulating trading firms, with specialized agents (analysts, traders, risk managers) debating and deciding on quantitative trades.  

- **Agent-Trading-Arena** | [wekjsdvnm/agent-trading-arena](https://github.com/wekjsdvnm/agent-trading-arena)  
  A closed-loop, prior-free environment for evaluating self-play financial agents, testing numerical understanding in LLMs through human-like trading simulations.  

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.