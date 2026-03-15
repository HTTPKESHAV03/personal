# Keshav's Portfolio Website

A modern, responsive portfolio website for Full Stack Developer Keshav, built with HTML, CSS, and JavaScript.

## 🚀 Live Demo
**Deploy Status:** Netlify  
**Live Site:** https://keshav-portfolio.netlify.app

## 📋 Features

- **Modern Design**: Clean, developer-style layout with dark theme
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Smooth scrolling navigation and hover effects
- **Skills Showcase**: Categorized skills with icons
- **Project Gallery**: Card-based project showcase
- **GitHub Integration**: Live GitHub stats and profile link
- **Contact Form**: Simple contact form for inquiries
- **Resume Download**: Direct download link for resume

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Grid and Flexbox
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icons for skills and social links
- **Boxicons**: Additional icon library

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript functionality
├── resume.pdf          # Resume file (placeholder)
├── images/             # Image assets folder
└── README.md           # This file
```

## 🚀 Deployment Instructions

### Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Repository name: `portfolio-website`
5. Make it **Public** (so Netlify can access it)
6. **Do NOT** initialize with README, .gitignore, or license
7. Click "Create repository"

### Step 2: Upload Portfolio Files

Upload the following files to your GitHub repository:

**Required Files:**
- `index.html` - Main website file
- `style.css` - Stylesheet
- `script.js` - JavaScript functionality
- `resume.pdf` - Your resume (replace placeholder)

**Optional:**
- `images/` folder - Add any images you want to use

**Upload Methods:**
- **GitHub Web Interface**: Drag and drop files into the repository
- **Git Commands** (if you have Git installed):

```bash
# Initialize git in your project folder
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial commit: Portfolio website"

# Add remote repository
git remote add origin https://github.com/YOUR_USERNAME/portfolio-website.git

# Push to GitHub
git push -u origin main
```

### Step 3: Connect to Netlify

1. Go to [Netlify.com](https://netlify.com) and sign in with your GitHub account
2. Click **"Add new site"** → **"Import an existing project"**
3. Choose **"Deploy with GitHub"**
4. Authorize Netlify to access your GitHub account
5. Select the `portfolio-website` repository from the list

### Step 4: Configure Deployment Settings

**Build Settings:**
- **Branch to deploy:** `main` (or `master` if you used that)
- **Build command:** Leave empty (this is a static site)
- **Publish directory:** `/` (root directory)

**Advanced Settings (Optional):**
- **Site name:** `keshav-portfolio` (or your preferred name)
- **Build status:** Enable build notifications if desired

Click **"Deploy site"**

### Step 5: Enable Automatic Deployment

Netlify automatically enables continuous deployment! Every time you push changes to your GitHub repository:

1. GitHub notifies Netlify of the changes
2. Netlify automatically rebuilds and redeploys your site
3. The live site updates within minutes

**To test auto-deployment:**
1. Make a small change to your code (e.g., update the about text)
2. Commit and push to GitHub
3. Watch Netlify automatically deploy the changes

## 📊 Deployment Workflow

```
Local Computer
      ↓ (git push)
GitHub Repository
      ↓ (webhook)
   Netlify
      ↓ (build & deploy)
Live Portfolio Website
   https://keshav-portfolio.netlify.app
```

**Workflow Steps:**
1. **Develop locally** - Make changes to your code
2. **Commit & Push** - Send changes to GitHub
3. **Auto-deploy** - Netlify detects changes and rebuilds
4. **Live updates** - Website automatically updates

## 🔧 Customization

### Changing Colors
Edit the CSS custom properties in `style.css`:

```css
:root {
  --bg-color: #0F172A;
  --primary-color: #3B82F6;
  --accent-color: #8B5CF6;
  --text-color: #F1F5F9;
  --card-bg: #1E293B;
}
```

### Adding Projects
Add new project cards in the `projects-grid` section of `index.html`:

```html
<div class="project-card">
    <div class="project-image">
        <div class="image-placeholder">
            <i class="fas fa-code"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="tech-stack">
            <span class="tag">Tech1</span>
            <span class="tag">Tech2</span>
        </div>
        <a href="#" class="github-btn">
            <i class="fab fa-github"></i> View on GitHub
        </a>
    </div>
</div>
```

### Updating GitHub Stats
Replace `HTTPKESHAV03` in the GitHub stats URL with your actual GitHub username.

## 📞 Contact

**Keshav**  
Full Stack Developer  
Email: your.email@example.com  
GitHub: https://github.com/HTTPKESHAV03

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ by Keshav**</content>
<parameter name="filePath">d:\K\portfolio\README.md