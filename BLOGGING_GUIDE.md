# How to post news or a daily blog entry

Your News & Blog page is powered by GitHub Pages and Jekyll. You do **not** need to edit `news.html` every day.

## Add a new post directly on GitHub

1. Open your `LungtenCosmo.github.io` repository.
2. Open the `_posts` folder.
3. Click **Add file → Create new file**.
4. Name it using this format: `YYYY-MM-DD-short-title.md`.
   - Example: `2026-09-14-edna-school-training.md`
5. Paste the template below and replace the title, category and text.
6. Click **Commit changes**.
7. GitHub Pages will rebuild the site and the new post will automatically appear at the top of `news.html`.

```markdown
---
layout: post
title: "Your post title"
category: "Project news"
subtitle: "Optional one-sentence subtitle"
---

Write your post here.

You can use **bold text**, *italics*, headings and lists.

## A heading

- First point
- Second point
```

## Suggested categories

- Project news
- Field note
- Research update
- Workshop
- Publication
- Daily blog

## Adding a photo to a post

Upload the photograph to `assets/blog/`, then add this line in your post:

```markdown
![Short description of the photo](/assets/blog/photo-name.jpg)
```

Keep filenames short and use hyphens instead of spaces.
