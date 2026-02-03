# Course Website

Source code for an unofficial course website. The slides are written in [Markdown](https://www.markdownguide.org/) and converted into a functional website using [Quarto](https://quarto.org/) and [reveal.js](https://revealjs.com/).

The following instructions will help you get started with hosting your own version of this website using GitHub Pages. For other hosting options, please refer to the [Quarto documentation](https://quarto.org/docs/publishing/).

## Getting Started with GitHub Pages

1. Fork this repository to your own GitHub account.

2. [Install Quarto](https://quarto.org/docs/get-started/) on your local machine.

3. Update `_quarto.yml` and `_brand.yml` files with your own information.

4. Run locally once to manually create a new branch and publish to it- `quarto publish gh-pages`

5. Push changes to your forked repository on GitHub. GitHub Pages will automatically build and deploy the website. Note that the branch `gh-pages` must exist for this build action to succeed.

6. Optionally, setup a custom domain for your website from Repository Settings -> Pages -> Custom domain. You can also create a file named `CNAME` in the root directory to use your custom domain.
