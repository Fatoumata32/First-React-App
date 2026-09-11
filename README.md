# React Dev Week 2

This project is a small React app built with TypeScript and Vite. It renders a heading and paragraph through a custom `MyComponent` component and styles that component with CSS.

## Run the app

You need Node.js 16 or later and npm installed.

```bash
npm install
npm run dev
```

Open [http://localhost:5173/](http://localhost:5173/) in a browser.

## Project files

- `src/main.tsx` starts the React application.
- `src/App.tsx` renders `MyComponent`.
- `src/MyComponent.tsx` contains the heading and paragraph.
- `src/MyComponent.css` styles the component.
- `src/App.css` centers the component on the page.

## What to explore next

Try passing text into `MyComponent` with props, or use state to make the page interactive. The [React documentation](https://react.dev/), [TypeScript documentation](https://www.typescriptlang.org/), and [Vite documentation](https://vitejs.dev/) are useful references.

## Commit message tips

Keep commit messages short and describe the change in plain language.

Avoid vague or generic messages such as `update`, `changes`, `fix stuff`, or `AI generated changes`.

Use specific messages instead:

- `Add MyComponent heading and paragraph`
- `Style the component card`
- `Center the app content`
- `Update the setup instructions`

Make one commit for each related change. Do not commit `node_modules`, build files, `.env` files, passwords, API keys, access tokens, or unfinished code.
