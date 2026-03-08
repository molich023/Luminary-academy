# 🎓 Luminary Academy — School Website

A complete, production-ready school website with Parent, Teacher, and Student portals.
Built with pure HTML, CSS, and JavaScript. No frameworks or dependencies required.

---

## 📁 File Structure

```
luminary-academy/
├── index.html        ← Main website (all pages in one file)
├── 404.html          ← Custom "Page Not Found" page
├── netlify.toml      ← Netlify config + security headers
├── robots.txt        ← SEO crawler instructions
├── sitemap.xml       ← SEO sitemap
└── README.md         ← This file
```

---

## 🚀 How to Deploy on Netlify (Step-by-Step)

### METHOD 1: Drag & Drop (Easiest — 2 Minutes)

1. Go to **https://netlify.com** and click **"Sign Up"**
2. Sign up with your email, Google, or GitHub account
3. Once logged in, you'll see the Netlify dashboard
4. Find the section that says **"Want to deploy a new site without connecting to Git?"**
5. You'll see a box that says **"Drag and drop your site folder here"**
6. Open your file explorer and drag the entire **`luminary-academy`** folder into that box
7. Wait 10–30 seconds for the upload to complete
8. 🎉 Your site is LIVE! Netlify gives you a free URL like:
   `https://random-name-123.netlify.app`

---

### METHOD 2: GitHub + Netlify (Best for Updates)

**Step 1 — Create a GitHub account**
- Go to **https://github.com** and sign up free

**Step 2 — Create a new repository**
- Click the **"+"** icon → **"New repository"**
- Name it: `luminary-academy`
- Set to **Public**
- Click **"Create repository"**

**Step 3 — Upload your files**
- Click **"uploading an existing file"**
- Drag ALL files from the `luminary-academy` folder
- Click **"Commit changes"**

**Step 4 — Connect to Netlify**
- Go to **https://netlify.com** → **"Add new site"** → **"Import an existing project"**
- Choose **"GitHub"** and authorize Netlify
- Select your `luminary-academy` repository
- Build settings:
  - Build command: *(leave empty)*
  - Publish directory: `.`
- Click **"Deploy site"**

**Step 5 — Done!** 🎉
Every time you update files on GitHub, Netlify automatically redeploys!

---

## 🌐 Custom Domain Setup (Optional)

Want a custom domain like `www.youracademy.com`?

1. In Netlify dashboard → **"Domain settings"** → **"Add custom domain"**
2. Enter your domain name
3. Netlify will show you **DNS nameservers** to add to your domain registrar
4. Update nameservers at GoDaddy / Namecheap / wherever you bought the domain
5. Wait 24-48 hours for DNS propagation
6. Netlify automatically adds a **FREE SSL certificate** ✅

---

## ✏️ How to Customize the Website

Open `index.html` in any text editor (Notepad, VS Code, etc.) and find/replace:

| What to change | Search for | Replace with |
|---|---|---|
| School name | `Luminary Academy` | Your school name |
| Tagline | `Excellence Since 1998` | Your school's tagline |
| Phone | `+1 (555) 123-4567` | Your phone number |
| Email | `info@luminary.edu` | Your email |
| Address | `123 Academy Drive` | Your address |
| Stats | `2,400+`, `98%`, `150+` | Your real stats |
| Year founded | `1998` | Your year |

---

## 🛡️ Security Features Included

- ✅ OWASP Top 10 security headers (via netlify.toml)
- ✅ X-Frame-Options: DENY (anti-clickjacking)
- ✅ Content Security Policy (XSS prevention)
- ✅ HSTS (force HTTPS)
- ✅ X-Content-Type-Options (MIME sniffing prevention)
- ✅ Login brute-force protection (3 attempts)
- ✅ MFA / Two-Factor Authentication field
- ✅ Input sanitization
- ✅ CSRF token simulation
- ✅ Session timeout (15 minutes)

---

## 📱 Features Overview

### Parent Portal
- Live grade tracking (A+, B+, etc. per subject)
- Historical progress reports
- Real-time bus GPS tracker
- Attendance calendar
- Teacher messaging
- Fee management
- Push notifications to phone

### Teacher Portal
- Post assignments & resources
- Online grading with rubrics
- Class analytics dashboard
- Live class roster
- Parent communication
- Timetable management

### Student Portal
- Homework hub with due dates
- Gamified XP & badge system
- E-Library (10,000+ books)
- AI practice quiz generator
- Study groups
- Personal timetable

---

## 📞 Support

For customization help or questions, contact your web developer.

Built with ❤️ for Luminary Academy — Where Futures Begin.
