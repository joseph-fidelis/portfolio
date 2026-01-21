# Fidelis Uwem Joseph - Personal Portfolio & Blog

A modern, responsive personal website and blog built with [MkDocs](https://www.mkdocs.org/) and the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme. This portfolio showcases my work as a software engineer specializing in enterprise-grade systems across mobile, web, backend, automation, and cloud infrastructure.

**Live Site:** [https://charmides.github.io](https://charmides.github.io)

## 🎯 About

This repository contains the source code for my personal portfolio website. It's a comprehensive showcase of my expertise in:

- **Full-Stack Engineering** - End-to-end application design and development
- **Mobile Engineering** - iOS, Android, and cross-platform mobile solutions
- **Backend Development** - Scalable systems using PHP (Laravel, SlimPHP) and Python (FastAPI, Django)
- **Automation & DevOps** - Infrastructure automation and operational excellence
- **Technical Writing** - Blog posts on software engineering best practices

## 📁 Project Structure

```
.
├── mkdocs.yml              # MkDocs configuration
├── requirements.txt        # Python dependencies
├── README.md              # This file
└── docs/
    ├── index.md           # Home page
    ├── tags.md            # Blog tags page
    ├── about/             # Resume and expertise showcase
    │   ├── index.md       # Overview with role cards
    │   ├── fullstack.md   # Full-stack engineering details
    │   ├── mobile.md      # Mobile engineering details
    │   └── automations.md # Automation & DevOps details
    ├── projects/          # Project showcase
    │   └── index.md
    ├── blog/              # Blog posts and articles
    │   ├── index.md
    │   └── posts/         # Individual blog post articles
    ├── skill/             # Skill documentation
    │   ├── backend.md
    │   ├── mobile.md
    │   ├── library.md
    │   └── automations.md
    └── assets/            # Images and static assets
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip (Python package manager)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Serve locally**
   ```bash
   mkdocs serve
   ```
   
   The site will be available at `http://localhost:8000`

## 📦 Dependencies

This project uses:

- **mkdocs** (1.6.1) - Static site generator
- **mkdocs-material** (9.6.12) - Material Design theme for MkDocs
- **mkdocs-blog-plugin** (0.25) - Blog functionality with post metadata
- **mkdocs-material-extensions** (1.3.1) - Extended features for Material theme
- **Markdown** (3.8) - Markdown processor
- **pymdown-extensions** (10.15) - Additional Markdown extensions
- **python-dateutil** (2.9.0.post0) - Date utilities for blog posts
- **PyYAML** (6.0.2) - YAML parser for configuration

## 🎨 Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Dark/Light Mode** - Automatic theme switching based on system preferences
- **Fast Navigation** - Instant page loads with smooth transitions
- **Blog with Categories** - Organized blog posts with tags and reading time estimates
- **Search** - Built-in full-text search across all content
- **Social Integration** - Links to GitHub, LinkedIn, Instagram, Twitter, and YouTube
- **Mobile Optimized** - Progressive enhancement for all device sizes
- **SEO Friendly** - Optimized metadata and structured content

## ✍️ Writing Content

### Adding a Blog Post

1. Create a new `.md` file in `docs/blog/posts/`
2. Add front matter with metadata:
   ```yaml
   ---
   date: 2024-01-21
   categories:
     - Performance
   authors:
     - name: Fidelis Uwem Joseph
   ---
   ```
3. Write your content in Markdown
4. The blog plugin automatically generates listings and categories

### Adding a Project

1. Update or create content in `docs/projects/index.md`
2. Follow the existing structure and styling

## 🚢 Deployment

The site is automatically deployed to GitHub Pages using GitHub Actions.

To manually deploy:

```bash
mkdocs gh-deploy
```

This builds the site and pushes it to the `gh-pages` branch.

## 🔗 Connect

- **GitHub:** [@joseph-fidelis](https://github.com/joseph-fidelis)
- **LinkedIn:** [Fidelis Joseph Uwem](https://www.linkedin.com/in/fidelis-joseph-uwem/)
- **Instagram:** [@le_charmides](https://www.instagram.com/le_charmides/)
- **Twitter:** [@charmides](https://twitter.com/charmides)
- **YouTube:** [@charmides](https://www.youtube.com/@charmides)

## 📝 License

This portfolio and its content are personal projects. Please refer to any specific licenses mentioned in individual sections or contact me for usage inquiries.

## 📧 Contact

For inquiries or collaboration opportunities, please reach out through any of the social channels listed above.


