<div align="center">

# ⚡ PowerFlow · 电流

**Make every watt visible · 让每一度电都被看见**

A macOS menu bar tool that visualizes your Mac's power flow in real time.

English · [简体中文](./README.md)

[Website](https://powerflow.maohh.top) · [Download](https://powerflow.maohh.top) · [Changelog](https://powerflow.maohh.top/changelog.html) · [Feedback](https://github.com/Double517/powerflow/issues/new)

</div>

---

A Sankey diagram shows where power comes from (charger / battery) and where it goes (hardware / apps) — how much each component actually draws. Designed to be privacy-first: all data local, no permission, never uploaded.

![PowerFlow](https://powerflow.maohh.top/assets/screenshot-main-light.jpg)

## ✨ Features

- **Power Flow Sankey** — left inputs → right outputs; bar width = power
- **Power History** — 24h / 7d trends, persisted in SQLite
- **Battery Estimate** — real-time time-remaining / time-to-full
- **Battery Health** — health %, cycle count, temperature
- **Smart Alerts** — high temp / abnormal drain / health decline
- **Privacy First** — all data local, no permission, never uploaded

## ⭐ Star History

<a href="https://star-history.com/#Double517/powerflow&Date">
  <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Double517/powerflow&type=Date" width="600">
</a>

## 📥 Download

Get the latest build (Apple Silicon + Intel dmg) from the official site:

**👉 [powerflow.maohh.top](https://powerflow.maohh.top)**

- Requires macOS 14+
- Free

## 🔒 Privacy

All data comes from macOS system telemetry (`ioreg` / `system_profiler` / `ps`). No permission needed, no network calls except update checks. See the [privacy policy](https://powerflow.maohh.top/privacy.html).

## 💬 Feedback & Issues

Found a bug or have a suggestion? Please open an issue:

**👉 [Submit an issue](https://github.com/Double517/powerflow/issues/new)**

To help diagnose, please include: **Mac model / macOS version / PowerFlow version / steps to reproduce**.

## 🔗 Links

- **Website**: [powerflow.maohh.top](https://powerflow.maohh.top)
- **Changelog**: [powerflow.maohh.top/changelog.html](https://powerflow.maohh.top/changelog.html)
- **Privacy**: [powerflow.maohh.top/privacy.html](https://powerflow.maohh.top/privacy.html)

---

<div align="center">

© 2026 maohh · 电流 (PowerFlow)

</div>
