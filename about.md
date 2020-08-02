---
layout: default
---

<img class="logo" src="../assets/{{site.logo}}" align="middle">

<h3 align="center">Raven</h3>

<p align="center">A piracy blog</p>

<br />

### ABOUT THE PROJECT

<!-- Todo: put a screenshot of the home page -->

<!-- [![X][X]](X) -->

Raven is a blog dedicated to digital piracy. The go-to place for all your piracy related stuff. News, guides, and wikis.

This blog is community driven and heavily depends upon them for it’s maintenance and development. Anyone who is interested can write a new post and create a new pull request to add your post on the blog. You can also propose updates for the older or misinformed articles in the issues.


### GETTING STARTED

To write a new blog post, follow these simple steps.


#### PREREQUISITES

The only thing that you'll need is your favorite text editor. Or if you wanna do it on-the-go, then you can do that with your favorite notes app.


#### SETUP

The first thing you'll need to do is setup the front matter properly.

```
---
layout: post
title: Hello World
snippet: This had to be done
tags: [test]
published: true
author: Maximous Black
author_link: https://xuac.github.io/
---

This is a sample post.
```

You can see the rendered version of the above example [here](https://xuac.github.io/raven/helloworld/). If you want a complete style guide, you can find that [here](https://xuac.github.io/raven/styleguide/).

`layout: post` - this is to be left as it is for pot to be structured properly

`title: string` - Title of the post. Should be properly capitalised except if it contains a name that is specifically capitalised.

`snippet: string` - one-line summary or prologue of your post. This will be shown under the title on the home page.

`tags: array` - tag (or tags separated by commas) related to the post.

`published: boolean` - if the post is still a draft then the value should be 'false'.

`author: string` - Name of the author. If author doesn't want to disclose the name for some reason, change the name to 'anonymous'.

`author_link: URL` - link to the author's profile or website. For anonymous author, change this to '#'.

Naming structure is also really important. The name of the post should follow a structure similar to this:

```
YYYY-MM-DD-title-of-the-post.md
```

Make sure everything is in lowercase and there are no special characters. The last thing you want is a broken link to your post.


#### SUGGESTING CHANGES

You can request or help people update the older posts so that they don't become obsolete. You can also request features that you think are necessary.

You must follow this template while requesting an update.

```
post: 2020-01-31-piracy-101

issue: it's perfect

sources:
 - https://www.example.com/
 - https://www.example.org/
```

`post: string` - name of the article or relative URL.

`issue: string` - full description of problem with the post or a section of the post.

`sources: array` - list of updated sources and articles. 

Feature and post requests don't need to follow this template and can open a regular issue.


### ROADMAP

See the [open issues](https://github.com/xuac/raven/issues) for a list of proposed features (and known issues).


### CONTRIBUTION

Contributions are what makes Raven such an amazing blog. Any contributions you make are **extremely appreciated**.

1. Fork the Project

2. Create a new Branch with name 'article-title' or 'new-feature-name'

3. Commit your Changes and Push to the Branch.

4. Open a Pull Request with the summary of the article or description of the feature.


### DISCLAIMER
<pre style="white-space: pre-wrap; white-space: -moz-pre-wrap; white-space: -pre-wrap; white-space: -o-pre-wrap; word-wrap: break-word;" >
This blog (Raven) or it's authors do not host or directly link to any pirated content. Any of the links mentioned by this blog (Raven) or it's authors are purely for reference use. This blog (Raven) or it's authors do not support use of any form of piracy. All the information on this blog (Raven) is purely for informational purposes and is not intended to support copyright infringement. Any of the authors or any real person mentioned anywhere on this blog (Raven) takes no responsibility for anyones's liable actions. All characters performing piracy are purely fictional and any real life incidents similar to any of them is purely coincidental. If you are a copyright owner or an agent thereof, and you believe that any content hosted on this blog infringes your copyrights, then you may open a new issue about it.
</pre>

*And of course, no ravens were harmed during the creation of this blog.*

### LICENSE

Distributed under the Unlicense License. See [LICENSE](../LICENSE) for more information.
