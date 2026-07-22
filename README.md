# ie-SRA // Wallet Pitch

**Intelligent Energy – Simulation | Reconnaissance | Analytics**
A single-file, mobile-optimized pitch card for the Navy's AI-powered energy readiness platform.

---

## What It Is

A self-contained HTML wallet brief designed to be shared at the speed of a hallway conversation. Scan the QR code, tap the demo link, or forward the URL — no app, no install, no CDN required.

Built to support rapid stakeholder engagement for the ie-SRA (Intelligent Energy – Simulation | Reconnaissance | Analytics) platform across Navy installations.

---

## Live Demo

**[thompsonryane-collab.github.io/ie-SRA](https://thompsonryane-collab.github.io/ie-SRA)**

Short link: [bit.ly/4gibQn2](https://bit.ly/4gibQn2)

---

## What's Inside

| Element | Description |
|---|---|
| **Header** | One-line value prop tied to Navy AI Strategy FY27 milestones |
| **QR Code** | Base64-embedded — no external image dependency |
| **Demo Button** | Deep-links to live SimReconMobile prototype |
| **Share Button** | Native share sheet on mobile, clipboard fallback on desktop |
| **Telemetry Strip** | Status, deploy time, and FY27 alignment at a glance |
| **Use Cases** | Energy Resilience Modeling, Predictive Maintenance, Reporting & Briefings, Cost & Schedule Risk, Compliance Automation |
| **Advantages** | Zero CDN Deps · Air-Gap Ready · No Vendor Lock-In · Deploy <1 Day |
| **Live Clock** | Real-time ET timestamp in the chrome bar |

---

## Architecture

```
walletPitch.html   ← entire app (HTML + CSS + JS, one file)
```

Single-file architecture means:
- Zero build process
- Deploy by uploading one file
- Works offline after first load
- Air-gap compatible

---

## Deployment

1. Rename `walletPitch.html` → `index.html`
2. Upload to your GitHub repo via **Add file → Upload files**
3. Enable GitHub Pages (Settings → Pages → Deploy from `main` branch root)
4. Done — live in under a minute

No dependencies. No npm. No config.

---

## FY27 Alignment

ie-SRA is designed to satisfy all Navy AI Strategy FY27 milestones:

- Rapid deployment to any installation (<1 day)
- AI-assisted energy resilience and readiness reporting
- Predictive analytics for maintenance and cost risk
- Compliance automation for energy reporting requirements

---

## Status

| Base | Status |
|---|---|
| NB San Diego | 🟢 LIVE |
| NS Norfolk | 🟢 LIVE |

---

## Contact

Built by the ie-SRA team. For demo access or integration inquiries, use the share link above or scan the QR code on the pitch card.

---

*UNCLASSIFIED // MISSION-READY AI*
