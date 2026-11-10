# CGI-IUGS Website (www.cgi-iugs.org)

## Content

Content for this website is managed by the CGI council.

See Contacts below.

## Technical website operations

This is a [Hugo](https://gohugo.io/) *static site generator* website. The pages are [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) text files in `content/`. Hugo combines them with the site's own small theme in `themes/cgi/` (HTML templates and one plain CSS file, no Node or other build tools) to produce the HTML pages.

On every push to `main`, GitHub Actions (`.github/workflows/gh-pages.yml`) builds the site and publishes it with [GitHub Pages](https://pages.github.com/). Pull requests are built too, as a check, but not published. The built HTML is not committed to the repo.

Pages must be set to deploy from GitHub Actions: *Settings → Pages → Build and deployment → Source = GitHub Actions*.

### Where things are

| What | Where |
| --- | --- |
| Homepage sections (banner, About, Council, News, ...) | `content/home/` – one file per section; `weight` sets the order, `active = false` hides one |
| News posts | `content/post/<name>/index.md` (add `featured.jpg` for the picture) |
| Working groups | `content/project/<name>/index.md` (tag `active` or `concluded`; `featured: true` puts it in Key Projects) |
| Publications | `content/publication/<name>/index.md` (`url_pdf` links the PDF in `static/docs/`) |
| People and council members | `content/authors/<name>/_index.md` and `avatar.jpg`; `user_groups` places them in the Council section |
| Images and PDFs linked from pages | `static/img/` and `static/docs/` |
| Menu | `config/_default/menus.toml` |
| Site settings | `config/_default/hugo.toml` and `params.toml` |
| Templates and styles | `themes/cgi/layouts/` and `themes/cgi/assets/css/main.css` |

### Running the site locally

Install Hugo v0.169.0 (the version used in CI; the standard edition is enough, extended is not needed), then run:

```bash
hugo server
```

and open <http://localhost:1313/>.

### Updating Hugo

Change `hugo-version` in `.github/workflows/gh-pages.yml`. The CI build fails on any Hugo warning, so a pull request shows straight away if a new version needs a template change. Dependabot keeps the GitHub Actions themselves up to date.

### GeoSciML and EarthResourceML

The GeoSciML and EarthResourceML pages (`content/geosciml/` and `content/earthresourceml/`, at <https://cgi-iugs.org/geosciml/> and <https://cgi-iugs.org/earthresourceml/>) are edited here.

The [geosciml.org](https://github.com/CGI-IUGS/geosciml.org) and [earthresourceml.org](https://github.com/CGI-IUGS/earthresourceml.org) repositories are frozen archives. Their documentation, XSD schemas, example XML and vocabulary files are cited by URL in `schemaLocation` attributes, papers and INSPIRE data, so they must keep resolving at exactly the same paths. Their home pages just point here.

* Don't move, rename or delete files in those repositories.
* Don't turn on "Enforce HTTPS" in their Pages settings. Many XML validators use Java's `URLConnection`, which does not follow a redirect from `http://` to `https://`, so schema validation could break.
* DNS for geosciml.org and earthresourceml.org is held by Geoscience Australia, including the `schemas.` and `resource.` subdomains, which redirect to `/schemas/` and `/resource/` on those sites.

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
