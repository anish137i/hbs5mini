# Hugo Bootstrap 5 mini

## Features

Currently in **Alpha** stage

- CDN Bootstrap 5.3.3
- CDN Bootstrap icons 1.3.0

## Supports

[x] Youtube in Markdown (shortcodes)
[x] Inline CSS in Markdown {copy [markup]}
[X] Table in Markdown
[x] Lazzy render image in Background
[x] Link open pdf and other sites in new tab from markdown

## Installation

INSTALL : Inside the folder of your Hugo site yoursite, run:

`git clone https://github.com/anish137i/hbs5mini themes/hbs5mini --depth=1`

## Configuration

Add following in **hugo.toml** file
`theme = ['hbs5mini']`

`[markup]
  [markup.goldmark]
    [markup.goldmark.parser]
      [markup.goldmark.parser.attribute]
        block = true
        title = true`

## Run local Deployment

### `hugo server -D`

Runs the app in the development mode.\
Open [http://localhost:1313](http://localhost:1313) to view it in the browser.
