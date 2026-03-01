<p align="center">
  <img src="https://raw.githubusercontent.com/Bradley-Hunter/vellum-releases/main/icon.png" alt="Vellum" width="128" height="128" />
</p>

<h1 align="center">Vellum</h1>

<p align="center">
A modern, privacy-focused desktop web browser built with Electron, React, and TypeScript.
</p>

<p align="center">
  <a href="https://github.com/Bradley-Hunter/vellum-releases/releases/latest">
    <img src="https://img.shields.io/github/v/release/Bradley-Hunter/vellum-releases?label=latest&style=flat-square" alt="Latest Release" />
  </a>
  <a href="https://github.com/Bradley-Hunter/vellum-releases/releases">
    <img src="https://img.shields.io/github/downloads/Bradley-Hunter/vellum-releases/total?style=flat-square" alt="Downloads" />
  </a>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue?style=flat-square" alt="Platforms" />
</p>

---

## Download

Go to the [latest release](https://github.com/Bradley-Hunter/vellum-releases/releases/latest) and download the installer for your platform:

| Platform | File |
|----------|------|
| Windows  | `vellum-x.x.x-setup.exe` |
| macOS    | `vellum-x.x.x.dmg` |
| Linux    | `vellum-x.x.x.AppImage` / `.deb` / `.snap` |

Vellum includes built-in auto-updates — once installed, you'll be notified when new versions are available.

## Features

**Tabbed Browsing with Workspaces** — Organize your tabs into named workspaces. Create, rename, and switch between workspaces to keep browsing sessions separate and focused.

**Split-Pane Tiling** — View two pages side-by-side with vertical or horizontal split panes. Great for reference material, comparisons, or multitasking.

**Bookmarks & Folders** — Save, organize, and search bookmarks. Create folders, drag-and-drop to rearrange, and quickly bookmark the current page with `Ctrl+D`.

**Browsing History** — Search and browse your recent history. Clear it anytime.

**Cloud Sync** — Optionally create an account to sync bookmarks, history, and settings across devices. See what tabs are open on your other machines.

**Site Permissions** — Granular per-site control over camera, microphone, geolocation, notifications, screen sharing, clipboard, and more.

**Built-in Text Editor** — A lightweight editor accessible at `vellum://editor` with open, save, and save-as support.

**Session Persistence** — Your workspaces, tabs, and window state are saved automatically and restored on launch.

## System Requirements

- **Windows** 10 or later (x64)
- **macOS** 11 (Big Sur) or later
- **Linux** — Ubuntu 20.04+, Fedora 33+, or equivalent (x64)

## Reporting Bugs & Pain Points

Found something broken or frustrating? [Open an issue](https://github.com/Bradley-Hunter/vellum-releases/issues/new) using one of the templates below.

### Before You Report

1. **Update to the latest version.** Your issue may already be fixed. Check your version in the About panel.
2. **Search [existing issues](https://github.com/Bradley-Hunter/vellum-releases/issues)** to avoid duplicates. If yours already exists, add a thumbs-up reaction and leave a comment with any extra details.

---

### Bug Report Template

Use this format when something is broken or not working as expected. Copy the template below into your issue body.

```
**Vellum Version:** (e.g. 0.10.8)
**OS:** (e.g. Windows 11, macOS 14 Sonoma, Ubuntu 24.04)
**Install Method:** (installer, AppImage, .deb, .snap, .dmg)

### Description
A clear, concise summary of the bug.

### Steps to Reproduce
1. Go to '...'
2. Click on '...'
3. Scroll down to '...'
4. Observe '...'

### Expected Behavior
What you expected to happen.

### Actual Behavior
What actually happened instead.

### Screenshots / Recordings
If applicable, drag and drop images or screen recordings here.

### Additional Context
Any other relevant details — error messages, URLs that trigger the issue,
whether it happens every time or only sometimes, etc.
```

**Title format:** Prefix with **\[Bug\]** and use a short, specific description.

| Good Title | Bad Title |
|---|---|
| [Bug] Bookmarks disappear after renaming a workspace | Bug with bookmarks |
| [Bug] Split pane does not resize below 300px | UI is broken |
| [Bug] Cloud sync fails silently on slow connections | Sync doesn't work |

---

### Pain Point Template

A pain point isn't a bug — it's something that works but feels slow, confusing, or awkward. These reports are just as valuable. Copy the template below into your issue body.

```
**Vellum Version:** (e.g. 0.10.8)
**OS:** (e.g. Windows 11, macOS 14 Sonoma, Ubuntu 24.04)

### What I Was Trying to Do
Describe the task or goal you had in mind.

### What Made It Difficult
Explain what about the current experience was frustrating or inefficient.

### Suggested Improvement (Optional)
If you have an idea for how it could be better, describe it here.

### Screenshots / Recordings
If applicable, drag and drop images or screen recordings here.
```

**Title format:** Prefix with **\[Pain Point\]** (e.g. `[Pain Point] No way to reorder bookmarks without drag-and-drop`).

---

### General Tips

- **One issue per report.** Don't combine multiple problems into a single issue.
- **Be specific.** "It crashes when I press Ctrl+D on a `file://` URL" is actionable. "It crashes sometimes" is not.
- **Include the URL if relevant.** Some issues only happen on certain sites.
- **Mention frequency.** Does it happen every time, or only occasionally?

## License

This project is licensed under the [GPL-3.0 License](LICENSE).
