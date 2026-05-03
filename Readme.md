# Shlok Nemani – CEO Website
**Maruti Textile | Personal Portfolio Website**

---

## 📁 Project Structure

```
SITE_ONE/
├── index.html       ← Main webpage
├── style.css        ← All styling
├── script.js        ← Animations & interactivity
├── images/          ← Your photos go here
│   ├── photo1.jpg   ← Hero section photo
│   ├── photo2.jpg   ← About section main photo
│   └── photo3.jpg   ← About section small photo
└── README.md        ← This file
```

---

## 🖼️ Adding Your Photos

1. Open the `images/` folder
2. Add your 3 photos named exactly:
   - `photo1.jpg` → Hero (large main photo, portrait style)
   - `photo2.jpg` → About section (big card)
   - `photo3.jpg` → About section (small card, can reuse a photo)
3. Best photo size: **800×1000px** or similar portrait ratio
4. If you don't add photos, placeholder boxes appear automatically

---

## 🚀 Hosting on GitHub Pages (Step by Step)

### STEP 1 – Install Git (if not already installed)
- Download from: https://git-scm.com/downloads
- Install and restart VS Code

### STEP 2 – Create a GitHub Account
- Go to https://github.com and sign up (free)

### STEP 3 – Create a New Repository
1. Click the **"+"** icon (top right on GitHub) → "New repository"
2. Repository name: `shlok-nemani` (or anything you like)
3. Set to **Public**
4. Do NOT tick "Add README"
5. Click **Create repository**

### STEP 4 – Open VS Code and Open Terminal
- Open VS Code
- Go to: **Terminal → New Terminal** (or press Ctrl + `)
- Navigate to your project folder:
  ```
  cd path/to/shlok-nemani-website
  ```
  Example: `cd C:/Users/Shlok/Desktop/shlok-nemani-website`

### STEP 5 – Run These Commands in Terminal (one by one)

```bash
git init
git add .
git commit -m "Initial website launch"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/shlok-nemani.git
git push -u origin main
```
⚠️ Replace `YOUR_USERNAME` with your actual GitHub username.

### STEP 6 – Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** (top tab)
3. Scroll down to **"Pages"** (left sidebar)
4. Under "Branch", select **main** → folder **/root**
5. Click **Save**
6. Wait 1–2 minutes, then your site is live at:
   ```
   https://YOUR_USERNAME.github.io/shlok-nemani/
   ```

---

## 🌐 Later: Connect Your Company Domain

When you're ready to connect `www.marutitextile.com` (or similar):

1. In GitHub → Settings → Pages → **Custom domain**
2. Enter your domain (e.g. `shlok.marutitextile.com`)
3. At your domain registrar (GoDaddy/BigRock/etc.), add a CNAME record:
   - Name: `shlok` (or `www`)
   - Value: `YOUR_USERNAME.github.io`
4. Wait 24hrs for DNS to propagate

---

## ✏️ How to Update the Website

After making any changes in VS Code, run:
```bash
git add .
git commit -m "Updated about section"
git push
```
GitHub Pages auto-updates within 1–2 minutes.

---

## 📝 Things to Personalise

Open `index.html` and update:
- Email address (search for `shlok@marutitextile.com`)
- LinkedIn URL (search for `linkedin.com/in/shloknemani`)
- Phone or WhatsApp (optional – add in the Contact section)
- Company founding year (search for "Decades of Trust")

---

Built with pure HTML, CSS & JavaScript. No frameworks needed.