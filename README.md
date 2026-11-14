<p align="center">
  <a href="https://rayxopanel.com">
    <img src="https://rayxopanel.com/og.png" alt="RAYXO — Webhosting Manager" width="640">
  </a>
</p>

<p align="center">
  <b>A free, open-source hosting panel for VPS owners and web hosting providers.</b><br>
  Panel hosting gratis &amp; open source untuk VPS dan penyedia web hosting.
</p>

<p align="center">
  <a href="https://rayxopanel.com">Website</a> ·
  <a href="https://rayxopanel.com/en/docs/">Docs</a> ·
  <a href="https://rayxopanel.com/docs/">Dokumentasi</a> ·
  <a href="https://rayxopanel.com/en/changelog/">Changelog</a> ·
  <a href="https://github.com/fianbiasa/rayxo/discussions">Discussions</a>
</p>

<p align="center">
  <a href="https://github.com/fianbiasa/rayxo/releases/latest"><img src="https://img.shields.io/github/v/release/fianbiasa/rayxo?include_prereleases&label=release" alt="Latest release"></a>
  <img src="https://img.shields.io/badge/Ubuntu-24.04_LTS-E95420?logo=ubuntu&logoColor=white" alt="Ubuntu 24.04 LTS">
  <img src="https://img.shields.io/badge/arch-amd64_%7C_arm64-555" alt="amd64 and arm64">
  <img src="https://img.shields.io/badge/status-beta-orange" alt="Beta">
</p>

---

RAYXO manages domains, SSL, PHP, databases, email, DNS, FTP, SSH and cron jobs on your own Ubuntu server, with a reseller level and no license fees. It installs with a single command.

| Feature | What you get |
| --- | --- |
| 🌐 **Domains & redirects** | Subdomains, aliases, pointers, 301/302 redirects. Nginx in front of Apache, so `.htaccess` keeps working. |
| 🐘 **Multi-PHP** | PHP 7.4 to 8.5 per domain, each site with its own PHP-FPM pool. |
| 🔒 **Automatic SSL** | Let's Encrypt issued and renewed for you, including wildcards and `mail.<domain>`, or bring your own certificate. |
| 🗄️ **MariaDB** | Databases, users, one-click phpMyAdmin, import and export, table repair, and remote access per IP. |
| 📧 **Email hosting** | Mailboxes, forwarders, catch-all, automatic replies, filters and a spam filter per mailbox, with Roundcube webmail. DKIM, SPF and DMARC set up for you: 10/10 on mail-tester. |
| 🧭 **DNS server** | PowerDNS zones from a template (resellers can have their own), a record editor for customers, and wildcard SSL through DNS. |
| 📁 **FTP, SFTP & file manager** | FTPS locked to one folder, SFTP without a shell, and a file manager in the browser. |
| 📦 **Plans & quotas** | Disk and inode quotas, per-plan limits (domains, databases, email accounts and more), bulk suspend and plan changes for hosting providers. |
| 👥 **Resellers** | Reseller plans with overselling; resellers make their own plans and accounts, log in as a customer, and use their own brand, nameservers and sign-in domain. |
| 📊 **Bandwidth & limits** | Bandwidth counted from the server's logs, 30-day graphs of bandwidth, disk, CPU and memory, monthly limits, plus CPU, memory and process limits per account (cgroups). |
| ⚙️ **Per-website settings** | Error pages, password-protected folders, hotlink protection, MIME types, CGI, per-site limits, logs and GoAccess visitor reports. |
| 🔑 **SSH & REST API** | SSH in a jail with SSH keys, and a REST API with login keys. |
| 🔔 **Alerts & tickets** | Email and Telegram alerts, support tickets and messages to customers. |
| 🧰 **Admin tools** | Extra IP addresses, a process monitor, every account's login history, and a configuration editor that tests and rolls back. |
| 🛡️ **Isolated accounts** | Every hosting account is its own Linux user. Sign in with 2FA or a passkey. |

## Install

On a fresh Ubuntu 24.04 LTS server, as root:

```bash
wget https://rayxopanel.com/setup.sh
sudo bash setup.sh --admin-email you@yourdomain.com
```

Then open `https://your-hostname:2222`. See the [installation guide](https://rayxopanel.com/en/docs/installation/) for DNS and firewall requirements.

## Source code

Development happens in **[fianbiasa/rayxo](https://github.com/fianbiasa/rayxo)**. Issues, pull requests and releases all live there.

📬 [hi@rayxopanel.com](mailto:hi@rayxopanel.com)
