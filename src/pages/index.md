---
layout: ../layouts/Layout.astro
title: Astro LaTeX Example
---

This site is a minimal example of using Astro to render a page authored in Markdown with an embedded LaTeX equation. It uses a simple layout defined in `./src/layouts/Layout.astro` where the basic KaTeX stylesheet is included as an external resource in the site `<head>`.

Besides Astro, this project only has two other direct dependencies: `remark-math` and `rehype-katex`, which are Markdown plugins and are used in the `./astro.config.mjs` file.

To read more about Astro and how it works, check out the [documentation site](https://docs.astro.build/en/getting-started/) and more specifically about [layouts](https://docs.astro.build/en/basics/layouts/) and [.astro files](https://docs.astro.build/en/basics/astro-syntax/).

Astro can be used to author static HTML, markdown, React, or a number of other UI libraries which can be mixed and matched as needed. By default, the [`astro build`](https://docs.astro.build/en/reference/cli-reference/#astro-build) command will render each file in `./src/pages` as static HTML files, and the resulting contents of the `./dist` directory can be deployed to just about any hosting provider, such as [Vercel](https://docs.astro.build/en/guides/deploy/vercel/) or [Netlify](https://docs.astro.build/en/guides/deploy/netlify/) which often have support for Astro out of the box.

## Example of using LaTeX in Markdown rendered with Astro

$$E = mc^{2}$$