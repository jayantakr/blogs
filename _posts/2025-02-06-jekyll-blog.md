---
layout: post
title: "Full SetUp of Jekyll"
author: "Jayanta Kumar Kamila"
date: 2025-02-06
description: "A comprehensive guide on setting up a Jekyll blog using GitHub Pages, covering installation, configuration, deployment, and customization—all without using any external tools."
---


### **Full setup of Jekyll on GitHub Pages**

Here's a minimalist approach to setting up Jekyll on GitHub Pages using only the _config.yml and .md files. No external tools or plugins—just pure Jekyll and GitHub Pages. So to setup this follow the following steps:

(/blogs/images/blog.png)

### **Steps 1: Create a GitHub Repository**
1. Go to `GitHub` and log in.
2. Click **New Repository**.
3. Name: `Blogs` (also you can give any other name)
(This is required for GitHub Pages hosting.)
4. Choose **Public.**
5. Click **Create Repository.**
(/blogs/images/repo create.png)

### **Step 2: Add Jekyll Files to Your Repository**

# *1. Create `_config.yml`*
This file tells GitHub how to build your Jekyll site.

1. In your GitHub repository, click **Add file > Create new file**.

2. Name it **_config.yml**.

3. Write some content inside the file, like

```
---
title: "My Blog"
author: "Jayanta Kumar Kamila"
description: "A personal blog created using Jekyll."
baseurl: "/blogs"
url: "https://jayantakr.github.io" ("https://username-github.github.io")
theme: minima
---

```
4. Click **Commit changes.**


# *2. Create an `index.md` File*
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


# *3. Create a `_posts` Directory*
This is where your blog posts will go.

1. In your repository, **click Add file > Create new file.**

2. Name it `_posts/2025-02-08-Jekyll-Setup.md.`

3. Write some content inside the file like 

```
---
layout: post
title: "Full Jekyll Setup"
date: 2025-02-08
categories: [Blog, Personal]
---

```

Welcome to my first blog post! This is a simple post written using Markdown.

4. Click **Commit changes.**


### **Step 3: Enable GitHub Pages (as live)**

1. Go to **Settings > Pages in your GitHub repository.**

(/blogs/images/pic.jpg)

(/blogs/images/pic1.jpg)
2. Under **"Branch", select main.**
(/blogs/images/pic3.png)
3. Click Save.

### **Step 4: Add More Blog Posts**
To add a new post, follow these steps:
1. Click **Add file > Create new file.**
2. Name it in the format:
`_posts/YYYY-MM-DD-title.md`
3. Write the content:

```
---
layout: post
title: "Second Blog Post"
date: 2025-02-09
categories: [Thoughts]
---

```

This is my second blog post.
4. Click **Commit changes**.


### **Step 5: Customize Your Blog**
Edit **_config.yml** to personalize:
- Change the **title** and **description**.
- Modify the **theme**.(Choose the theme whichi will be suitable for your blog)

### **Conclusion: How to setup of Jekyll on Github Pages?**
With this configuration, you now have a complete Jekyll-powered blog hosted for free on GitHub Pages with only `_config.yml` and `.md` files—no complicated installations! Your blog is lightweight, customizable, and entirely in your control.
With this easy yet powerful configuration, you now have a complete website that is:
- **Free to host on GitHub Pages**
- **Simple to manage with Markdown**
- **Customizable with themes and plugins**
- **SEO-friendly using Jekyll's native capabilities**

This tutorial took you through setting up your repository, setting up Jekyll, creating posts, setting up GitHub Pages, and customizing your site—all with minimal work.
