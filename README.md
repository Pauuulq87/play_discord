<div align="center">

# Play Discord

<img src="https://api.iconify.design/mdi/robot.svg" width="64" height="64" alt="Discord Bot"/>

Discord news collector bot — auto-collect RSS news and push to designated channels.

**English** | [繁體中文](./README_zh-TW.md) | [简体中文](./README_zh-CN.md)

</div>

---

## Features

- Discord Bot integration
- RSS Feed news collection
- Keyword filtering
- Scheduled push notifications
- Zero-cost deployment (Zeabur free tier)

## Quickstart

```bash
# Install dependencies
npm install

# Configure
cp .env.example .env
# Edit .env with your settings

# Dev mode
npm run dev

# Build
npm run build
```

## Project Structure

```
src/main/typescript/
├── core/       # Discord Bot core
├── services/   # RSS collection service
├── commands/   # Bot commands
└── utils/      # Utilities
```

## Deployment

Deploy on Zeabur. See `docs/specs/tech-choices.md` for details.

---

## License

MIT

## Acknowledgements

Made with ❤️ by **Pauuulq87**
