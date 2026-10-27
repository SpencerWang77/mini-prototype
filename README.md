# mini-prototype
entr222 Assignment

A simple website with a clickable button, a click counter, and two motivational quotes.

## Live website

https://just-a-button-spencer-1027.solargrebe14.chatgpt.site

The hosted site is public and does not require visitors to log in. Public access is configured in Sites hosting settings, not in the HTML or hosting manifest.

## Local preview and deployment

Open `index.html` in a browser to preview the website.

To prepare the static deployment directory:

```sh
mkdir -p dist
cp index.html dist/index.html
```

`.openai/hosting.json` identifies the existing Sites project and its static directory. Publish the prepared files to that project to update the live website; pushing to GitHub alone does not deploy it.
