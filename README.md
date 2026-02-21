# Nithindev N - Portfolio Website

A clean, professional portfolio website designed to be accessible to everyone - technical and non-technical visitors alike.

## 🌟 Overview

This website serves as my personal portfolio, showcasing my work, sharing my thoughts through blog posts, and providing a way for people to connect with me.

## 📁 Project Structure

```
nithindevn.github.io/
├── index.html              # Home page with introduction
├── blog.html               # Blog listing page
├── projects.html           # Projects showcase page
├── css/
│   └── style.css          # Main stylesheet
├── blog/
│   └── posts/             # Individual blog post files
│       └── sample-post.html  # Template for new posts
├── assets/
│   └── images/            # Images for blog posts and projects
└── README.md              # This file
```

## 🎨 Design Philosophy

- **Clean & Professional**: Modern design that works for interviews and professional networking
- **Accessible**: Easy to understand for both technical and non-technical visitors
- **Responsive**: Works perfectly on phones, tablets, and desktop computers
- **Fast**: Lightweight and quick to load

## ✏️ How to Add a New Blog Post

1. **Copy the template**:
   - Navigate to `blog/posts/`
   - Copy `sample-post.html` and rename it (e.g., `my-first-post.html`)

2. **Edit your new post**:
   - Update the `<title>` tag
   - Change the date and category tag
   - Replace the content with your writing

3. **Add it to the blog listing**:
   - Open `blog.html`
   - Add a new entry at the top of the blog posts section:

   ```html
   <article class="blog-entry">
     <div class="blog-meta">
       <span class="blog-date">Month Day, Year</span>
       <span class="blog-tag">Category</span>
     </div>
     <h2 class="blog-title">Your Post Title</h2>
     <p class="blog-excerpt">
       A brief 2-3 sentence summary of your post...
     </p>
     <a href="blog/posts/your-post-file.html" class="blog-read-more">Read more →</a>
   </article>
   ```

4. **Save and commit**:
   ```bash
   git add .
   git commit -m "Add new blog post: Your Title"
   git push
   ```

## 🚀 How to Add a New Project

Open `projects.html` and add a new project card:

```html
<div class="project-card">
  <div class="project-header">
    <h3 class="project-title">Your Project Name</h3>
    <div class="project-tech">
      <span class="tech-tag">Technology 1</span>
      <span class="tech-tag">Technology 2</span>
    </div>
  </div>
  <p class="project-description">
    Describe what your project does in simple terms that anyone can understand.
    Focus on the problem it solves or the value it provides.
  </p>
  <div class="project-links">
    <a href="your-github-link" class="project-link">View Code →</a>
    <a href="your-demo-link" class="project-link">See Live Demo →</a>
  </div>
</div>
```

## 🖼️ Adding Images to Blog Posts

1. Save your images in `assets/images/`
2. In your blog post HTML, add:
   ```html
   <img src="../../assets/images/your-image.jpg" alt="Description" style="max-width: 100%; border-radius: 8px; margin: 1.5rem 0;">
   ```

## ⚙️ Customization

### Update Your Personal Information

**In `index.html`**:
- Line 27: Update your name
- Line 28: Update your subtitle/title
- Lines 35-42: Update your bio
- Lines 93-95: Update your contact links (GitHub, LinkedIn, Email)

**In `blog.html` and `projects.html`**:
- Update the header logo if you want consistency

### Change Colors

Edit `css/style.css` and modify these variables (around line 2-14):

```css
:root {
  --accent-primary: #0066cc;     /* Main accent color (links, buttons) */
  --accent-secondary: #0052a3;   /* Hover state for accent elements */
  --text-primary: #212529;       /* Main text color */
  /* ... other variables */
}
```

Popular color schemes:
- **Blue** (current): `--accent-primary: #0066cc;`
- **Green**: `--accent-primary: #28a745;`
- **Purple**: `--accent-primary: #6f42c1;`
- **Orange**: `--accent-primary: #fd7e14;`

## 🌐 Deploying to GitHub Pages

1. **Push your code**:
   ```bash
   git add .
   git commit -m "Initial portfolio website"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click "Settings"
   - Scroll to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"

3. **Access your site**:
   - Your website will be live at: `https://yourusername.github.io`
   - It may take a few minutes to deploy

## 📝 Writing Tips for Blog Posts

- **Write clearly**: Use simple language that anyone can understand
- **Be conversational**: Write like you're explaining to a friend
- **Use examples**: Real-world examples help illustrate your points
- **Break it up**: Use headings, lists, and short paragraphs
- **Proofread**: Check for typos and grammatical errors before publishing

## 🛠️ Technologies Used

- HTML5
- CSS3 (Grid, Flexbox)
- Responsive Design
- GitHub Pages

## 📞 Need Help?

If you need help customizing this website or adding content, feel free to:
- Check the template files for examples
- Review this README for guidance
- Test changes locally before pushing to GitHub

## 📄 License

Feel free to use this template for your own portfolio website!

---

Built with care by Nithindev N
