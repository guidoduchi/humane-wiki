# GitHub Pages Setup

This wiki is designed as a lightweight single-page application using **Docsify**.

## Deployment Target

Expected public URL:

```text
https://guidoduchi.github.io/humane-wiki/
```

## Required GitHub Pages Settings

In GitHub:

```text
Repository → Settings → Pages
```

Use:

```text
Source: Deploy from a branch
Branch: main
Folder: /root
```

## Why `.nojekyll` Exists

GitHub Pages normally supports Jekyll processing. This wiki does not need Jekyll.

The `.nojekyll` file tells GitHub Pages to serve the files directly, including files that begin with underscores such as:

- `_sidebar.md`
- `_navbar.md`

## Why `404.html` Exists

Docsify normally uses hash routes such as:

```text
/#/docs/canon/canon.md
```

The `404.html` file redirects direct GitHub Pages paths back into Docsify routing so links are more forgiving.

## Local Preview

From the repository root:

```bash
python -m http.server 3000
```

Then open:

```text
http://localhost:3000
```

Or use Docsify CLI:

```bash
npm i docsify-cli -g
docsify serve .
```

## Site Files

| File | Purpose |
|---|---|
| `index.html` | Docsify single-page app shell. |
| `README.md` | Homepage content. |
| `_sidebar.md` | Main wiki navigation. |
| `_navbar.md` | Top navigation. |
| `.nojekyll` | Prevents Jekyll processing. |
| `404.html` | GitHub Pages SPA redirect helper. |
