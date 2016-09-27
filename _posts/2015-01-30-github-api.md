---
layout:     post
title:      Merge Branches on Github via API
date:       2015-01-30 22:53:00
summary:    If you host your Git repository on Github you may consider using the Github API for automation.
categories: software_development
---

If you host your Git repository on Github you may consider using the Github API for merge automation. The main benefit is that you won't need a local repository. Instead all operations are done on the Github servers. If I caught your attention, [take a look at my project on Github](https://github.com/thorbenegberts/github-api-merge-script). Feel free to use, fork or tear it to pieces to match your own needs. The script is based on the [ruby flavour of Octokit](https://github.com/octokit/octokit.rb).