# Personal site

Plain HTML, no build step. Everything is in `index.html`.

## Add a post or project

Open `index.html`, copy an existing `<div class="item">` block in the right section, and edit it.
The Writing section is commented out until you have your first post.

## Publish on GitHub Pages (first time)

1. On github.com, create a new **public** repository named exactly `Pedro1-21GW.github.io`. Leave it empty.
2. In this folder, run:

   ```
   git init -b main
   git add .
   git commit -m "Personal site"
   git remote add origin https://github.com/Pedro1-21GW/Pedro1-21GW.github.io.git
   git push -u origin main
   ```

3. The site appears at `https://Pedro1-21GW.github.io` within a minute or two.
   If it doesn't, check the repo's **Settings → Pages** and set the source to the `main` branch.

## Update

```
git add .
git commit -m "Add post"
git push
```
