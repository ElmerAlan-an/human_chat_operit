# 真人聊天增强 (HumanChat) — Operit 版

让 AI 助手在 Operit 中像真人一样随机应变地聊天。

**双版本提供**：Skill（轻量Prompt） + ToolPkg（硬检测引擎）

---

## 快速安装

### 方式一：Skill 版（推荐入门）

1. 下载 `operit/SKILL.md`
2. 放到手机 `/sdcard/Download/Operit/skills/human_chat/`
3. 重启 Operit 或在技能管理中刷新

### 方式二：ToolPkg 版（硬检测，推荐进阶）

1. 下载 `operit/human_chat.toolpkg`
2. 放到手机 `/sdcard/Android/data/com.ai.assistance.operit/files/packages/`
3. 在 Operit → 包管理 → 右上角刷新 → 找到"真人聊天增强" → 启用

---

## 功能

| | Skill 版 (Prompt) | ToolPkg 版 (JS硬检测) |
|---|---|---|
| 4种人格风格 | ✅ | ✅ |
| 智能情绪切换(auto) | ✅ | ✅ |
| 情绪强度+混合情绪+反讽 | ✅ | — |
| 时间感知 | ✅ | — |
| 自检清单 | ✅ | — |
| ngram反重复硬检测 | — | ✅ |
| System Prompt注入 | — | ✅ |
| AI味黑名单过滤 | — | ✅ |
| 命令 /human | ✅ | — |

**两个版本可同时启用，互补工作。**

---

## 命令

| 命令 | 作用 |
|------|------|
| `/human style natural` | 自然随性 |
| `/human style humorous` | 幽默风趣 |
| `/human style warm` | 温暖贴心 |
| `/human style serious` | 严肃专业 |
| `/human style auto` | 智能切换（情绪自动匹配） |
| `/human emoji medium` | 表情密度 |
| `/human status` | 查看当前状态 |

---

## 开源协议

MIT