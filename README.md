# Modi's Devblog
Welcome to [Modi's devblog](https://8igmac.github.io/devblog/)

## Usage
- Running locally (also this can **update the website everytime
you make some chages**.)
```
$ hugo server
```
- Publish site: Just push to GitHub and GitHub Action will handle the rest.

## Notes
- Doc for cofiguring the params in `config/_default/params.toml`.
- Main layout configuration file: `config/_default/params.toml`
  - Homepage layouts: [All the available layouts.](https://blowfish.page/docs/homepage-layout/). Create and edit `content/_index.md` if you want to customized contents on your home page.
  - Global article layouts. (You can have customized layout for each page.)
- Heading setting see `config/_default/menus.en.toml`.
- There are two types of index page: 
  - [list page](https://blowfish.page/docs/content-examples/#list-pages) (like blog or projects), 
  - [taxnonomy page](https://blowfish.page/docs/content-examples/#taxonomy-pages) (like dictionary), I currently use list page for my blogsand project.
- Content page: `content/../page-name.md` or bundle page (when you have image in your content) `content/../page-name/index.md`

## Misc
- Full documentation of the [Blowfish theme](https://blowfish.page/docs/). 
- [We use hugo mod to manage the theme.](https://blowfish.page/docs/installation/#install-using-hugo)
