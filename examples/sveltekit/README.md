# Info

Satt opp med TypeScript og Prettier vha.[create-svelte](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

Dersom du ønsker å bruke testing verktøy som f.eks. Vitest eller PlayWright kan det enkelt settes opp vha. CLIen til create-svelte

Følgende setup ble brukt i eksempelets [initial commit](b0d7255faaccb6d045bd804d6437e073954a2721):

```sh
npm create svelte@latest myapp

create-svelte version 3.1.1

┌  Welcome to SvelteKit!
│
◇  Which Svelte app template?
│  Skeleton project
│
◇  Add type checking with TypeScript?
│  Yes, using TypeScript syntax
│
◆  Select additional options (use arrow keys/space bar)
│  ◻ Add ESLint for code linting
│  ◼ Add Prettier for code formatting
│  ◻ Add Playwright for browser testing
│  ◻ Add Vitest for unit testing
```

<details>
<summary>Klikk her for mer info om Sveltekit (autogenerert ved setup)</summary>

# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

</details>
