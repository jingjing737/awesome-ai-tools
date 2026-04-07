# Awesome AI Tools 🔥

> A curated list of awesome AI tools, frameworks, libraries, and resources to supercharge your workflow.
> 精心整理的 AI 工具列表，助你效率飞升！

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/jingjing737/awesome-ai-tools?style=flat)](https://github.com/jingjing737/awesome-ai-tools/stargazers)
[![License](https://img.shields.io/github/license/jingjing737/awesome-ai-tools)](LICENSE)

---

# ⭐ Featured Project | 明星项目

## 🔥 DevTools Hub - 开发者工具箱

> **115 个实用命令 · macOS/Linux/Windows 全平台支持**

```
pip install devtools-hub
# 或者
brew install devtools-hub
```

**[GitHub](https://github.com/jingjing737/devtools-hub) · [PyPI](https://pypi.org/project/devtools-hub/) · [文档](https://github.com/jingjing737/devtools-hub#readme)**

---

### 功能一览 | Features at a Glance

| 分类 | 命令示例 | 说明 |
|------|----------|------|
| 🚀 **系统监控** | `devtools cpu` `devtools mem` `devtools disk` | 实时监控 CPU、内存、磁盘 |
| 🌐 **网络工具** | `devtools net` `devtools ports` `devtools ip` | 网络速度、端口扫描、IP 查询 |
| ⚡ **性能测试** | `devtools bench` | 一键性能基准测试 |
| 📊 **进程管理** | `devtools top` `devtools ps` | 查看高占用进程 |
| 🛠️ **开发辅助** | `devtools ping` `devtools dns` `devtools curl` | 开发者常用网络工具 |
| 🐳 **Docker** | `devtools docker ps` `devtools docker images` | Docker 容器管理 |
| 📁 **文件工具** | `devtools find` `devtools du` `devtools size` | 文件查找和大小分析 |
| 🔧 **系统工具** | `devtools uptime` `devtools who` `devtools battery` | 系统信息和电池状态 |

### 使用示例 | Quick Examples

```bash
# 系统状态一览
$ devtools status
┌─────────────────────────────────────┐
│  🖥️ MacBook-Air | Darwin 24.6.0   │
│  CPU: 45% (8核) | 内存: 62%        │
│  磁盘: 35% | 网络: ↑2.1 ↓5.8 MB/s │
└─────────────────────────────────────┘

# 性能基准测试
$ devtools bench
{
  "cpu_score": 245.3,
  "memory_score": 189.2,
  "disk_score": 312.8,
  "total_score": 747.3
}

# 端口扫描
$ devtools ports 80 443 22 3306
🔍 Scanning 4 ports...
  ✅ 80 (HTTP) - open
  ✅ 443 (HTTPS) - open
  ❌ 22 (SSH) - filtered
  ❌ 3306 (MySQL) - closed

# 自更新到最新版本
$ dev selfupdate
📦 正在检查更新...
✅ 已更新到 v3.0.0
```

### 为什么选择 DevTools Hub？

- ✅ **115+ 命令** - 涵盖开发日常所需
- ✅ **零配置** - 安装即用，无需复杂设置
- ✅ **跨平台** - macOS / Linux / Windows
- ✅ **自更新** - 一条命令升级到最新版本
- ✅ **开源免费** - MIT 许可证
- ✅ **持续更新** - 活跃开发中

---

## 📚 Table of Contents | 目录

- [Large Language Models](#large-language-models)
- [Image Generation](#image-generation)
- [Audio & Speech](#audio--speech)
- [Video Generation](#video-generation)
- [Code Assistant](#code-assistant)
- [AI Agents & Automation](#ai-agents--automation)
- [Developer Tools](#developer-tools)
- [Productivity](#productivity)
- [Data & Analytics](#data--analytics)
- [Writing & Content](#writing--content)
- [AI Art & Design](#ai-art--design)
- [Education & Learning](#education--learning)
- [Gaming](#gaming)
- [Finance](#finance)
- [Healthcare](#healthcare)
- [Security](#security)
- [Robotics & Hardware](#robotics--hardware)
- [AI Research](#ai-research)
- [Open Source Models](#open-source-models)
- [AI Communities](#ai-communities)

---

## Large Language Models | 大语言模型

### Cloud APIs | 云端 API
- [OpenAI GPT-4](https://platform.openai.com/) - Most capable GPT model
- [Claude](https://claude.ai/) - Anthropic's AI assistant
- [Gemini](https://gemini.google.com/) - Google's multimodal AI
- [Mistral AI](https://mistral.ai/) - Open and efficient LLMs
- [Cohere](https://cohere.com/) - Enterprise AI platform
- [Anthropic Claude API](https://www.anthropic.com/) - Claude API access

### Local Models | 本地模型
- [Ollama](https://ollama.ai/) - Run LLMs locally
- [llama.cpp](https://github.com/ggerganov/llama.cpp) - LLM inference in C/C++
- [LM Studio](https://lmstudio.ai/) - Discover, download, and run LLMs
- [text-generation-webui](https://github.com/oobabooga/text-generation-webui) - Web UI for LLMs
- [KoboldCpp](https://github.com/LostRuins/koboldcpp) - GGML LLM inference

### Chinese LLMs | 中文大模型
- [通义千问 Qwen](https://tongyi.aliyun.com/) - Alibaba's LLM
- [文心一言](https://yiyan.baidu.com/) - Baidu's LLM
- [智谱清言](https://chatglm.cn/) - Zhipu's LLM
- [讯飞星火](https://xinghuo.xfyun.cn/) - iFlytek's LLM

---

## Image Generation | 图像生成

- [Midjourney](https://www.midjourney.com/) - AI image generation
- [DALL-E](https://openai.com/dall-e-3) - OpenAI's image model
- [Stable Diffusion](https://stability.ai/) - Open source image generation
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - Workflow-based UI for Stable Diffusion
- [Leonardo AI](https://leonardo.ai/) - AI art platform
- [Adobe Firefly](https://firefly.adobe.com/) - Adobe's generative AI
- [Canva AI](https://canva.com/) - AI design tools
- [Pika](https://pika.art/) - Text to video (also image)
- [Runway](https://runwayml.com/) - AI creative tools
- [Civitai](https://civitai.com/) - AI model sharing

### Image Editing | 图像编辑
- [Remove.bg](https://remove.bg/) - AI background removal
- [cleanup.pictures](https://cleanup.pictures/) - AI object removal
- [Let's Enhance](https://letsenhance.io/) - AI image upscaling
- [DeepAI](https://deepai.org/) - AI image tools

---

## Audio & Speech | 音频与语音

- [ElevenLabs](https://elevenlabs.io/) - AI voice cloning
- [Whisper](https://openai.com/research/whisper) - Speech recognition
- [Mubert](https://mubert.com/) - AI music generation
- [Suno](https://suno.ai/) - AI music creation
- [Udio](https://udio.ai/) - AI music generation
- [Coqui](https://coqui.ai/) - Open source voice AI
- [PlayHT](https://play.ht/) - AI text to speech
- [Murf AI](https://murf.ai/) - AI voice generator
- [WellSaid Labs](https://wellsaidlabs.com/) - AI voice synthesis
- [Respeecher](https://respeecher.com/) - AI voice conversion

### Audio Editing | 音频编辑
- [Adobe Podcast](https://podcast.adobe.com/) - AI audio editing
- [Krisp](https://krisp.ai/) - AI noise removal
- [LALAL.AI](https://lalal.ai/) - AI stem separation

---

## Video Generation | 视频生成

- [Sora](https://openai.com/sora) - OpenAI's video generation
- [Runway](https://runwayml.com/) - AI video editing and generation
- [Pika](https://pika.art/) - Text to video AI
- [Kaiber](https://kaiber.ai/) - AI video generation
- [Synthesia](https://synthesia.io/) - AI video avatars
- [HeyGen](https://heygen.com/) - AI video generation
- [InVideo](https://invideo.io/) - AI video creation
- [Veed.io](https://veed.io/) - Online video editor with AI

### Video Editing | 视频编辑
- [CapCut](https://capcut.com/) - AI video editor
- [Descript](https://descript.com/) - Video editing with AI
- [Runway](https://runwayml.com/) - Advanced video editing

---

## Code Assistant | 代码助手

- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer
- [Cursor](https://cursor.sh/) - AI-first code editor
- [Claude](https://claude.ai/) - Code understanding and generation
- [Codeium](https://codeium.com/) - Free AI code acceleration
- [Tabnine](https://tabnine.com/) - AI code completion
- [Replit](https://replit.com/) - AI coding platform
- [Amazon CodeWhisperer](https://aws.amazon.com/codewhisperer/) - Amazon's code generator
- [CodeGeex](https://codegeex.cn/) - Chinese AI code assistant
- [Mintlify](https://mintlify.com/) - AI documentation writer

### IDE Plugins | IDE 插件
- [IntelliJ AI Assistant](https://www.jetbrains.com/ai/) - JetBrains AI
- [VS Code AI Toolkit](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.vscode-ai-toolkit) - Microsoft AI

---

## AI Agents & Automation | AI 代理与自动化

- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - Autonomous AI agents
- [LangChain](https://www.langchain.com/) - Build LLM applications
- [CrewAI](https://crewai.com/) - Multi-agent AI frameworks
- [AutoGen](https://microsoft.github.io/autogen/) - Microsoft multi-agent framework
- [n8n](https://n8n.io/) - Workflow automation with AI
- [Zapier](https://zapier.com/) - Connect AI to 5000+ apps
- [Make](https://make.com/) - Scenario automation

### Agent Platforms | 代理平台
- [OpenAI Assistants](https://platform.openai.com/docs/assistants) - OpenAI agents
- [Claude Agents](https://docs.anthropic.com/claude/docs) - Anthropic's agent capabilities
- [AgentGPT](https://agentgpt.reworkd.ai/) - Autonomous AI agents
- [Godmode](https://godmode.space/) - AI agent playground

---

## Developer Tools | 开发者工具

> ⭐ **推荐**: [DevTools Hub](https://github.com/jingjing737/devtools-hub) - 115 个开发命令，一个工具全搞定！

### CLI Tools | 命令行工具
- [DevTools Hub](https://github.com/jingjing737/devtools-hub) - **115 commands** for system monitoring, network, docker, files
- [httpie](https://httpie.io/) - User-friendly CLI HTTP client
- [bat](https://github.com/sharkdp/bat) - Cat clone with syntax highlighting
- [fd](https://github.com/sharkdp/fd) - Fast alternative to find
- [exa](https://github.com/ogham/exa) - Modern ls replacement
- [ripgrep](https://rg) - Ultra-fast grep alternative
- [fzf](https://github.com/junegunn/fzf) - Fuzzy finder
- [jq](https://stedolan.github.io/jq/) - JSON processor
- [tldr](https://tldr.sh/) - Simplified man pages
- [gh](https://cli.github.com/) - GitHub CLI

### API Development | API 开发
- [Postman](https://www.postman.com/) - API platform
- [Insomnia](https://insomnia.rest/) - API client
- [Bruno](https://www.usebruno.com/) - Open source API client
- [Apifox](https://apifox.com/) - API management (Chinese)
- [Apipost](https://www.apipost.cn/) - API collaboration (Chinese)
- [Swagger](https://swagger.io/) - API documentation
- [Hoppscotch](https://hoppscotch.io/) - API request builder

### Database Tools | 数据库工具
- [DBeaver](https://dbeaver.io/) - Universal database tool
- [TablePlus](https://tableplus.com/) - Database GUI
- [Redis Insight](https://redis.com/) - Redis GUI
- [MongoDB Compass](https://www.mongodb.com/) - MongoDB GUI
- [Adminer](https://www.adminer.org/) - Database management

### DevOps | 运维工具
- [Docker](https://docker.com/) - Container platform
- [Kubernetes](https://kubernetes.io/) - Container orchestration
- [Prometheus](https://prometheus.io/) - Monitoring system
- [Grafana](https://grafana.com/) - Observability platform
- [Ansible](https://ansible.com/) - Automation platform
- [Terraform](https://terraform.io/) - Infrastructure as code

---

## Productivity | 效率工具

- [Notion](https://notion.so/) - All-in-one workspace
- [Obsidian](https://obsidian.md/) - Markdown-based knowledge base
- [Raycast](https://raycast.com/) - Productivity launcher (macOS)
- [Alfred](https://www.alfredapp.com/) - Productivity tool (macOS)
- [Todoist](https://todoist.com/) - Task management
- [Linear](https://linear.app/) - Issue tracking
- [ClickUp](https://clickup.com/) - All-in-one workspace
- [Anytype](https://anytype.io/) - Local-first workspace

### AI Productivity | AI 效率
- [Otter.ai](https://otter.ai/) - AI meeting assistant
- [Fireflies.ai](https://fireflies.ai/) - AI meeting notes
- [Mem](https://mem.ai/) - AI-powered notes
- [Taskade](https://www.taskade.com/) - AI task management
- [BeeHero](https://www.beehero.ai/) - AI project management

---

## Data & Analytics | 数据分析

- [pandas](https://pandas.pydata.org/) - Python data analysis
- [NumPy](https://numpy.org/) - Numerical computing
- [Apache Spark](https://spark.apache.org/) - Big data processing
- [dbt](https://www.getdbt.com/) - Data transformation
- [Metabase](https://metabase.com/) - Business intelligence
- [Apache Superset](https://superset.apache.org/) - BI and exploration
- [Observable](https://observablehq.com/) - Data visualization

### AI Analytics | AI 分析
- [Hex](https://hex.tech/) - Data notebooks
- [Mode](https://mode.com/) - Analytics platform
- [Posit Cloud](https://posit.co/) - R & Python analytics

---

## Writing & Content | 写作与内容

- [Claude](https://claude.ai/) - Long-form writing assistant
- [Jasper](https://jasper.ai/) - AI content generator
- [Copy.ai](https://copy.ai/) - AI copywriting
- [Writesonic](https://writesonic.com/) - AI writing assistant
- [Rytr](https://rytr.me/) - AI writing tool
- [Sudowrite](https://sudowrite.com/) - Creative writing AI
- [INK](https://inkforall.com/) - AI content optimization

### Chinese Writing | 中文写作
- [秘塔写作猫](https://xiezuocat.com/) - AI 中文写作助手
- [讯飞写作](https://xfwriting.com/) - iFlytek AI writing
- [反向词典](https://反向词典.cn/) - Find the right words

---

## AI Art & Design | AI 设计与艺术

- [Figma](https://figma.com/) - Collaborative design with AI
- [Adobe Firefly](https://firefly.adobe.com/) - Adobe generative AI
- [Khroma](https://khroma.co/) - AI color palette generator
- [Designs.ai](https://designs.ai/) - AI design tools
- [Uizard](https://uizard.io/) - AI UI designer
- [Galileo AI](https://ultragenerativeai.com/) - AI UI generation
- [Framer AI](https://framer.ai/) - AI website builder

---

## Education & Learning | 教育学习

- [Khan Academy](https://khanacademy.org/) - Free education with AI
- [Duolingo](https://duolingo.com/) - AI-powered language learning
- [Coursera](https://coursera.org/) - Online courses with AI
- [edX](https://edx.org/) - Online learning platform
- [Quizlet](https://quizlet.com/) - AI-powered flashcards
- [Wolfram Alpha](https://wolframalpha.com/) - Computational knowledge
- [Phind](https://phind.com/) - AI search engine for developers

### AI Learning | AI 学习
- [fast.ai](https://fast.ai/) - Deep learning made easy
- [DeepLearning.AI](https://deeplearning.ai/) - AI education
- [Hugging Face Course](https://huggingface.co/course) - NLP course

---

## Gaming | 游戏

- [Inworld AI](https://inworld.ai/) - AI game characters
- [Scenario](https://scenario.com/) - AI game asset generation
- [Latitude](https://latitude.io/) - AI game creation
- [Artbreeder](https://artbreeder.com/) - AI image blending
- [Waifulabs](https://waifulabs.com/) - AI anime character generator
- [Charisma](https://charisma.ai/) - Interactive AI characters

---

## Finance | 金融

- [AlphaSense](https://alpha-sense.com/) - AI market intelligence
- [Kensho](https://kensho.com/) - AI analytics for finance
- [Bloomberg GPT](https://bloomberg.com/) - Financial language model
- [Numerai](https://numerai.com/) - AI hedge fund
- [Kavout](https://kavout.com/) - AI stock scoring

### Trading | 交易
- [QuantConnect](https://quantconnect.com/) - Algorithmic trading
- [Alpaca](https://alpaca.markets/) - Commission-free trading API
- [Quantopian](https://quantopian.com/) - Python algorithmic trading

---

## Healthcare | 医疗健康

- [Google Health](https://health.google.com/) - AI health research
- [DeepMind](https://deepmind.com/) - AI for healthcare
- [Insilico Medicine](https://insilico.com/) - AI drug discovery
- [BenevolentAI](https://benevolent.ai/) - AI drug development
- [PathAI](https://pathai.com/) - AI pathology
- [Viz.ai](https://viz.ai/) - AI medical imaging

---

## Security | 安全

- [Darktrace](https://darktrace.com/) - AI cybersecurity
- [CrowdStrike](https://crowdstrike.com/) - AI endpoint protection
- [SentinelOne](https://sentinelone.com/) - AI security platform
- [Cymulate](https://cymulate.com/) - AI security testing
- [Vectra AI](https://vectra.ai/) - AI threat detection

### Security Tools | 安全工具
- [Metasploit](https://metasploit.com/) - Penetration testing
- [Burp Suite](https://portswigger.net/) - Web security testing
- [OWASP ZAP](https://owasp.org/) - Security testing

---

## Robotics & Hardware | 机器人与硬件

- [ROS](https://www.ros.org/) - Robot Operating System
- [NVIDIA Isaac](https://developer.nvidia.com/isaac) - Robotics platform
- [Boston Dynamics](https://boston dynamics.com/) - Advanced robots
- [Figure](https://figure.ai/) - AI humanoid robots
- [Agility Robotics](https://agility.ai/) - Digit robot

### Edge AI | 边缘计算
- [NVIDIA Jetson](https://developer.nvidia.com/jetson) - Edge AI platform
- [Intel OpenVINO](https://openvino.ai/) - AI inference toolkit
- [TensorFlow Lite](https://tensorflow.org/lite) - Mobile ML

---

## AI Research | AI 研究

- [Hugging Face](https://huggingface.co/) - ML community & models
- [Papers with Code](https://paperswithcode.com/) - ML papers with code
- [arXiv](https://arxiv.org/) - AI research papers
- [AI Index](https://aiindex.stanford.edu/) - AI metrics
- [OpenAI Research](https://openai.com/research) - OpenAI publications
- [Google DeepMind](https://deepmind.com/research) - Research publications
- [Anthropic Research](https://anthropic.com/research) - AI safety research

---

## Open Source Models | 开源模型

### Text Models | 文本模型
- [Llama](https://llama.meta.com/) - Meta's open source LLM
- [Mistral](https://mistral.ai/) - Open source models
- [Falcon](https://falconllm.tii.ae/) - TII's open source LLM
- [MPT](https://www.mosaicml.com/) - MosaicML models
- [RedPajama](https://together.ai/) - Open source training data
- [Vicuna](https://lmsys.org/) - Chatbot arena winner
- [ChatGLM](https://chatglm.cn/) - Chinese open source LLM
- [Baichuan](https://www.baichuan-ai.com/) - Chinese LLM

### Image Models | 图像模型
- [Stable Diffusion](https://stability.ai/) - Open source image generation
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - Stable Diffusion UI
- [ControlNet](https://github.com/lllyasviel/ControlNet) - Image control
- [LoRA](https://github.com/microsoft/LoRA) - Low-rank adaptation

### Multimodal | 多模态
- [LLaVA](https://llava-vl.github.io/) - Large language & vision assistant
- [MiniGPT-4](https://minigpt-4.github.io/) - Vision-language model
- [Flamingo](https://deepmind.com/) - Few-shot learner
- [GPT-4V](https://openai.com/) - Vision capabilities in GPT-4

---

## AI Communities | AI 社区

- [Hugging Face](https://huggingface.co/) - ML community platform
- [Reddit r/MachineLearning](https://reddit.com/r/MachineLearning) - ML discussions
- [Reddit r/Artificial](https://reddit.com/r/Artificial) - AI news
- [AI Twitter](https://twitter.com/i/communities) - AI researchers
- [AI Discord](https://discord.gg/) - Various AI Discord servers
- [Stack Overflow](https://stackoverflow.com/) - Developer Q&A

### Chinese Communities | 中文社区
- [知乎 AI](https://www.zhihu.com/topic/AI) - Chinese AI discussions
- [机器之心](https://jiqizhixin.com/) - AI news in Chinese
- [AI Watch](https://ai.watch/) - AI trends
- [GitHub Daily](https://github.com/trending) - Trending repos

---

## Contributing | 贡献

Contributions are welcome! Please feel free to submit a Pull Request.

欢迎提交贡献！请随时提交 Pull Request。

---

## License | 许可证

This list is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License.

[![Stargazers over time](https://starchart.cc/jingjing737/awesome-ai-tools)](https://starchart.cc/jingjing737/awesome-ai-tools)

---

<p align="center">
  <strong>⭐ Star this repo to support the project! | 点个 Star 支持一下！⭐</strong>
</p>
