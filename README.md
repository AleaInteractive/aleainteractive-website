# Alea Interactive Website

This repository contains the source code for the official website of Alea Interactive, available at [www.aleainteractive.com](https://www.aleainteractive.com).

The site is built using the [Hugo](https://gohugo.io/) static site generator.

## Development

To run the website locally for development, you need to have Hugo installed. You can find the installation instructions [here](https://gohugo.io/installation/).

Once Hugo is installed, clone the repository and run the following command from the root of the project:

```bash
hugo server -D
```

This will start a local server, and you can view the site at `http://localhost:1313`.

## Deployment

The website is automatically deployed to GitHub Pages whenever a change is pushed to the `main` branch. The deployment process is managed by the GitHub Actions workflow defined in `.github/workflows/deploy.yml`.

## Licencing
This repository uses a split Licence

* **Code and Scripts:** Licenced under the [MIT License](LICENSE-CODE.md).
* **Images and creative Work:** Licenced under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)](LICENSE-CONTENT.md).
