---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Are you writing pythonic code?"
subtitle: ""
summary: ""
authors: [mgoliveira]
tags: [code]
categories: [tips]
date: 2023-01-16T18:26:38Z
lastmod: 2023-01-16T18:26:38Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Believe it or not, there's a whole lot more to python than just programming. There's a whole philosophy surronding writing Python code. And there's no better telling of the principles of writing pythonic code than *The Zen of Python*, go ahead and open up your favourite Python IDE and type this:


```python
import this
```

    The Zen of Python, by Tim Peters
    
    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts.
    Special cases aren't special enough to break the rules.
    Although practicality beats purity.
    Errors should never pass silently.
    Unless explicitly silenced.
    In the face of ambiguity, refuse the temptation to guess.
    There should be one-- and preferably only one --obvious way to do it.
    Although that way may not be obvious at first unless you're Dutch.
    Now is better than never.
    Although never is often better than *right* now.
    If the implementation is hard to explain, it's a bad idea.
    If the implementation is easy to explain, it may be a good idea.
    Namespaces are one honking great idea -- let's do more of those!


Yep, Python is so self-documenting that it bundles its own principles. You should see *The Zen of Python* as a mantra that shall follow you through your Python journey.

## Getting into the Python mindset

Let's say you want to attribute a list with a set of coordinates to their own variables, if you come from a different programming language, you may feel tempted to do it like this:



```python
coord = (1, 2, 3)
x = coord[0]
y = coord[1]
z = coord[2]
print(f"Your coordinates are: ({x},{y},{z})")
```

    Your coordinates are: (1,2,3)


You'll probably be content with this implementation, it's pretty much as elegant as it gets when it comes to deconstucting a tuple. However, as straightforwared as this code may be at first, it is not *pythonic*. Let's take a look at another implementation that integrates this philosophy:


```python
coord = (1, 2, 3)
x,y,z = (1, 2, 3)
print(f"Your coordinates are: ({x},{y},{z})")
```

    Your coordinates are: (1,2,3)


As you can see, the result is exactly the same. As for the computational complexity of the code, it also didn't seem to change much - the interpreter still had to assign those values to each of the corresponding in-memory locations. However, the second implementation has two key advantages:
* It has less lines of code
* It takes advantage of Python's multiple assignments
* It is more readable

You just stumbled into the heart of Python - the philosophy that your code does not only need to work, but it also needs to be readable to your fellow developers. Programming in Python is, as we can conclude, much more than an exercise of computer science, it is an art.
