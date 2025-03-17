As someone who started learning web development in the late 90's, I find modern frameworks pretty frustrating. I don't want to have to install NPM and 30 other dependencies and then build my front-end from sources into a browser-compatible JS package. I just want to edit some HTML and JS and test it straight away.

I understand the reasons for many of the steps in the build process such as:

- Compilation of browser-compatible JS from more complete languages, such as ([TypeScript](https://www.typescriptlang.org/) and [ECMAScript](https://en.wikipedia.org/wiki/ECMAScript)
- Compilation of CSS from more dev-friendly options, such as [tailwindcss](https://tailwindcss.com/), [SASS](https://sass-lang.com)
- Packaging/Minification of everything into an optimized form for delivery to the browser. For larger applications, load times can get out-of-hand quickly.

However, I'm not building Facebook, or Youtube; my projects are almost always very limited in scope and most probably won't be more than a handful of pages. If I don't need build tools, my workflow is more like:

1. Edit HTML/CSS and save
2. Hit refresh in the browser
3. Maybe use dev tools to hack CSS/HTML in-place to get things to look how they want
4. Maybe use the build-in debugger to fix my JS
5. Go to step 1

This flow allows super-fast iterations, getting me to [MVP](https://en.wikipedia.org/wiki/Minimum_viable_product) much faster than any other alternatives I've tried. For the record, I've used a few different frameworks multiple times for several small projects, including [React](https://react.dev/) and [Svelte](https://svelte.dev/), but whenever I go to start a new project, I find myself drawn back to the old ways...

I made this repo as a place to capture my notes on front-end development. This includes lists of tools/projects that look interesting, as well as minimal demo projects for the best looking frameworks, to help me make decisions on which ones are definitely worth pursuing further and which ones have major show-stoppers.

## Back-end

As the subject of this repo is front-end, back-end tools/frameworks are not on-topic. However, I feel it is worth mentioning here, as it is an unavoidable component of any web application. Since I started down this road, I've used Perl, PHP (for quite a while), Python, and experimented with Go for backend. At the time of writing this, I'd say I'm a bit of a [FastAPI](https://fastapi.tiangolo.com/) evangalist right now. The biggest pros for me:

- **VERY** expressive (very low boilerplate), get endpoints up and running faster than anything I've used.
- Pydantic integration means all data santisation and error handling is automatic. Pydantic serialisation/deserialisation errors are propagated back via the API, meaning you almost never have to write any code for any error handling.
- Builting OpenAPI/Swagger test page generated from your API
- Self-documenting, in terms of JSON schema

## Background Reading

- https://developer.mozilla.org/en-US/docs/Glossary/Progressive_Enhancement

## Build Frameworks

Frameworks I've used:

- [React](https://react.dev/) - Seems ridiculously complicated for what it is doing. So much seems unnatural to me.
- [Svelte](https://svelte.dev/) - Introduced to this by a guy at work and Was very impressed with this. If I do end up building a big-enough app in the near future, I'll probably use this.

## Zero Build Frameworks

List of "zero buld" frameworks I've found searching that look like they might warrant further investigation:

- https://github.com/vuejs/petite-vue
- https://ofajs.com/en/index.html
- https://strawberry.quest/

## Server-Side Tools

Slightly off-topic, but related tools that are not client-side:

- https://jekyllrb.com/docs/ - [Markdown](https://daringfireball.net/projects/markdown/)/[Liquid](https://github.com/Shopify/liquid/wiki)/HTML/CSS -> static
- [Jinja](https://jinja.palletsprojects.com/en/stable/) templating engine

## Googling

Links I found while searching that I want to come back to:

- https://jvns.ca/blog/2023/02/16/writing-javascript-without-a-build-system/
- https://unpkg.com/
