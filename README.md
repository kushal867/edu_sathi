# 🎓 EduSathi — Your Education Companion

> **AI-powered education guidance platform for Nepali students** — Find the perfect college, prepare for entrance exams, book verified hostels, and explore global study opportunities, all in one place.

---

## 🌐 Live Preview

Open `index.html` in your browser or serve with any local HTTP server.

---

## 📸 Screenshots

| Homepage | Colleges | AI Counsellor |
|----------|----------|---------------|
| Hero with AI search | College listing & filters | Sathi chat interface |

---

## ✨ Features

- 🤖 **AI College Matching** — Personalized college recommendations based on your profile, grades, and goals
- 🏫 **College Directory** — Browse 1000+ top colleges across Nepal with fee structure, affiliation, and ratings
- 🌍 **Study Abroad** — Explore universities in USA, Australia, UK and more with visa guidance
- 📚 **Entrance Prep** — IOE, CEE, IELTS/PTE preparation resources and roadmaps
- 🏠 **Hostel Finder** — 500+ verified student hostels with amenities and proximity filters
- 💬 **AI Counsellor (Sathi)** — 24/7 AI-powered chat counsellor for personalized guidance
- 🔐 **Auth System** — Login, Signup, and Forgot Password flows

---

## 🗂️ Project Structure

```
edu_sathi/
├── index.html                  # Homepage
├── css/
│   ├── global.css              # Design tokens, resets, base styles
│   ├── navbar.css              # Navigation bar styles
│   ├── footer.css              # Footer styles
│   ├── home.css                # Homepage section styles
│   ├── responsive.css          # Mobile & tablet breakpoints
│   ├── colleges.css            # College listing page
│   ├── college-detail.css      # College detail page
│   ├── auth.css                # Login / Signup / Forgot password
│   ├── ai-match.css            # AI match questionnaire
│   ├── ai-counsellor.css       # AI chat counsellor
│   ├── entrance-prep.css       # Entrance prep page
│   ├── hostels.css             # Hostel finder page
│   ├── study-abroad.css        # Study abroad page
│   └── blog.css                # Blog page
├── pages/
│   ├── colleges/               # College listing & detail pages
│   ├── ai-match/               # AI matching questionnaire
│   ├── ai-counsellor/          # Sathi AI chat page
│   ├── entrance-prep/          # Exam prep resources
│   ├── hostels/                # Hostel finder
│   ├── study-abroad/           # International study page
│   ├── blog/                   # Blog / articles
│   ├── login.html              # Login page
│   ├── signup.html             # Signup page
│   ├── forgot-password.html    # Password recovery
│   ├── about.html              # About us
│   └── contact.html            # Contact & support
└── assets/
    └── images/
        ├── logo/               # Brand logo (PNG)
        ├── colleges/           # College photos
        ├── hostels/            # Hostel photos
        └── hero-student.jpg    # Hero section image
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 (Semantic) |
| Styling | Vanilla CSS (no frameworks) |
| Fonts | Google Fonts — Poppins |
| Icons | Inline SVG |
| Hosting | Static (any web server / GitHub Pages) |

---

## 🚀 Getting Started

### Run Locally

Simply open the project in VS Code and use the **Live Server** extension:

```bash
# Or serve with Python
python3 -m http.server 8000
```

Then visit: `http://localhost:8000`

### No build step required
This is a pure HTML/CSS project — no Node.js, no bundler, no dependencies.

---

## 🎨 Design System

| Token | Value |
|-------|-------|
| Primary (Navy) | `#0F3460` |
| Accent (Orange) | `#F7941D` |
| Font | Poppins (300–700) |
| Border Radius | `12px` cards, `8px` inputs |
| Spacing base | `8px` grid |

---

## 📄 Pages Overview

| Page | Path |
|------|------|
| Homepage | `/index.html` |
| Colleges | `/pages/colleges/index.html` |
| College Detail | `/pages/colleges/detail.html` |
| Study Abroad | `/pages/study-abroad/index.html` |
| Hostel Finder | `/pages/hostels/index.html` |
| Entrance Prep | `/pages/entrance-prep/index.html` |
| AI Match | `/pages/ai-match/questionnaire.html` |
| AI Counsellor | `/pages/ai-counsellor/index.html` |
| Login | `/pages/login.html` |
| Signup | `/pages/signup.html` |

---

## 🤝 Contributing

1. Fork the repo
2. Create a feature branch: `git checkout -b feat/your-feature`
3. Commit your changes: `git commit -m "feat: add your feature"`
4. Push and open a Pull Request

---

## 📬 Contact

- 📧 support@edusathi.com.np
- 📞 +977 1 4400XXX
- 🌐 [edusathi.com.np](https://edusathi.com.np)

---

## 📝 License

© 2024 EduSathi Nepal. All rights reserved.
