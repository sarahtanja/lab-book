---
title: "Rendering Images in Jekyll Minimal Mistakes"
categories:
  - blog
---
This post is for troubleshooting why my images are not rendering on the Minimal Mistakes site. 

The minimal mistakes jekyll [assets/images](https://github.com/mmistakes/minimal-mistakes/tree/master/docs/assets/images) folder images are all either .png or .jpg files

The [post](https://mmistakes.github.io/minimal-mistakes/post%20formats/post-image-standard/) & [file](https://github.com/mmistakes/minimal-mistakes/blob/master/docs/_posts/2010-08-05-post-image-standard.md) on including a standard image says:

The preferred way of using images is placing them in the `/assets/images/` directory and referencing them with an absolute path. Prepending the filename with `{% raw %}{{ site.url }}{{ site.baseurl }}/assets/images/{% endraw %}` will make sure your images display properly in feeds and such.

In my `config.yml`file I added the lines:

```yml
url		 : "sarahtanja.github.io"
baseurl	 : "/lab-book"
```



**HTML:**

```html
{% raw %}<img src="{{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg" alt="">{% endraw %}
```
{% raw %}<img src="{{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg" alt="">{% endraw %}

... nothing 

**Kramdown:**

```markdown
{% raw %}![alt]({{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg){% endraw %}
```
{% raw %}

![alt]({{ site.url }}{{ site.baseurl }}/assets/images/githuboctocat.png)

{% endraw %}

... 

**Kramdown without '{% raw %} {% endraw %} wrap':**

```kramdown
![img-png]({{ site.url }}{{ site.baseurl }}/assets/images/githuboctocat.png)
```

We have a winner!
{: .notice--success}

![img-png]({{ site.url }}{{ site.baseurl }}/assets/images/githuboctocat.png)



Image that fills page content container by adding the `.full` class with:

**HTML:**

```html
{% raw %}<img src="{{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg" alt="" class="full">{% endraw %}
```

**Kramdown with %raw%:**
```markdown
{% raw %}![alt]({{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg)
{: .full}{% endraw %}
```
{% raw %}![alt]({{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg)
{: .full}{% endraw %}

{% raw %} {% endraw %} isn't showing in the code fence?

**Kramdown without %raw%:**
```
![img-jpg]({{ site.url }}{{ site.baseurl }}/assets/images/githuboctocat.svg)
{: .full}
```
We have another winner!
{: .notice--success}
![img-jpg]({{ site.url }}{{ site.baseurl }}/assets/images/githuboctocat.svg)
{: .full}

---
Supposedly, you can [embed images](https://www.fabriziomusacchio.com/blog/2021-08-11-Minimal_Mistakes_Cheat_Sheet/#via-markdown) in three ways... here I'm just trying to get markdown or html to work (not messing with liquid galleries yet)

# Via Markdown

absolute path - doesn't render in Typora or Jekyll page, does show in [GitHub repo preview](https://github.com/sarahtanja/lab-book/blob/master/_posts/2023-02-02-test.md)
```
![img-svg](https://github.com/sarahtanja/lab-book/blob/master/assets/images/githuboctocat.svg)
```
![img-svg](https://github.com/sarahtanja/lab-book/blob/master/assets/images/githuboctocat.svg)

relative path - this shows in Typora, but nowhere else
```
![img-png](..\assets\images\githuboctocat.png)
```
![img-png](..\assets\images\githuboctocat.png)

# Via HTML

```
<figure style="width: 80px" class="align-center">
  <a href="/assets/images/githuboctocat.svg" title="octocat" alt="octocat">
  <img src="/assets/images/githuboctocat.svg" alt=""></a>
  <figcaption>octocat</figcaption>
</figure>
```
<figure style="width: 80px" class="align-center">
  <a href="/assets/images/githuboctocat.svg" title="octocat" alt="octocat">
  <img src="/assets/images/githuboctocat.svg" alt=""></a>
  <figcaption>octocat</figcaption>
</figure>

This doesn't show locally, on GitHub preview, or on Jekyll site
