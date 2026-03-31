# Clawd Codex 🚀

[English](#english) | [中文](#中文)

---

<a name="中文"></a>
## 中文

> 基于 Claude Code 源码的开源重构实现

### ✨ 项目愿景

**Clawd Codex** 是一个基于 **Claude Code 源码**进行深度学习和重构的开源项目。我们通过对原始代码的系统性分析与重新实现，打造一个**透明、可定制、可自我改良**的 AI 编程助手生态系统。

> 📖 **为什么重构？** 我们相信，理解一个系统的最好方式就是重新构建它。通过逆向学习和重构实践，我们不仅获得了技术洞察，更创造了一个完全开放、可供社区共同演进的代码库。

### 🌟 核心亮点

#### 🔥 Python-First 架构
- **150+ 命令** 完整移植，覆盖代码审查、重构、调试等 Claude Code 的核心场景
- **100+ 工具** 模块化设计，支持 MCP 协议扩展
- **28+ 子系统** 构建完整的 AI 编程助手运行时

#### ⚡ 强大的运行时引擎
- **会话持久化** - 随时保存和恢复对话状态
- **多模式远程支持** - SSH、Teleport、Direct Connect 任你选择
- **Bootstrap 图系统** - 智能路由命令和工具调用
- **成本追踪** - 实时监控 API 使用和费用

#### 🧪 完整的测试覆盖
```bash
python3 -m unittest discover -s tests -v
```
40+ 测试用例确保系统稳定性

### 🎯 路线图

#### 🏗️ 当前阶段 (v0.x)
- [x] Python 核心运行时
- [x] 命令/工具镜像系统
- [x] 会话管理与持久化
- [x] 远程模式支持
- [x] Bootstrap 图引擎

#### 🔮 即将推出

##### 🦫 Go 版本 (计划中)
高性能、跨平台的 Go 语言实现：
- **10x 启动速度提升**
- **单二进制部署** - 无需 Python 环境
- **更低的内存占用**
- **原生并发支持**

##### 📚 中英文双语教学版
全球首个完整的 AI 编程助手教程：
- **从零开始** 构建 AI 编程助手
- **中英双语注释** 每一行代码
- **交互式学习** 边学边练
- **架构深度解析** 理解每个设计决策

##### 🤖 24小时自动迭代系统
革命性的自我进化机制：
- **持续集成** - 24/7 自动运行测试
- **智能分析** - Claude 自动识别改进点
- **安全合并** - 人工审核 + AI 建议
- **版本追溯** - 每次迭代都有完整记录

### 🚀 快速开始

#### 环境要求
- Python 3.10+
- 可选：Anthropic API Key（用于完整功能）

#### 安装
```bash
git clone https://github.com/GPT-AGI/Clawd-Codex.git
cd Clawd-Codex
```

#### 核心命令

```bash
# 查看移植摘要
python3 -m src.main summary

# 列出已移植的命令
python3 -m src.main commands --limit 20

# 列出已移植的工具
python3 -m src.main tools --limit 20

# 搜索命令和工具
python3 -m src.main route "review code"

# 运行 Bootstrap 会话
python3 -m src.main bootstrap "analyze security" --limit 5

# 运行测试
python3 -m unittest discover -s tests -v
```

### 🤝 参与贡献

**我们热烈欢迎所有开发者提交 PR！** 🎉

#### 如何贡献

1. **Fork 本仓库** → 创建你自己的分支
2. **进行修改** → 修复 Bug、添加功能、改进文档
3. **提交 Pull Request** → 详细描述你的改动
4. **Code Review** → 我们会尽快审核并合并

#### 贡献类型

- 🐛 **修复 Bug** - 发现问题？直接修！
- ✨ **新功能** - 有好想法？实现它！
- 📝 **文档改进** - 文档永远不够完美
- 🌍 **国际化** - 帮助翻译成更多语言
- 🧪 **测试用例** - 增加测试覆盖率

### ⚠️ 免责声明

本项目是对 **Claude Code 源码**的独立学习和重构实现：

- 本项目**不拥有**原始 Claude Code 源码的所有权
- 本项目**不隶属于、未被认可、也未被 Anthropic 维护**
- 本项目是对公开信息的**独立学习、分析和重新实现**
- 我们尊重原始创作者的知识产权

---

<a name="english"></a>
## English

> Open-source reimplementation based on Claude Code source

### ✨ Vision

**Clawd Codex** is an open-source project based on deep learning and reimplementation of **Claude Code source code**. Through systematic analysis and reimplementation, we're building a **transparent, customizable, and self-improving** AI coding assistant ecosystem.

> 📖 **Why reimplement?** We believe the best way to understand a system is to rebuild it. Through reverse engineering and reimplementation, we've gained technical insights and created a fully open codebase for community evolution.

### 🌟 Highlights

#### 🔥 Python-First Architecture
- **150+ Commands** fully ported, covering code review, refactoring, debugging and more
- **100+ Tools** with modular design, supporting MCP protocol extensions
- **28+ Subsystems** building a complete AI coding assistant runtime

#### ⚡ Powerful Runtime Engine
- **Session Persistence** - Save and restore conversation states anytime
- **Multi-mode Remote Support** - SSH, Teleport, Direct Connect
- **Bootstrap Graph System** - Intelligent command and tool routing
- **Cost Tracking** - Real-time API usage and cost monitoring

#### 🧪 Complete Test Coverage
```bash
python3 -m unittest discover -s tests -v
```
40+ test cases ensure system stability

### 🎯 Roadmap

#### 🏗️ Current Stage (v0.x)
- [x] Python core runtime
- [x] Command/Tool mirror system
- [x] Session management & persistence
- [x] Remote mode support
- [x] Bootstrap graph engine

#### 🔮 Coming Soon

##### 🦫 Go Version (Planned)
High-performance, cross-platform Go implementation:
- **10x faster startup**
- **Single binary deployment** - No Python required
- **Lower memory footprint**
- **Native concurrency support**

##### 📚 Bilingual Tutorial Edition
World's first complete AI coding assistant tutorial:
- **Build from scratch** - Construct your own AI assistant
- **Bilingual comments** - Every line explained in Chinese & English
- **Interactive learning** - Learn by doing
- **Architecture deep dive** - Understand every design decision

##### 🤖 24/7 Auto-Iteration System
Revolutionary self-evolution mechanism:
- **Continuous Integration** - 24/7 automated testing
- **Intelligent Analysis** - Claude auto-identifies improvements
- **Safe Merging** - Human review + AI suggestions
- **Version Tracking** - Complete history of every iteration

### 🚀 Quick Start

#### Requirements
- Python 3.10+
- Optional: Anthropic API Key (for full functionality)

#### Installation
```bash
git clone https://github.com/GPT-AGI/Clawd-Codex.git
cd Clawd-Codex
```

#### Core Commands

```bash
# View porting summary
python3 -m src.main summary

# List ported commands
python3 -m src.main commands --limit 20

# List ported tools
python3 -m src.main tools --limit 20

# Search commands and tools
python3 -m src.main route "review code"

# Run bootstrap session
python3 -m src.main bootstrap "analyze security" --limit 5

# Run tests
python3 -m unittest discover -s tests -v
```

### 🤝 Contributing

**We warmly welcome all developers to submit PRs!** 🎉

#### How to Contribute

1. **Fork this repo** → Create your own branch
2. **Make changes** → Fix bugs, add features, improve docs
3. **Submit Pull Request** → Describe your changes in detail
4. **Code Review** → We'll review and merge ASAP

#### Contribution Types

- 🐛 **Bug Fixes** - Found an issue? Fix it!
- ✨ **New Features** - Have an idea? Implement it!
- 📝 **Documentation** - Docs can always be better
- 🌍 **Internationalization** - Help translate to more languages
- 🧪 **Test Cases** - Increase test coverage

### ⚠️ Disclaimer

This project is an independent learning and reimplementation of **Claude Code source**:

- This project does **not own** the original Claude Code source
- This project is **not affiliated with, endorsed by, or maintained by Anthropic**
- This project is an **independent learning, analysis, and reimplementation** of publicly available information
- We respect the intellectual property of the original creators

---

## 📜 License

This project is built with open-source spirit. See LICENSE file for details.

---

<p align="center">
  <i>"AI should not be a black box. It should be an open tool we create together."</i>
</p>

<p align="center">
  <b>Star ⭐</b> | <b>Fork 🍴</b> | <b>Watch 👀</b>
</p>
