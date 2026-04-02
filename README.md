# Dooz Cartridges

Official cartridge registry for [Dooz Bridge](https://github.com/dooziesoft/dooz-bridge).

## Cartridges

### Free

| Cartridge | Description | Category |
|-----------|-------------|----------|
| 🕐 **Git Time-Traveler** | Visualize git history and checkout commits | dev-tools |
| 🩺 **NPM Doctor** | Summarize npm audit vulnerabilities | dev-tools |
| 🐳 **Docker Skipper** | Manage containers and view logs | dev-tools |
| 🎬 **Video Wizard** | Convert videos with ffmpeg | media |
| 🌤️ **Weather Station** | Beautiful weather reports from wttr.in | utility |
| 📋 **Clipboard Manager** | Advanced clipboard history | utility |
| 📝 **Markdown Preview** | Live preview markdown files | utility |
| 🔍 **Code Analyzer** | Static analysis and code quality reports | dev-tools |
| 🗄️ **Database Manager** | Query and manage databases | dev-tools |
| ☁️ **Backup Master** | Automated backup workflows | utility |

### AI Coding

| Cartridge | Description | Category |
|-----------|-------------|----------|
| 🤖 **Aider** | AI pair programming with any LLM | ai-coding |
| 🧠 **Claude Code** | Anthropic Claude Code CLI | ai-coding |
| 💻 **Copilot CLI** | GitHub Copilot CLI integration | ai-coding |
| 🦙 **Ollama** | Local LLM inference via Ollama | ai-coding |
| 🎯 **Cursor** | Cursor IDE CLI integration | ai-coding |
| 🌊 **Windsurf** | Codeium Windsurf integration | ai-coding |
| 📊 **Jules** | Google Jules async task submission | ai-coding |
| 🔮 **Gemini CLI** | Google Gemini CLI | ai-coding |
| 🚀 **DeepSeek CLI** | DeepSeek Coder CLI | ai-coding |
| ⚡ **Tabby** | Self-hosted AI coding assistant | ai-coding |

### Workflows

| Cartridge | Description | Category |
|-----------|-------------|----------|
| 🔎 **PR Review** | Automated PR review pipeline | workflow |
| 🧪 **Test Gen** | AI test generation | workflow |
| 🔧 **Refactor** | AI-assisted refactoring | workflow |
| 🐛 **Debug** | Interactive debugging session | workflow |
| 📖 **Docs** | Documentation generation | workflow |
| 🛡️ **Security Audit** | Security vulnerability scanning | workflow |
| 🔄 **Migration** | Framework/version migration assistant | workflow |
| 🎓 **Onboard** | New developer onboarding assistant | workflow |

### Integrations

| Cartridge | Description | Category |
|-----------|-------------|----------|
| 🐙 **GitHub** | GitHub API (PRs, issues, actions) | integration |
| 🦊 **GitLab** | GitLab API integration | integration |
| 📌 **Jira** | Jira issue tracking integration | integration |
| 📐 **Linear** | Linear issue tracking integration | integration |
| 💬 **Slack** | Slack notifications and commands | integration |
| 📓 **Notion** | Notion workspace integration | integration |
| 🎨 **Figma** | Figma design file access | integration |
| 🚨 **Sentry** | Sentry error monitoring | integration |

## Registry

```
https://raw.githubusercontent.com/dooziesoft/dooz-cartridges/main/registry.json
```

## Creating a Cartridge

1. Create `cartridges/your-cartridge/`
2. Add `manifest.json`:
   - `id`: Unique identifier
   - `name`: Display name
   - `description`: Short description
   - `binary`: CLI tool (must be in PATH)
   - `gui.inputs`: Form fields
   - `gui.template`: Command template

## License

MIT
