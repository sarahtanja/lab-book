---
title: "R Markdown Post Template"

categories:
#  - foundations
#  - protocols
#  - writing
#  - goals
#  - committee meetings
  - blog-troubleshooting
  
tags:
  - RMarkdown

link-citations: true

editor_options: 
  markdown: 
    wrap: 72
    
toc: true
toc_label: "Table of Contents" # default: Content
toc_icon: "heart"  # corresponding Font Awesome icon name without the "fa" prefix
toc_sticky: true   # enables sticky toc
    
bibliography: references.bib
---

# Insert Citations

[@liboiron2021`]`\[@liboiron2021] \*\*not in-text citation\*\*

@bahr2015\@bahr2015 \*\*in-text citation\*\*

# Insert Images

## From web URL

`![coral-icon](https://cdn.iconscout.com/icon/free/png-512/coral-2524619-2112940.png?f=avif&w=256)`

!\[coral-icon\](<https://cdn.iconscout.com/icon/free/png-512/coral-2524619-2112940.png?f=avif&w=256)>

## From GitHub URL

`![coral-icon](https://github.com/sarahtanja/lab-book/blob/master/assets/images/coral-icon.png)`

![coral-icon](https://github.com/sarahtanja/lab-book/blob/master/assets/images/coral-icon.png)

## From file

`![coral-icon]({{ site.url }}{{ site.baseurl }}/assets/images/coral-icon.png)`

!\[coral-icon\]({{ site.url }}{{ site.baseurl
}}/assets/images/coral-icon.png)

# Make `HTML` Notice Blocks

A notice displays information that explains nearby content. Often used
to call attention to a particular detail.

When using Kramdown `{: .notice}` can be added after a sentence to
assign the `.notice` to the `<p></p>` element.

**Changes in Service:** We just updated our [privacy policy](#) here to
better service our customers. We recommend reviewing the changes. {:
.notice}

**Primary Notice:** Lorem ipsum dolor sit amet, consectetur adipiscing
elit. Integer nec odio. [Praesent libero](#). Sed cursus ante dapibus
diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet. {:
.notice--primary}

**Info Notice:** Lorem ipsum dolor sit amet, [consectetur adipiscing
elit](#). Integer nec odio. Praesent libero. Sed cursus ante dapibus
diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet. {:
.notice--info}

**Warning Notice:** Lorem ipsum dolor sit amet, consectetur adipiscing
elit. [Integer nec odio](#). Praesent libero. Sed cursus ante dapibus
diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet. {:
.notice--warning}

**Danger Notice:** Lorem ipsum dolor sit amet, [consectetur
adipiscing](#) elit. Integer nec odio. Praesent libero. Sed cursus ante
dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet. {:
.notice--danger}


**Success Notice:** Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet. {: .notice-success}


# References
