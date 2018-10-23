# NLP1

This repository hosts NLP1's github pages.


# Contribute a page

You can add a page by adding a markdown file to the root of the repository. This file stards with a header

```
---
layout: default
title: New Page
menu: yes
---
```

where you specify a title for the page and whether or not it appears in the menu from the main page `index.md`. The default layout is typically what you need.

The rest of this file is just standard markdown syntax, for example

```
---
layout: default
title: Projects
menu: yes
---

# Project 1

* Read this 
* Write that

Due date: ...

# Project 2

* Implement this
* Implement that

Due date: ...
```

# Contribute a lecture

To modify the syllabus you do not need to edit `syllabus.md` directly, instead you need to add an record to a database of lectures. You will find one under `nlp1/_data/2018/lectures.yml`. This is just a yaml file with records indicated by a dash, each record is essentially a dictionary of key-value pairs. The keys there are rendered nicely by a template specified in `_includes/lecture.html`. You will hardly need to touch the template. 

I left an example lecture, so you can see how to add your own. To make sure your lecture gets rendered you need to provide `selected: y` as opposed to `selected: n`.

# Adding resources

If you need to add resources such as pdfs, latex filex, data, add to the folder `nlp1/resources` and link it from a certain page.
