# saraf-radhika.github.io

Personal website, hosted with GitHub Pages at https://saraf-radhika.github.io

## Editing

- Content lives in `index.html`.
- Styling lives in `style.css` (colours are at the top under `:root`).

## Publishing changes

```sh
git add .
git commit -m "Update site"
git push
```

The live site updates about a minute after pushing.

## Writing a blog post

1. Copy `_drafts/example-post.md` into a folder called `_posts`.
2. Rename it `YYYY-MM-DD-short-title.md`, for example `_posts/2026-12-01-responsible-ai-in-banking.md`.
3. Edit the `title` and `description` at the top, then write the post in Markdown below them.
4. Commit and push. The post appears on `/blog/` and on the home page.

Posts in `_drafts` are never published. An RSS feed is available at `/feed.xml`.
