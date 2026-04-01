# Claude Code in Action - Course Notes

**[English](README.md)** | **[中文](README.zh.md)**

Complete study notes from Anthropic Academy's official course **"Claude Code in Action"**.

## About This Course

This course is provided by Anthropic and covers how to use Claude Code — a command-line AI coding assistant — to accelerate your development workflow. It spans from foundational concepts to advanced integrations, designed for engineers looking to incorporate AI-assisted programming into their daily work.

**Course link:** [Anthropic Academy - Claude Code in Action](https://anthropic.skilljar.com/claude-code-in-action)

## Course Content

**21 lessons** | ~**1 hour** of video | **5 modules**

### Module 1: What is Claude Code?
| # | Lesson | Description |
|---|--------|-------------|
| 01 | Introduction | Course overview |
| 02 | What is a Coding Assistant? | How AI coding assistants work: the Tool Use mechanism |
| 03 | Claude Code in Action | How Claude Code combines multiple tools for complex tasks |

### Module 2: Getting Hands On
| # | Lesson | Description |
|---|--------|-------------|
| 04 | Claude Code Setup | Installing and configuring Claude Code |
| 05 | Project Setup | Project initialization and practice environment |
| 06 | Adding Context | `/init`, CLAUDE.md, and `@` file references |
| 07 | Making Changes | Modifying code with Claude Code, Plan Mode & Thinking Mode |

### Module 3: Advanced Features
| # | Lesson | Description |
|---|--------|-------------|
| 09 | Controlling Context | Context management: compact, clearing conversations, multi-session strategies |
| 10 | Custom Commands | Custom slash commands (`/.claude/commands/`) |
| 11 | MCP Servers | Integrating external tools via MCP protocol (Playwright browser automation, etc.) |
| 12 | GitHub Integration | Automated PR reviews and issue handling with GitHub Actions |

### Module 4: Hooks and the SDK
| # | Lesson | Description |
|---|--------|-------------|
| 13 | Introducing Hooks | Hooks concept: injecting custom logic before/after tool calls |
| 14 | Defining Hooks | Hook configuration: matcher, command, exit codes |
| 15 | Implementing a Hook | Hands-on: writing a hook to prevent reading .env files |
| 16 | Gotchas Around Hooks | Common pitfalls and debugging tips for hooks |
| 17 | Useful Hooks! | Practical hook: auto-formatting code |
| 18 | Another Useful Hook | Practical hook: Stop Hook for auto git commit |
| 19 | The Claude Code SDK | Running Claude Code programmatically via SDK |

### Module 5: Wrapping Up
| # | Lesson | Description |
|---|--------|-------------|
| 20 | Quiz on Claude Code | 8 quiz questions with answers |
| 21 | Summary and Next Steps | Course wrap-up |

## Repository Structure

```
├── README.md                                    # This file (English)
├── README.zh.md                                 # 中文版 README
├── en/                                          # English (original)
│   ├── Claude_Code_in_Action_Full_Course.md     #   Full course notes (merged)
│   ├── 01_Introduction.txt                      #   Individual lesson content
│   ├── ...
│   └── 21_Summary_and_next_steps.txt
└── zh/                                          # Chinese (coming soon)
```

## Learning Objectives

By the end of this course, you'll be able to:

- Understand AI coding assistant architecture and the tool use mechanism
- Use Claude Code's core tools for file manipulation, command execution, and code analysis
- Manage context effectively using `/init`, CLAUDE.md, and `@` references
- Use Plan Mode and Thinking Mode for complex tasks
- Create custom commands to automate repetitive development workflows
- Extend Claude Code capabilities with MCP servers
- Set up GitHub Actions for automated PR reviews
- Write hooks to control Claude Code's tool call behavior
- Integrate AI capabilities into automation pipelines using the Claude Code SDK

## Prerequisites

- Basic command-line experience
- Access to Claude Code and an API key

## License

This repository contains personal study notes from the Anthropic Academy course. All original course content is owned by Anthropic PBC.
