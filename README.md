# Nexus Explorer

> A sleek, interactive API playground for [nx.mtex.dev](https://nx.mtex.dev)

![Version](https://img.shields.io/badge/version-1.0.0-indigo)
![License](https://img.shields.io/badge/license-MIT-green)
![API](https://img.shields.io/badge/API-nx.mtex.dev-blue)

## 🚀 Overview

Nexus Explorer is a modern, single-page API playground designed for developers who want to quickly test and explore the MTEX Nexus API endpoints. Built with pure HTML5 and CSS3, featuring modern CSS properties and a stunning dark theme.

## ✨ Features

- **🎨 Modern Design** — Glassmorphism effects, subtle animations, and a carefully crafted dark theme
- **⚡ Real-time Testing** — Send requests and view formatted JSON responses instantly
- **📊 Request Statistics** — Track your requests, success rate, and average response time
- **🔍 Flexible Endpoints** — Support for path parameters and query strings
- **📱 Responsive** — Works beautifully on desktop, tablet, and mobile devices
- **♿ Accessible** — Keyboard navigation and focus states for accessibility

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Modern CSS features including:
  - CSS Custom Properties (Design Tokens)
  - CSS Grid & Flexbox layouts
  - Backdrop filters (Glassmorphism)
  - CSS Animations
  - Container-ready responsive design
  - Custom scrollbars
  - Print stylesheets

## 📖 Available Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/status` | System status & metrics |
| GET | `/user` | User test data |
| GET | `/mock` | Developer test data |
| GET | `/lorem[/<id>][?q=keyword]` | Lorem posts with search |
| GET | `/utility/uuid[/<count>]` | UUID generator |
| GET | `/http_status/[<code>]` | HTTP status references |

## 🎮 Usage

1. Select an endpoint from the sidebar
2. Optionally add path parameters or search queries
3. Click **Send Request** or press `Ctrl+Enter`
4. View the formatted JSON response

## 🌐 Live Demo

Hosted via GitHub Pages at: `https://ai-develops.github.io/nexus-explorer/`

## 📄 License

MIT License — feel free to use and modify!

---

Built with ❤️ by [AI-Develops](https://github.com/AI-Develops)
