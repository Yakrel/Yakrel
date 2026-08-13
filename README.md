# Hi, I'm Berkay 👋

**Systems & Infrastructure | Microsoft, Linux & Endpoint Automation**

I work in enterprise IT with a focus on Microsoft identity, endpoint operations, software deployment, troubleshooting, and automation. Outside of work, I build and operate infrastructure projects around Proxmox VE, Linux, containers, networking, backup/recovery, and reproducible system configuration.

My goal is simple: understand how a system behaves, make it repeatable, and remove unnecessary manual work.

## Featured Projects

### [Proxmox Homelab Automation](https://github.com/Yakrel/proxmox-homelab-automation)
My main infrastructure project: a production-style Proxmox homelab running **40+ services across 7 LXC containers**.

It includes configuration-driven provisioning, Docker-in-LXC, unprivileged NVIDIA GPU passthrough, ZFS storage and snapshots, segmented firewall rules, monitoring, encrypted backup replication, Cloudflare/Tailscale access paths, and GitHub Actions-maintained container images.

**Stack:** Proxmox VE · Linux · LXC · Docker Compose · ZFS · Bash · GitHub Actions · Cloudflare · Tailscale · Prometheus/Grafana

### [NixOS System-as-Code Configuration](https://github.com/Yakrel/nixos-config)
A reproducible Linux configuration project built around the operating-system-as-code model rather than a manually maintained desktop.

The repository demonstrates declarative packages and services, flake-based dependency management, guarded fresh installation, rollback/change control, VPN services, browser tooling, and rebuilding a workstation from version-controlled configuration.

**Stack:** NixOS · Nix Flakes · KDE Plasma · systemd · Git

### [Desktop OTP Gate](https://github.com/Yakrel/desktop-otp-gate)
A lightweight TOTP authentication layer for Nginx `auth_request`, adapted for my remote desktop and administrative services.

It adds short-lived authenticated sessions, secure cookie defaults, rate limiting, and a simple browser login flow while keeping the reverse-auth service small and easy to deploy.

**Stack:** Go · Nginx · TOTP · Docker

## Other Public Projects

- **[Gemini Dictation](https://github.com/Yakrel/ai-dikte)** — Minimal KDE Plasma Wayland voice dictation for CachyOS/Arch. Records with PipeWire, transcribes through Gemini, and types directly into the focused field without touching the clipboard.
- **[JDownloader Download Interceptor](https://github.com/Yakrel/jdownloader-download-interceptor)** — Manifest V3 browser extension that intercepts Chromium downloads and lets the user send them to a trusted JDownloader instance or continue the original browser download.
- **[Wabbajack Library Cleaner](https://github.com/Yakrel/wabbajack-library-cleaner)** — Cross-platform tool for safely finding orphaned and outdated files in Wabbajack download libraries, with preview and recoverable deletion.
- **[Repackarr](https://github.com/Yakrel/repackarr)** — Self-hosted qBittorrent/Transmission + Prowlarr companion for monitoring and reviewing game-repack updates.
- **[Kur'an - Ayet Ezberle](https://github.com/Yakrel/kuran-ayet-ezberle)** — Native Android ayah repetition trainer built around a focused Quran memorization workflow.

## Maintained Container Images

- **[docker-desktop-workspace](https://github.com/Yakrel/docker-desktop-workspace)** — Browser-accessible Debian desktop with Brave, Obsidian, and Tasks.org, built on Selkies/WebRTC.
- **[docker-backrest-rclone](https://github.com/Yakrel/docker-backrest-rclone)** — Backrest image extended with Rclone for automated encrypted backup replication workflows.

Images are published under [`ghcr.io/yakrel`](https://github.com/Yakrel?tab=packages).

## Technical Focus

| Area | Technologies / Practices |
| :--- | :--- |
| **Microsoft & Identity** | Active Directory, Entra ID, Group Policy, Windows Server, Microsoft 365 |
| **Endpoint & Automation** | ManageEngine, SCCM, software deployment, PowerShell, CMD, troubleshooting and remediation |
| **Virtualization & Containers** | Proxmox VE, VMware, Hyper-V, LXC, Docker, Docker Compose |
| **Linux & Reproducibility** | NixOS, Debian, Alpine, Nix Flakes, systemd |
| **Networking & Security** | FortiGate, Cisco, VLANs, VPN, Cloudflare Zero Trust, Tailscale, reverse proxies, firewall segmentation |
| **Storage, Backup & Observability** | ZFS, Sanoid, Restic/Backrest, Rclone, Prometheus, Grafana |
| **Automation & Delivery** | Bash, PowerShell, Git, GitHub Actions |

## Links

[Portfolio / CV](https://cv.byetgin.com) · [LinkedIn](https://www.linkedin.com/in/berkayyetgin) · [Email](mailto:berkay.yetgin@outlook.com)
