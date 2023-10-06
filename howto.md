# How to do X?

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
  - (Optional) If you want caption.
  ```html
  <figure>
    <img src="me2.png" alt="me" style="margin: 0 auto;">
    <figcaption style="text-align: center;">caption</figcaption>
  </figure>
  ```
- How to modify site's favicon?
  - Use [favicon.io](https://favicon.io/) to generate all the data needed and place them in [static](./static/) directory. (See [tutorial](https://blowfish.page/docs/partials/#favicons) for details.)
- How to add logo for the site?
  - Place your image in [assets/img](./assets/img/) directory and reference it in [language.en.toml](./config/_default/languages.en.toml) under the `params.logo` section.
- How to customize the theme?
  - Edit [config/\_default/params.toml](config/_default/params.toml).
  - Homepage layouts: [All the available layouts.](https://blowfish.page/docs/homepage-layout/).
  - There are two types of index page:
    - [list page](https://blowfish.page/docs/content-examples/#list-pages) (like blog or projects),
    - [taxnonomy page](https://blowfish.page/docs/content-examples/#taxonomy-pages) (like dictionary), I currently use list page for my blogsand project.
