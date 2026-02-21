# Quick Start Guide

This is a simplified guide to get you started quickly with your portfolio website.

## 📝 First Steps After Setup

### 1. Update Your Personal Info (5 minutes)

Open `index.html` and update:
- **Line 27**: Your name
- **Lines 35-42**: Your bio/description
- **Lines 93-95**: Your GitHub, LinkedIn, and Email links

### 2. Add Your First Blog Post (10 minutes)

1. Go to `blog/posts/` folder
2. Copy `sample-post.html` → rename to `my-first-post.html`
3. Edit the file:
   - Change the title
   - Update the date
   - Write your content
4. Open `blog.html` and add your post to the listing (copy an existing entry and modify it)

### 3. Add Your Projects (15 minutes)

Open `projects.html` and:
- Replace the sample projects with your own
- Update project names, descriptions, and links
- Change technology tags to match what you used

### 4. Test Locally

Open `index.html` in your browser to preview your changes.

### 5. Publish to GitHub Pages

```bash
git add .
git commit -m "Customize portfolio website"
git push origin main
```

Then enable GitHub Pages in your repository settings.

## 🎨 Quick Customizations

### Change Accent Color

In `css/style.css`, find line 6 and change:
```css
--accent-primary: #0066cc;  /* Change this color code */
```

Popular colors:
- Blue (professional): `#0066cc`
- Green (fresh): `#28a745`
- Purple (creative): `#6f42c1`
- Red (bold): `#dc3545`

### Add Images to Blog Posts

1. Save image in `assets/images/`
2. In your blog post, add:
```html
<img src="../../assets/images/your-photo.jpg" alt="Description" style="max-width: 100%; border-radius: 8px; margin: 1.5rem 0;">
```

## 📂 File Structure at a Glance

```
├── index.html           → Your home page (edit your bio here)
├── blog.html            → Blog listing (add new posts here)
├── projects.html        → Projects showcase (add projects here)
├── blog/posts/          → Individual blog post files
├── assets/images/       → Your images
└── css/style.css        → Styling (colors, fonts, spacing)
```

## 🆘 Common Tasks

**Add a blog post**: Copy `sample-post.html` → edit it → add entry in `blog.html`

**Add a project**: Open `projects.html` → copy a project card → edit it

**Change colors**: Edit `css/style.css` → modify variables at the top

**Add images**: Put in `assets/images/` → reference in HTML

## 🚀 Deploy Checklist

Before pushing to GitHub:
- [ ] Updated your name everywhere
- [ ] Changed contact links (GitHub, LinkedIn, Email)
- [ ] Added at least one real project
- [ ] Tested in browser locally
- [ ] All links work correctly

Ready? Run:
```bash
git add .
git commit -m "Launch my portfolio"
git push origin main
```

Visit GitHub repo → Settings → Pages → Enable GitHub Pages

Your site will be live at: `https://yourusername.github.io`

---

That's it! For more details, check `README.md`
