---
title: How to Use the Chirpy Theme in Jekyll
date: 2024-01-27 02:53:31 +0700
categories: [jekyll, themes, chirpy]
tags: [jekyll, chirpy, tutorial]
---

## Introduction

The Chirpy theme is a versatile and powerful theme for Jekyll, perfect for bloggers and developers alike. It offers a range of features like a mobile-friendly design, dark/light mode, and extensive documentation. This tutorial will guide you through setting up the Chirpy theme on a Jekyll site.

## Prerequisites

Before starting, make sure you have:

- Basic knowledge of terminal/command line usage
- Git installed on your system
- A GitHub account (if you plan to deploy on GitHub Pages)

## Step 1: Fork the Chirpy Repository

First, fork the official [Chirpy theme repository](https://github.com/cotes2020/jekyll-theme-chirpy/) on GitHub to your account.

## Step 2: Clone the Repository

Clone the forked repository to your local machine:

```bash
git clone https://github.com/[your-username]/[your-username].github.io.git
cd [your-username].github.io
```

## Step 3: Install Jekyll and Dependencies

Ensure you have Jekyll installed. If not, install it along with other dependencies:

```bash
gem install jekyll bundler
bundle install
```

## Step 4: Run Locally

To run your site locally:

```bash
bundle exec jekyll s
```

You can view the site at `http://localhost:4000`.

## Step 5: Customize Your Site

Edit the `_config.yml` file to customize site settings. Add posts in the `_posts` directory. Chirpy uses markdown files for blog posts.

## Step 6: Deploying Your Site

### GitHub Pages

1. Push your changes to GitHub.
2. Enable GitHub Pages in the repository settings, using the `main` branch.

### Other Platforms

Follow the specific platform's documentation for deployment instructions.

## Conclusion

You've now successfully set up a Jekyll site using the Chirpy theme. Explore the [theme's documentation](https://chirpy.cotes.page/docs/) for more customization options and features.

---
