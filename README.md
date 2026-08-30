# Hi, I'm Berkay 👋

**Systems & Infrastructure | Microsoft, Linux & Endpoint Automation**

I work in enterprise IT with a focus on identity, endpoint operations, software deployment, troubleshooting, and automation. Outside of work, I build and operate infrastructure and tooling projects around Proxmox VE, Linux, containers, networking, backup/recovery, and reproducible system configuration.

I like systems I can understand, rebuild, and automate.

## Featured Projects

### [Proxmox Homelab Automation](https://github.com/Yakrel/proxmox-homelab-automation)
My main infrastructure project: a personal Proxmox VE environment spanning **7 unprivileged LXC containers** for gateway, media, utility, desktop, AI, development, and gaming workloads.

It includes configuration-driven LXC provisioning, Docker Compose deployment, segmented firewall rules, shared NVIDIA GPU access, ZFS snapshots, encrypted Restic/Backrest backups with rclone replication, Cloudflare/Tailscale access paths, and custom container images built through GitHub Actions.

**Stack:** Proxmox VE · Linux · LXC · Docker Compose · ZFS · Bash · GitHub Actions · Cloudflare Tunnel · Tailscale

### [AI Dikte](https://github.com/Yakrel/ai-dikte)
Cross-platform voice dictation for **Windows 10/11** and Linux desktops including **KDE Plasma, Hyprland, and Omarchy**.

A toggle hotkey streams audio to Gemini Transcribe Live and injects the finalized transcription directly into the focused field without reading or modifying the clipboard. Windows uses Unicode `SendInput`; Linux selects the appropriate Wayland typing backend for the active desktop. Windows releases are built and runtime-tested in GitHub Actions.

**Stack:** Python · Win32 SendInput · PipeWire · Wayland · PowerShell/Bash · GitHub Actions · Gemini API

### [NixOS System-as-Code Configuration](https://github.com/Yakrel/nixos-config)
A reproducible NixOS workstation configuration built around declarative packages, services, desktop settings, and version-controlled system state.

The repository includes flake-based dependency management, a guarded fresh-install path, rollback/change-control workflows, VPN services, browser tooling, and workstation rebuilds from source-controlled configuration.

**Stack:** NixOS · Nix Flakes · KDE Plasma · systemd · Git

## Other Public Projects

- **[Windows Postsetup Updater](https://github.com/Yakrel/windows-postsetup-updater)** — Zero-dependency Go utility that discovers and verifies upstream Windows installer updates, performs atomic downloads, preserves local license files, and publishes standalone Windows/Linux binaries through GitHub Actions.
- **[Wabbajack Library Cleaner](https://github.com/Yakrel/wabbajack-library-cleaner)** — Cross-platform tool for finding orphaned and outdated Wabbajack downloads, with preview, recoverable deletion, native Windows/Linux binaries, and a public web frontend.
- **[JDownloader Download Interceptor](https://github.com/Yakrel/jdownloader-download-interceptor)** — Manifest V3 Chromium extension that can route a download to a trusted JDownloader instance while preserving the browser's original download path when requested.
- **[Repackarr](https://github.com/Yakrel/repackarr)** — Self-hosted qBittorrent/Transmission + Prowlarr companion for monitoring, reviewing, and optionally downloading newer game-repack releases.
- **[Kur'an - Ayet Ezberle](https://github.com/Yakrel/kuran-ayet-ezberle)** — Native Android Quran memorization app built with Kotlin, Jetpack Compose, Media3, Room, Hilt, and background download/update workflows.
- **[Desktop OTP Gate](https://github.com/Yakrel/desktop-otp-gate)** — A maintained adaptation of `simple-nginx-otp` for Nginx `auth_request`, with shorter session controls, stronger cookie defaults, rate limiting, and a custom login UI.
- **[Omarchy ISO Build Fork](https://github.com/Yakrel/omarchy-iso)** — Personal fork used to pin custom ISO builds to selected upstream Omarchy revisions and automate build/release cleanup while staying synchronized with upstream development.

## Maintained Container Images

- **[docker-desktop-workspace](https://github.com/Yakrel/docker-desktop-workspace)** — Browser-accessible Debian Trixie Wayland desktop with Brave, Obsidian, Tasks.org, Labwc, and Selkies.
- **[docker-backrest-rclone](https://github.com/Yakrel/docker-backrest-rclone)** — Backrest image extended with rclone and scheduling support for automated backup replication workflows.

Images are published under [`ghcr.io/yakrel`](https://github.com/Yakrel?tab=packages).

## Professional & Project Focus

| Area | Technologies / Practices |
| :--- | :--- |
| **Identity & Endpoint Operations** | Active Directory, Entra ID, Group Policy, ManageEngine, software deployment, troubleshooting and remediation |
| **Virtualization & Containers** | Proxmox VE, LXC, Docker, Docker Compose |
| **Linux & Reproducibility** | NixOS, Arch-based Linux, Debian, Nix Flakes, systemd |
| **Networking & Remote Access** | VLAN/firewall segmentation, Cloudflare Tunnel, Tailscale, reverse proxies, split DNS |
| **Storage & Backup** | ZFS, Sanoid, Restic/Backrest, rclone |
| **Automation & Delivery** | Bash, PowerShell, Python, Go, Git, GitHub Actions |

## Links

[Portfolio / CV](https://cv.byetgin.com) · [LinkedIn](https://www.linkedin.com/in/berkayyetgin) · [Email](mailto:berkay.yetgin@outlook.com)
