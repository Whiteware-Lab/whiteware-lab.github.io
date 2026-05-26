# Whiteware Lab Landing Page

Static landing page for the GitHub Pages repository:

```text
whiteware-lab.github.io
```

## Files

```text
.
├── index.html
├── styles.css
└── assets/
    └── brand/
        ├── whiteware-lab-logo-full.png
        ├── whiteware-lab-logo-full.svg
        ├── whiteware-lab-mark.png
        ├── whiteware-lab-mark.svg
        └── whiteware-lab-avatar.png
```

## How to publish on GitHub Pages

1. Create a public repository named `whiteware-lab.github.io` under the `Whiteware-Lab` organization.
2. Copy these files into the repository root.
3. Commit and push to the default branch.
4. Open:

```text
https://whiteware-lab.github.io
```

Usually GitHub Pages starts serving organization pages automatically when the repository name matches the Pages pattern.

If it does not appear, go to:

```text
Repository → Settings → Pages
```

Then set:

```text
Source: Deploy from a branch
Branch: main
Folder: /root
```

## Notes

This is intentionally plain HTML/CSS. No build system, no npm, no framework.
