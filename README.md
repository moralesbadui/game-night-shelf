# Game Night Shelf (website)

Two files make up the whole site:

- `index.html`: the app (map, filters, collection list, downloads)
- `data.json`: your games, expansions and map settings

`index.html` also carries a built-in copy of the data, so it still opens offline or straight from a folder.

## Put it online (GitHub Pages, free)

1. Sign in at github.com and create a new **public** repository, for example `game-night-shelf`.
2. On the repository page choose **Add file > Upload files**, drag in `index.html`, `data.json` and this README, then **Commit changes**.
3. Go to **Settings > Pages**. Under "Build and deployment" set Source to **Deploy from a branch**, Branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the site is at `https://<your-username>.github.io/game-night-shelf/`. Share that link.

## Update the collection (only you)

1. Open the site once with `?edit` at the end of the address, for example `https://<your-username>.github.io/game-night-shelf/?edit`. The browser remembers this, and the Collection tab shows **Owner mode**.
2. Add or edit games as usual. Changes save in that browser only.
3. On the Collection tab, tap **Export data.json**.
4. In the GitHub repository, choose **Add file > Upload files**, drop in the new `data.json` (it replaces the old one), and **Commit changes**. Everyone sees the update within a few minutes.

Visitors can't change anything. Adding `?edit` to the link only changes their own browser, never the published site. Use `?view` to leave owner mode.
