---
layout: post
title:"Git - no branches ready for upload"
date: 2013-04-15 10:09:07
categories: Git
tags: Git
---

You must do the following steps:

{% highlight sh %}
$ repo abandon <branch> <project>
$ repo start <branch> <project>
$ git reset --hard <latest-github-commit-id>
  (git add/commit)
$ repo upload <project>
{% endhighlight %}
