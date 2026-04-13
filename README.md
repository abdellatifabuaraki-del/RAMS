# RAMS — Recruitment Agency Management System

A full-featured, single-file SaaS UI for recruitment agencies. Built with vanilla HTML, CSS, and JavaScript — no build tools, no dependencies, no backend required.

🔗 **[Live Demo](https://your-username.github.io/rams)**

---

## Features

| Module | Capabilities |
|---|---|
| **Dashboard** | KPI cards, bar chart, activity feed, quick actions |
| **Pipeline** | Kanban board across 5 hiring stages |
| **Applicants** | Search, filter, sort, paginate, bulk actions, detail drawer |
| **Documents** | Tab filter, approve/reject, upload modal |
| **Job Orders** | Progress tracking, search, add/delete |
| **Analytics** | Charts, agent performance, destination breakdown |
| **Accounting** | Ledger, expense tracking, category filters |
| **Audit Trail** | Searchable timeline, action filter |
| **Chat** | Threaded messages, auto-reply simulation |
| **Integrations** | Toggle connect/disconnect with 6 services |
| **Billing** | Plan comparison, invoice history, payment method |
| **Settings** | General, agency, notifications, security, users, data |
| **Roles & Permissions** | 6 roles × 20 permissions RBAC matrix |

---

## Design System

- **Colors:** Brand blue `#1447E6` · Teal · Green · Amber · Red · Purple
- **Fonts:** [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque) (UI) + [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) (data)
- **Themes:** Full light + dark mode via CSS custom properties
- **Accessibility:** `focus-visible`, ARIA labels, keyboard navigation throughout

---

## Deploy to GitHub Pages

```bash
# 1. Clone this repo
git clone https://github.com/your-username/rams.git
cd rams

# 2. Enable GitHub Pages in repo Settings → Pages
#    Source: Deploy from branch → main → / (root)

# 3. Visit your live URL
#    https://your-username.github.io/rams
```

Or just drag `index.html` to [netlify.com/drop](https://netlify.com/drop) for an instant URL.

---

## Local Development

No build step needed. Just open the file:

```bash
open index.html
# or
npx serve .
```

---

## Keyboard Shortcuts

| Key | Action |
|---|---|
| `⌘K` / `Ctrl+K` | Open command palette |
| `1` | Go to Dashboard |
| `2` | Go to Applicants |
| `3` | Go to Job Orders |
| `4` | Go to Analytics |
| `Esc` | Close modal / drawer / palette |

---

## License

MIT — free to use, modify, and deploy.
