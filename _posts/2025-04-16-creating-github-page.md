---
layout: post
title:  "Creating a GitHub page"
date:   2025-04-16 16:06:00 -0300
categories: jekyll github
---

This page was created using [Jekyll](https://jekyllrb.com/) and of course, hosted on [GitHub](https://www.github.com).

This post is intended to go through the steps to properly set up a page.

# Creating the repository

Just follow the instructions on [GitHub pages](https://pages.github.com/) main page.

# Setting-up Jekyll

Follow the procedures on [GitHub pages docs](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll).

Mind the following:
- Jekyll is not officially supported on Windows, so Linux is the recommended choice here if you want to test your page locally.
- You can also use the [GitHub online editor](https://github.dev/) if you're not interested in the local testing

Also, don't forget to choose a theme and also set it properly.

# Creating content

Now you have a page set up, your content can be created just by adding markdown files

- Blog post

    All blog posts will be inside the `/_posts/` folder, and their names must be on the format: `YYYY-MM-DD-post-title.md`

    Those files will have a header, called front matter in this context in this format, like the one from ths very post:

    ```yaml
    ---
    layout: post
    title:  "Creating a GitHub page"
    date:   2025-04-16 16:06:00 -0300
    categories: jekyll github
    ---
    ```

    After that, just write the content with markdown syntax and you'll have a post like this one!