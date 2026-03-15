# 📖 event-page-template — Instructions

Get your event page live in minutes. No coding experience needed.

---

## 📋 Table of Contents

1. [Getting Started](#1-getting-started)
2. [Editing the Config Block](#2-editing-the-config-block)
3. [Setting Your Theme](#3-setting-your-theme)
4. [Setting Up the RSVP Button](#4-setting-up-the-rsvp-button)
5. [Deploying to GitHub Pages](#5-deploying-to-github-pages)
6. [FAQ](#6-faq)

---

## 1. Getting Started

1. Go to [github.com/bloxiebuilds/event-page-template](https://github.com/bloxiebuilds/event-page-template)
2. Click **"Use this template"**
3. Name your repo and click **"Create repository"**
4. Open `index.html` — preview it in your browser instantly!

---

## 2. Editing the Config Block

Open `index.html` and find the `CONFIG` block near the top:

```js
const CONFIG = {
  eventName:   "Summer Rooftop Bash",
  tagline:     "Good music. Good people. Great views.",
  date:        "Saturday, July 19, 2026",
  time:        "7:00 PM – 12:00 AM",
  location:    "The Rooftop, 123 Main St, Salt Lake City",
  mapsUrl:     "https://maps.google.com",
  rsvpUrl:     "#",
  rsvpLabel:   "RSVP Now",
  darkMode:    true,
  accentColor: "#f472b6",
};
```

| Field | What to put |
|-------|-------------|
| `eventName` | The name of your event |
| `tagline` | A short catchy description |
| `date` | The event date (e.g. `"Saturday, July 19, 2026"`) |
| `time` | Start and end time |
| `location` | Full address |
| `mapsUrl` | Paste a Google Maps link here |
| `rsvpUrl` | Link to a Google Form, Eventbrite, email, etc. |
| `rsvpLabel` | Text on the RSVP button |
| `accentColor` | Any hex color for the accent |

---

## 3. Setting Your Theme

| Value | Result |
|-------|--------|
| `true` | Always dark |
| `false` | Always light |
| `"toggle"` | Visitor can switch between dark and light |

---

## 4. Setting Up the RSVP Button

Set `rsvpUrl` to wherever you want people to go when they click RSVP:

- **Google Form** — paste the form URL
- **Email** — use `"mailto:your@email.com"`
- **Eventbrite** — paste your event link
- **Not ready yet** — leave it as `"#"`

---

## 5. Deploying to GitHub Pages

1. Push your repo to GitHub (make sure it's public)
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Click **Save** — your page will be live at:

```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME
```

Share that link with your guests!

---

## 6. FAQ

**Q: The countdown shows 00 00 00 00 — why?**
Make sure your `date` field is in a format JavaScript can read, like `"July 19, 2026"` or `"2026-07-19"`.

**Q: Can I change the accent color?**
Yes! Set `accentColor` to any hex code, like `"#6EE7B7"` or `"#A78BFA"`.

**Q: Can I add more details to the page?**
Yes — duplicate one of the `.detail-row` blocks in the HTML and update the icon, label, and value.

**Q: Can I use this for a birthday, wedding, or meetup?**
Absolutely — it works for any kind of event!

---

<p align="center">event-page-template was made by <a href="https://github.com/bloxiebuilds">bloxiebuilds</a></p>
