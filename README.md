# 👋 Hi, I'm Jake!

Welcome to my data analytics portfolio! This site showcases my projects, skills, and journey as a data analyst using the Jekyll minima theme with a solarized-dark skin.

## 🏗️ Site Structure

This portfolio site includes the following pages:

- **Home** (`/`) - Landing page with professional introduction
- **About** (`/about/`) - Detailed background, skills, and technical expertise
- **Projects** (`/projects/`) - Showcase of data science projects and work
- **Contact** (`/contact/`) - Contact information and collaboration opportunities
- **Blog Posts** - Sample blog post in the data science category

## 🚀 Getting Started

### Local Development

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Serve the site locally:**
   ```bash
   bundle exec jekyll serve
   ```

3. **View the site:**
   Open `http://localhost:4000` in your browser

### GitHub Pages Deployment

This site is configured for GitHub Pages deployment:
- Push changes to the `main` branch
- GitHub Pages will automatically build and deploy your site
- Your site will be available at `https://jworking2.github.io`

## 📝 Customization Guide

### 1. Update Your Information

**_config.yml** - Update site settings:
- Change `title`, `author`, `email`
- Update `description`
- Replace social media URLs in `social_links`

**Contact Page** (`contact.md`):
- Replace placeholder social media URLs
- Update email address and location information
- Customize collaboration opportunities section

### 2. Add Your Projects

**Projects Page** (`projects.md`):
- Replace sample projects with your actual work
- Update GitHub repository URLs
- Add live demo links
- Include screenshots or project images

### 3. Customize About Page

**About Page** (`about.md`):
- Add your personal story and background
- Update technical skills with your expertise
- Customize the specializations section
- Add your actual experience and achievements

### 4. Add Blog Posts

Create new blog posts in the `_posts` directory:
```
_posts/YYYY-MM-DD-post-title.md
```

Each post should have front matter:
```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS -0400
categories: [category1, category2]
tags: [tag1, tag2]
---
```

### 5. Theme Customization

The site uses the minima theme with solarized-dark skin. To change:
- Edit `minima.skin` in `_config.yml`
- Available skins: `classic`, `dark`, `auto`, `solarized-light`, `solarized-dark`, `solarized`

## 📂 File Structure

```
├── _config.yml          # Site configuration
├── _posts/              # Blog posts directory
├── about.md             # About page
├── contact.md           # Contact page
├── index.md             # Home page
├── projects.md          # Projects showcase
├── Gemfile              # Ruby dependencies
├── .gitignore           # Files to ignore in git
└── README.md            # This file
```

## 🛠️ Built With

- **Jekyll** - Static site generator
- **Minima Theme** - Clean, responsive Jekyll theme
- **GitHub Pages** - Free hosting for Jekyll sites
- **Markdown** - Easy content writing

## 📚 Next Steps

1. **Personalize Content**: Replace all placeholder content with your information
2. **Add Real Projects**: Include your actual data science projects with descriptions
3. **Customize Design**: Modify colors, fonts, or layout if desired
4. **Add Images**: Include project screenshots, headshots, or visualizations
5. **SEO Optimization**: Update meta descriptions and titles
6. **Analytics**: Consider adding Google Analytics for visitor tracking

## 💡 Tips

- Use the `bundle exec jekyll serve --livereload` command for automatic page refresh during development
- Test your site locally before pushing to GitHub
- Keep project descriptions concise but informative
- Include links to live demos or GitHub repositories
- Update your blog regularly with data science insights

---

*This portfolio site was created to showcase data analytics skills and projects. Feel free to customize it to match your personal brand and professional goals!*
