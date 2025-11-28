# Digital Wellness Plan

A self-guided wellbeing resource for FE & HE college teaching staff and Professional Learning Support (PLS) staff to manage their digital wellbeing.

## 🎯 What is this?

The Digital Wellness Plan helps educators identify digital wellbeing challenges ("symptoms") and implement evidence-based solutions ("treatments"). Think of it as your personal "Digital Wellness Surgery" - browse symptoms, find treatments, and track your progress.

## ✨ Key Features

- **📊 Dashboard**: See your active goals and daily motivational messages
- **🏥 Wellbeing Surgery**: Browse 30 symptom/treatment cards across 8 sections
- **⭐ Favourites**: Save cards that resonate with you for quick reference
- **⚙️ Settings**: Customize font size and manage your data
- **🔒 Privacy-First**: All data stored locally on your device only
- **📱 Fully Responsive**: Works on mobile, tablet, and desktop
- **♿ Accessible**: Designed with accessibility in mind

## 📚 The 8 Sections

1. **Screen Time & Boundaries** - Managing constant connectivity and setting healthy limits
2. **Communication Stress** - Email overwhelm, instant response pressure, message overload
3. **Information Overload** - News fatigue, content backlog, doomscrolling
4. **Work-Life Balance** - After-hours work, boundary setting, protecting personal time
5. **Sleep & Evening Use** - Bedtime scrolling, screen-disrupted sleep
6. **Focus & Productivity** - Deep work, task switching, notification interruptions
7. **Social Media** - Comparison, FOMO, intentional use
8. **Physical Health** - Posture, eye strain, sedentary behavior, movement

Each section contains multiple cards with specific symptoms and actionable treatment strategies.

## 🚀 Quick Start

### Option 1: Use Directly (Simplest)
1. Download all files
2. Open `index.html` in your web browser
3. Start exploring!

### Option 2: Deploy to GitHub Pages
See `GITHUB_SETUP.md` for step-by-step instructions on:
- Creating a GitHub repository
- Uploading your files
- Getting a live URL
- Updating content

### Option 3: Embed in Moodle/LMS
See `MOODLE_SETUP.md` for instructions on:
- Adding as a direct link (recommended)
- Embedding via iframe
- Student instructions

## 📁 File Structure

```
digital-wellness-plan/
├── index.html              # Dashboard page
├── surgery.html            # Browse cards
├── favourites.html         # Saved favourites
├── settings.html           # Settings & data management
├── assets/
│   └── logo.svg           # Lightbulb logo
├── css/
│   └── styles.css         # All styling
├── js/
│   ├── data.js            # 30 cards + 40 messages
│   ├── storage.js         # localStorage wrapper
│   ├── main.js            # Dashboard functionality
│   ├── surgery.js         # Card browsing & flipping
│   ├── favourites.js      # Favourites page
│   └── settings.js        # Settings functionality
├── README.md              # This file
├── GITHUB_SETUP.md        # GitHub deployment guide
├── MOODLE_SETUP.md        # Moodle integration guide
└── ADD_CONTENT.md         # How to add more cards/messages
```

## 🎨 Design

- **Dark Theme**: Easy on the eyes for extended use
- **Digiwest Colors**: Vibrant magenta, cyan, orange, and yellow accents
- **Flippable Cards**: Click to reveal treatment strategies
- **Responsive**: Adapts to all screen sizes
- **Accessible**: Keyboard navigation, adjustable font sizes

## 🔒 Privacy & Data

**Your data stays on your device.** We don't collect, transmit, or store anything on servers.

- All data stored in browser localStorage
- No tracking or analytics
- No external API calls
- You have complete control
- Clear data anytime from Settings

### What's Stored
- Your selected goals (max 3)
- Your favourited cards (unlimited)
- Your settings preferences (font size)

### What's NOT Stored
- Nothing on servers
- No personal information
- No tracking data
- No usage analytics

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No frameworks or dependencies
- **localStorage** - Client-side data persistence
- **Responsive Design** - Mobile-first approach
- **Single Page Application** - Fast, smooth navigation
- **Modern Browsers** - Works in Chrome, Firefox, Safari, Edge

## 💻 Requirements

- Modern web browser (last 2 years)
- JavaScript enabled
- 10MB storage space (localStorage)

## 📖 Adding More Content

Currently includes:
- **30 cards** (about 4 per section)
- **40 motivational messages**

Want to expand? See `ADD_CONTENT.md` for:
- How to add new cards
- How to add new messages
- Content templates
- Quality checklist

The original design planned for 64+ cards and 150+ messages - plenty of room to grow!

## 🎯 Who is this for?

**Primary Users**: Teaching staff in Further Education & Higher Education colleges

**Secondary Users**: Professional Learning Support (PLS) staff

Both groups face unique digital wellbeing challenges:
- Constant connectivity expectations
- Email and messaging overload
- Work-life boundary blur
- Screen fatigue from teaching and admin
- Information overload

## 📝 License

[To be determined]

## 🙏 Acknowledgments

- **Marc Brackett** - Mood Meter inspiration (future feature)
- **Digiwest** - Branding and color palette
- **FE & HE teaching community** - For whom this resource is built

## 📧 Contact & Support

[Institution contact information to be added]

## 🗺️ Future Plans

- Expanded card library (64+ cards)
- More motivational messages (150+)
- Check-in mood tracking
- Reflection journal
- Data export/import
- Print-friendly summaries

---

**Built with care for educators who care for others.** 💙

*Version 1.0 - November 2024*
