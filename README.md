# Claude Code in Action - Course Notes

Anthropic Academy 官方课程 **"Claude Code in Action"** 的完整学习笔记。

## 课程简介

本课程由 Anthropic 官方提供，系统讲解如何使用 Claude Code（命令行 AI 编码助手）加速开发工作流。课程涵盖从基础原理到高级集成的完整内容，适合希望将 AI 辅助编程融入日常开发的工程师。

**课程地址：** [Anthropic Academy - Claude Code in Action](https://anthropic.skilljar.com/claude-code-in-action)

## 课程内容

共 **21 节课**，约 **1 小时视频**，分为 5 个模块：

### Module 1: What is Claude Code?
| # | Lesson | Description |
|---|--------|-------------|
| 01 | Introduction | 课程介绍 |
| 02 | What is a Coding Assistant? | AI 编码助手的工作原理：工具调用（Tool Use）机制 |
| 03 | Claude Code in Action | Claude Code 如何组合多种工具完成复杂任务 |

### Module 2: Getting Hands On
| # | Lesson | Description |
|---|--------|-------------|
| 04 | Claude Code Setup | 安装配置 Claude Code |
| 05 | Project Setup | 项目初始化与练习环境搭建 |
| 06 | Adding Context | `/init`、CLAUDE.md、`@` 文件引用 |
| 07 | Making Changes | 使用 Claude Code 修改代码、Plan Mode 与 Thinking Mode |

### Module 3: Advanced Features
| # | Lesson | Description |
|---|--------|-------------|
| 09 | Controlling Context | 上下文管理：compact、清除对话、多会话策略 |
| 10 | Custom Commands | 自定义斜杠命令（`/.claude/commands/`） |
| 11 | MCP Servers | 通过 MCP 协议集成外部工具（Playwright 浏览器自动化等） |
| 12 | GitHub Integration | GitHub Actions 自动化 PR 审查与 Issue 处理 |

### Module 4: Hooks and the SDK
| # | Lesson | Description |
|---|--------|-------------|
| 13 | Introducing Hooks | Hooks 概念：在工具调用前后插入自定义逻辑 |
| 14 | Defining Hooks | Hook 配置结构：matcher、command、exit codes |
| 15 | Implementing a Hook | 实战：编写防止读取 .env 文件的 Hook |
| 16 | Gotchas Around Hooks | Hook 开发的常见陷阱与调试技巧 |
| 17 | Useful Hooks! | 实用 Hook：自动格式化代码 |
| 18 | Another Useful Hook | 实用 Hook：Stop Hook 自动生成 git commit |
| 19 | The Claude Code SDK | 通过 SDK 以编程方式调用 Claude Code |

### Module 5: Wrapping Up
| # | Lesson | Description |
|---|--------|-------------|
| 20 | Quiz on Claude Code | 8 道测验题及答案 |
| 21 | Summary and Next Steps | 课程总结 |

## 文件结构

```
├── README.md                                    # 本文件
├── Claude_Code_in_Action_Full_Course.md         # 完整课程笔记（合并版）
├── 01_Introduction.txt                          # 各课时原始内容
├── 02_What_is_a_coding_assistant.txt
├── ...
└── 21_Summary_and_next_steps.txt
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

## License

This repository contains personal study notes from the Anthropic Academy course. All original course content is owned by Anthropic PBC.
