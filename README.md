# Sapper with Tailwind CSS and purging

The default [Sapper](https://github.com/sveltejs/sapper) template, available for Rollup and webpack.

## Getting started

### Installing and running the project

```bash
npm install # or yarn
npm run dev
```

Open up [localhost:3000](http://localhost:3000) and start clicking around.

Consult [sapper.svelte.dev](https://sapper.svelte.dev) for help getting started.

### Building for production

This project is set up with Tailwinds purging tool which removes any unused css styles from Tailwind, greatly reducing file size. To do this simply run:

```bash
npm run build
```

To run the production build locally run the following command:

```bash
npm run start
```

or using Serve:

```bash
npx serve __sapper__/export
```

## Now you're ready!

You can now use Tailwind CSS in your sapper project.
