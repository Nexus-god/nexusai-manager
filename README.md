# NexusAI Tools 🚀

> Professional AI Account Management & Protocol Gateway (v4.1.31)

<div align="center">

<img src="public/icon.png" alt="NexusAI Logo" width="120" height="120" style="border-radius: 24px;">

**Your Personal High-Performance AI Gateway**

Not just account management — the ultimate solution for breaking through API barriers.

[![Version](https://img.shields.io/badge/Version-4.1.31-blue?style=flat-square)](https://github.com/Nexus-god/nexusai-manager)
![Tauri](https://img.shields.io/badge/Tauri-v2-orange?style=flat-square)
![Rust](https://img.shields.io/badge/Backend-Rust-red?style=flat-square)
![React](https://img.shields.io/badge/Frontend-React-61DAFB?style=flat-square)

[English](#english) · [简体中文](#简体中文) · [Русский](#русский)

</div>

---

## 🎉 v4.1.31 — Major Update

<div align="center">
<img src="assets/fix-403-banner.png" alt="No More 403 Errors" width="700">
</div>

### ✅ What's Fixed

| 🔧 Fix | EN | 中文 | RU |
|--------|-----|------|-----|
| ~~403 Forbidden~~ | **Completely resolved** — no more 403 errors | 彻底解决 403 错误 | **Полностью исправлено** — больше никаких 403 |
| ~~Account Bans~~ | **Fixed** — improved session rotation | 改进会话轮换，防止封禁 | **Исправлено** — нет блокировок |
| ~~Rate Limiting~~ | **Bypassed** — smart request distribution | 智能请求分配 | **Обход** — умное распределение запросов |
| ~~Connection Drops~~ | **Stable** — auto-reconnect, zero downtime | 自动重连，零停机 | **Стабильно** — автопереподключение |
| ~~Token Expiry~~ | **Auto-refresh** — seamless renewal | 后台无缝刷新 | **Авто-обновление** токенов |

---

<a name="english"></a>

## 🌐 English

### About

NexusAI Tools is a full-featured desktop application designed for developers and AI enthusiasts. It combines multi-account management, protocol conversion, and intelligent request scheduling to provide you with a stable, fast, and cost-effective **local AI gateway**.

Convert Web Sessions (Google/Anthropic) into standardized API interfaces, eliminating protocol barriers between different providers.

### Core Features

- 🎛️ **Smart Dashboard** — Real-time monitoring of all accounts: Gemini Pro, Gemini Flash, Claude quota tracking
- 🔄 **Multi-Account Management** — One-click seamless switching between accounts with automatic session rotation
- 🌐 **Protocol Conversion** — Convert Google/Anthropic web sessions to standard OpenAI-compatible API
- 🛡️ **Stability Engine** — Smart request distribution, automatic cooldown, session health monitoring
- 📊 **Usage Analytics** — Token consumption tracking, cost estimation, rate limit monitoring
- 🔒 **Encrypted Storage** — AES-256 encrypted local storage for all credentials
- 🖥️ **Remote Session Support** — Virtual desktop integration for multi-device management
- 🔑 **OAuth Integration** — Seamless Google OAuth login flow
- 🌍 **Multi-Language** — English, Chinese, Russian interface

### Installation

#### Quick Start

```bash
git clone https://github.com/Nexus-god/nexusai-manager.git
cd nexusai-manager
npm install
npm run dev
```

#### AI-Assisted Setup (Recommended)

Copy the commands above into your AI coding assistant (Cursor, Claude Code, Windsurf, Cline) — it will handle everything automatically, including dependency installation and configuration.

#### Build from Source

```bash
npm run build
npm run tauri build
```

### Tech Stack

| Component | Technology |
|-----------|-----------|
| Framework | Tauri v2 |
| Backend | Rust |
| Frontend | React 19 + TypeScript |
| UI | Ant Design + Tailwind CSS |
| State | Zustand |
| Routing | React Router v7 |
| Build | Vite 7 |

### Screenshots

<div align="center">
<img src="docs/images/dashboard.png" alt="Dashboard" width="700">
<p><i>Smart Dashboard — Real-time account monitoring</i></p>

<img src="docs/images/accounts.png" alt="Account Management" width="700">
<p><i>Multi-Account Management — One-click switching</i></p>
</div>

### System Requirements

- Windows 10/11, macOS 12+, or Linux
- Node.js 18+
- npm 9+
- 4GB RAM minimum

---

<a name="简体中文"></a>

## 🇨🇳 简体中文

### 关于

NexusAI Tools 是一个专为开发者和 AI 爱好者设计的全功能桌面应用。它将多账号管理、协议转换和智能请求调度完美结合，为您提供一个稳定、极速且成本低廉的**本地 AI 中转站**。

通过本应用，您可以将常见的 Web 端 Session (Google/Anthropic) 转化为标准化的 API 接口，消除不同厂商间的协议鸿沟。

### 核心功能

- 🎛️ **智能仪表盘** — 实时监控所有账号的健康状况，包括 Gemini Pro、Flash、Claude 的配额
- 🔄 **多账号管理** — 一键无缝切换账号，自动会话轮换
- 🌐 **协议转换** — 将 Google/Anthropic Web Session 转为标准 OpenAI 兼容 API
- 🛡️ **稳定引擎** — 智能请求分配、自动冷却、会话健康监控
- 📊 **用量分析** — Token 消耗跟踪、成本估算、速率限制监控
- 🔒 **加密存储** — AES-256 加密本地存储所有凭证
- 🌍 **多语言** — 英语、中文、俄语界面

### 安装

```bash
git clone https://github.com/Nexus-god/nexusai-manager.git
cd nexusai-manager
npm install
npm run dev
```

> 💡 **AI辅助安装:** 将上面的命令复制到您的 AI 编程助手中（Cursor、Claude Code、Windsurf），它会自动处理一切。

---

<a name="русский"></a>

## 🇷🇺 Русский

### О проекте

NexusAI Tools — полнофункциональное десктопное приложение для разработчиков и AI-энтузиастов. Объединяет управление множеством аккаунтов, конвертацию протоколов и интеллектуальную маршрутизацию запросов в стабильный, быстрый и бюджетный **локальный AI-шлюз**.

Приложение конвертирует Web-сессии (Google/Anthropic) в стандартизированные API-интерфейсы, устраняя барьеры между провайдерами.

### Возможности

- 🎛️ **Умная панель** — Мониторинг всех аккаунтов в реальном времени: квоты Gemini Pro, Flash, Claude
- 🔄 **Мультиаккаунт** — Переключение между аккаунтами в один клик с авторотацией сессий
- 🌐 **Конвертация протоколов** — Web-сессии Google/Anthropic → стандартный OpenAI-совместимый API
- 🛡️ **Стабильность** — Умное распределение запросов, автоматический кулдаун, мониторинг здоровья сессий
- 📊 **Аналитика** — Отслеживание токенов, оценка затрат, мониторинг лимитов
- 🔒 **Шифрование** — AES-256 для всех учётных данных
- 🌍 **Мультиязычность** — Английский, китайский, русский

### Установка

```bash
git clone https://github.com/Nexus-god/nexusai-manager.git
cd nexusai-manager
npm install
npm run dev
```

> 💡 **Установка через AI:** Скопируйте команды выше в ваш AI-ассистент (Cursor, Claude Code, Windsurf) — он всё сделает автоматически.

---

## 📁 Project Structure

```
nexusai-manager/
├── src/                  # React frontend
│   ├── components/       # UI components
│   ├── pages/           # Application pages
│   ├── stores/          # Zustand state management
│   ├── utils/           # Utilities & helpers
│   └── i18n/            # Internationalization
├── src-tauri/           # Rust backend (Tauri)
│   ├── src/
│   │   ├── modules/     # Core modules
│   │   └── main.rs      # Entry point
│   └── Cargo.toml
├── docs/                # Documentation
├── assets/              # Static assets
├── locales/             # Language files
└── package.json
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first.

## License

[CC-BY-NC-SA-4.0](LICENSE)

---

<div align="center">

**Made with ❤️ by NexusAI Team**

[Report Bug](https://github.com/Nexus-god/nexusai-manager/issues) · [Request Feature](https://github.com/Nexus-god/nexusai-manager/issues)

</div>
