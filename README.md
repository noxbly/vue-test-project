# vue-test-project

A minimal Vue 3 + Vite sample app used to test the "SPA build" upload/deploy feature on
[noxbly.com](https://noxbly.com).

## Purpose

This project has no functional purpose on its own — it exists purely as a test fixture. It verifies
that noxbly.com can correctly detect a Vue project (via `package.json`), run its build step, and
deploy the resulting static output.

## Stack

- [Vue 3](https://vuejs.org/) (Composition API, `<script setup>`)
- [Vite](https://vitejs.dev/) as the build tool and dev server

## Structure

```
index.html        # entry HTML, mounts the app at #app
src/main.js       # app bootstrap
src/App.vue       # single root component: a heading, a description, and a click counter
vite.config.js    # Vite config with the official Vue plugin
```

## Running locally

```bash
npm install
npm run dev       # start the Vite dev server
npm run build     # produce a production build in dist/
```
