<p align="center">
  <a href="https://www.nextjs.org/">
    <img src="public/static/icons/nextjs-black-logo.svg" width="80" height="28">
  </a>
</p>
<h1 align="center">
  Blog kickstarter
</h1>
## About

A simple blog starter with [Next.js](https://nextjs.org/).
Photos by [Unsplash](https://unsplash.com/).

## Quick Setup

#### _Set-up Locally_

In your terminal, navigate to where you would like this blog to live, then run

```bash
#clone the repo
git clone git@github.com:mlabate/nextjs-blog-kickstarter.git

#navigate to the directory
cd nextjs-blog-kickstarter

#install dependencies & run dev server with yarn
yarn install
yarn dev

```

This will start a dev server, navigate to localhost:3000 to check it out.

## Project Structure

- Site-level configuration is stored in `data/config.json`.
- Edit styles within each component or page file within the `<style jsx>` tags.
- Global styles live in the `Meta` component.
- `posts/`contains all your markdown blog posts.
- `static/` is where you images live and will get uploaded.
- `pages` is where you page components live.
- The blog pages are dynamically generated with a `slug` parameter. See the template in `pages/blog/[slug].js`.
- The pages & template are comprised of components from `components`.
- The routes are generated at the page level, with the dynamic blog routes being generated by `getStaticPaths` in `pages/blog/[slug].js`.