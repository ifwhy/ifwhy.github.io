# 🎓 Academic Portfolio - Ivan Wahyu Nugroho

<div align="center">

[![Jekyll](https://img.shields.io/badge/Jekyll-4.0+-CC0000?style=for-the-badge&logo=jekyll&logoColor=white)](https://jekyllrb.com/)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-327FC7?style=for-the-badge&logo=github&logoColor=white)](https://pages.github.com/)
[![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)](https://www.ruby-lang.org/)
[![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)](https://sass-lang.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://javascript.com/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fifwhy.github.io&style=for-the-badge&logo=github&label=Portfolio)](https://ifwhy.github.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Last Commit](https://img.shields.io/github/last-commit/ifwhy/ifwhy.github.io?style=for-the-badge&logo=github)](https://github.com/ifwhy/ifwhy.github.io)

</div>

---

## 📋 Table of Contents

- [🎯 About](#-about)
- [✨ Features](#-features)
- [🚀 Quick Start](#-quick-start)
- [💻 Local Development](#-local-development)
  - [🛠️ Prerequisites](#️-prerequisites)
  - [📦 Installation](#-installation)
  - [🔧 Using Different IDEs](#-using-different-ides)
  - [🐳 Using Docker](#-using-docker)
  - [📝 Using VS Code DevContainer](#-using-vs-code-devcontainer)
- [📂 Project Structure](#-project-structure)
- [🎨 Customization](#-customization)
- [📱 Deployment](#-deployment)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)

---

## 🎯 About

**Welcome to my academic portfolio!** 👋

This is a professional academic website built with **Jekyll** and hosted on **GitHub Pages**. It serves as a comprehensive showcase of my academic journey, including research publications, teaching experience, blog posts, and more.

> 🌟 **Live Website**: [ifwhy.github.io](https://ifwhy.github.io)

### 👤 About Me

- **Name**: Ivan Wahyu Nugroho
- **Affiliation**: Universitas Sebelas Maret
- **Location**: Boyolali, Central Java, Indonesia
- **Interests**: Mathematics, Computer Science, Academic Research

---

## ✨ Features

🎨 **Modern Design**: Clean, professional, and responsive academic template  
📱 **Mobile-First**: Optimized for all devices and screen sizes  
📚 **Publication Management**: Showcase your research papers and citations  
🎤 **Talks & Presentations**: Display your conference talks and seminars  
👨‍🏫 **Teaching Portfolio**: Highlight your teaching experience and courses  
📝 **Academic Blog**: Share insights with integrated blog functionality  
🔍 **SEO Optimized**: Built-in search engine optimization  
🌙 **Dark Mode Support**: Toggle between light and dark themes  
📊 **Analytics Integration**: Track your website performance  
🚀 **Fast Loading**: Optimized for speed and performance

---

## 🚀 Quick Start

Ready to create your own academic portfolio? Follow these simple steps:

### 1. 📋 Prerequisites

- GitHub account (with verified email)
- Basic knowledge of Git and Markdown
- Text editor (VS Code recommended)

### 2. 🔧 Setup Your Repository

1. **Fork this repository** or use it as a template
2. **Rename** your repository to `[your-username].github.io`
3. **Clone** the repository to your local machine:
   ```bash
   git clone https://github.com/[your-username]/[your-username].github.io.git
   cd [your-username].github.io
   ```

### 3. ⚙️ Configure Your Site

1. **Edit `_config.yml`** with your personal information
2. **Replace** the avatar image in `/images/` folder
3. **Update** your content in the respective directories
4. **Commit and push** your changes

### 4. 🌐 Go Live

1. Enable **GitHub Pages** in your repository settings
2. Your site will be available at `https://[your-username].github.io`
3. Changes typically take 1-10 minutes to appear live

---

## 💻 Local Development

Want to preview your changes before publishing? Set up local development:

### 🛠️ Prerequisites

Make sure you have the following installed:

- **Ruby** (version 2.7 or higher)
- **Node.js** (for asset compilation)
- **Git** (for version control)

### � Setup Instructions

### 📦 Installation

#### 🐧 Linux/WSL:

```bash
sudo apt install ruby-dev ruby-bundler nodejs
```

If you encounter package errors, update first:

```bash
sudo apt update && sudo apt upgrade -y
```

#### 🍎 MacOS:

```bash
brew install ruby node
gem install bundler
```

#### 🪟 Windows:

- Install [Ruby+Devkit](https://rubyinstaller.org/)
- Install [Node.js](https://nodejs.org/)
- Run `gem install bundler` in Command Prompt

### 🔧 Using Different IDEs

1. **Install dependencies** using the commands above
2. **Install Ruby gems**:

   ```bash
   bundle install
   ```

   > 💡 **Permission Issues?** Use local installation:
   >
   > ```bash
   > bundle config set --local path 'vendor/bundle'
   > bundle install
   > ```

3. **Start the development server**:

   ```bash
   jekyll serve -l -H localhost
   ```

   or use bundle exec for consistency:

   ```bash
   bundle exec jekyll serve -l -H localhost
   ```

4. **Open your browser** to `http://localhost:4000`

> 🔄 The server automatically rebuilds and refreshes on file changes!

### 🐳 Using Docker

Prefer containerized development? Use Docker:

```bash
chmod -R 777 .
docker compose up
```

Access your site at `http://localhost:4000`

### 📝 Using VS Code DevContainer

Using VS Code? Take advantage of the included dev container:

1. **Open project** in VS Code
2. **Press F1** → "Dev Container: Reopen in Container"
3. **Wait for setup** (automatic)
4. **Access site** at `http://localhost:4000`

---

## 📂 Project Structure

```
academic-pages/
├── 📁 _data/           # Site data (navigation, CV, etc.)
├── 📁 _includes/       # Reusable HTML components
├── 📁 _layouts/        # Page layouts
├── 📁 _pages/          # Static pages (about, CV, etc.)
├── 📁 _posts/          # Blog posts
├── 📁 _publications/   # Research publications
├── 📁 _talks/          # Conference talks
├── 📁 _teaching/       # Teaching experience
├── 📁 _sass/           # Styling (SCSS)
├── 📁 assets/          # CSS, JS, fonts
├── 📁 files/           # Downloadable files (PDFs, etc.)
├── 📁 images/          # Images and avatars
├── 📄 _config.yml      # Main site configuration
├── 📄 Gemfile          # Ruby dependencies
└── 📄 package.json     # Node.js dependencies
```

---

## 🎨 Customization

### 🎯 Basic Configuration

Edit `_config.yml` to customize:

- **Personal Information**: Name, bio, location
- **Social Links**: GitHub, LinkedIn, Twitter, etc.
- **Site Settings**: Title, description, URL
- **Analytics**: Google Analytics integration

### 🖼️ Adding Content

#### 📝 Blog Posts

Create new files in `_posts/` following the naming convention:

```
YYYY-MM-DD-post-title.md
```

#### 📚 Publications

Add your papers in `_publications/` with metadata:

```yaml
---
title: "Your Paper Title"
date: 2024-01-01
venue: "Conference Name"
paperurl: "http://link-to-paper.pdf"
---
```

#### 🎤 Talks

Document your presentations in `_talks/`:

```yaml
---
title: "Talk Title"
date: 2024-01-01
venue: "Conference/Event"
location: "City, Country"
---
```

### 🎨 Styling

- **Colors**: Edit `_sass/_variables.scss`
- **Layouts**: Modify files in `_layouts/`
- **Components**: Update `_includes/` files

---

## 📱 Deployment

### 🚀 GitHub Pages (Recommended)

1. **Push your changes** to the main branch
2. **Enable GitHub Pages** in repository settings
3. **Select source**: Deploy from branch (main)
4. **Custom domain** (optional): Add CNAME file

### 🌐 Other Platforms

This Jekyll site can also be deployed to:

- **Netlify**: Drag and drop deployment
- **Vercel**: Git integration
- **AWS S3**: Static hosting
- **Your own server**: Build and upload `_site/`

---

## 🤝 Contributing

Found a bug or want to suggest an improvement?

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature-name`
3. **Commit** your changes: `git commit -m 'Add feature'`
4. **Push** to branch: `git push origin feature-name`
5. **Submit** a pull request

### 🐛 Reporting Issues

- **Bug Reports**: [Submit via GitHub Issues](https://github.com/ifwhy/ifwhy.github.io/issues)
- **Feature Requests**: [Start a Discussion](https://github.com/ifwhy/ifwhy.github.io/discussions)

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### 🙏 Acknowledgments

This site is built using the **Academic Pages** template downloaded from:

> 📥 **Original Repository**: [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io)

This amazing template is built on top of:

- **[Academic Pages](https://academicpages.github.io/)** - Original template
- **[Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)** - Jekyll theme foundation
- **[Jekyll](https://jekyllrb.com/)** - Static site generator
- **[GitHub Pages](https://pages.github.com/)** - Hosting platform

Special thanks to the maintainers:

- [Stuart Geiger](https://github.com/staeiou) - Original template creator
- [Robert Zupko](https://github.com/rjzupkoii) - Current maintainer
- [Michael Rose](https://github.com/mmistakes) - Minimal Mistakes theme

---

## 🌟 If this helped you, consider giving it a star

[![GitHub stars](https://img.shields.io/github/stars/ifwhy/ifwhy.github.io?style=social)](https://github.com/ifwhy/ifwhy.github.io)
[![GitHub forks](https://img.shields.io/github/forks/ifwhy/ifwhy.github.io?style=social)](https://github.com/ifwhy/ifwhy.github.io/fork)

### Happy coding! 🚀
