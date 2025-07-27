# White Beluga All-in-One Package

This repository contains the complete White Beluga project, including:

- **Client PWA**: A progressive web app interface for clients.
- **Founder Portal**: Dashboard interface for founders.
- **Assets**: Logos, icons, and splash images.
- **Scripts**: Utility scripts for aura and time matrix.
- **Automation**: GitHub Actions workflow to back up client and founder data daily.

## Folder Structure

```
.white-beluga/
│
├── .github/
│   └── workflows/
│       └── backup.yml
│
├── assets/
│   └── icons/
│       └── splash.png
│       └── villa.jpg
│
├── client-pwa/
│   ├── index.html
│   ├── manifest.json
│   ├── service-worker.js
│   └── client_data/
│       ├── aura_session_data/
│       ├── reports/
│       ├── emotions.yaml
│       └── rituals.json
│
├── founder-portal/
│   ├── index.html
│   └── founder_data/
│       ├── metrics.json
│       └── emotions-log.md
│
├── scripts/
│   ├── aura.js
│   └── time-matrix.js
│
├── index.html
├── offersheet.html
├── README.md
└── .gitignore
```

## Usage

1. Clone the repository.
2. Deploy the `index.html` at the root for the main homepage.
3. Use `client-pwa/` for the client progressive web app.
4. Use `founder-portal/` for the founder dashboard.
5. The GitHub Actions workflow will back up data daily.

