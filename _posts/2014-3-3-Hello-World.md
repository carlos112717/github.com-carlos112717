---
layout: post
title: Hard and symbolic links in Linux
---
                                                      ![imagen linux]({{ site.baseurl }}/images/linux-img.jpg)
                                                      
In Linux, each of the files is represented by an inode, a kind of unique serial code that contains all the information about the data that can be found in that file.

A hard link is nothing more than a label or a new name associated with an inode. It is a way of identifying the same content with different names. This link is not a separate copy of the above file but a different name for exactly the same content.

                                                         ![imagenhard]({{ site.baseurl }}/images/symbolicand-hard.jpg)
                                                         


