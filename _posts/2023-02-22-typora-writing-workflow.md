---
title: "Science Writing & Citing Workflow with Typora, Zotero & Pandoc"
categories:
  - writing
tags:
  - Typora
  - Zotero  
  - Pandoc
  - citation management
  - Markdown
  - academic writing
---

I am a process-oriented person, meaning I like to lay out all the steps and understand them in depth to make working through things more enjoyable for me. In this post I'll lay out my process for science writing. This is something that has taken me a few years to figure out, and it will likely continue to evolve as apps and technologies change. 

[Typora](https://typora.io/) 

[Zotero](https://www.zotero.org/)

[Pandoc](https://pandoc.org/)

To kick things off, and to be transparent, I pretty much copy the workflow from Ben Butterworth's post ['Markdown for convenient academic writing'](https://orth.uk/markdown-for-convenient-academic-writing/), posted in 2020, with a few changes. One change, is `Typora` is no longer free, (I bit the bullet and purchased it for $14.99). I like using `Typora` for the ability to visually see rendered markdown as I type. 

*Note:* I work on a Windows 11 OS

I have also enjoyed using [`RMarkdown`](https://rmarkdown.rstudio.com/), however I found it a little tedious and time-consuming to `'knit'` every time I wanted to see my rendered markdown file. When working primarily with text (and not data), I find `Typora` to be a simpler markdown environment. It's what I use as my markdown editor for these posts! 
{. :notice--info}

> "Kaneohe Bay, which is located on the on the NE coast of Oahu, Hawaii, represents one of the most intensively studied estuarine coral reef ecosystems in the world. Despite a long history of anthropogenic disturbance, from early settlement to post European contact, the coral reef ecosystem of Kaneohe Bay appears to be in better condition in comparison to other reefs around the world. The island of Moku o Loe (Coconut Island) in the southern region of the bay became home to the Hawaii Institute of Marine Biology in 1947, where researchers have since documented the various aspects of the unique physical, chemical, and biological features of this coral reef ecosystem." [@bahrUnnaturalHistoryKaneohe2015] 

Zotero --> Edit --> Preferences --> Better BibTex --> Citation keys

![zotero-citationkey-preferences-screenshot]({{ site.url }}{{ site.baseurl }}/assets/images/zotero-citation-key.png)

![](C:\Users\ssdon\OneDrive\Documents\lab-book\assets\images\zotero-citation-key.png)

Changing a pattern will only affect items created/changed after you changed the pattern; ==existing keys are not automatically regenerated when you change the pattern==. If you want your keys to update after a pattern change you will have to select your items, right-click, navigate to Better BibTex, and select `Refresh BibTex key`. This will not affect keys you have pinned.

[@bahr2015]

\cite{@bahr2015}

\bibliographystyle{unsrt}

\bibliography{reflexive-essay}

https://joshcarpenter.ca/plain-text-refs-mgmt/

l@[iboiron2021
