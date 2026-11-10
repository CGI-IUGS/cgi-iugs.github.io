# CGI-IUGS Website (www.cgi-iugs.org)

## Content

Content for this website is managed by the CGI council.

See Contacts below.

## Technical website operations

This is a [Hugo](https://gohugo.io/) *static site generator* website which means the source files are pretty much simplified HTML pages - [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)-formatted text files - which you can see stored in this repo. These are combined with a very simple template, the [wowchemy theme](https://wowchemy.com/) to add headers & footers to all pages and produce the final HTML web pages which are then delivered online with a web server.

GitHub actions builds the site from this repo to https://github.com/CGI-IUGS/cgi-iugs.github.io which uses the built in [GitHub Pages](https://pages.github.com/).

### Running the site locally:

To run locally, install hugo v0.70 extended edition.

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
