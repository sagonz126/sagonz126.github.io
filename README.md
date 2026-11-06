# saul.gonzález: personal research site

Static site for GitHub Pages. No plugins, nothing to update, free.

## What's where

```
index.html                    home page: hero, "How I got here", research, contact
style.css                     all colours and fonts (change a colour once, it changes everywhere)
assets/saul.jpg               profile photo
projects/remy-cointreau.html  Rémy pitch; also the template for every new project
files/                        CV and project files (Excel models, PDF memos)
```

## Publish (browser only, about 10 minutes)

1. Sign in to github.com as **sagonz126**.
2. Top right "+", then "New repository". Name it exactly `sagonz126.github.io`.
   Set it to Public. Click "Create repository".
3. Click "uploading an existing file". Drag in everything inside this folder
   (index.html, style.css, README.md and the folders assets, files, projects).
   Click "Commit changes".
4. Settings, then Pages. Source: "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
5. After a minute or two the site is live at https://sagonz126.github.io

Tip: until you want it public, you can skip step 4. Nothing is published without it.

## Change a text yourself

1. Open the file on github.com (for example `index.html`).
2. Click the pencil icon (Edit).
3. Find the sentence with Ctrl+F, change only the words between the tags.
   Example: in `<p class="lead">I spent three years...</p>` change only the text,
   never the parts inside `< >`.
4. Click "Commit changes". The site updates in about a minute.

## Swap the photo

Upload a new photo named `saul.jpg` into the `assets` folder (replace the old one).
Portrait format (4:5) works best.

## Before going public

- Put the web CV in `files/` named exactly `Saul-Gonzalez-CV.pdf`.
- Link or remove the "Coming soon" research cards.
- Add the Excel and PDF links on the Rémy page once they exist.
- Optional: buy a domain, then Settings, Pages, Custom domain.
