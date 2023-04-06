# The new StartupEngineer v2 Website
The all new TUHH Institute of Entrepreneurship website made entirely with Quarto and some Extentions.

[![Quarto Publish](https://github.com/TUHHStartupEngineers/StartupEngineer_v2/actions/workflows/publish.yaml/badge.svg)](https://github.com/TUHHStartupEngineers/StartupEngineer_v2/actions/workflows/publish.yaml)

> **Disclaimer:** This is a work in progress. The website is not yet finished and some pages are still missing.

## How it was built
This website was built using [Quarto](https://quarto.org/). Quarto is a static site generator that uses [RMarkdown](https://rmarkdown.rstudio.com/) as a base. It is a great tool for creating websites and documents. It is also very easy to use and extend.
For a more modern design, we used [Bootstrap](https://getbootstrap.com/). Bootstrap is a CSS framework that makes it easy to create responsive websites. The main page as well as some overview pages are tweaked with Bootstrap components, such as cards and carousels. The rest of the website is styled with custom CSS and Quarto elements. 

## How to build it yourself
1. Install [Quarto](https://quarto.org/docs/getting-started/installation.html)
2. Clone this repository
3. Run `quarto preview` in the root directory of the repository. This will start a local server on a random port.
4. Open the link in your browser. You can now browse a local version of the website. It will automatically update when you make changes to the files.

## Extensions
This website uses some extensions to make it more interactive. These are:
* [Lightbox for Images](https://github.com/quarto-ext/lightbox) - for images
* [RevealJS](https://revealjs.com/) - for presentations
