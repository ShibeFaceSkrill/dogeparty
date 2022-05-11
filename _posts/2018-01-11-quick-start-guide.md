---
layout: post
title:  "Tips and Tricks of Mediumish"
author: sal
categories: [ Jekyll, tutorial, web development ]
image: "https://images.unsplash.com/photo-1541544537156-7627a7a4aa1c?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=a20c472bc23308e390c8ffae3dd90c60&auto=format&fit=crop&w=750&q=80"
# internal or external # image: assets/images/14.jpg
featured: true
hidden: true
beforetoc: "Markdown editor is a very powerful thing. In this article I'm going to show you what you can actually do with it, some tricks and tips while editing your post."
toc: true

---

## So how do we do spoilers?

```html
<span class="spoiler">My hidden paragraph here.</span>
```

## Product Reviews

It's actually really simple! Add the rating in your YAML front matter. It also supports halfs:

```html
---
layout: post
title:  "Inception Movie"
author: john
categories: [ Jekyll, tutorial ]
tags: [red, yellow]
image: assets/images/11.jpg
description: "My review of Inception movie. Actors, directing and more."
rating: 4.5
---
```

## Special formatting

As well as bold and italics, you can also use some other special formatting in Markdown when the need arises, for example:

+ ~~strike through~~
+ ==highlight==
+ \*escaped characters\*

## site.baseurl

site stores all the variables we set in config and frontmatter.. and whatever system variables are baked in too I'm sure.

`![walking]({{ site.baseurl }}/assets/images/8.jpg)`

![walking]({{ site.baseurl }}/assets/images/8.jpg)
