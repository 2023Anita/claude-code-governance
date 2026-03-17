# Claude Code 架构治理工程实践

[![GitHub stars](https://img.shields.io/github/stars/claude-code-governance?style=flat)](https://github.com/claude-code-governance/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/claude-code-governance?style=flat)](https://github.com/claude-code-governance/network)
[![License](https://img.shields.io/github/license/claude-code-governance)](LICENSE)
[![Contributors](https://img.shields.io/github/contributors/claude-code-governance)](https://github.com/claude-code-governance/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/claude-code-governance/main)](https://github.com/claude-code-governance/commits/main)

---

> 企业级 Claude Code 架构治理实践指南，帮助团队建立规范、高效的 AI 辅助开发体系

## 多语言版本

[![English](https://img.shields.io/badge/lang-English-blue.svg)](i18n/README-en.md)
[![日本語](https://img.shields.io/badge/lang-日本語-orange.svg)](i18n/README-ja.md)
[![한국어](https://img.shields.io/badge/lang-한국어-green.svg)](i18n/README-ko.md)
[![中文](https://img.shields.io/badge/lang-中文-red.svg)](README.md)

---

## 概述

本项目系统性地介绍 Claude Code 在企业环境中的架构治理最佳实践，涵盖治理委员会建设、分层治理架构设计、核心治理机制实施等关键主题。通过本指南，团队可以建立既规范又灵活的 AI 辅助开发体系，在保持代码质量的同时充分发挥 AI 的生产力优势。

## 核心特性

| 特性 | 描述 |
|------|------|
| 🏛️ **分层治理架构** | 决策层、架构层、工程层三级治理体系 |
| 👥 **治理委员会机制** | 明确的角色定义与职责分工 |
| ⚙️ **核心治理机制** | 评审、门禁、度量、反馈四大支柱 |
| 📈 **渐进式实施路径** | 四阶段落地策略 |
| 💼 **最佳实践案例** | 真实企业场景的实践经验 |

## 目录导航

### 开始阅读

| 章节 | 标题 | 描述 |
|------|------|------|
| [01](./chapters/zh/01-intro.md) | 架构治理概述 | 定义、重要性、核心价值 |
| [02](./chapters/zh/02-committee.md) | 治理委员会 | 角色定义、职责分工 |
| [03](./chapters/zh/03-layered-arch.md) | 分层治理架构 | 三层架构设计 |
| [04](./chapters/zh/04-mechanisms.md) | 核心治理机制 | 评审、门禁、度量、反馈 |
| [05](./chapters/zh/05-implementation.md) | 实施路径 | 四阶段落地策略 |
| [06](./chapters/zh/06-cases.md) | 案例与实践 | 真实企业案例 |
| [07](./chapters/zh/07-faq.md) | 常见问题 | FAQ与解决方案 |

或者查看 [完整目录](./SUMMARY.md)

## 快速开始

### 入门路径

1. **了解概念** - 阅读 [架构治理概述](./chapters/zh/01-intro.md)
2. **理解架构** - 学习 [分层治理架构](./chapters/zh/03-layered-arch.md)
3. **建立机制** - 掌握 [核心治理机制](./chapters/zh/04-mechanisms.md)
4. **实施落地** - 按照 [实施路径](./chapters/zh/05-implementation.md) 推进

### 核心原则

- **适度治理** - 既不过于宽松导致失控，也不过于严格抑制创新
- **渐进演化** - 治理体系需要随团队成熟度逐步完善
- **透明可追溯** - 所有治理决策都有清晰的依据和记录
- **持续反馈** - 定期评估治理效果并优化

## 项目结构

```
claude-code-governance/
├── i18n/                       # 多语言版本
│   ├── README-en.md           # English
│   ├── README-ja.md           # 日本語
│   ├── README-ko.md           # 한국어
│   └── summary/               # 多语言目录
├── chapters/                   # 章节内容
│   ├── zh/                    # 中文
│   ├── en/                    # English
│   ├── ja/                    # 日本語
│   └── ko/                    # 한국어
├── assets/                     # 资源文件
├── README.md                   # 主 README
└── SUMMARY.md                  # 完整目录
```

## 贡献指南

欢迎提交 Issue 和 Pull Request 来改进本指南！

### 贡献方式

- 🐛 报告问题
- 📝 提交修改
- 📚 完善文档
- 💡 提出建议

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 了解详情。

---

*本项目旨在帮助企业更好地利用 Claude Code 提升开发效率，同时保持代码质量和安全标准。*
