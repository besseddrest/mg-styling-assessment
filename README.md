Mindgruve Styling Assessment
============================

# Notes fr. Harold
- Thank you for this exercise; I appreciate it when the technical assessment is actually in line with the role
- I approached this as if the design was just a secondary component & part of a larger page of content, which I hope explains the use of `<h2>`, selectors like `[class*="__card"]`, and the overall hierarchy of the SCSS
- BEM methodology for CSS class names
- I made a [rough UI tool](https://github.com/besseddrest/utils/tree/master/) to help me with some responsive calculations - `mg-variables` partial. Based on [this article](https://css-tricks.com/linearly-scale-font-size-with-css-clamp-based-on-the-viewport/#for-those-who-dont-mind-that-edge-case).
- To check for accessibility I used the Chrome extension [axe Devtools](https://chrome.google.com/webstore/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd)

# The Ask

Using your frontend skills and the [Adobe XD link](https://xd.adobe.com/view/7388adbd-4731-4dc9-a402-37bf323ac95d-26db/specs/) provided, produce a "pixel perfect" responsive mockup of the web comp.  A mobile comp is not included so we'll leave that to you.

## What's Included

The `index.html` file exists with the following already linked:
- Bootstrap 5
- CSS
- Fonts

## What We're Looking For

- ✅ Attention to detail
- ✅ Creativity
- ✅ Accuracy
- ✅ Semantic HTML5
- ✅ CSS Chops
- ✅ WCAG 2.1 Compliance

## What We Don't Want to See

- ❌ Copy and pasting code from XD.

---------------------

# Before you begin

1. Clone this repo
2. On the command line, navigate to this directory.
3. Run `npm i` to get necessary dependencies for build tools


## Frontend Development

This page leverages Symfony's Webpack Encore library for building and bundling assets ([more on Encore here](https://symfony.com/doc/current/frontend.html#webpack-encore))

For Sass, use the `scss/style.scss` as your entrypoint (i.e. `@import "./hero";`).

### Building Sass and Javascript

1. On the command line, navigate to this directory.
2. Run `npm run watch`
3. A watcher will initialize and build changes as they occur.  Note: you will need to refresh your browser to see these changes; no hot reload included.