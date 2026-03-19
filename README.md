<div align="center">

<img src="https://img.shields.io/badge/AnymeX-Beta-FF6B35?style=for-the-badge&labelColor=0D0D0D" height="36"/>

# AnymeX β

**Distribution repository for beta builds of [AnymeX](https://github.com/RyanYuuki/AnymeX)**

[![Main Repo](https://img.shields.io/badge/Main%20Repo-RyanYuuki%2FAnymeX-5865F2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RyanYuuki/AnymeX)
[![Beta Repo](https://img.shields.io/badge/Beta%20Repo-Shebyyy%2FAnymeX--Preview-FF6B35?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shebyyy/AnymeX-Preview)

[![Latest Release](https://img.shields.io/github/v/release/Shebyyy/AnymeX-Preview?style=for-the-badge&label=Beta%20Release&color=FF6B35)](https://github.com/Shebyyy/AnymeX-Preview/releases/latest)

</div>

---

## What is this repo?

This repository **only exists to distribute beta builds** of AnymeX. No development, issues, or contributions happen here.

Beta builds are automatically generated from the main repository with a few key differences to allow **side-by-side installation** with the stable version:

| Property | Stable | Beta |
|---|---|---|
| **App Name** | AnymeX | AnymeX β|
| **Logo** | Default | Distinct beta logo |
| **Package Name** | `com.ryan.anymex` | `com.ryan.anymexbeta` |

> [!CAUTION]
> Beta builds may be unstable or contain bugs. Use at your own risk.

---

## Fork Setup (important)

If you fork this repository and run the workflows in your own repo:

1. **You do not need to rename workflow secrets.**  
   Keep the same secret names used in `.github/workflows/*.yml` (for example: signing keys, API keys, webhook tokens).
2. **Set a repository variable** named `MAIN_SOURCE_REPO` to the main app source repo you want to build from (format: `owner/repo`).  
   - Default is `RyanYuuki/AnymeX` if the variable is not set.
3. Workflows that use `${{ github.repository }}` already point to your fork automatically for releases, tags, and artifacts.

> [!TIP]
> In your fork, go to **Settings → Secrets and variables → Actions → Variables** and add:
> - `MAIN_SOURCE_REPO=owner/repo`

---

## Downloads

| Channel | Description | Link |
|---|---|---|
| **Stable** | Recommended for most users | [![Stable Release](https://img.shields.io/github/v/release/RyanYuuki/AnymeX?style=flat-square&label=Download&color=5865F2)](https://github.com/RyanYuuki/AnymeX/releases/latest) |
| **Beta** | Latest test builds | [![Beta Release](https://img.shields.io/github/v/release/Shebyyy/AnymeX-Preview?style=flat-square&label=Download&color=FF6B35)](https://github.com/Shebyyy/AnymeX-Preview/releases/latest) |

---

## Main Project

All source code, development, issues, and contributions live in the main repository:

<div align="center">

**[RyanYuuki/AnymeX](https://github.com/RyanYuuki/AnymeX)**

*Please open issues, feature requests, and pull requests there, not here.*
