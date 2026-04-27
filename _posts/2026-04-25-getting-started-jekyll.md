---
layout: default
title: "Getting Started with Jekyll & GitHub Pages"
date: 2026-04-26
excerpt: "Learn how to set up a beautiful blog using Jekyll and GitHub Pages in just a few minutes."
---

# Getting Started with Jekyll & GitHub Pages

Jekyll and GitHub Pages are a match made in heaven for developers who want a simple, fast, and free blogging platform. In this post, I'll walk you through the basics.

## What is Jekyll?

Jekyll is a **static site generator** that transforms your plain text files into a beautiful website. It's:
- **Fast** - No database queries, just static HTML
- **Secure** - No server-side code to hack
- **Simple** - Write in Markdown, deploy with git

## Why GitHub Pages?

GitHub Pages provides **free hosting** directly from your GitHub repository. It has built-in Jekyll support, which means you can:
- Write posts in Markdown
- Push to GitHub
- Your site updates automatically

## Getting Started

1. **Install Ruby** - Download from [rubyinstaller.org](https://rubyinstaller.org/)
2. **Install Jekyll** - Run `gem install jekyll bundler`
3. **Create a new site** - Run `jekyll new my-blog`
4. **Run locally** - Run `bundle exec jekyll serve`
5. **Visit** - Open `http://localhost:4000`

## Creating Your First Post

Create a file in `_posts/` folder with the format: `YYYY-MM-DD-title.md`

```markdown
---
layout: post
title: "My First Post"
date: 2026-04-26
---

# Hello World!

This is my first post written in Markdown.
```

## Deploying to GitHub Pages

1. Push your site to GitHub
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" → main branch
4. Your site will be live at `https://yourusername.github.io`

That's it! You now have a live blog! 🎉

---

**Next Steps:**
- Customize your theme
- Add more posts
- Connect a custom domain
- Add comments (using Disqus or similar)

Happy blogging!
