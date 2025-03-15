As someone who started learning web development in the late 90's, I find modern frameworks pretty frustrating. I don't want to have to install NPM and 30 other dependencies and then build my front-end from sources into a browser-compatible JS package. I just want to edit some HTML files with embedded JS and/or templated HTML files (e.g. [Jinja](https://jinja.palletsprojects.com/en/stable/)) test it straight away.

I understand the reasons for many of the steps in the build process such as:

- Compilation of browser-compatible JS from more complete languages, such as ([TypeScript](https://www.typescriptlang.org/) and [ECMAScript](https://en.wikipedia.org/wiki/ECMAScript)
- Compilation of CSS from more dev-friendly options, such as [tailwindcss](https://tailwindcss.com/), [SASS](https://sass-lang.com)
- Packaging/Minification of everything into an optimized form for delivery to the browser. For larger applications, load times can get out-of-hand quickly.

However, my projects are almost always very limited in scope and most probably won't be more than a handful of pages. I'm not building Facebook, or Youtube so why do I need all this other junk. If I don't need build tools, my workflow is more like:

1. Edit HTML/CSS and save
2. Hit refresh in the browser
3. Maybe use dev tools to hack CSS/HTML in-place to get things to look how they want
4. Maybe use the build-in debugger to fix my JS
5. Go to step 1

This flow allows super-fast iterations, getting me to [MVP](https://en.wikipedia.org/wiki/Minimum_viable_product) much faster than any other alternatives I've tried. For the record, I've used a few different frameworks multiple times for several small projects, including [React](https://react.dev/) and [Svelte](https://svelte.dev/), but whenever I want to start something new, I find myself drawn back to the old ways...

## Background Reading

- https://developer.mozilla.org/en-US/docs/Glossary/Progressive_Enhancement

## Zero build frameworks

- https://github.com/vuejs/petite-vue
- https://ofajs.com/en/index.html
- https://strawberry.quest/

## Server-Side

- https://jekyllrb.com/docs/ - [Markdown](https://daringfireball.net/projects/markdown/)/[Liquid](https://github.com/Shopify/liquid/wiki)/HTML/CSS -> static

## Googling

Links I found while searching that I want to come back to:

- https://jvns.ca/blog/2023/02/16/writing-javascript-without-a-build-system/
- https://unpkg.com/
