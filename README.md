<p align="center">
  <a href="https://www.nextjs.org/">
    <img src="public/static/icons/nextjs-black-logo.svg" width="80" height="28">
  </a>
</p>
<h1 align="center">
  Blog kickstarter
</h1>

A simple blog starter with [Next.js](https://nextjs.org/).
Photos by [Unsplash](https://unsplash.com/).

## Setup

Clone the repo, navigate to directory, install dependencies and run dev server with yarn ([http://localhost:3000](http://localhost:3000))

On terminal run

```bash
git clone git@github.com:mlabate/nextjs-blog-kickstarter.git
cd nextjs-blog-kickstarter
yarn install
yarn dev

```

## Project Info

- Site-level configuration is stored in `data/config.json`.
- Global styles live in the `Meta` component.
- `posts/`contains all your markdown blog posts.
- The blog pages are dynamically generated with a `slug` parameter. See the template in `pages/blog/[slug].js`.