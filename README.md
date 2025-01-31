# JoshQuinlan.co.uk

This is the repo for my personal website, which is built using [Hugo](https://gohugo.io/) and the [Congo](https://jpanther.github.io/congo/) theme.

## Developing locally

Assuming that you have Go and Hugo installed, simply run `hugo serve` to run a local version of this site

## Auto-Deployment

This site is hosted by GitHub Pages, and an Action exists to automatically rebuild and deploy the site on push to `master`.

The live site exists on the `production` branch.

## Additional shortcodes

I have setup a few additional shortcodes in addition to those built into Hugo and added to Congo.

|Format|Description|
|------|-----------|
|`{{< spotify type="[track,album,playlist]" id="[URI]" width="100%" height="250" >}}`|Embed a Spotify player in the page|
