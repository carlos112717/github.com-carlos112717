---
layout: post
title: hard and symbolic links in Linux
---
                    ({{ site.baseurl }}/images/config.png)
In Linux, each of the files is represented by an inode, a kind of unique serial code that contains all the information about the data that can be found in that file.

A hard link is nothing more than a label or a new name associated with an inode. It is a way of identifying the same content with different names. This link is not a separate copy of the above file but a different name for exactly the same content.

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.
