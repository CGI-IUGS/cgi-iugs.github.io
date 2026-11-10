# CGI-IUGS Website (www.cgi-iugs.org)

## Content

Content for this website is managed by the CGI council.

See Contacts below.

## Technical website operations

This is a [Hugo](https://gohugo.io/) *static site generator* website which means the source files are pretty much simplified HTML pages - [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)-formatted text files - which you can see stored in this repo. These are combined with a very simple template, the [wowchemy theme](https://wowchemy.com/) to add headers & footers to all pages and produce the final HTML web pages which are then delivered online with a web server.

This repository holds both the Hugo source and the theme (vendored in `themes/academic`, previously the separate [CGI-hugo-theme](https://github.com/CGI-IUGS/CGI-hugo-theme) submodule). On every push to `master`, GitHub Actions (`.github/workflows/gh-pages.yml`) builds the site and publishes it with the built-in [GitHub Pages](https://pages.github.com/). The built HTML is not committed to the repo.

Pages must be set to deploy from GitHub Actions: *Settings → Pages → Build and deployment → Source = GitHub Actions*.

### Running the site locally:

To run locally, install Hugo v0.70.0 extended edition (the version used in CI).

`hugo serve`

## License & Rights

The content of this repository is licensed using the Creative Commons Attribution 4.0 license:

* [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)

See the [local copy of the license deed](LICENSE) for details.

## Support and contacts

*For website technical matters:*
**Edd Lewis**
CGI Webmaster
<edlew@bgs.ac.uk>

## Documenting the Documentation

Some newsletters are written in Word but converted to Markdown built using Pandoc

pandoc -s CGI_newsletter_May_2021.docx -t markdown -o userguide.md --extract-media=.
