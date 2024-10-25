---
slug: long-blog-post
title: Long Blog Post
authors: yangshun
tags: [hello, docusaurus]
---

This is the summary of a very long blog post,

Use a `<!--` `truncate` `-->` comment to limit blog post size in the list view.

<!-- truncate -->

# Connect Local Git Repository to GitHub using SSH
```
ssh-keygen -t ed25519 -C "bachchu333@gmail.com"
ls ~/.ssh/
cd ~/.ssh/
cat .pub
[open github > setting >ssh and gpg]
```
## git configure
```
git config --global user.name "Mir"
git config --global --get user.name
git config --global user.email your_email@gmail.com
git config --global --get user.email
```
## Create Repository on GitHub
## Push your code-base into GitHub
```