---
layout: default
---

# Auto Success
The ["autogenerator"]({% 2016-1-1-Autogenerator-Test.md %}) worked for @jasonlong's Cayman theme, as presented in the blog your reading, but what you see on the surface is not the end of it. I've moved the entireity of the blog to jekyll posting inheritance model of layouts for static site generation, including errors, posts, and even other layouts, thanks to the work of @pietromenna. The end hierarchy looks something like this:
- default
  - Autogenerator Test
  - Spoon Knife
  - Octowisdom
  - Christmas Spirit
  - Texas
    - Texas \(post\)
  - Hello GitHub
    - Hello GitHub
  - error
    - 404
    - 403

I initially wanted to show this post for example of the new theme, but to prevent codeception, I'll show the Autogenerator post that proposed these changes:

<iframe src="{% 2016-1-1-Autogenerator-Test.md %}"></iframe>
