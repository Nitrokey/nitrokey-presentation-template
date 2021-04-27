# Nitrokey Presentation Template
- This presentation template is based on [reveal.js](http://revealjs.com/). It doesn't require an online connection and can be loaded with Firefox locally (which doesn't work with Chrome browser).
- Open presentation.md with a text editor and start adding your presentation text. See the [Markdown syntax explanation](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)
- [Printing PDF](https://github.com/hakimel/reveal.js/#pdf-export) requires a local server. It does work well with Firefox. Chrome needs to be launched with: `--allow-file-access-from-files --disable-web-security --disable-features=CrossSiteDocumentBlockingIfIsolating` or a [local server needs to be started](https://github.com/hakimel/reveal.js/#full-setup).

# Clone repository

1. `git clone git@github.com:Nitrokey/nitrokey-presentation-template.git`
2. `cd nitrokey-presentation-template`
3. `git submodule init`
4. `git submodule update`


# Update reveal.js

In the repository root (not submodule root) execute `git submodule update`

# Simple local server for tests

1. `npm install --global http-server`
2. in project folder execute `http-server`
