# Wedding Invitation Website

A beautiful, animated wedding invitation website for Aarav & Diya featuring GSAP animations and responsive design.

## 🚀 How to Run

### Option 1: Python HTTP Server (Recommended)
```bash
cd top
python -m http.server 8000
```
Then open `http://localhost:8000/wedding-invitation-website-phi.vercel.app` in your browser.

### Option 2: Live Server (VS Code Extension)
1. Install the "Live Server" extension in VS Code
2. Right-click on `wedding-invitation-website-phi.vercel.app` and select "Open with Live Server"

### Option 3: Node.js HTTP Server
```bash
cd top
npx http-server
```

## 📁 Project Structure

```
top/
├── wedding-invitation-website-phi.vercel.app  # Main HTML file
├── CSS/                                       # Stylesheets
├── JavaScript/                                # GSAP libraries (from CDN)
├── Font/                                      # Font files
├── Media/                                     # Images and media files
└── embed/                                     # Embedded Google Maps (not in use)
```

## ✨ Features

- 🎨 Beautiful gradient design with royal maroon and gold colors
- ✨ Smooth GSAP animations and scroll triggers
- 🎵 Background music toggle
- 📱 Fully responsive design
- 💌 RSVP form with submit functionality
- 📍 Venue and timeline sections
- ✍️ Typewriter effect for story section
- 🎊 Floating particle and petal effects

## 🛠️ Dependencies

All dependencies are loaded from CDN:
- **Tailwind CSS** - for styling
- **GSAP** (3.12.2) - for animations
- **ScrollTrigger** - for scroll-based animations
- **TextPlugin** - for text animation effects
- **Font Awesome** - for icons
- **Google Fonts** - for typography

## 📝 Customization

Edit `wedding-invitation-website-phi.vercel.app` to customize:
- Names and dates
- Colors in the Tailwind config
- Animation timings
- Content and text
- Media files

## ✅ Status

✓ Server is running and accepting connections
✓ All animations working correctly
✓ RSVP form functional
✓ Responsive design tested

Enjoy!
