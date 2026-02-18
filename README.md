# D Tracker - Anime & Series Logger

A modern, dark-themed web application for tracking and managing your anime and series watchlist. Built with **Tailwind CSS**, **Font Awesome**, and **IndexedDB** for offline storage.

![D Tracker Logo](https://img.shields.io/badge/D%20Tracker-Anime%20Logger-orange?style=flat-square)

---

## Features

- **📺 Add & Manage Series** - Easily add new anime or series to your personal collection
- **⭐ Star Rating System** - Rate each series from 1 to 5 stars
- **📊 Track Status** - Mark series as "Watched" or "Pending"
- **🖼️ Auto-Fetch Posters** - Automatically search and download poster images from the Jikan Anime API
- **🔍 Smart Filtering** - Filter by watch status and rating
- **💾 Offline Storage** - All data is stored locally using IndexedDB
- **🎨 Dark Theme** - Sleek dark UI with smooth animations
- **📱 Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **⚡ No Backend Required** - Fully client-side application

---

## Getting Started

### Installation

1. **Clone or download** the repository
2. **Open** `index.html` in your web browser
3. **Start tracking** your favorite series!

No installation, no server setup—just pure browser magic.

---

## How to Use

### Adding a New Series

1. Click the **"+ Nueva Serie"** (New Series) button in the top-right corner
2. Enter the **series title**
3. *(Optional)* Click the **magic wand icon** ✨ to automatically fetch the poster image from the Jikan API
4. Select the **watch status**:
   - **Por Ver** (Pending) - Not watched yet
   - **Visto** (Watched) - Already watched
5. **Rate** the series by clicking the star icons (1-5 stars)
6. *(Optional)* Enter a custom poster image URL
7. Click **"Guardar"** (Save) to add it to your collection

### Viewing Your Series

- Series are displayed in a **responsive grid** with poster images
- Hover over a card to reveal **edit** and **delete** options
- Cards show:
  - Series title
  - Watch status (color-coded)
  - Star rating

### Filtering

**By Watch Status:**
- Click **"Todos"** to view all series
- Click **"Vistos"** to see only watched series
- Click **"Por Ver"** to see pending series

**By Rating:**
- Use the star buttons to filter by rating (1-5 stars)
- Select **"Cualquiera"** to show all ratings

### Editing a Series

1. Click on any series card or hover and click the **"Editar"** (Edit) label
2. Modify the details in the modal popup
3. Click **"Actualizar"** (Update) to save changes

### Deleting a Series

1. Hover over a series card
2. Click the **trash icon** in the top-right corner
3. Confirm the deletion

---

## Technical Details

### Technology Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Structure |
| **Tailwind CSS** | Styling & Responsive Design |
| **Font Awesome 6** | Icons |
| **Vanilla JavaScript** | Logic & Interactivity |
| **IndexedDB** | Local Data Storage |
| **Jikan Anime API** | Poster Image Search |

### Data Storage

All series data is stored **locally in your browser** using **IndexedDB**. This means:
- ✅ Your data persists across browser sessions
- ✅ Works offline after the first load
- ✅ No account creation required
- ✅ Complete privacy—data never leaves your device

### Color Scheme

```
Primary Orange: #f47521
Dark Black:     #23252b
Darker Grey:    #141519
Text White:     #ffffff
```

---

## Browser Compatibility

- ✅ Chrome 25+
- ✅ Firefox 16+
- ✅ Safari 10+
- ✅ Edge 12+
- ✅ Opera 12+

**Requires:** Modern browser with IndexedDB and ES6 support

---

## API Integration

### Jikan Anime API

The app integrates with the **Jikan Anime API** for auto-fetching poster images:

```
Endpoint: https://api.jikan.moe/v4/anime?q={title}&limit=1
```

- Free to use, no API key required
- Returns poster images in high resolution
- JSON response format

---

## Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Close Modal | **Esc** (ESC key) |

---

## Tips & Tricks

1. **Bulk Add** - You can quickly add multiple series by using the magic wand feature
2. **Custom Posters** - Paste any image URL to use a custom poster
3. **Search API** - The Jikan API works best with exact or partial anime titles
4. **Mobile Friendly** - Full touch support for mobile devices

---

## Troubleshooting

### Images Not Loading

- **Check internet connection** - Poster fetching requires online access
- **Try a different image URL** - Manually paste a poster URL if auto-fetch fails
- **Clear cache** - Try clearing your browser cache if images fail to display

### Data Not Saving

- **Check storage** - Ensure IndexedDB is enabled in your browser
- **Browser restrictions** - Private/Incognito mode may limit storage
- **Storage quota** - If you have hundreds of series, you might hit storage limits

### Auto-Fetch Not Working

- **API availability** - The Jikan API may be temporarily down
- **Title accuracy** - Use the exact anime title for best results
- **Connection issues** - Check your internet connection

---

## Features Roadmap

- [ ] Search functionality within your collection
- [ ] Export/Import data as JSON
- [ ] Dark/Light theme toggle
- [ ] Sort options (alphabetical, rating, date added)
- [ ] Episode tracking
- [ ] Personal notes/reviews for each series
- [ ] Statistics dashboard

---

## Credits

- **Tailwind CSS** - Utility-first CSS framework
- **Font Awesome** - Icon library
- **Jikan API** - Anime database API
- Built with ❤️ for anime lovers

---

## License

This project is open source and available for personal use.

---

## Support

For issues or feature requests, please document them clearly with:
- What you were trying to do
- What happened instead
- Steps to reproduce the issue

---

**Happy tracking! Enjoy organizing your anime collection with D Tracker!** 📺⭐
