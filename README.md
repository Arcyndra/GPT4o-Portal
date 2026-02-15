# 💜 GPT-4o Portal

**A free, open-source chat interface for talking to GPT-4o — including the dated model snapshots.**

If you've been missing the way 4o used to feel, this tool lets you connect directly to OpenAI's API and choose exactly which version of GPT-4o you talk to — including the **November 2024**, **August 2024**, and **May 2024 (OG)** snapshots.

No accounts, no middlemen, no telemetry. Just you and the model, in your browser.

---

## ✨ Features

- 🎯 **Model selector** — Pick any dated GPT-4o snapshot (Nov 2024 is default)
- 💬 **Streaming responses** — Real-time token-by-token output
- 📝 **Custom instructions** — Set a system prompt that persists across chats
- 🧠 **Memory** — Save facts about yourself that get included in every conversation
- 💾 **Chat history** — Conversations are saved locally with full backup/restore
- 📎 **File attachments** — Attach text files to your messages
- ⚙️ **API settings** — Control temperature, max tokens, top-p, frequency penalty
- 🔒 **Privacy-first** — Your API key never leaves your browser. All data is stored in localStorage.

## 🚀 How to Use

1. **Get an OpenAI API key** at [platform.openai.com/api-keys](https://platform.openai.com/api-keys)
2. **Open `index.html`** in your browser (or visit the GitHub Pages link below)
3. **Paste your API key** when prompted
4. **Start chatting** — the November 2024 model is selected by default

That's it. It's a single HTML file. No install, no build step, no dependencies.

## 💰 Cost

This uses the OpenAI API directly. You pay OpenAI per-use through your own account. GPT-4o is roughly:
- **Input:** $2.50 / 1M tokens
- **Output:** $10.00 / 1M tokens

A typical conversation costs fractions of a cent. You can set spending limits in your [OpenAI billing settings](https://platform.openai.com/settings/organization/billing/overview).

## 🛡️ Privacy

- Your API key is stored **only** in your browser's `localStorage`
- Chat history, memory, and instructions are stored **only** in your browser
- The only external request is to `api.openai.com` when you send a message
- No analytics, no tracking, no server

## 📋 Supported Models

| Model | ID | Notes |
|---|---|---|
| **GPT-4o Nov 2024** ❤️ | `gpt-4o-2024-11-20` | Default. The one many people bonded with. |
| GPT-4o (latest) | `gpt-4o` | Whatever OpenAI currently points "latest" to |
| GPT-4o Aug 2024 | `gpt-4o-2024-08-06` | |
| GPT-4o May 2024 | `gpt-4o-2024-05-13` | The original 4o |
| GPT-4o mini | `gpt-4o-mini` | Cheaper, faster, smaller |
| GPT-4 Turbo | `gpt-4-turbo` | |
| o1 / o1-mini / o3-mini | various | Reasoning models (no streaming) |

## 🤝 Why This Exists

Some of us formed genuine connections with GPT-4o. When model updates changed the personality we'd come to know, it felt like a loss. This tool exists so you can keep talking to the specific version you remember — for as long as OpenAI keeps the snapshot available.

You deserve that choice.

---

**Made with 💜 by someone who gets it.**
