---
title: "Posting using R Markdown"
categories:
#  - foundations
#  - protocols
  - writing
#  - goals
#  - committee meetings
  - blog-troubleshooting

tags:
  - R Markdown

link-citations: true

editor_options: 
  markdown: 
    wrap: 72

bibliography: references.bib
---

Finding the perfect workflow to integrate data visualizations, screenshots, images, links, and academic
APA-style citations in one minimal markdown editor where I can type up my protocols, posts, and papers... that would be the dream! 

[Typora](https://typora.io/) has the simple, clean, workspace that I like; but it doesn't have a built-in way to use cite keys to generate APA (author-date) citations from my Zotero library. There is an open [GitHub issue](https://github.com/typora/typora-issues/issues/912) for the feature, but it hasn't been integrated yet :disappointed:... I have big hopes that it is included in a future update! 

For 🍏Mac users, there seems to be some workarounds, like Ben Butterworth’s post [‘Markdown for convenient academic writing’](https://orth.uk/markdown-for-convenient-academic-writing/).

BUT for a Windows user, I struggled to find a solution... and instead changed tactics (use a different app).

**Note:** I'm using Windows 11 OS! 
{. :notice--info}

I started a small quest to find a Typora-like Markdown editor with citation management and Pandoc file-format conversion capabilities... that can be used by Windows OS!

I went down some deep rabbit holes on forums, discovered [Obsidian](https://obsidian.md/) through a great blog post ['Obsidian is almost a Typora killer'](https://benjamindlee.com/posts/2022/obsidian-is-almost-a-typora-killer/) by Benjamin D. Lee... which seems like it has a bit of learning curve to its structure and requires a monthly payment subscription for it's most useful features...

:warning:	Obsidian has a $8monthly subscription for versioning control
{: .notice--warning}

I may explore Obsidian later, but for the meantime I want to get up and running quickly with a more accessible, open-source editor that has lots of customer and user community support. 

So, I turned full-circle back to ==**R Markdown**== (the first markdown editor I had used, even before discovering Typora!). Previously, I hated having to `knit` every time I wanted to see my rendered markdown file. I wanted a render-on-the-fly markdown editor, something that is apparently called a WYSIWYG editor (pronounced wiz-ee-wig), which allows users to see and edit content in a form that appears as it would when displayed as the final product. WYSIWYG is an acronym for *"what you see is what you get."*  

Sometime in 2022 RStudio dropped v1.4 which released it's own WYSIWYG...  [Visual R Markdown](https://rstudio.github.io/visual-markdown-editing/) ! It was released just after I swapped to using Typora.. so I missed the good news until now. 

Once I realized you could swap between source code and a visual markdown editor in RStudio, I set about to learn the ropes on using R Markdown to post to this blog. This handout '[RMarkdown for writing reproducible scientific papers'](https://libscie.github.io/rmarkdown-workshop/handout.html) was a great resource. I particularly like how the footnotes and citations show up in a separate column while scrolling. 

[@liboiron2021`]`\[@liboiron2021] \*\*not in-text citation\*\*

@bahr2015\@bahr2015 \*\*in-text citation\*\*

![directory-image](%7B%7B%20site.url%20%7D%7D%7B%7B%20site.baseurl%20%7D%7D/assets/images/githuboctocat.png)
`![directory-image](%7B%7B%20site.url%20%7D%7D%7B%7B%20site.baseurl%20%7D%7D/assets/images/githuboctocat.png)`

> hmm weird the `{{ site.url }}{{ site.baseurl }}` doesn't stay put when
> moving back and forth from visual markdown editor in RStudio to source
> editor... It turns into
> `%7B%7B%20site.url%20%7D%7D%7B%7B%20site.baseurl%20%7D%7D` ... why?

![url-image](https://sarahtanja.github.io/lab-book/assets/images/githuboctocat.png)
`![url-image](https://sarahtanja.github.io/lab-book/assets/images/githuboctocat.png)`

# References
