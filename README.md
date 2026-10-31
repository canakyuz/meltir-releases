<p align="center">
  <img src="assets/meltir-banner.webp" alt="MELTIR Hive, your own team of AI bots on your Mac" width="100%">
</p>

# MELTIR Hive

Your own team of AI bots, in one window on your Mac. Every bot in the sidebar is a real agent with its own name, face, instructions and project. Talk to them like contacts, watch them work, approve what matters.

Hive is invite-only for now. This repository holds the builds and the update feed.

## What you get

- **A roster of bots.** Each bot keeps one running conversation, its own instructions and the project it works in. Pin, hide, duplicate or edit them like chats.
- **Pick an engine per bot.** Bots run on the agent CLIs already on your Mac: Claude Code, Codex or Grok Build. Your existing logins and subscriptions, no proxy in the middle.
- **Bots ask before they act.** Shell commands, file edits and questions show up as cards in the chat: allow, deny or answer.
- **A plain chat on the home page.** The box on the Hive home page starts a normal conversation when you do not need a bot.
- **Local first.** Bots, conversations and files stay on your computer. The MELTIR account is only used to sign in.

## Get access

1. **Get an invite.** Hive accounts are created by invitation. Ask for one at [meltir.wesan.co](https://meltir.wesan.co); you will receive a personal invite link for your email address.
2. **Set your password.** Open the invite link, choose a password and confirm. The link works once and expires.
3. **Install MELTIR** (next section) and open it.
4. **Sign in.** Click **Sign in**. The sign-in page opens in your browser; enter your email and password. When it finishes you are sent back to the app and Hive opens.

## Download

1. Open the [latest release](https://github.com/canakyuz/meltir-releases/releases/latest) and download `MELTIR-<version>-arm64.dmg`.
2. Open the DMG and drag **MELTIR** to Applications.

| | |
|---|---|
| System | macOS 12+ on Apple Silicon |
| Signing | Signed and notarized |
| Windows, Linux, Intel Macs | Not published |

## Set up an engine

Bots need at least one agent CLI installed and logged in on your Mac:

| Engine | Install |
|---|---|
| Claude Code | [claude.com/claude-code](https://claude.com/claude-code) |
| Codex | [github.com/openai/codex](https://github.com/openai/codex) |
| Grok Build | [x.ai/cli](https://x.ai/cli) |

Install the CLI, run it once in Terminal and log in with your own account.

Installed engines show up in the engine picker when you create a bot.

## Updates

MELTIR updates itself from this repository, so there is no need to download each version by hand. Pre-release builds (`-beta`) reach installs that are already on a beta.

## Privacy

Your bots, their conversations and their files live in MELTIR's folder on your Mac. The MELTIR server only holds your account (email, password hash and what your account can open). Engine logins stay with the CLIs themselves.

## Help

Signing out, an expired session or a lost invite: write from [meltir.wesan.co](https://meltir.wesan.co). Your files and conversations stay on your Mac when you sign out.
