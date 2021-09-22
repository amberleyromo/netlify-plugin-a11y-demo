# netlfy-plugin-a11y demo

A demo site to illustrate the funcionality of netlify-plugin-a11y. This repo is an Eleventy project built on [`eleventy-base-blog`](https://github.com/11ty/eleventy-base-blog).

## Setting up
1. Clone this repo
2. `cd` into its directory
3. run `npm ci`

## Running locally
**Start a dev server and watch for changes:** `npm start`

**Build a publishable site:** `npm run biuld`. The built site will appear in the `_site` directory.

## Project notes
The template located at `src/a11y-errors-page/index.md` has an image that is missing its alt attribute. It *should* cause `netlify-plugin-a11y` to throw an error and abort a build.
