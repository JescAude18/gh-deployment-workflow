# gh-deployment-workflow

Simple project for deploying a static website to GitHub Pages with GitHub Actions.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Installation & Usage](#installation--usage)
- [Example Output](#example-output)
- [How It Works](#how-it-works)
- [Error Handling](#error-handling)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Author](#author)
- [License](#license)

## About

This repository contains a minimal static website and a GitHub Actions workflow
designed to publish the site to GitHub Pages. It is meant to be easy to read,
easy to adapt, and useful as a starting point for a small deployment demo.

**Project Reference:** [roadmap.sh/projects/github-actions-deployment-workflow](https://roadmap.sh/projects/github-actions-deployment-workflow)

## Features

- Static landing page ready for GitHub Pages.
- GitHub Actions-friendly structure.
- Lightweight setup with no build tooling required.
- Easy to customize for personal or learning projects.

## Project Structure

```text
.
├── .github/
│   └── workflows/
│       └── deploy.yml
├── index.html
└── README.md
```

## Requirements

- A GitHub repository with GitHub Pages enabled.
- GitHub Actions available on the repository.
- A modern browser to preview the static page locally.

## Installation & Usage

1. Clone the repository.
2. Open `index.html` in a browser to preview the site locally.
3. Push your changes to GitHub.
4. Configure GitHub Pages in the repository settings.
5. Add or adapt your GitHub Actions workflow to deploy the contents of the
repository to Pages.

## Example Output

When deployed, the site displays a simple hero section with a highlighted title,
supporting text, and a few feature tiles that summarize the project.

## How It Works

The workflow should typically run on pushes to the default branch, build or
prepare the site if needed, and publish the contents of the repository to
GitHub Pages. Because this project is static, the deployment can stay very
simple and usually only needs to copy the HTML file to the Pages environment.

## Error Handling

- If the page does not appear on GitHub Pages, check that Pages is enabled for
the repository.
- If the workflow fails, inspect the Actions logs for the failing step.
- If the local preview looks wrong, verify that `index.html` was saved and that
the browser is loading the correct file.

## Roadmap

- Extend the workflow with preview and production deployment steps.
- Turn the landing page into a more practical site using a static site generator such as Hugo, Jekyll, or Astro.
- Build a richer personal portfolio with multiple pages, reusable layouts, and shared components.
- Add optional assets such as images, icons, a favicon, and social preview metadata.
- Expand the README with workflow configuration examples and deployment notes.

## Contributing

Contributions are welcome. Keep changes small, focused, and consistent with the current project layout.
If you improve the service behavior or documentation, update this README so it stays accurate.

1. Fork the project
2. Create a branch for your feature (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Author

**Created by**: Jessica MOUSSOUGAN

**Email**: [jessicamoussougan@gmail.com](mailto:jessicamoussougan@gmail.com)

**GitHub**: [@JescAude18](https://github.com/JescAude18)

## License

No license yet.

This project is currently for personal training and learning.
