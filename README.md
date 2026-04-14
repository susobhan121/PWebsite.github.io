# 🌟 Prerana Ayachit – Personal Portfolio

A modern, responsive personal portfolio website built with pure **HTML, CSS, and JavaScript** — no frameworks, no build tools.

🔗 **Live Site**: [https://PreranAayachit.github.io/portfolio](https://PreranAayachit.github.io/portfolio)

---

## 📸 Features

- ✅ **Responsive Design** – Works on all screen sizes
- 🌙 **Dark Mode Toggle** – Persistent across sessions via localStorage
- 🎞️ **Animated Sections** – Scroll-triggered fade-in animations
- 📊 **Animated Skill Bars** – Triggered on scroll
- 🖼️ **Gallery with Lightbox** – Filter by category + full-screen viewer
- 📬 **Contact Form** – With success state simulation
- ⬆️ **Back to Top Button** – Appears on scroll
- 🔤 **Rotating Greeting** – Multilingual animated text

---

## 📁 Folder Structure

```
prerana-portfolio/
│
├── index.html              ← Main portfolio page
├── style.css               ← All styles + dark mode + responsive
├── script.js               ← Interactivity (theme, gallery, animations)
├── README.md               ← This file
│
└── assets/
    ├── images/
    │   ├── profile.jpg         ← ⭐ YOUR PROFILE PHOTO (required)
    │   ├── event1.jpg          ← Event/college photo
    │   ├── event2.jpg          ← Event/college photo
    │   └── photo2.jpg          ← Additional photo
    │
    ├── certificates/
    │   ├── ai4a.jpg            ← AI4A certificate scan
    │   ├── design-thinking.jpg ← Design Thinking certificate
    │   ├── ace.jpg             ← ACE project certificate
    │   ├── coursera.jpg        ← Coursera certificate
    │   ├── netcad.jpg          ← NetCAD certificate
    │   ├── matlab.jpg          ← MATLAB achievement
    │   └── yuva-ai.jpg         ← Yuva AI certificate
    │
    └── projects/
        ├── ai4a-project.jpg        ← Screenshot of AI4A project
        ├── design-thinking-project.jpg ← Design Thinking screenshot
        ├── ace-project.jpg         ← ACE project screenshot
        └── portfolio.jpg           ← Screenshot of this portfolio
```

---

## 🖼️ Adding Your Images

> **IMPORTANT**: Replace placeholder images with your actual photos and scanned certificates.

1. **Profile photo** → `assets/images/profile.jpg`  
   (Any size; ideally square or portrait)

2. **Certificates** → `assets/certificates/` folder  
   Scan or photograph each certificate and save as JPG/PNG with the exact filenames listed above.

3. **Project screenshots** → `assets/projects/` folder  
   Take screenshots of your project outputs/demos.

---

## 🚀 Deploying to GitHub Pages

### Step 1 – Create Repository
1. Go to [github.com](https://github.com) → New Repository
2. Name it `portfolio` (or your name)
3. Make it **Public**

### Step 2 – Upload Files
```bash
git init
git add .
git commit -m "Initial portfolio upload"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
```

Or use **GitHub Desktop** / drag-and-drop upload on GitHub.com

### Step 3 – Enable GitHub Pages
1. Go to your repository → **Settings**
2. Click **Pages** in the left sidebar
3. Under "Source" → select **main branch** → root folder
4. Click **Save**
5. Wait 1-2 minutes → your site is live at:  
   `https://YOUR_USERNAME.github.io/portfolio`

### Step 4 – Update Links
In `index.html`, update these placeholders:
- GitHub profile link: `https://github.com/PreranAayachit`
- LinkedIn link: `https://www.linkedin.com/in/prerana-ayachit`
- Project GitHub links (in the project cards)

---

## 🛠️ Customization

| What to change | Where |
|---|---|
| Name, intro text | `index.html` → `#home` section |
| Skills percentages | `index.html` → `data-width="85"` attributes |
| Project links | `index.html` → project card `<a href="#">` tags |
| Color scheme | `style.css` → `:root` CSS variables |
| Contact details | `index.html` → `#contact` section |

---

## 📧 Contact

**Prerana Ayachit**  
📧 ayachitprerana@gmail.com  
📱 +91 9270235211  
🔗 [LinkedIn](https://www.linkedin.com/in/prerana-ayachit)

---

*Built with ❤️ using HTML, CSS & JavaScript — no frameworks needed.*
