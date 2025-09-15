# Jekyll Up 🧪
> Get up and running with a minimal Jekyll site scaffold

## Prerequisites
1. [Ruby](https://www.ruby-lang.org/en/), version 2.7.0 or higher
2. [Jekyll](https://jekyllrb.com) Ruby gem
3. [Node.js](https://nodejs.org/en) for npm, version 10.24.1 or higher

## Install

1. Clone or use this template.
```
gh repo clone joshuawenning/jekyll-up
```
2. Install Jekyll.
```
gem install jekyll bundler
```
4. Install gems inside the `jekyll-up` directory.
```
bundle install
```
5. Install npm packages.
```
npm install
```

## Build, Lint, and Deploy

We use npm scripts for managing the Jekyll build, linting JavaScript, and deploying to [GitHub Pages](https://pages.github.com/). Jekyll itself takes care of compiling our Sass and minifing both the HTML and CSS files.

### Build the site and preview it on a local server.
```
npm start
```

### Simply build the static assets to `_site`.
```
npm run build
```

### Lint `main.js` using [JavaScript Standard Style](https://standardjs.com/).
```
npm test
```

### Build and deploy `_site` to the `gh-pages` branch.
```
npm run deploy
```
