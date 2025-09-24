# Anonymous Research Project Pages

This repository hosts anonymous project pages for academic paper submissions. The pages are built using Jekyll and GitHub Pages.

## Getting Started

1. **Fork this repository** to your GitHub account
2. **Enable GitHub Pages** in your repository settings:
   - Go to Settings > Pages
   - Set source to "Deploy from a branch"
   - Select the `main` branch and `/ (root)` folder
   - Click Save
3. Your site will be available at `https://<your-username>.github.io/<repository-name>/`

## Adding a New Project

1. Create a new Markdown file in the `projects` directory (e.g., `2023-paper-title.md`)
2. Use the following template for your project page:

```markdown
---
layout: project
title: "Your Paper Title"
subtitle: "Brief subtitle"
paper_url: https://example.com/paper.pdf
code_url: https://github.com/username/repository  # Optional
dataset_url: https://example.com/dataset  # Optional
---

## Abstract
Your abstract goes here...

## Method
Method details...

## Results
Your results...
```

3. The page will be automatically available at `https://<your-username>.github.io/<repository-name>/projects/2023-paper-title`

## Customization

- Update `_config.yml` to change site-wide settings
- Modify `_layouts/project.html` to change the project page layout
- Add custom CSS in `assets/css/style.scss`

## Projects

- [Super-Resolution Project](/projects/superres)
- [APT Project](/projects/apt)
