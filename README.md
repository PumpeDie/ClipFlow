# ClipFlow 🚀📋

[![License: GPLv3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![GitHub Issues](https://img.shields.io/github/issues/PumpeDie/ClipFlow)](https://github.com/PumpeDie/ClipFlow/issues)
[![GitHub Stars](https://img.shields.io/github/stars/PumpeDie/ClipFlow)](https://github.com/PumpeDie/ClipFlow/stargazers)
[![Mozilla Add-on](https://img.shields.io/amo/v/clipflow)](https://addons.mozilla.org/firefox/addon/clipflow/)
[![npm](https://img.shields.io/npm/v/clipflow)](https://www.npmjs.com/package/clipflow)

> The missing clipboard-to-upload tool for Firefox (and soon other browsers).  
> Inspired by Opera GX's killer feature — now open-source and extensible.

***

## Features ✨
- **Paste-to-upload** from clipboard (screenshots, text, files)
- **Recent files picker** without digging through folders
- **Native-like popup** (dark/light theme support)
- _Coming soon:_ Cross-browser support (Chromium-based)

***

## Quick Start 🛠️
### For Users
1. Install from [Firefox Add-ons](https://addons.mozilla.org/firefox/addon/clipflow/) (once published)
2. Click the toolbar icon or use `Ctrl+Shift+V` to trigger the picker

### For Developers
```bash
# Clone and build
git clone https://github.com/PumpeDie/ClipFlow.git
cd ClipFlow
make firefox

# Load in Firefox:
# 1. Go to about:debugging
# 2. Load "dist/firefox.xpi" as temporary add-on
```

---

## Contributing 🤝
We welcome PRs! Please read our:
- [Contributing Guidelines](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)

_Typical workflow:_
1. Fork → Branch → `make test` → PR
2. Discuss → Merge → Celebrate! 🎉

---

## License ⚖️
GNU GPLv3 - See [LICENSE](LICENSE) for details.

---

> 💡 **Pro Tip**: Use the issue templates for [bug reports](.github/ISSUE_TEMPLATE/bug_report.md) or [feature requests](.github/ISSUE_TEMPLATE/feature_request.md)!
