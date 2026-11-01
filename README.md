# Share97 Worker: Desktop Social Media Publishing App for Windows, macOS and Linux

**[Share97](https://share97.com) Worker** is a free desktop app that publishes your scheduled social media posts from your own computer. Sign in to Instagram, TikTok, X, LinkedIn, Facebook, YouTube, Pinterest, Threads and Reddit, keep each session on your device, and let your [Share97](https://share97.com) workflows post in the background.

[**Download Share97 Worker**](https://share97.com/download) · [Share97 website](https://share97.com) · [API and MCP docs](https://share97.com/docs) · [Latest release](https://github.com/share97-com/share97-worker/releases/latest)

## Download

Current version: **0.2.0**

| Operating system | Installer | Size | Version |
|---|---|---|---|
| Windows 10/11 (x64) | [Share97-Worker-0.2.0-win-x64.exe](https://github.com/share97-com/share97-worker/releases/download/v0.2.0/Share97-Worker-0.2.0-win-x64.exe) | 126 MB | 0.2.0 |
| macOS (Apple Silicon) | [Share97-Worker-0.2.0-mac-arm64.dmg](https://github.com/share97-com/share97-worker/releases/download/v0.2.0/Share97-Worker-0.2.0-mac-arm64.dmg) | 133 MB | 0.2.0 |
| macOS (Intel) | [Share97-Worker-0.2.0-mac-x64.dmg](https://github.com/share97-com/share97-worker/releases/download/v0.2.0/Share97-Worker-0.2.0-mac-x64.dmg) | 137 MB | 0.2.0 |
| Linux (AppImage) | [Share97-Worker-0.2.0-linux-x86_64.AppImage](https://github.com/share97-com/share97-worker/releases/download/v0.2.0/Share97-Worker-0.2.0-linux-x86_64.AppImage) | 139 MB | 0.2.0 |
| Linux (Debian, Ubuntu) | [Share97-Worker-0.2.0-linux-amd64.deb](https://github.com/share97-com/share97-worker/releases/download/v0.2.0/Share97-Worker-0.2.0-linux-amd64.deb) | 105 MB | 0.2.0 |

Checksums are in [`SHA256SUMS`](https://github.com/share97-com/share97-worker/releases/download/v0.2.0/SHA256SUMS). All versions are on the [releases page](https://github.com/share97-com/share97-worker/releases).

> Installers are not code signed yet. Windows SmartScreen and macOS Gatekeeper may warn on first launch. On macOS, right-click the app and choose **Open**.

## Supported social media platforms

Add several profiles per platform. Each profile keeps its own login cookies.

- Instagram
- TikTok
- X (Twitter)
- LinkedIn
- Facebook
- YouTube
- Pinterest
- Threads
- Reddit

## What you can do

- **Schedule and auto-post from your computer.** Choose a Worker account in a [Share97 workflow](https://share97.com/workflows) and it publishes in the background, from the system tray.
- **Manage multiple accounts.** Keep several profiles on the same platform, with separate sessions.
- **Publish through the API.** Send posts with the [Share97 REST API or MCP server](https://share97.com/docs) to accounts signed in on your device.
- **Use a browser AI agent.** Write an instruction on a workflow node. Worker opens the profile in a browser window and a LangChain agent carries out the task. It uses your own [api14](https://api14.com) key, entered by hand or through the api14 connector.
- **Point it at your own server.** The server address defaults to `https://share97.com` and can be changed in the app.

## Getting started

1. Install Share97 Worker for your operating system.
2. Click **Connect to Share97** and approve in your browser, or paste a Share97 API key.
3. Pick a platform, then sign in on its own login page.
4. Select the account in a [workflow](https://share97.com/workflows) or use it through the [API](https://share97.com/docs).

Keep the app running: posts sent while it is closed fail with an `offline` error instead of waiting.

## Privacy

- Login cookies stay on your device and are never sent to Share97.
- API keys are encrypted with your operating system's keychain.
- With the AI agent, page content from the account being operated is sent to the model you choose through api14.

## Good to know

- Worker posts through a browser session using your account. Some platforms forbid automation and may restrict accounts that use it. Accounts connected through the official API on [Share97](https://share97.com) do not carry this risk.
- Worker does not bypass sign-in, captcha or identity checks. It stops and asks you to sign in again.
- Platform pages change over time, so an individual publishing step can break until an update ships.
- This repository hosts installers and release notes. It does not contain the source code.

## FAQ

**Is Share97 Worker free?**
The download is free. Limits on your [Share97 plan](https://share97.com/billing) still apply, and AI agent model usage is billed to your own api14 account.

**Do I need Share97 Worker to use Share97?**
No. Worker is optional. You can also [connect accounts through official APIs](https://share97.com/accounts).

**Where are my passwords stored?**
Worker never asks for your passwords. You sign in on each platform's own page, and only the resulting session stays on your device.

**Can I add more than one account on the same platform?**
Yes, within your plan's account limit.

## Türkçe

**Share97 Worker**, planlı sosyal medya paylaşımlarını kendi bilgisayarından yapan masaüstü uygulamasıdır. Instagram, TikTok, X, LinkedIn, Facebook, YouTube, Pinterest, Threads ve Reddit hesaplarını bağla, her profilin oturumu cihazında kalsın. [Share97'den indir](https://share97.com/download).

---

Share97: [share97.com](https://share97.com)
