# North Korea–Russia Cooperation Timeline

**A CSIS Beyond Parallel project** | [beyondparallel.csis.org](https://beyondparallel.csis.org)

An interactive timeline documenting major developments in the growing North Korea–Russia relationship since July 2022, built by the CSIS Korea Chair.

**Live site:** [andysaulim.github.io/Timeline-of-North-Korea-Russia-Cooperation-since-2022](https://andysaulim.github.io/Timeline-of-North-Korea-Russia-Cooperation-since-2022/)

---

## About

Since Russia's full-scale invasion of Ukraine in February 2022, North Korea and Russia have dramatically deepened their bilateral cooperation — spanning arms transfers, troop deployments, economic deals, diplomatic realignment, and technology exchange. This timeline tracks those developments in one place.

**Authors:** Victor Cha and Andy Lim, CSIS Korea Chair

---

## Database at a Glance

| | |
|---|---|
| **Coverage** | July 2022 – present |
| **Landmark events** | 14 |
| **Military** | 115+ |
| **Intelligence** | 65+ |
| **Diplomatic** | 43+ |
| **Economic** | 36+ |
| **Technology** | 18+ |

*Event counts update automatically as new entries are added to the data source.*

---

## Key Numbers

- **12M+** artillery shells transferred to Russia
- **14–15K** North Korean troops deployed to Ukraine
- **100+** North Korean ballistic missiles fired in Ukraine
- **30,000+** North Korean workers deployed to Russia
- **$9.6–12.3B** estimated North Korean earnings from Russia *(CSIS Korea Chair estimate)*

Source: [CSIS Beyond Parallel](https://youtu.be/JJu6_Gysw7s)

---

## Data Source — Google Sheets (Live Backend)

Event data is stored in a public Google Sheet and fetched live on every page load. This means **no HTML edits are needed to add or update events** — just update the sheet.

**Sheet:** [Timeline of North Korea-Russia Cooperation Since 2022](https://docs.google.com/spreadsheets/d/10XZCpGPwokuLVFd-Mj_zt5A4bK7TD99AL-cHgQBY3Mc/)

### Adding a new entry

Open the Google Sheet and add a new row at the top (below the title card in row 2). Fill in these columns:

| Column | Description | Example |
|--------|-------------|---------|
| **Year** | 4-digit year | `2025` |
| **Month** | Month number | `6` |
| **Day** | Day number | `19` |
| **Display Date** | Human-readable date | `6/19/2025` |
| **Headline** | Event headline | `Putin visits Pyongyang...` |
| **Text** | Full event description | Plain text, no HTML |
| **Media** | Image URL | `https://...` |
| **Media Credit** | Photo credit | `KCNA` |
| **Media Caption** | Caption text | `Kim Jong-un and Putin...` |
| **Group** | Category | `Military`, `Intelligence`, `Diplomatic`, `Economic`, or `Technology` |
| **Background** | Source URL | `https://...` |

The timeline updates for all visitors on the next page load. No GitHub push required.

### If the sheet fetch fails

The page falls back silently to a set of baked-in events so the site never goes blank. Check that the sheet sharing is set to **Anyone with the link → Viewer**.

---

## Features

- **Live data** from Google Sheets — updates without touching the HTML
- **Search** across all events by keyword
- **Multi-select filters** by year and category
- **Sidebar navigation** — jump to any year, filter by category
- **Lightbox photos** for entries with imagery
- **Share on social** — X, Bluesky, LinkedIn
- **Cite database** — Chicago, APA, MLA citation formats
- **CSV / JSON / Embed export**
- **Mobile responsive**
- **Single file** — `index.html` is fully self-contained, no build step

---

## Hosting

This project is a single self-contained HTML file (`index.html`). No build tools, no server, no dependencies.

### GitHub Pages

1. Upload `index.html` to the repository root
2. Go to **Settings → Pages → Deploy from branch → main → / (root)**
3. Site goes live at `https://yourusername.github.io/repo-name/`

### Updating the site

- **New events:** Add rows to the Google Sheet — no deploy needed
- **Design changes:** Edit `index.html` and push to GitHub

---

## Citation

**Chicago:**
Victor Cha and Andy Lim, "Timeline of North Korea–Russia Cooperation Since 2022," CSIS Beyond Parallel, updated continuously, https://beyondparallel.csis.org/timeline-of-north-korea-russia-cooperation-since-2022/.

**APA:**
Cha, V., & Lim, A. (2025). *Timeline of North Korea–Russia cooperation since 2022*. CSIS Beyond Parallel. https://beyondparallel.csis.org/timeline-of-north-korea-russia-cooperation-since-2022/

---

## License

© 2025 Center for Strategic and International Studies (CSIS). All rights reserved.
Content may not be republished without permission. Contact [beyondparallel.csis.org](https://beyondparallel.csis.org) for licensing inquiries.
