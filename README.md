[![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-526CFE?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)

# GitHub Repository Template for Course Websites

This template is designed to simplify the creation of educational course websites that automatically publish via [GitHub Pages](https://pages.github.com/), powered by [GitHub Actions](https://github.com/features/actions). Built using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), this template offers a sleek, responsive design that enhances the learning experience. Perfect for educators and trainers looking to deliver content online, this repository provides a robust starting point that includes necessary configurations and detailed documentation. With just a few clicks, you can see your site go live effortlessly!

## Installation

Click in the green `Use this template` button, then select `Create a new repository`.

Enter a name and description for your new repository. Ensure the `Include all branches` checkbox is checked.

Then click on `Create repository`.

Now, the GitHub Actions will build and deploy your site for the first time. Visit the `Actions` section to monitor the progress. Once ready, your site will go live.

To view your course site URL, click on the gear icon in the `About` section and then check the `Use your GitHub Pages website` checkbox.

## Usage

Just clone the repo and modify the files using VSCode, or make changes directly on the GitHub website if you're comfortable with it.

This website is built using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/). You should read their documentation to understand what's going on. Simply put, to modify the site structure, you need to change the [`mkdocs.yml`](mkdocs.yml) file. 

You can modify the `nav` section to create new pages and sections:

```yaml
nav:
  - Home: index.md
  - Getting Started:
      - Welcome to the course: welcome.md
  - Lectures:
      - lectures/index.md
  - Material:
    - material/index.md
  - Instructor:
    - instructor/index.md
```

Everything is writing using [Markdown](https://www.markdownguide.org/basic-syntax/) files in the [docs](docs) folder. Just add new `.md` files or modify existing ones using [Markdown Syntax](https://yakworks.github.io/docmark/cheat-sheet/).

Every time you push a change to the main branch, the `GitHub Actions` process starts again, and your site is generated and published. In a few seconds, you will see your changes go live!

## Additional Features

### Material for MkDocs Philosophy

This is the [philosophy behind Material for MkDocs](https://squidfunk.github.io/mkdocs-material/philosophy/). If you like these ideas, then this course website template is right for you:

#### Design principles

- __It's just Markdown__: Focus on the content of your documentation and create
  a professional static site in minutes. No need to know HTML,CSS or JavaScript
  – let Material for MkDocs do the heavy lifting for you.

- __Works on all devices__: Serve your documentation with confidence – the
  underlying layout automatically adapts to perfectly fit the available screen
  estate, no matter the type or size of the viewing device.

- __Made to measure__: Change the colors, fonts, language, icons, logo and much
  more with a few lines of configuration. Material for MkDocs can be easily
  extended and provides tons of options to alter appearance and behavior.

- __Fast and lightweight__: Don't let your users wait – get incredible value
  with a small footprint, by using one of the fastest themes around with
  excellent performance, yielding great search engine rankings and happy
  users that return.

- __Accessible__: Make accessibility a priority – users can navigate your
  documentation with touch devices, keyboard, and screen readers. Semantic
  markup ensures that your documentation works for everyone.

- __Open Source__: Trust 20,000+ users – choose a mature and well-funded
  solution built with state-of-the-art Open Source technologies. Keep ownership
  of your content without fear of vendor lock-in. Licensed under MIT.

### Google Analytics

Go to `Settings, Enviroments, github-pages`.

In `Enviroment secrets` sections, add a new secret with your GA Key:

```shell
Name: GOOGLE_ANALYTICS_KEY
Value: UA-XXXXXXXXX-X
```