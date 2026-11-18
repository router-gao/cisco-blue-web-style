# Cisco-inspired blue web style

A portable Agent Skill for the user's approved cyan, blue and gray-blue web palette. Open [the example](assets/example.html) to preview it. The palette is inspired by Cisco's public website and is an independent style reference.

## Install from GitHub

Clone directly into the skill folder for automatic discovery in compatible clients. Restart the client if it caches the skill list.

**Codex** (Bash)

```sh
git clone https://github.com/router-gao/cisco-blue-web-style.git "${CODEX_HOME:-$HOME/.codex}/skills/cisco-blue-web-style"
```

**Claude Code** (Bash)

```sh
git clone https://github.com/router-gao/cisco-blue-web-style.git ~/.claude/skills/cisco-blue-web-style
```

On Windows PowerShell, use the same Git URL with "$env:USERPROFILE/.codex/skills/cisco-blue-web-style" or "$env:USERPROFILE/.claude/skills/cisco-blue-web-style" as the destination. Update a Git installation with `git -C <installed-skill-folder> pull --ff-only`.

**ChatGPT and Claude web** — download `cisco-blue-web-style.zip` from [Releases](https://github.com/router-gao/cisco-blue-web-style/releases/latest) and upload it via the product's Skills interface, where available. Upload a new ZIP to update a web installation.

**DeepSeek harness** — the harness controls skill discovery. If it supports Agent Skills, clone into its configured skills directory (the final folder name should be `cisco-blue-web-style`). Otherwise load `SKILL.md` as instructions and make `assets/` available to the agent. The model alone does not install skills.

Try asking “用思科蓝白 Skill 做一个独立 HTML 页面，画出读题和写答案的流程。”
