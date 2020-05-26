---
title: Sometimes the answer is simply in the data plot 
summary: LibreOffice Calc
date: 2020-01-12T23:23:17+03:00

reading_time: true
share: true
profile: true
comments: true

image:
  placement: 1
  focal_point: "Left"
  priview_only: false
  alt_text: ""
---

Take for the example the Laptop Battery Life problem in HackerRank (https://www.hackerrank.com/challenges/battery/problem). From the problems description, it’s obvious that it’s a regression problem, and most of us would most definitely jump straight to creating model or using rather complex algorithms to try and solve it, like I almost did.

![](/static/img/in_plot/in_plot_1.png)

So after being frustrated with trying to figure out how I would load and preprocess the data on HackerRank, I decided to just use LibreOfficeCalc, and plot a graph to “just” check out the data. Guess was I found out, all values basically double until 4 on the x axis, where they just amounted to 8. Check the header image.

Lesson, always check you data plot, because no matter how complex you think a problem might be, the solution might just be one graph away. 😎😎😎, My solution ended up being:

![](static/img/in_plot/in_plot_2.png)

Cheers.