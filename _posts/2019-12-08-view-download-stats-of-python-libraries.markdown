---
layout: post
title:  "View download stats of Python libraries"
date:   2019-12-08 11:46:42 +0100
categories: pepy.tech
---
I remember when I started my project Climoji, to search emojis from your terminal, I wanted to see how many downloads it had and if it was useful.

The problem is that data was removed from PyPI and it wasn’t easy to get download stats of that project. If you want this data you should query the data in the official download stats repository and it was tedious. Also if you want to add an amazing badge like it was impossible.

Then to solve that problem I created pepy.tech. It queries the official data for you and also it generates a badge to insert into your README.md, like this one: ![Requests Downloads Badge](https://pepy.tech/badge/requests).

Now it is quite popular in the Python community, as a lot of popular libraries use this badge to query data. Some of them are:
* Requests
* Pinject
* OpenCV
* PySampleGUI
* Masonite

Here is the number of users visiting pepy.tech each week from the beginning of the project. Currently the site has over 1000 weekly visitors, also the visitors are growing.

![Visitors of pepy.tech until Desember of 2019](/assets/2019_desember_usage_of_pepy.png)

Hope this project helped the community. I will try to improve it in the future.
