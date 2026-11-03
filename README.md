# Share97 Worker: Desktop Social Media Automation App for Windows, macOS and Linux

**[Share97](https://share97.com) Worker** is a free desktop app that runs your scheduled social media posts from your own computer. Sign in to Instagram, TikTok, X, LinkedIn, Facebook, YouTube, Pinterest, Threads and Reddit, keep each session on your device, and let a LangChain AI agent post, pull data and handle follow actions in the background.

[**Download Share97 Worker**](https://share97.com/download) · [Share97 website](https://share97.com) · [Latest release](https://github.com/share97-com/share97-worker/releases/latest)

## Download

Current version: **0.5.0** (Windows). macOS and Linux builds of 0.5.0 are coming; until then the 0.3.0 installers below are the latest for those systems.

| Operating system | Installer | Size | Version |
|---|---|---|---|
| Windows 10/11 (x64) | [Share97-Worker-0.5.0-win-x64.exe](https://github.com/share97-com/share97-worker/releases/download/v0.5.0/Share97-Worker-0.5.0-win-x64.exe) | 127 MB | 0.5.0 |
| macOS (Apple Silicon) | [Share97-Worker-0.3.0-mac-arm64.dmg](https://github.com/share97-com/share97-worker/releases/download/v0.3.0/Share97-Worker-0.3.0-mac-arm64.dmg) | 133 MB | 0.3.0 |
| macOS (Intel) | [Share97-Worker-0.3.0-mac-x64.dmg](https://github.com/share97-com/share97-worker/releases/download/v0.3.0/Share97-Worker-0.3.0-mac-x64.dmg) | 137 MB | 0.3.0 |
| Linux (AppImage) | [Share97-Worker-0.3.0-linux-x86_64.AppImage](https://github.com/share97-com/share97-worker/releases/download/v0.3.0/Share97-Worker-0.3.0-linux-x86_64.AppImage) | 139 MB | 0.3.0 |
| Linux (Debian, Ubuntu) | [Share97-Worker-0.3.0-linux-amd64.deb](https://github.com/share97-com/share97-worker/releases/download/v0.3.0/Share97-Worker-0.3.0-linux-amd64.deb) | 107 MB | 0.3.0 |

SHA-256 of the Windows 0.5.0 installer: `3e8aafcd412e7f4c25dda0bf00ca4841b5282c267a0b9be8fdfd93f64ddb3eb9`. Checksums for 0.3.0 are in [`SHA256SUMS`](https://github.com/share97-com/share97-worker/releases/download/v0.3.0/SHA256SUMS). All versions are on the [releases page](https://github.com/share97-com/share97-worker/releases).

> Installers are not code signed yet. Windows SmartScreen and macOS Gatekeeper may warn on first launch. On macOS, right-click the app and choose **Open**.

Installed apps update themselves: Worker checks for a new version every six hours, downloads it in the background and installs it when no job is running.

## What's new in 0.5.0

- **Workflows page.** All your Share97 workflows on their own page: turn auto-posting on or off, choose the Worker that runs each workflow, run one now, and see upcoming slots and recent runs. Editing opens the Share97 workflow editor.
- **Workers page.** Every device connected to your Share97 account, marked online or offline, with its accounts and the workflows that run on it. Accounts connected through the official API are listed too. The same view is on [share97.com/workers](https://share97.com/workers).
- **Workers per workflow.** An account added in Worker belongs to that device. A workflow can be assigned to one Worker, and then only that device's accounts can be used in it.
- **15 languages.** The app and its menus follow your system language, like the Share97 website: English, Turkish, German, Spanish, French, Italian, Dutch, Polish, Swedish, Portuguese, Hindi, Indonesian, Korean, Japanese and Arabic.

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

- **Control your workflows.** See your [Share97 workflows](https://share97.com/workflows), upcoming posts and recent runs. Turn auto-posting on or off, pick the Worker that runs a workflow, or run it now.
- **See every connection.** The Workers page lists each of your computers, its accounts and its workflows, plus accounts that publish from the server through the official API.
- **Post with an AI agent.** Worker opens the profile in a browser window and a LangChain agent does the work, using models from [api14](https://api14.com).
- **Pull data and manage follows.** Ask the agent for account data or follower lists, or to follow or unfollow up to 20 accounts per task.
- **Keep the computer running.** With your approval, Worker turns off sleep and the screen-off timer, keeps a laptop running with its lid closed and starts with the computer. One button restores your previous settings.
- **Manage multiple accounts.** Keep several profiles on the same platform, with separate sessions.
- **Point it at your own server.** The server address defaults to `https://share97.com` and can be changed in the app.

## Getting started

1. Install Share97 Worker for your operating system.
2. Click **Sign in with Share97** and approve in your browser. Your computer now appears as a Worker on [share97.com/workers](https://share97.com/workers).
3. Optional: in **AI Agent**, click **Connect with api14** and approve in your browser. The agent needs it to post and run tasks.
4. Choose whether to prepare the computer to keep running.
5. In **Accounts on this device**, pick a platform and sign in on its own login page. The window then opens your profile.
6. Select the account in a [workflow](https://share97.com/workflows), and optionally assign the workflow to this Worker on the **Workflows** page.

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

**What is a Worker?**
Each computer signed in to Share97 Worker is one Worker. Accounts you add in the app belong to that computer, and workflows that use them publish from it.

**Can I run Worker on several computers?**
Yes. Each one shows up separately on the Workers page. Assign a workflow to the computer that holds its accounts.

**Where are my passwords stored?**
Worker never asks for your passwords. You sign in on each platform's own page, and only the resulting session stays on your device.

**Can I add more than one account on the same platform?**
Yes, within your plan's account limit.

**Can I undo the power settings?**
Yes. Press **Restore previous settings** in the app's Settings before you uninstall it.

## Türkçe

**Share97 Worker**, planlı sosyal medya paylaşımlarını kendi bilgisayarından yapan masaüstü uygulamasıdır. Instagram, TikTok, X, LinkedIn, Facebook, YouTube, Pinterest, Threads ve Reddit hesaplarını bağla, her profilin oturumu cihazında kalsın. Paylaşım, veri çekme ve takip işlerini LangChain ajanı yapar. 0.5.0 ile **Akışlar** (aç/durdur, Worker seç, şimdi çalıştır) ve **Worker'lar** (bütün cihazlar ve bağlantıları) ayrı sayfalarda; uygulama sitenin on beş dilinde. [Share97'den indir](https://share97.com/download).

---

Share97: [share97.com](https://share97.com)
