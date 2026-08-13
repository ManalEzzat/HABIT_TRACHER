
| # | الشخص | Name | المسؤولية | الملفات |
|---|---|---|---|---|
| 1 | أحمد ابراهيم شعبان | Ahmed Ibrahim Shaaban | Core / Infra Lead — Tokens + Components + Data Layer + Router | `tokens.css`, `components.css`, `data.js`, `router.js`, `index.html` |
| 2 | داليا سامى عبدالعزيز | Dalia Samy Abdelaziz | Dashboard | `dashboard.html/css/js` |
| 3 | نهلة ياسر عرفات عبد الحي | Nahla Yasser Arafat Abdelhay | My Habits | `habits.html/css/js` |
| 4 | بسملة حسن عبدالله | Basmala Hassan Abdallah | Statistics | `stats.html/css/js` |
| 5 | منال عزت احمد جاد | Manal Ezzat Ahmed Gad | Settings + Recommendations | `settings.html/css/js`, `recommendations.js` |

# 🌿 Habits Dashboard

A fully responsive habit-tracking dashboard built with pure **HTML, CSS & JavaScript** — no backend, no database, no framework. All data lives in the browser via `localStorage`.


## ✨ Features

### 📊 Dashboard
- Contextual greeting header with live status message
- 4 stat cards — today's progress ring, longest streak, weekly completion rate, active habits
- Ongoing / Completed habit panels
- **Interactive weekly bar chart with day picker** — click any past day to view its data
- Category breakdown with progress bars
- Personalized habit recommendations with dismiss-on-add
- All-done celebration banner

### ✅ My Habits
- Filter by category (Mind / Body / Health / Wellness / All)
- Detailed habit rows — streak, best streak, weekly dot log, target chip, check button
- Add / edit habits

### 📈 Statistics
- Streak leaderboard sorted highest → lowest
- Full weekly heatmap (habit × day)
- Summary cards — total check-ins, average completion %, habits on track

### ⚙️ Settings & Profile
- Dark / Light mode toggle
- Export / Import data as JSON
- Reset data
- User profile page

## 🧱 Tech Stack

| Layer | Tech |
|---|---|
| Structure | HTML |
| Styling | CSS (custom design tokens, bootstrap) |
| Logic | JavaScript  |
| Persistence | `localStorage` — no server, no database |

## 📁 Project Structure

```
habits-dashboard/
├── index.html
├── dashboard.html
├── habits.html
├── stats.html
├── settings.html
├── profile.html
├── styles/
│   ├── tokens.css
│   ├── components.css
│   └── ...
└── js/
    ├── data.js
    ├── router.js
    └── ...
```

