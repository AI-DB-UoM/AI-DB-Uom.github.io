---
layout: post
title: Database performance tuning with Multi-armed Bandits
subtitle: Performance tuning is a crucial step in database preparation since it enables fast query responses to user enquiries. This project aims to fully automate performance tuning of databases by choosing physical design structures that speed up query analysis. Our approach removes the need for costly human personnel and automatically adjusts to user queries (and data) whilst they are doing analysis. DBA Bandits are not only able to successfully tune unpredictable and ad hoc workloads (unknown a priori), but also provide statistical guarantees on the fitness of proposed design structures – first such guarantees in the world of database performance tuning.
author: Renata
categories: MAB
banner:
  # video: https://vjs.zencdn.net/v/oceans.mp4
  loop: true
  volume: 0.8
  start_at: 8.5
  image: https://miro.medium.com/v2/resize:fit:1200/1*5q0Mihf29fftuXpKWWX2uA.png
  opacity: 0.618
  background: "#000"
  height: "100vh"
  min_height: "38vh"
  heading_style: "font-size: 4.25em; font-weight: bold; text-decoration: underline"
  subheading_style: "color: gold"
tags: MAB index tunning
top: 1
sidebar: []
---

Performance tuning is a crucial step in database preparation since it enables fast query responses to user enquiries. This project aims to fully automate performance tuning of databases by choosing physical design structures that speed up query analysis. Our approach removes the need for costly human personnel and automatically adjusts to user queries (and data) whilst they are doing analysis. DBA Bandits are not only able to successfully tune unpredictable and ad hoc workloads (unknown a priori), but also provide statistical guarantees on the fitness of proposed design structures – first such guarantees in the world of database performance tuning.

## This is a video


![](//www.youtube.com/watch?v=glBoRyShD7E&list=PLSE8ODhjZXjYVdJKka5g3xTKfPBITrxOu&index=2)

## This is a paper 

<div style="display: flex; justify-content: center;">
    <embed src="https://renata.borovica-gajic.com/data/2021_icde.pdf" width="80%" height="400" />
</div>

## These are links, latex formulas, and codes

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

$ a \* b = c ^ b $

$ 2^{\frac{n-1}{3}} $

$ \int_a^b f(x)\,dx. $

```cpp
#include <iostream>
using namespace std;

int main() {
  cout << "Hello World!";
  return 0;
}
// prints 'Hi, Tom' to STDOUT.
```

```python
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

p1 = Person("John", 36)

print(p1.name)
print(p1.age)
```
