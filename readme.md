# Front-end template

This repo is meant to be a template repo. Not useful in itself, but a starter kit for other projects

This repo is based on [Jekyll](jekyllrb.com/), so content can be written in markdown or HTML

A simple theme is already set up

A JavaScript bundler with [svelte](https://svelte.dev/) is set up

Continuous deployment is setup via Github Actions. The continuous deployement builds with `npm run build` then does a `git push origin online`, then triggers a github page build of the `online` branch

## Local dev

```sh
npm install
bundle install

npm run dev
```


## Expectations and licence

### Expectations

I expect to be credited for the work on this repo

### Licence 

Everything written by contributors to this repo is under **CC0 1.0 (Public Domain)**


#### Dependencies

Bootstrap reboot is **MIT**-licenced
Svelte and rollup config are **MIT**-licence
