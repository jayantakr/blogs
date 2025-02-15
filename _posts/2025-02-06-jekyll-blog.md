---
layout:post
title: "Jayanta's Blog"
author: "Jayanta Kumar Kamila"
date:2025-02-06
description: "A personal blog created using Jekyll."
---
# Full setup of Jekyll on Github Pages

Here's a minimalist approach to setting up Jekyll on GitHub Pages using only the _config.yml and .md files. No external tools or plugins—just pure Jekyll and GitHub Pages. So to setup this follow the following steps:

## Steps 1: Create a GitHub Repository
1. Go to `GitHub` and log in.
2. Click **New Repository**.
3. Name: `Blogs` (also you can give any other name)
(This is required for GitHub Pages hosting.)
4. Choose **Public.**
5. Click **Create Repository.**


## Step 2: Add Jekyll Files to Your Repository
### 1. Create `_config.yml`
This file tells GitHub how to build your Jekyll site.

1. In your GitHub repository, click **Add file > Create new file**.

2. Name it **_config.yml**.

3. Write some content inside the file, like
```

title: "My Blog"
author: "Jayanta Kumar Kamila"
description: "A personal blog created using Jekyll."
baseurl: "/blogs"
url: "https://jayantakr.github.io" ("https://username-github.github.io")
theme: minima

```
4. Click **Commit changes.**

### 2. Create an index.md File
This is your homepage.

1. Click **Add file > Create new file.**

2. Name it **index.md**.

3. Write some content inside this, like 

```
---
layout: default
title: "BLOG"
---

```
4. Click **Commit changes.**

### 3. Create a _posts Directory
This is where your blog posts will go.

1. In your repository, **click Add file > Create new file.**

2. Name it `_posts/2025-02-08-Jekyll-Setup.md.`

3. Write some content inside the file like 

---
layout: post
title: "Full Jekyll Setup"
date: 2025-02-08
categories: [Blog, Personal]
---

Welcome to my first blog post! This is a simple post written using Markdown.

4. Click **Commit changes.**

## Step 3: Enable GitHub Pages(as live)

1. Go to **Settings > Pages in your GitHub repository.**
2. Under **"Branch", select main.**
3. Click Save.

## Step 4: Add More Blog Posts
To add a new post, follow these steps:
1. Click **Add file > Create new file.**
2. Name it in the format:
`_posts/YYYY-MM-DD-title.md`
3. Write the content:
---
layout: post
title: "Second Blog Post"
date: 2025-02-09
categories: [Thoughts]
---

This is my second blog post.
4. Click **Commit changes**.

## Step 5: Customize Your Blog
Edit **_config.yml** to personalize:
- Change the **title** and **description**.
- Modify the **theme**.(Choose the theme whichi will be suitable for your blog)

By this way you can have a **fully working Jekyll blog** using just _config.yml and .md files.