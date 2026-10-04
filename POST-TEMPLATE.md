# How to write a new blog post

1. On github.com, open this repository, then the `_posts` folder.
2. Click **Add file**, then **Create new file**.
3. Name the file: the date, then the title in lower case with dashes, ending in `.md`.
   Example: `2026-11-02-why-history-belongs-in-maths-lessons.md`
4. Copy everything between the two lines below into the file, change the title,
   description and tags, and write your post underneath.
5. Click **Commit changes**. The post appears on the site in a minute or two.

------------------------------------------------------------
---
layout: post
title: "Your title here"
description: "One sentence that appears under the title and in the list of posts."
tags: [teaching, maths]
---

Write your first paragraph here. Leave a blank line between paragraphs.

## A heading

- A bullet point
- **Bold text** and *italic text*
- A link: [The Calculus Chronicles](https://liamyardley.github.io/The-Calculus-Chronicles/)

Maths: wrap it in double dollar signs, for example $$x^2 + y^2 = r^2$$.
A line on its own between double dollar signs is shown centred:

$$
\int_1^e \frac{dx}{x} = 1
$$

An image: put the file in `assets/img/`, then write
![Description of the picture](/assets/img/your-picture.webp)
------------------------------------------------------------

Tips
- The date in the file name sets the date shown on the post. A future date hides the post until that day.
- To fix a typo later, open the post on github.com, click the pencil icon, edit, and commit.
- To delete a post, open it, click the three dots (…) and choose Delete file.
