---
title: "Posting using R-Markdown"
categories:
  - writing
tags:
  - Pandoc
  - citation management
  - Markdown
  - academic writing

bibliography: references.bib
---

Using R-Markdown through R-Studio may be the best way for me to integrate citations into my science writing. I want to be able to integrate screenshots, images, web-links, and academic APA-style citations in one markdown editor.

[**Note:** I'm using Windows 11 OS!]{.ul} {. :notice--info}

[@liboiron2021] ... not in-text citation

@bahr2015 ... in-text citation

![directory-image](%7B%7B%20site.url%20%7D%7D%7B%7B%20site.baseurl%20%7D%7D/assets/images/githuboctocat.png) `![directory-image](%7B%7B%20site.url%20%7D%7D%7B%7B%20site.baseurl%20%7D%7D/assets/images/githuboctocat.png)`

> hmm weird the `{{ site.url }}{{ site.baseurl }}` doesn't stay put when moving back and forth from visual markdown editor in RStudio to source editor... It turns into `%7B%7B%20site.url%20%7D%7D%7B%7B%20site.baseurl%20%7D%7D` ... why?

![url-image](https://sarahtanja.github.io/lab-book/assets/images/githuboctocat.png) `![url-image](https://sarahtanja.github.io/lab-book/assets/images/githuboctocat.png)`

# References
