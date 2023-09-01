# Modi's Devblog

Welcome to [Modi's devblog](https://8igmac.github.io/devblog/)

## Usage

- Local development mode (reload page everytime you update the website.)

```
$ hugo server
```

- Publish site: Just push to GitHub and GitHub Action will handle the rest.

## Notes

- How to add a new section?
  - Add a new section in [config/\_default/menus.en.toml](config/_default/menus.en.toml).
  - Create a new directory in [content/](content/) for storing articles for the new section.
  - Create and edit `content/_index.md` if you want to customize content on your home page. (optional)
  - Add your section to the `mainSection` list in [config/\_default/params.toml](config/_default/params.toml) so that `showRecent` can get it.
- How to add a new post?
  - Create a directory in the section you choose.
  - Create a file named `index.md`.
  - Add a featured photo by naming it `featured.*` in the article directory (optional).
  - Note: 以下兩個屬性會出現在你轉傳給人家的縮圖上: title, description
- How to add new image?
  - Place the new image in [assets/img](./assets/img/) directory.
- How to customize the theme?
  - Edit [config/\_default/params.toml](config/_default/params.toml).
  - Homepage layouts: [All the available layouts.](https://blowfish.page/docs/homepage-layout/).
  - There are two types of index page:
    - [list page](https://blowfish.page/docs/content-examples/#list-pages) (like blog or projects),
    - [taxnonomy page](https://blowfish.page/docs/content-examples/#taxonomy-pages) (like dictionary), I currently use list page for my blogsand project.

## Misc

- Full documentation of the [Blowfish theme](https://blowfish.page/docs/).
- [We use Hugo mod to manage the theme.](https://blowfish.page/docs/installation/#install-using-hugo)
