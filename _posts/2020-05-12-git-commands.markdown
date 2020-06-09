---
layout: post
title:  "Git Commands"
date:   2020-05-12 14:34:57 +0100
categories: git
excerpt: Some useful Git commands
sticky: true
---

Here are some useful Git commands..

**Clone repository**

    git clone path_to_repository

**Pull and overwrite existing changes**

    git fetch --all
    git reset --hard origin/master

**Set Windows integrated authentication**

    git config --global credential.http://servername:port.integrated true

**Store credentials in repo config (WARNING: stores credentials in plain text)**

    git remote set-url origin https://<USERNAME>:<PASSWORD>@github.com/path/to/repo.git

**Store credentials locally in credentials store (WARNING: stores credentials in plain text**

    git config --global credential.helper store
