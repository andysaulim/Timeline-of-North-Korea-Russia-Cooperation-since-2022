# North Korea–Russia Cooperation Timeline

**A CSIS Beyond Parallel project** | [beyondparallel.csis.org](https://beyondparallel.csis.org)

An interactive timeline documenting major developments in the growing North Korea–Russia relationship since July 2022, built by the CSIS Korea Chair.

---

## About

Since Russia's full-scale invasion of Ukraine in February 2022, North Korea and Russia have dramatically deepened their bilateral cooperation — spanning arms transfers, troop deployments, economic deals, diplomatic realignment, and technology exchange. This timeline tracks those developments in one place.

**Authors:** Victor Cha and Andy Lim, CSIS Korea Chair  
**Research assistance:** Grace Chung, Jiyoon Han, Yesun Kim, Joanne Lee, Seungmin Ryu, Yujin Son, Hyunseung Yu

---

## Database at a Glance

| | |
|---|---|
| **Total events** | 277 |
| **Coverage** | July 2022 – February 2026 |
| **Landmark events** | 14 |
| **Military** | 115 |
| **Intelligence** | 65 |
| **Diplomatic** | 43 |
| **Economic** | 36 |
| **Technology** | 18 |

**By year:** 2022 (9) · 2023 (15) · 2024 (58) · 2025 (160) · 2026 (35)

---

## Key Numbers

- **12M+** artillery shells transferred to Russia
- **14–15K** North Korean troops deployed to Ukraine
- **100+** North Korean ballistic missiles fired in Ukraine
- **30,000+** North Korean workers deployed to Russia
- **$9.6–12.3B** estimated North Korean earnings from Russia *(CSIS Korea Chair estimate)*

---

## Features

- **Search** across all 277 events by keyword
- **Filter** by year, category, official, or landmark status
- **Sidebar navigation** — jump to any year, filter by category
- **Lightbox photos** for entries with imagery
- **Share, cite, and export** — individual event sharing, Chicago/APA/MLA citations, CSV/JSON/Embed export
- **Mobile responsive** — collapsible filter panel, sticky navigation
- **Fully self-contained** — single HTML file, no build step required

---

## Hosting

This project is a single self-contained HTML file (`index.html`). No build tools, no server-side code, no dependencies to install.

### GitHub Pages

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set source to **Deploy from branch → main → / (root)**
4. Your site will be live at `https://yourusername.github.io/repo-name/`

### Local

```bash
# Just open the file directly in any browser
open index.html
```

---

## Data

All events are stored as a JSON array inside `index.html`. Each entry includes:

```json
{
  "id": 0,
  "year": 2022,
  "month": 7,
  "day": 13,
  "tag": "diplomatic",
  "headline": "North Korea Recognized Independence of Donetsk and Luhansk...",
  "text": "Full event description...",
  "source": "https://...",
  "media": "https://...",
  "credit": "Yonhap",
  "caption": "...",
  "event_id": "NK-RU-2022-07-13-01",
  "confidence": "confirmed",
  "is_landmark": false
}
```

**Export formats available from the timeline UI:** CSV · JSON · Embeddable iframe code

---

## Methodology

Events are included if they represent a direct, documentable bilateral interaction between North Korea and Russia — diplomatic meetings, arms transfers, economic agreements, troop deployments, technology exchanges, and related sanctions actions by third parties. Unverified rumors and indirect references are excluded.

Confidence levels:
- **Confirmed** — verified by U.S. government, South Korean intelligence, or primary state media sources
- **Reported** — credibly reported by multiple independent outlets
- **Unconfirmed** — single-source or preliminary reporting

Sources are cross-referenced against the Congressional Research Service (CRS IF12760), NCNK trackers, 38 North analyses, and open-source satellite imagery reporting by CSIS Beyond Parallel.

---

## Citation

**Chicago:**  
Victor Cha and Andy Lim, "Timeline of North Korea–Russia Cooperation Since 2022," CSIS Beyond Parallel, May 2025, https://beyondparallel.csis.org/timeline-of-north-korea-russia-cooperation-since-2022/.

**APA:**  
Cha, V., & Lim, A. (2025). *Timeline of North Korea–Russia cooperation since 2022*. CSIS Beyond Parallel. https://beyondparallel.csis.org/timeline-of-north-korea-russia-cooperation-since-2022/

---

## License

© 2025 Center for Strategic and International Studies (CSIS). All rights reserved.  
Content may not be republished without permission. Contact [beyondparallel.csis.org](https://beyondparallel.csis.org) for licensing inquiries.

For satellite imagery: Copyright notices are embedded in individual entries. Imagery may not be republished without permission from the respective copyright holders.
