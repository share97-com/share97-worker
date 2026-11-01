# Share97 Worker: Desktop Social Media Automation App for Windows, macOS and Linux

**[Share97](https://share97.com) Worker** is a free desktop app that runs your scheduled social media posts from your own computer. Sign in to Instagram, TikTok, X, LinkedIn, Facebook, YouTube, Pinterest, Threads and Reddit, keep each session on your device, and let a LangChain AI agent post, pull data and handle follow actions in the background.

[**Download Share97 Worker**](https://share97.com/download) · [Share97 website](https://share97.com) · [Latest release](https://github.com/share97-com/share97-worker/releases/latest)

## Download

Current version: **0.3.0**

| Operating system | Installer | Size | Version |
|---|---|---|---|
| Windows 10/11 (x64) | [Share97-Worker-0.3.0-win-x64.exe](https://github.com/share97-com/share97-worker/releases/download/v0.3.0/Share97-Worker-0.3.0-win-x64.exe) | 125 MB | 0.3.0 |
| macOS (Apple Silicon) | [Share97-Worker-0.3.0-mac-arm64.dmg](https://github.com/share97-com/share97-worker/releases/download/v0.3.0/Share97-Worker-0.3.0-mac-arm64.dmg) | 133 MB | 0.3.0 |
| macOS (Intel) | [Share97-Worker-0.3.0-mac-x64.dmg](https://github.com/share97-com/share97-worker/releases/download/v0.3.0/Share97-Worker-0.3.0-mac-x64.dmg) | 137 MB | 0.3.0 |
| Linux (AppImage) | [Share97-Worker-0.3.0-linux-x86_64.AppImage](https://github.com/share97-com/share97-worker/releases/download/v0.3.0/Share97-Worker-0.3.0-linux-x86_64.AppImage) | 139 MB | 0.3.0 |
| Linux (Debian, Ubuntu) | [Share97-Worker-0.3.0-linux-amd64.deb](https://github.com/share97-com/share97-worker/releases/download/v0.3.0/Share97-Worker-0.3.0-linux-amd64.deb) | 107 MB | 0.3.0 |

Checksums are in [`SHA256SUMS`](https://github.com/share97-com/share97-worker/releases/download/v0.3.0/SHA256SUMS). All versions are on the [releases page](https://github.com/share97-com/share97-worker/releases).

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

- **See and control your schedule.** Your [Share97 workflows](https://share97.com/workflows), upcoming posts and recent runs appear in the app. Turn auto-posting on or off, or run a workflow now.
- **Browse bulk contents.** List the contents of your workflows, filtered by workflow or group.
- **Post with an AI agent.** Worker opens the profile in a browser window and a LangChain agent does the work, using models from [api14](https://api14.com).
- **Pull data and manage follows.** Ask the agent for account data or follower lists, or to follow or unfollow up to 20 accounts per task.
- **Keep the computer running.** With your approval, Worker turns off sleep and the screen-off timer, keeps a laptop running with its lid closed and starts with the computer. One button restores your previous settings.
- **Manage multiple accounts.** Keep several profiles on the same platform, with separate sessions.
- **Point it at your own server.** The server address defaults to `https://share97.com` and can be changed in the app.

## Getting started

1. Install Share97 Worker for your operating system.
2. Click **Sign in with Share97** and approve in your browser.
3. Click **Connect with api14** and approve in your browser.
4. Choose whether to prepare the computer to keep running.
5. Pick a platform and sign in on its own login page. The window then opens your profile.
6. Select the account in a [workflow](https://share97.com/workflows).

Keep the app running: posts sent while it is closed fail with an `offline` error instead of waiting.

## Privacy

- Login cookies stay on your device and are never sent to Share97.
- Connection keys are encrypted with your operating system's keychain and are never shown.
- Page content from the account being operated is sent to the model you choose through api14.

## Good to know

- Worker acts through a browser session using your account. Some platforms forbid automation and may restrict accounts that use it, especially for follow actions. Accounts connected through the official API on [Share97](https://share97.com) do not carry this risk.
- Worker does not bypass sign-in, captcha or identity checks. It stops and asks you to sign in again, and it stops when a platform shows a limit or warning.
- Do not put a closed, running laptop in a bag: it can overheat. Some laptops may still enter low power when the lid closes.
- On Linux, always-on only holds while Worker is open, and Worker does not start with the computer.
- This repository hosts installers and release notes. It does not contain the source code.

## FAQ

**Is Share97 Worker free?**
The download is free. Limits on your [Share97 plan](https://share97.com/billing) still apply, and AI model usage is billed to your own api14 account.

**Do I need Share97 Worker to use Share97?**
No. Worker is optional. You can also [connect accounts through official APIs](https://share97.com/accounts).

**Where are my passwords stored?**
Worker never asks for your passwords. You sign in on each platform's own page, and only the resulting session stays on your device.

**Can I add more than one account on the same platform?**
Yes, within your plan's account limit.

**Can I undo the power settings?**
Yes. Press **Restore previous settings** in the app's Settings before you uninstall it.

## Türkçe

**Share97 Worker**, planlı sosyal medya paylaşımlarını kendi bilgisayarından yapan masaüstü uygulamasıdır. Instagram, TikTok, X, LinkedIn, Facebook, YouTube, Pinterest, Threads ve Reddit hesaplarını bağla, her profilin oturumu cihazında kalsın. Paylaşım, veri çekme ve takip işlerini LangChain ajanı yapar. [Share97'den indir](https://share97.com/download).

---

Share97: [share97.com](https://share97.com)
