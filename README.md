#Widgets

Custom widgets built for embedding in Notion. Hosted via GitHub Pages at `https://kmorris1370.github.io/Widgets/`

---

## Widgets

### Weather
**URL:** `https://kmorris1370.github.io/Widgets/weather/`

A minimal 7-day weather widget for Rock Island, IL. Displays current temperature, condition, and a weekly forecast with weather icons.

**Stack:** HTML · CSS · JavaScript · OpenWeatherMap API

**Features:**
- Current temperature and condition
- 7-day forecast with high/low temps
- Auto-refreshes every 10 minutes
- Monospace font, black theme
- Designed to embed cleanly in Notion

**Setup:**
Replace the API key in `weather/index.html` with your own free key from [openweathermap.org](https://openweathermap.org/api):
```javascript
const API_KEY = 'your-key-here';
```

---

## Embedding in Notion

1. Copy the widget URL
2. In Notion type `/embed`
3. Paste the URL and click **Embed link**
4. Resize the embed block to fit your layout

---

## Repo Structure

```
Notion-Widgets/
├── weather/
│   └── index.html
└── README.md
```

---

## Planned Widgets

- Bill reminder
- Notion quick note

---


- All widgets are static HTML/CSS/JS — no build step required
- Designed to match a dark monospace Notion aesthetic
- API keys should never be committed to public repos — use environment variables or a proxy for production
