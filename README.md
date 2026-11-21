<div align="center">

<img src="https://cdn.ctrlops.io/website/icon.png" width="88" height="88" alt="CtrlOps logo" />

# CtrlOps

### Deploy, debug and manage Linux servers with AI. One desktop app over SSH, with no agent on your servers.

[![Website](https://img.shields.io/badge/Website-ctrlops.io-35B729?style=flat-square)](https://ctrlops.io)
[![Latest](https://img.shields.io/badge/Latest-v2.0.0%20The%20Docker%20Update-35B729?style=flat-square)](https://ctrlops.io/changelog)
[![Docs](https://img.shields.io/badge/Docs-Read-blue?style=flat-square)](https://ctrlops.io/docs)
[![G2](https://img.shields.io/badge/G2-4.8%2F5-FF492C?style=flat-square)](https://www.g2.com/products/ctrlops/reviews)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/JhRCp3hsT9)
[![X](https://img.shields.io/badge/X-@ctrlops__ai-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/ctrlops_ai)
[![Platforms](https://img.shields.io/badge/macOS%20%7C%20Windows%20%7C%20Linux-supported-lightgrey?style=flat-square)](https://ctrlops.io/docs/getting-started/download)

**[Download](https://ctrlops.io/docs/getting-started/download)** · **[Docs](https://ctrlops.io/docs)** · **[Features](https://ctrlops.io/features)** · **[Pricing](https://ctrlops.io/pricing)** · **[Changelog](https://ctrlops.io/changelog)** · **[Discord](https://discord.gg/JhRCp3hsT9)**

</div>

---

## What is CtrlOps?

**CtrlOps is a desktop app for managing Linux servers over SSH.** It keeps your servers in one list and opens each one in its own tab with a file manager, logs, live monitoring and an AI terminal. It adds tools for alerts, SSH keys, access reviews, security audits, port forwarding, backups, deploys, PM2, Docker, cron jobs and saved scripts.

CtrlOps connects straight from your computer to your servers over SSH. There is no agent, no web panel and no new port on the server, and your SSH keys and credentials stay on your computer.

It runs on **macOS** (Apple Silicon and Intel), **Windows** (Microsoft Store) and **Linux** (.deb), and manages any Linux server you can reach over SSH.

Used by **1,000+ engineers in 160+ countries** · **4.8/5 on G2** · **#5 Product of the Day on Product Hunt, twice**

---

## What's new in v2.0: The Docker Update

Released 14 November 2026. Full notes in the [changelog](https://ctrlops.io/changelog).

- **[Docker Management](https://ctrlops.io/features/docker-management):** a Docker tool in every server's sidebar, over SSH with no agent. Install Docker in one click when it's missing, see containers grouped by Compose stack, start, stop, restart, recreate or duplicate a container, read its logs and open a terminal inside it with an AI panel.
- **Compose stacks and builds from code:** deploy a Compose stack you write, upload or generate from a form. Build a container from GitHub, GitLab, Bitbucket, Gitea or a zip file, or run an image from Docker Hub or another registry.
- **One-click apps and databases:** install an app from the Marketplace or create a database from a ready-made template.
- **Domains and HTTPS for containers:** CtrlOps checks the DNS, sets up Nginx or Traefik and gets a Let's Encrypt certificate that renews on the server.
- **Volume backups:** back up a container's volumes on a schedule and restore any restore point, even after the container is gone.
- **A Free plan:** up to 2 servers on 2 devices with no end date, next to the Personal, Team and Enterprise plans.
- **Easier Add Server:** pick a host from your `~/.ssh/config`, connect with password-protected `.pem` keys, and see exactly where a failed connection stopped.

---

## The problem it solves

Running several Linux servers means constant tool-switching: a spreadsheet of IP addresses, terminal windows nobody can tell apart, SSH keys spread across PuTTY and WinSCP, deploys done by hand over SSH, and monitoring you only open after something has broken. None of it is hard. It is slow, repetitive and spread across too many places.

CtrlOps puts that work in one desktop app on your machine: your servers, keys, files, logs, deploys and containers, one tab per server.

---

## Features

### Servers & files

| Feature | What it does |
|---|---|
| [Multi-Server Management](https://ctrlops.io/features/multi-server-management) | Every server by name in one list, each in its own tab. Tag, favorite and search them, and import from Termius or your `~/.ssh/config`. |
| [File Manager](https://ctrlops.io/features/file-manager) | Browse, edit, upload and download server files over SSH. No SFTP client, no second login. |
| [Log Management](https://ctrlops.io/features/log-management) | Finds the Nginx, PM2, Docker and system logs on the server. Search them, follow them live, download them. |
| [Backups](https://ctrlops.io/features/backup) | Scheduled folder backups to S3-compatible storage (AWS S3, Cloudflare R2, Backblaze B2, Wasabi and more), with a log of every run and restore points. |

### Security & access

| Feature | What it does |
|---|---|
| [SSH Management](https://ctrlops.io/features/ssh-management) | Every key in `authorized_keys` with a name on it. Add a user or revoke a key in one form, instead of editing the file by hand. |
| [Access Management](https://ctrlops.io/features/access-management) | See who can log in to which server, and who has sudo. Remove someone's key from every server at once, or add a person to many servers in one step. |
| [Security Audit](https://ctrlops.io/features/security-audit) | 25 read-only audits over SSH, a hardening score and a PDF report, with fixes you approve. |
| [Port Forwarding](https://ctrlops.io/features/port-forwarding) | Save local, remote and dynamic SOCKS tunnels. Reach a private database without opening a port. |

### Monitoring & deployment

| Feature | What it does |
|---|---|
| [Infrastructure Monitoring](https://ctrlops.io/features/infra-monitoring) | Live CPU, memory and disk for the server you're on, and the processes using them. |
| [Alerts](https://ctrlops.io/features/alerts) | High CPU, a filling disk, a stopped service or an expiring certificate, sent to Slack, Telegram or a webhook. Alerts run on the server, so they fire with CtrlOps closed. |
| [One-Click Deployment](https://ctrlops.io/features/deployment) | Node.js, React and Next.js from GitHub to your VPS, with PM2, Nginx and SSL set up for you. |
| [PM2 Process Manager](https://ctrlops.io/features/pm2-process-manager) | Every PM2 process with its status, CPU, memory and restarts. Restart, reload or read its logs in one click. |
| [Docker Management](https://ctrlops.io/features/docker-management) | Containers, Compose stacks, logs and shells over SSH, plus one-click apps, databases and domains. No agent. |

### AI & automation

| Feature | What it does |
|---|---|
| [AI Terminal](https://ctrlops.io/features/ai-terminal) | Ask in plain English. It writes the Linux command, explains it, and runs it only after you approve. Use your own AI key, ChatGPT or OpenRouter sign-in, or a local model such as Ollama. |
| [Script Directory](https://ctrlops.io/features/script-directory) | Save the commands you retype, with variables, and run them on any server in one click. 19 built-in scripts included. |
| [Cron Jobs](https://ctrlops.io/features/cron-jobs) | See every cron job on the server, adopt the ones already there, and hear when one fails. |

All features: [ctrlops.io/features](https://ctrlops.io/features)

---

## Install

| Platform | How to install |
|---|---|
| macOS (Apple Silicon or Intel) | Download the `.dmg` from the [download page](https://ctrlops.io/docs/getting-started/download). |
| Windows 10 / 11 | Install from the [Microsoft Store](https://apps.microsoft.com/detail/9nq0bx1t87nt). |
| Linux (Debian, Ubuntu and derivatives, amd64) | Run the one-line installer below, or download the `.deb` from the [download page](https://ctrlops.io/docs/getting-started/download). |

```bash
curl -fsSL https://ctrlops.io/install.sh | sudo bash
```

The script downloads the official CtrlOps `.deb` over HTTPS and installs it with apt. Its checksum is at [ctrlops.io/install.sh.sha256](https://ctrlops.io/install.sh.sha256).

### Get started in three steps

1. **Sign in** with an email code or Google. A new account starts a 14-day free trial of Personal, no credit card needed, and moves to the Free plan when it ends.
2. **Add a server:** paste an SSH string, pick a host from your `~/.ssh/config`, or use a `.pem` key. You can also import your servers from Termius.
3. **Open it in a tab** and use the terminal, files, logs, monitoring and the rest.

Step-by-step guide: [connect your first server](https://ctrlops.io/docs/getting-started/quick-start)

---

## How it works

CtrlOps is **one hop**: your computer opens a direct SSH connection to your server. There is no CtrlOps relay, broker or cloud bridge in between.

```
┌───────────────────────────┐                    ┌───────────────────────────┐
│  Your computer            │        SSH         │  Your Linux server        │
│                           │ ─────────────────► │                           │
│  CtrlOps desktop app      │   direct, one hop  │  no agent                 │
│  saved servers, passwords │                    │  no web panel             │
│  and tokens: AES-256      │ ◄───────────────── │  no new port              │
└───────────────────────────┘                    └───────────────────────────┘
            │
            └── optional: your own AI key or a local model, called from your computer
```

- **Your secrets stay with you.** Key files stay where they are and CtrlOps saves only their paths. Saved servers, passwords, AI keys and tokens are AES-256 encrypted on your computer, and Vault Lock adds a passphrase if you want one.
- **Nothing to run on the server.** A few features add standard tools when you use them: a deploy installs Git, Node, PM2 and Nginx or Apache if they're missing, backups install rclone, alerts and scheduled jobs add cron entries, and Docker management can install Docker.
- **Works with what you have.** If a server accepts SSH, CtrlOps can manage it.
- **Clear about what leaves your machine.** You sign in with an account, and the app sends product usage events, never your commands, files or server data. AI requests go from your machine to the provider you pick.

Read more: [SSH & security model](https://ctrlops.io/docs/core/ssh-security)

---

## Pricing

Prices in USD. Live prices and the full comparison are on [ctrlops.io/pricing](https://ctrlops.io/pricing).

| Plan | Seats | Monthly | Monthly with Docker | Yearly | Yearly with Docker | Lifetime (Docker included) |
|---|---|---|---|---|---|---|
| **Free** | 1 | $0 | - | - | - | - |
| **Personal** | 1 | $9 | $19 | $90 | $190 | $349 |
| **Team** | 5 | $39 | $69 | $390 | $690 | $849 |
| **Enterprise** | Unlimited | $229 | $229 (included) | $2,290 | $2,290 (included) | $2,499 |

- **CtrlOps Docker add-on:** the "with Docker" columns are the full price with the add-on: +$10/month or +$100/year on Personal, +$30/month or +$300/year on Team. Enterprise, every Lifetime plan and the free trial already include Docker, at no extra cost.
- **Free:** up to 2 servers on 2 devices, with no end date. SSH, the file manager, live monitoring and the Script Directory, with small limits on the other tools. Docker is not part of Free.
- **14-day free trial** of Personal with every feature, including Docker. Any email, no credit card, and nothing is charged when it ends: the account moves to Free.
- **Paid plans:** unlimited servers and 2 devices per seat. You pay for people, never for servers. Yearly is 10 times monthly (2 months free).
- **Lifetime:** pay once, updates for life, with a 14-day refund window. Monthly and yearly plans renew automatically; cancel anytime.
- **No AI fee:** bring your own AI key or a local model.

---

## Free tools, no sign-up

25 free tools for SSH, Linux and DevOps work. 24 run entirely in your browser, so nothing you paste is uploaded. The VPS Security Scanner scans public hosts from our server and keeps no scan history.

**Connect & transfer**
[SSH Key Generator](https://ctrlops.io/tools/ssh-key-generator) ·
[SSH Config Generator](https://ctrlops.io/tools/ssh-config-generator) ·
[SSH Tunnel Generator](https://ctrlops.io/tools/ssh-tunnel-generator) ·
[SCP / rsync Command Builder](https://ctrlops.io/tools/scp-rsync-command-builder) ·
[PPK to OpenSSH Converter](https://ctrlops.io/tools/ppk-to-openssh-converter) ·
[OpenSSH to PPK Converter](https://ctrlops.io/tools/openssh-to-ppk-converter)

**Configure**
[nginx Config Generator](https://ctrlops.io/tools/nginx-config-generator) ·
[systemd Service Generator](https://ctrlops.io/tools/systemd-service-generator) ·
[Cron Expression Generator](https://ctrlops.io/tools/cron-expression-generator) ·
[htpasswd Generator](https://ctrlops.io/tools/htpasswd-generator) ·
[YAML Validator](https://ctrlops.io/tools/yaml-validator) ·
[YAML to JSON Converter](https://ctrlops.io/tools/yaml-to-json-converter) ·
[JSON to YAML Converter](https://ctrlops.io/tools/json-to-yaml-converter)

**Secure & audit**
[VPS Security Scanner](https://ctrlops.io/tools/vps-security-scanner) ·
[sshd_config Analyzer](https://ctrlops.io/tools/sshd-config-analyzer) ·
[nginx Config Analyzer](https://ctrlops.io/tools/nginx-config-analyzer) ·
[authorized_keys Analyzer](https://ctrlops.io/tools/authorized-keys-analyzer) ·
[SSL Certificate Decoder](https://ctrlops.io/tools/ssl-certificate-decoder) ·
[Chmod Calculator](https://ctrlops.io/tools/chmod-calculator)

**Check & calculate**
[DNS Record Lookup](https://ctrlops.io/tools/dns-record-lookup) ·
[curl Command Builder](https://ctrlops.io/tools/curl-command-builder) ·
[JWT Decoder & Verifier](https://ctrlops.io/tools/jwt-decoder-verifier) ·
[Base64 Encoder / Decoder](https://ctrlops.io/tools/base64-encoder-decoder) ·
[CIDR / Subnet Calculator](https://ctrlops.io/tools/cidr-subnet-calculator) ·
[Uptime & SLA Calculator](https://ctrlops.io/tools/uptime-sla-calculator)

All tools: [ctrlops.io/tools](https://ctrlops.io/tools)

---

## How CtrlOps compares

CtrlOps is more than an SSH client, and it isn't a panel you install on each server. It is one desktop app with SSH, files, logs, monitoring, deploys, Docker and an AI terminal.

| SSH clients and terminals | Server panels and PaaS |
|---|---|
| [CtrlOps vs Termius](https://ctrlops.io/compare/ctrlops-vs-termius) | [CtrlOps vs aaPanel](https://ctrlops.io/compare/ctrlops-vs-aapanel) |
| [CtrlOps vs PuTTY](https://ctrlops.io/compare/ctrlops-vs-putty) | [CtrlOps vs Webmin](https://ctrlops.io/compare/ctrlops-vs-webmin) |
| [CtrlOps vs MobaXterm](https://ctrlops.io/compare/ctrlops-vs-mobaxterm) | [CtrlOps vs RunCloud](https://ctrlops.io/compare/ctrlops-vs-runcloud) |
| [CtrlOps vs SecureCRT](https://ctrlops.io/compare/ctrlops-vs-securecrt) | [CtrlOps vs Dokploy](https://ctrlops.io/compare/ctrlops-vs-dokploy) |
| [CtrlOps vs Bitvise](https://ctrlops.io/compare/ctrlops-vs-bitvise) | |
| [CtrlOps vs WinSCP](https://ctrlops.io/compare/ctrlops-vs-winscp) | |
| [CtrlOps vs Royal TS](https://ctrlops.io/compare/ctrlops-vs-royalts) | |
| [CtrlOps vs Warp](https://ctrlops.io/compare/ctrlops-vs-warp) | |

All comparisons: [ctrlops.io/compare](https://ctrlops.io/compare)

---

## Frequently asked questions

<details>
<summary><b>Is CtrlOps free?</b></summary><br>

Yes, there is a Free plan for up to 2 servers on 2 devices, with no end date. It covers SSH, the file manager, live monitoring and the Script Directory, with small limits on the rest, such as 3 AI messages a day, 1 one-click deploy, 1 port forward, and 1 backup job, cron job and alert per server. Every new account also starts a 14-day free trial of Personal with every feature, including Docker. No credit card is needed. See [pricing](https://ctrlops.io/pricing).
</details>

<details>
<summary><b>Do you store my SSH keys or server credentials?</b></summary><br>

No. Your SSH key files stay where they are on your computer, and CtrlOps saves only their paths. Saved servers, passwords, AI keys and tokens are AES-256 encrypted on your computer, and you can add a Vault Lock passphrase. CtrlOps connects straight to your servers, with no cloud relay in between.
</details>

<details>
<summary><b>Do I need to install anything on my servers?</b></summary><br>

No agent, panel or new port. CtrlOps works over SSH. A few features add standard tools when you use them: a deploy installs Git, Node, PM2 and Nginx or Apache if they're missing, backups install rclone, and Docker management can install Docker.
</details>

<details>
<summary><b>Which operating systems does it run on?</b></summary><br>

The desktop app runs on macOS (Apple Silicon and Intel), Windows 10 and 11 through the Microsoft Store, and Linux as a `.deb` for Debian, Ubuntu and their derivatives. It manages any Linux server you can reach over SSH, such as Ubuntu, Debian, Rocky, AlmaLinux or Amazon Linux.
</details>

<details>
<summary><b>Does the AI terminal run commands on its own?</b></summary><br>

No. It writes the command, explains why, and waits for you to click Run. If you turn on Auto-Run in a terminal, read-only commands run by themselves, while `sudo` and anything that changes the server still ask first. Auto-Run is off in every new terminal.
</details>

<details>
<summary><b>Which AI providers are supported?</b></summary><br>

Sign in with ChatGPT or OpenRouter, bring your own key for OpenAI, Anthropic, Google or any OpenAI-compatible provider, or use a local model such as Ollama. Requests go from your machine to the provider you pick, and CtrlOps charges no AI fee. See the [AI Terminal docs](https://ctrlops.io/docs/modules/ai-terminal).
</details>

<details>
<summary><b>Can CtrlOps manage Docker?</b></summary><br>

Yes, since v2.0. Each server gets a Docker tool over SSH: containers grouped by Compose stack, logs, a terminal inside a container, Compose deploys, builds from Git, one-click apps and databases, domains with HTTPS, and volume backups. CtrlOps Docker is an add-on on Personal and Team, and included in Enterprise, every Lifetime plan and the free trial. See the [Docker docs](https://ctrlops.io/docs/modules/docker).
</details>

<details>
<summary><b>Can it manage many servers?</b></summary><br>

Yes. Paid plans have unlimited servers, and the Free plan covers 2. Your servers sit in one list with tags, favorites and search, and each one opens in its own tab, so a long build on one server never blocks work on another.
</details>

<details>
<summary><b>How is it different from Termius or MobaXterm?</b></summary><br>

Those are SSH clients. CtrlOps adds what you'd otherwise open separate tools for: a file manager, logs, live monitoring, alerts, deploys, PM2, Docker, access reviews, security audits and an AI terminal, in one desktop app. See the [full comparisons](https://ctrlops.io/compare).
</details>

---

## Who builds CtrlOps

CtrlOps is built by **TST Technology** (TST Tech Matrix Pvt Ltd, Ahmedabad, India) and has been in development since March 2025.

- **[Hiren Kalariya](https://www.linkedin.com/in/hiren-kalariya/)**, Co-Founder & CEO. Leads product and engineering on CtrlOps, and has shipped 60+ production systems.
- **[Daxesh Italiya](https://www.linkedin.com/in/daxesh-italiya)**, Co-Founder & CTO. Leads engineering, and built Wooffer, a server-monitoring platform, before CtrlOps.
- **[Parth Makwana](https://www.linkedin.com/in/parthmakwanapm)**, Co-Founder of TST Technology.

They write about Linux server management, SSH, deployment and practical DevOps on the [CtrlOps blog](https://ctrlops.io/blog).

---

## Find CtrlOps elsewhere

| | |
|---|---|
| Website | [ctrlops.io](https://ctrlops.io) |
| Documentation | [ctrlops.io/docs](https://ctrlops.io/docs) |
| Blog | [ctrlops.io/blog](https://ctrlops.io/blog) |
| Reviews | [ctrlops.io/reviews](https://ctrlops.io/reviews) |
| Roadmap | [ctrlops.io/roadmap](https://ctrlops.io/roadmap) |
| Changelog | [ctrlops.io/changelog](https://ctrlops.io/changelog) |
| Discord | [discord.gg/JhRCp3hsT9](https://discord.gg/JhRCp3hsT9) |
| X / Twitter | [@ctrlops_ai](https://x.com/ctrlops_ai) |
| YouTube | [@CtrlOpsAi](https://www.youtube.com/@CtrlOpsAi) |
| LinkedIn | [CtrlOps on LinkedIn](https://www.linkedin.com/products/tst-technology-ctrlops-deploy-debug-and-manage-servers-with-ai/) |
| Product Hunt | [producthunt.com/products/ctrlops](https://www.producthunt.com/products/ctrlops) |
| G2 | [g2.com/products/ctrlops](https://www.g2.com/products/ctrlops/reviews) |
| Indie Hackers | [indiehackers.com/product/ctrlops](https://www.indiehackers.com/product/ctrlops) |
| SourceForge | [sourceforge.net/software/product/CtrlOps](https://sourceforge.net/software/product/CtrlOps/) |
| Slashdot | [slashdot.org/software/p/CtrlOps](https://slashdot.org/software/p/CtrlOps/) |
| AlternativeTo | [alternativeto.net/software/ctrlops](https://alternativeto.net/software/ctrlops/) |
| Trustpilot | [trustpilot.com/review/ctrlops.io](https://www.trustpilot.com/review/ctrlops.io) |

---

## Support

- **Docs:** [ctrlops.io/docs](https://ctrlops.io/docs): installation, your first connection, every module and troubleshooting
- **Community:** [Discord](https://discord.gg/JhRCp3hsT9)
- **Email:** support@ctrlops.io
- **Help center:** [ctrlops.io/support](https://ctrlops.io/support)

<sub>Docker is a trademark of Docker, Inc. CtrlOps is not affiliated with or endorsed by Docker, Inc.</sub>
