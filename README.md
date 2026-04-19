# HPS Financial Dashboard

**A small business financial dashboard built as a portfolio project for [freeCodeCamp](https://www.freecodecamp.org).**

Built by [Garret Hebert](mailto:hebertprofessionalservices@gmail.com) · [Hebert Professional Services](mailto:hebertprofessionalservices@gmail.com)

---

## Live Demo

After enabling GitHub Pages on this repo (Settings → Pages → Deploy from branch → `main` / `root`), the dashboard will be live at:

```
https://<your-github-username>.github.io/<repo-name>/
```

---

## What It Does

This dashboard gives small business owners a clear, real-time view of their financials — revenue, expenses, and profit — without the complexity of enterprise software.

It mirrors the exact deliverables offered by Hebert Professional Services:

- **Monthly Financial Reporting** — revenue, expenses, and profit at a glance
- **Custom Reporting & Dashboards** — interactive charts and filters
- **Process Automation** — upload your own CSV and the dashboard builds itself

---

## Features

| Feature | Description |
|---|---|
| KPI Cards | Revenue, Expenses, Net Profit, and Profit Margin with month-over-month deltas |
| Bar Chart | Revenue vs. Expenses by month |
| Donut Chart | Expense breakdown by category |
| Line Chart | Net profit trend over time |
| P&L Statement | Full profit & loss table with section headers and color-coded net row |
| Key Insights | Auto-generated analysis — margin health, growth rate, expense ratio |
| Simple / Detailed Toggle | Executive summary view vs. full detailed dashboard |
| Month Filter | Filter all charts and the P&L by individual month |
| CSV Upload | Drag & drop your own data — no coding required |
| Reset to Sample | One-click restore of the demo data after uploading your own |
| Responsive | Works on desktop, tablet, and mobile |

---

## How to Use

### Option 1 — Open directly
Download `index.html` and open it in any modern browser. No server or install required.

### Option 2 — Clone the repo
```bash
git clone https://github.com/hebertprofessionalservices-source/financial-dashboard.git
cd financial-dashboard
open index.html        # macOS
# or
start index.html       # Windows
# or
xdg-open index.html    # Linux
```

### Option 3 — Host on GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, pick `main` and `/ (root)`.
4. Your dashboard will be live at `https://<your-username>.github.io/<repo-name>/` within a minute.

---

## CSV Format

To load your own data, upload a CSV with at least these three columns:

```
Month,Revenue,Expenses
Jan,18500,11200
Feb,21000,12400
Mar,24500,13100
```

Any additional columns are treated as **expense categories** and will appear in the donut chart and P&L breakdown automatically. Example:

```
Month,Revenue,Expenses,Software,Payroll,Marketing,Office,Misc
Jan,18500,11200,1800,5000,2100,1200,1100
```

Dollar signs and commas in numbers are handled automatically. A ready-to-use [`sample_data.csv`](sample_data.csv) is included in this repo.

---

## Tech Stack

| Tool | Purpose |
|---|---|
| HTML / CSS / JavaScript | Core structure, styling, and logic |
| [Chart.js](https://www.chartjs.org/) | Bar, donut, and line charts |
| [Papa Parse](https://www.papaparse.com/) | CSV parsing |
| Google Fonts (Playfair Display, DM Sans, DM Mono) | Typography |

No build tools, no frameworks, no dependencies to install. Single file. All third-party libraries are loaded from CDN.

---

## Project Structure

```
financial-dashboard/
├── index.html         # The dashboard (single-file app)
├── sample_data.csv    # Example CSV you can upload to test
├── README.md          # This file
├── LICENSE            # MIT
└── .gitignore
```

---

## About Hebert Professional Services

I help small businesses clean up their financials, understand their numbers, and save time by building simple, effective systems.

**Services:**
- Financial Cleanup & Organization — $500–$1,500
- Monthly Financial Reporting — $250–$500/month
- Custom Reporting & Dashboards — $300–$1,000
- Process Automation — $500–$2,000

**Contact:**
- Email: hebertprofessionalservices@gmail.com
- Phone: (601) 991-5132

---

## License

MIT License — see [LICENSE](LICENSE) for details.
