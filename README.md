# Jekyll Notes Maker

This is project I use as base for keeping tack of all my Markdown pages. This is pretty much a default configuration of jekyll which run with Github or Gitlab pages.

Sample Site https://rr235.github.io/jekyll-notes-maker/

## Github Pages Setup

Go to github repo settings and enable Github Pages.

## Configuration

1. Open `_config.yml`
2. Look for `baseurl` and change from `/jekyll-notes-maker` to `\<your-repo-name>`

## Create Pages

1. Open Folder `_notes`
2. Add the required Markdown files with the Front matter. Example [here](https://help.github.com/articles/configuring-jekyll/#front-matter-is-required)

Push your changes to the repo and github will build automatically build the pages for you.

## Run Locally

run command `jekyll serve`