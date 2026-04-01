# Claude Code in Action - 课程笔记

**[English](README.md)** | **[中文](README.zh.md)**

Anthropic Academy 官方课程 **"Claude Code in Action"** 的完整学习笔记。

## 课程简介

本课程由 Anthropic 官方提供，系统讲解如何使用 Claude Code（命令行 AI 编码助手）加速开发工作流。课程涵盖从基础原理到高级集成的完整内容，适合希望将 AI 辅助编程融入日常开发的工程师。

**课程地址：** [Anthropic Academy - Claude Code in Action](https://anthropic.skilljar.com/claude-code-in-action)

## 课程内容

共 **21 节课**，约 **1 小时视频**，分为 5 个模块：

### 模块一：什么是 Claude Code？
| # | 课时 | 描述 |
|---|------|------|
| 01 | Introduction | 课程介绍 |
| 02 | What is a Coding Assistant? | AI 编码助手的工作原理：工具调用（Tool Use）机制 |
| 03 | Claude Code in Action | Claude Code 如何组合多种工具完成复杂任务 |

### 模块二：动手实践
| # | 课时 | 描述 |
|---|------|------|
| 04 | Claude Code Setup | 安装配置 Claude Code |
| 05 | Project Setup | 项目初始化与练习环境搭建 |
| 06 | Adding Context | `/init`、CLAUDE.md、`@` 文件引用 |
| 07 | Making Changes | 使用 Claude Code 修改代码、Plan Mode 与 Thinking Mode |

### 模块三：高级功能
| # | 课时 | 描述 |
|---|------|------|
| 09 | Controlling Context | 上下文管理：compact、清除对话、多会话策略 |
| 10 | Custom Commands | 自定义斜杠命令（`/.claude/commands/`） |
| 11 | MCP Servers | 通过 MCP 协议集成外部工具（Playwright 浏览器自动化等） |
| 12 | GitHub Integration | GitHub Actions 自动化 PR 审查与 Issue 处理 |

### 模块四：Hooks 与 SDK
| # | 课时 | 描述 |
|---|------|------|
| 13 | Introducing Hooks | Hooks 概念：在工具调用前后插入自定义逻辑 |
| 14 | Defining Hooks | Hook 配置结构：matcher、command、exit codes |
| 15 | Implementing a Hook | 实战：编写防止读取 .env 文件的 Hook |
| 16 | Gotchas Around Hooks | Hook 开发的常见陷阱与调试技巧 |
| 17 | Useful Hooks! | 实用 Hook：自动格式化代码 |
| 18 | Another Useful Hook | 实用 Hook：Stop Hook 自动生成 git commit |
| 19 | The Claude Code SDK | 通过 SDK 以编程方式调用 Claude Code |

### 模块五：总结
| # | 课时 | 描述 |
|---|------|------|
| 20 | Quiz on Claude Code | 8 道测验题及答案 |
| 21 | Summary and Next Steps | 课程总结 |

## 文件结构

```
├── README.md                                    # 英文版 README
├── README.zh.md                                 # 本文件（中文）
├── en/                                          # English（原版）
│   ├── Claude_Code_in_Action_Full_Course.md     #   完整课程笔记（合并版）
│   ├── 01_Introduction.txt                      #   各课时原始内容
│   ├── ...
│   └── 21_Summary_and_next_steps.txt
└── zh/                                          # 中文版（即将推出）
```

## 学习目标

完成本课程后，你将能够：

- 理解 AI 编码助手的架构与工具调用机制
- 使用 Claude Code 的核心工具进行文件操作、命令执行和代码分析
- 通过 `/init`、CLAUDE.md 和 `@` 引用有效管理上下文
- 使用 Plan Mode 和 Thinking Mode 处理复杂任务
- 创建自定义命令自动化重复性开发工作
- 通过 MCP 服务器扩展 Claude Code 能力
- 设置 GitHub Actions 实现自动化 PR 审查
- 编写 Hooks 控制 Claude Code 的工具调用行为
- 使用 Claude Code SDK 将 AI 能力集成到自动化管道中

## 前置要求

- 基本的命令行操作经验
- Claude Code 访问权限和 API Key

## 许可证

本仓库包含 Anthropic Academy 课程的个人学习笔记。所有原始课程内容版权归 Anthropic PBC 所有。
