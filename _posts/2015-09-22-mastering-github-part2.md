---
layout: post
title: "Mastering GitHub Part 2 : Versioning state and tags"
description: ""
category: null
tags: []
published: true
---

Then we were asked to look a bit on few things like file states, which is really important because Git works both locally and on a distant server. Plus if you work with other people it starts getting messy and you should always know if you modified something or if you're going to get a modified version of a file you didn't touched.

Check status of your local repository. What are the possible states?

Unmodified
modified
added
deleted
renamed
copied
updated but unmerged

How to view the history or log of your repository. Why is this useful?

![2.PNG]({{site.baseurl}}/assets/basic/2.PNG)

Push changes to GitHub from your local repository.
_Done in the previous article._

Pull changes from GitHub to your local repository.
_Done in the previous article._

Create an use Tags at the local repository leve.

![6.PNG]({{site.baseurl}}/assets/basic/6.PNG)

Push and  pull tags to the remote (GitHub) repository.

![7.PNG]({{site.baseurl}}/assets/basic/7.PNG)

Setup git aliases for your local configuration.

![8.PNG]({{site.baseurl}}/assets/basic/8.PNG)

Get git to ignore certain files. Why do we want to do this?

.gitignore is the best way to avoid sending to git files we don't want to be public or that are not source code

![9.PNG]({{site.baseurl}}/assets/basic/9.PNG)

Check out how Git is supported in your favourite editor. Does it just show information or does it have support for Git commands?

Visual Studio supports both GIT command-line and provides a GUI for Git since VS2013.

![10.PNG]({{site.baseurl}}/assets/basic/10.PNG)
