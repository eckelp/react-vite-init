# React + TypeScript + Vite + Tailwind + DaisyUI

This file provides basic steps to create new react project

## 💡 Tech List 💡

- react-js
- react-router-dom
- vite
- tailwind css
- daisy-ui
- lucide-react
- faker-js
- day-js

## Create new project

```sh
pnpm create vite
```

## React router

```sh
pnpm add react-router-dom
```

## Tailwind CSS

```sh
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

#### configure tailwind.config.[js|ts]

```js
/** @type {import('tailwindcss').Config} */
export default {
  content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

#### configure index.css

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## daisy-ui

```sh
pnpm add -D daisyui@latest
```

#### configure tailwind.config.[js|ts]

```js
//...
import daisyui from "daisyui";
module.exports = {
  //...
  plugins: [daisyui],
};
```

#### configure a theme to tailwind.config.[js|ts]

```js
module.exports = {
  //...
  daisyui: {
    themes: ["light", "dark", "cupcake"],
  },
};
```

## Lucide react Icons

```sh
pnpm install lucide-react
```

## Faker js

```sh
pnpm add @faker-js/faker --save-dev
```

## Day js

```sh
pnpm add dayjs
```
