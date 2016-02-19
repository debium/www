---
layout: default
title: Auto Success
permalink: /AutoSuccess.html
---

# Auto Success
The ["autogenerator"]({% post_url 2016-1-1-Autogenerator-Test %}) worked for @jasonlong's Cayman theme, as presented in the blog your reading, but what you see on the surface is not the end of it. I've moved the entireity of the blog to jekyll posting inheritance model of layouts for static site generation, including errors, posts, and even other layouts, thanks to the work of @pietromenna. The end hierarchy looks something like this:

- default
  - Auto Success
  - Autogenerator Test
  - Spoon Knife
  - Octowisdom
  - Christmas Spirit
  - Texas
    - Texas \(post\)
  - Hello GitHub
    - Hello GitHub \(post\)
  - error
    - 404
    - 403

I initially wanted to show this post for example of the new theme, but to prevent codeception, I'll show the Autogenerator post that proposed these changes:

<iframe src="{% post_url 2016-1-1-Autogenerator-Test %}" width="100%" height="1000"></iframe>

Cool, right? This blog is going to be awesome now that automation provides it the room to be! Can't wait for the Easter update!
