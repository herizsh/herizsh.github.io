---
title: How to Setup Jekyll
date: 2024-01-27 02:49:31 +0700
categories: [jekyll, github, github-pages]
tags: [jekyll]
---

## Introduction

Jekyll is a simple, blog-aware, static site generator perfect for personal, project, or organization sites. Using Jekyll, you can transform plain text into static websites and blogs. It is an excellent tool for creating a site hosted on GitHub Pages without much hassle.

## Prerequisites

Before you begin, ensure you have a basic understanding of:

- HTML/CSS
- Markdown
- Ruby programming (basic)
- Git and GitHub

## Step 1: Install Ruby and Jekyll

Jekyll is a Ruby Gem, so you first need to install Ruby. The installation process varies based on your operating system:

- **Windows:** Use [RubyInstaller](https://rubyinstaller.org/)
- **macOS:** Ruby comes pre-installed, but you may need to update it.
- **Linux:** Installation commands vary by distribution.

After installing Ruby, install Jekyll and Bundler:

```bash
gem install jekyll bundler
```

## Step 2: Create a New Jekyll Site

Creating a new Jekyll site is straightforward. Run:

```bash
jekyll new my-awesome-site
cd my-awesome-site
```

## Step 3: Build and Run Your Site Locally

To build your site and make it available on a local server:

```bash
bundle exec jekyll serve
```

You can now view your new website at `http://localhost:4000`.

## Step 4: Customize Your Site

Customize your site by editing the `_config.yml` file and adding posts in the `_posts` directory. Jekyll uses the Liquid template language for templating.

## Step 5: Deploying to GitHub Pages

Deploy your site by:

1. Creating a GitHub repository.
2. Pushing your code to the repository.
3. Setting up GitHub Pages in the repository settings.

Your site should now be live!

## Conclusion

Congratulations! You've just set up a website with Jekyll and GitHub Pages. Explore further to customize and enhance your site.

---
