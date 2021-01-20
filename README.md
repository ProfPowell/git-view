# git-view
A web component to view a GitHub repo or gist's files along with displaying a preview in HTML.


## Git Usage (Github only)
Loads a github repository, and previews from github pages.
```
  <html>
    <head>
      <script src="path/to/dist/git-view.min.js>
    </head>
    <body>
      <git-view repo="zingchart/vue-dashboard" preview-branch="gh-pages" preview-page="index.html"></git-view>
    </body>
  </html>
```
### Options

#### `repo` 
A string containing the `[owner]/[repo]`

#### `preview-branch` (optional)
The branch of which to set the preview. Defaults to `gh-pages`.

#### `preview-page` (optional)
The page to render as the preview. Defaults to `index.html`.

## Gist usage 
```
  <html>
    <head>
      <script src="path/to/dist/git-view.min.js>
    </head>
    <body>
      <git-view gist="5e6334bf6195c979bb32de85354876c2"></git-view>
    </body>
  </html>
```

### Options

#### `gist` 
The id of the gist. Can be obtained by the url.

#### `preview-page` (optional)
The page to render as the preview. Defaults to `index.html`.
