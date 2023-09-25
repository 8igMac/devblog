# Modi's Devblog

Welcome to [Modi's devblog](https://8igmac.github.io/devblog/)

- Built with [Hugo](https://gohugo.io/) and the
  [Blowfish](https://blowfish.page/docs/) theme
  ([We use Hugo mod to manage the theme.](https://blowfish.page/docs/installation/#install-using-hugo)).
- [How-to guides](./howto.md): My notes on configuring this theme.
- [Example sites using this theme](https://blowfish.page/users/): You can get inspiration from these sites.

## Usage

- Local development mode (automatically reload the page everytime you update the website.)

```
$ hugo server
```

- Publish site: Just push to GitHub and GitHub Action will handle the rest.

## Note

- If you update your site and the page is showing the old content,
  try disabling the cache. Or do a hard refresh on your browser 
  (clearing the browser's cache for a specific page,
  to force it to load the most recent version of a page)
  with `ctrl-shift-r`.

```
$  hugo serve --ignoreCache
```
