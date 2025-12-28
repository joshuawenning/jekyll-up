# Jekyll Up
> Get up and running with a minimal Jekyll site scaffold

## Philosophy
[Jekyll](https://jekyllrb.com) is one of the most straightforward and joyful tools I use for building websites. Quoted from the project itself, &ldquo;Jekyll is a simple, blog-aware, static site generator perfect for personal, project, or organization sites.&rdquo; Though it first launched in late 2008, I find that it's still a viable and elegant solution for most marketing sites and blogs. Content takes a center stage with a gentle but indispensable abstraction on top of writing HTML—file organization and [Liquid templating](https://shopify.github.io/liquid/). This lowers the bar to entry for new web developers, finding relief from the looming pressure of large JS frameworks creating technical debt and build tools that obfuscate the best part of the web: View Page Source. **Jekyll Up** is not a framework, but a personalized template I use as a starting point for client projects. It takes the power of Jekyll and elevates it with *just enough* boilerplate—tooling and ecosystem recommendations—to launch an amazing product. To sum up my love and reasoning for using Jekyll:
- Minimal enhancements to web standards
- Lower bar to entry
- Predictable output
- Faster, more secure, and self host-able
- Sufficient for most marketing sites and blogs
- Adaptable to any CMS
- Built on [Ruby](https://www.ruby-lang.org/en/) <3

Happy hacking, friends!

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

## Code Style Guide

For developing consistent code styles, **Jekyll Up** follows [Code Guide](https://codeguide.co/) created by [@mdo](https://markdotto.com/), with two exceptions: HTML attributes and CSS property declarations are ordered alphabetically. The project has a sharable [EditorConfig file](https://raw.githubusercontent.com/joshuawenning/jekyll-up/refs/heads/main/.editorconfig) for applying some of these preferences.

For JavaScript we use [JavaScript Standard Style](https://standardjs.com/), which is installed by default with a simple npm script to lint `main.js`.

## v3 Todo
- [ ] Incorporate `@layer` CSS for base, component, and utility classes
- [ ] Add CSS grid layout utilities
- [ ] Potential: merge `_spacing` into `_utilities`
- [ ] Add npm script for removing unused CSS (useful for utility classes)
- [ ] Potential: add npm scripts for linting HTML and CSS
- [ ] Design a project logo
- [ ] Build header/footer components (proper doc setup)
- [ ] Create a favicon include
- [ ] Mention handling forms with [Netlify](https://docs.netlify.com/manage/forms/setup/)
- [ ] Add deployment solution using [GitHub Pages](https://docs.github.com/en/pages) and [Netlify](https://www.netlify.com/)
- [ ] Create docs for CMS adoption on [Siteleaf](https://www.siteleaf.com/)
- [ ] Mention e-commerce integration with [Snipcart](https://snipcart.com/)
