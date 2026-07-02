# Ocean of Opportunities
### Demo: https://kuwushagra.github.io/Ocean-of-Opportunities/
![GIF Showcasing the theme](https://github.com/kuwushagra/kuwushagra.github.io/blob/main/assets/images/project_screenshots/Ocean-of-Opportunities.gif?raw=true)
<br>Showcase yourself in the Ocean of Opportunities! A Jekyll powered personal portfolio website theme <br>
<hr>

## Quick Start (GitHub Pages)

### Step 1: Fork and Rename
1. Click the **Fork** button at the top-right corner of this repository.
2. Go to your new fork's **Settings** tab.
3. Rename the repository to `YOUR_USERNAME.github.io` (replace `YOUR_USERNAME` with your actual GitHub username).

### Step 2: Enable GitHub Pages
1. Inside your repository, go to **Settings** > **Pages** (under the "Code and automation" section).
2. Under **Build and deployment**, set the source to **Deploy from a branch**.
3. Choose the branch (e.g., `main` or `master`) and folder (`/(root)`).
4. Click **Save**. Your site will be live at `https://YOUR_USERNAME.github.io` within a few minutes!

---

## Configuration & Customization

All major settings are managed in the `_config.yml` file. Open this file and update the following fields:

* **Site Settings:** Update the `title`, `description`, and `author` name.
* **URLs:** Set `url` to `https://YOUR_USERNAME.github.io`. Ensure `baseurl` is set to `""` (blank) if you are using a user site.
* **Social Links:** Fill in your username handle for GitHub, and E-mail to activate navbar social links.

### Adding New Posts
To write a new blog post, create a markdown file inside the `_posts` directory. Use the following naming convention:
`YYYY-MM-DD-title-of-your-post.md`

Every post must start with front matter metadata:
```yaml
---
layout: post
title: "My First Blog Post"
date: YYYY-MM-DD HH:MM:SS +0000
image: https://linktoimage
categories: [category1]
tags: [tag1]
---
Your content goes here...
```

---

## Local Development

If you want to test changes on your computer before pushing them to GitHub:

### Prerequisites
Make sure you have [Ruby](https://ruby-lang.org) and [Bundler](https://bundler.io) installed.

### Setup Instructions
1. Clone your repository to your machine:
   ```bash
   git clone https://github.com
   cd YOUR_USERNAME.github.io
   ```
2. Install the required dependencies:
   ```bash
   bundle install
   ```
3. Run the local Jekyll server:
   ```bash
   bundle exec jekyll serve
   ```
4. Open your browser and navigate to `http://localhost:4000`.

---

## License

This theme is open-source and available under the [Apache 2.0 License](LICENSE).
