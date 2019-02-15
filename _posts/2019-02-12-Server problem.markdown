---
layout: post
title:  "Frond-end design"
date:   2019-02-12 21:58:47 -0500
categories: jekyll update
---
Recently I have been learning front-end design and implementation using javascript packages such as [G6] and [D3]. When I tried to run a very simple project that reads and displays a local json file, I encountered a bug, basically indicating that the internet cannot access local files. I googled and found two possible ways to solve this problem.

The first solution is to make the folder containing the files a server, which can be easily done with python:

Open a terminal in the foler->python -m SimpleHTTPServer or python3 -m http.server

Done.

The above solution, although seems easy, suffers from several shortcomings. For instance, we can only import local .js files but not files from the Internet. Therefore, the second solution is to upload the code onto a server. I'm trying to figure out this method and will share what I learn in the next several days.
[G6]: https://antv.alipay.com/zh-cn/g6/2.x/index.html
[D3]: https://d3js.org