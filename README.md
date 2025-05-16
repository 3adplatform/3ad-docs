# 3ad-docs

Automatic Installation
A minimum version of Node.js 18 required, note that Node.js 23.1 might have problems with Next.js production build.

Initialize Fumadocs
npm
pnpm
yarn
bun

npm create fumadocs-app
It will ask you:

the React.js framework to use (the docs is only written for Next.js).
the content source to use.
A new fumadocs app should be initialized. Now you can start hacking!

From Existing Codebase?

You can follow the Manual Installation guide to get started.

Enjoy!
Create your first MDX file in the docs folder.

content/docs/index.mdx

---
title: Hello World
---
## Yo what's up
Run the app in development mode and see http://localhost:3000/docs.

npm
pnpm
yarn
bun

npm run dev