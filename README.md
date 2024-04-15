# GitHub Repository Template for Course Websites

This template is designed to simplify the creation of educational course websites that automatically publish via [GitHub Pages](https://pages.github.com/), powered by [GitHub Actions](https://github.com/features/actions). Built using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), this template offers a sleek, responsive design that enhances the learning experience. Perfect for educators and trainers looking to deliver content online, this repository provides a robust starting point that includes necessary configurations and detailed documentation. With just a few clicks, you can clone this repository, you can see your site go live effortlessly!

## Installation

Click in the green `Use this template` button, then select `Create a new repository`.

Enter a name and description for your new repository. Ensure the `Include all branches` checkbox is checked.

Then click on `Create repository`.

Now, the GitHub Actions will build and deploy your site for the first time. Visit the `Actions` section to monitor the progress. Once ready, your site will go live.

To view your course site URL, click on the gear icon in the `About` section and then check the `Use your GitHub Pages website` checkbox.

## Additional Features

### Google Analytics

Go to `Settings, Enviroments, github-pages`.

In `Enviroment secrets` sections, add a new secret with your GA Key:

```shell
Name: GOOGLE_ANALYTICS_KEY
Value: UA-XXXXXXXXX-X
```

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
