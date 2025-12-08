# Dooz Cartridges

Official cartridge repository for [Dooz Bridge](https://github.com/dooziesoft/dooz-bridge).

## Cartridges

### Free Cartridges

| Cartridge | Description |
|-----------|-------------|
| 🕐 **Git Time-Traveler** | Visualize git history and checkout commits |
| 🩺 **NPM Doctor** | Summarize npm audit vulnerabilities |
| 🐳 **Docker Skipper** | Manage containers and view logs |
| 🎬 **Video Wizard** | Convert videos with ffmpeg |
| 🌤️ **Weather Station** | Beautiful weather reports from wttr.in |
| 📋 **Clipboard Manager** | Advanced clipboard history |
| 📝 **Markdown Preview** | Live preview markdown files |

### Pro Cartridges

| Cartridge | Price |
|-----------|-------|
| 🔍 **Code Analyzer Pro** | $9.99 |
| 🗄️ **Database Manager Pro** | $14.99 |
| ☁️ **Backup Master** | $4.99 |

## Registry

The registry is available at:
```
https://raw.githubusercontent.com/dooziesoft/dooz-cartridges/main/registry.json
```

## Creating Your Own Cartridge

1. Create a folder in `cartridges/your-cartridge-name/`
2. Add a `manifest.json` with:
   - `id`: Unique identifier (e.g., `com.yourname.cartridge-name`)
   - `name`: Display name
   - `description`: Short description
   - `binary`: CLI tool used (must be in PATH)
   - `gui.inputs`: Form fields
   - `gui.template`: Command template

## License

MIT
