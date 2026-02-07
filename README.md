<div align="center">

# Shannon AI Pentester 🚀
**Your autonomous AI security ninja that finds real exploits, not just alerts.**

[![GitHub Stars](https://img.shields.io/github/stars/KeygraphHQ/shannon?color=ff6b6b&label=Stars&logo=github&style=flat-square)](https://github.com/KeygraphHQ/shannon/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/KeygraphHQ/shannon?color=4ecdc4&label=Forks&logo=github&style=flat-square)](https://github.com/KeygraphHQ/shannon/network/members)
[![GitHub Language](https://img.shields.io/github/languages/top/KeygraphHQ/shannon?color=45b7d1&label=TypeScript&logo=typescript&style=flat-square)](https://github.com/KeygraphHQ/shannon)
[![Discord](https://img.shields.io/discord/1227907613271560283?color=7289da&label=Discord&logo=discord&style=flat-square)](https://discord.gg/KAqzSHHpRt)
[![Trendshift](https://trendshift.io/api/badge/repositories/15604)](https://trendshift.io/repositories/15604)

![Shannon Demo](assets/shannon-action.gif)

</div>

---

## 🎯 What is Shannon?

**Shannon is your AI pentester that delivers actual exploits, not just alerts.**

Shannon autonomously hunts for attack vectors in your code, then uses its built-in browser to execute real exploits—like injection attacks and auth bypass—to prove vulnerabilities are actually exploitable.

### The Problem Shannon Solves

Your team ships code daily with tools like Claude Code and Cursor, but your penetration test happens once a year. That's a **massive 364-day security gap** where vulnerabilities could be shipping to production.

Shannon closes this gap by acting as your on-demand whitebox pentester. It doesn't just find potential issues—it executes real exploits, providing concrete proof of vulnerabilities so you can ship with confidence.

---

## ✨ This Fork: VS Code Integration (by RafikTodak)

This fork adds **native VS Code integration**, making Shannon even more accessible for developers:

- **One-click pentesting** directly from VS Code
- **Live exploit preview** in your editor
- **Seamless workflow** with your existing development setup
- **Real-time vulnerability reporting** as you code

[![VS Code Extension](https://img.shields.io/badge/VS%20Code-Extension-007ACC?style=flat-square&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=RafikTodak.shannon-vscode)

---

## 🎬 See Shannon in Action

**Real Results**: Shannon discovered 20+ critical vulnerabilities in OWASP Juice Shop, including complete auth bypass and database exfiltration.

![Shannon Demo](assets/shannon-screen.png)

---

## 🚀 Quick Start

### 1. Install Shannon
```bash
npm install -g @keygraphhq/shannon
```

### 2. Run Your First Pentest
```bash
shannon scan --target https://your-web-app.com
```

### 3. Get Your Report
```bash
shannon report --output security-report.md
```

---

## 🔥 Key Features

| Feature | Benefit |
|---------|---------|
| **Fully Autonomous** | Launch with a single command, AI handles everything |
| **Pentester-Grade Reports** | Delivers reproducible exploits, not just warnings |
| **Built-in Browser** | Executes real exploits, not theoretical findings |
| **Advanced Auth Handling** | Handles 2FA/TOTP, Google OAuth, and complex login flows |
| **VS Code Integration** | Native extension for seamless developer workflow |
| **96.15% Success Rate** | Top performance on hint-free, source-aware benchmarks |

---

## 📊 Benchmark Performance

Shannon achieves **96.15% success rate** on the hint-free, source-aware XBOW benchmark, outperforming other autonomous pentesting solutions.

[View Benchmark Results](https://github.com/KeygraphHQ/shannon/tree/main/xben-benchmark-results/README.md)

---

## 🔗 Resources

- **[Website](https://keygraph.io)** - Learn about the broader Keygraph Platform
- **[Discord](https://discord.gg/KAqzSHHpRt)** - Join the community
- **[Sample Report](sample-reports/shannon-report-juice-shop.md)** - See a real pentest report
- **[VS Code Extension](https://marketplace.visualstudio.com/items?itemName=RafikTodak.shannon-vscode)** - Install the fork's VS Code integration

---

## 🤝 Contributing

This is a fork by [RafikTodak](https://github.com/RafikTodak) that adds VS Code integration to the original Shannon project.

- **Original Repository**: [KeygraphHQ/shannon](https://github.com/KeygraphHQ/shannon)
- **Issues**: Report bugs and feature requests
- **PRs**: Contributions are welcome!

---

## ⚖️ License

Shannon is released under the [MIT License](LICENSE).

---

**Shannon: Because every Claude (coder) deserves their Shannon.** 🛡️
