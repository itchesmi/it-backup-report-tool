# 🖥️ IT Backup Report Tool

A lightweight, offline-ready HTML tool for IT teams to quickly generate and send daily, weekend, and monthly backup status reports — no typing required.

---

## 🚀 Features

- **3 Report Types** — Daily, Weekend, and Monthly tabs
- **5 Status Options** per task:
  - ✅ OK
  - ✅⚠️ OK with Warning
  - ⚠️ Warning
  - 🔄 In Progress
  - ❌ Error
- **Smart Selectors** — choose PHDD (01/02), PSSD (01–04), and HDD In/Out numbers directly in the form
- **Auto-generated Message** — formatted report built instantly on button click
- **One-tap Sharing** — Copy to clipboard or send directly via WhatsApp
- **No internet required** — runs entirely in the browser as a single HTML file
- **Zero setup** — just open the file and go

---

## 📋 Report Sections

### Daily
| Field | Details |
|---|---|
| 🔄 FreeFileSync | Daily backup on PSSD (01–04) |
| 💾 NAV Full Backup | Backup folder sync |
| 🖴 PHDD NAV SQL Backup | Choose PHDD 01 or 02 |
| ☁️ OneDrive SQL Backup | Upload and space freed |
| 🔁 NAV Server Replication | Replication status |
| 🌡️ Server Room Temperature | Environment check |
| 🖥️ All Devices Running | Device health check |

### Weekend
| Field | Details |
|---|---|
| 💰 QB Backups | QuickBooks backup status |
| 🔁 AD Server Replication | Active Directory replication |
| 🔁 NAV Server Replication | NAV replication status |

### Monthly
| Field | Details |
|---|---|
| 🗄️ Archive Sync HDD | HDD replaced and new HDD added (select both) |
| 🔒 Firewall Config | Config file downloaded |
| 📂 AD Full Backup & Replication | Full monthly AD backup |
| 🖥️ Minor Server Backups | All server backups done |

---

## 📦 Usage

1. Download `backup-report-tool.html`
2. Open it in any browser
3. Select the report tab — **Daily**, **Weekend**, or **Monthly**
4. Tap the status for each task
5. Add a note if needed (warning, error, or in-progress)
6. Hit **⚡ Generate Report**
7. **📋 Copy** or **💬 Send via WhatsApp**

---

## 🛠️ Tech Stack

- Plain HTML, CSS, JavaScript
- No frameworks, no dependencies
- Single file — fully portable

---

## 📁 File Structure

```
it-backup-report-tool/
└── backup-report-tool.html   # The entire tool in one file
```

---

## 📄 License

MIT — free to use and modify for your team.
