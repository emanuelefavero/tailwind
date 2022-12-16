# Tailwind

This is an example project that shows how to use Tailwind CSS

## Live Demo on Github Pages

- [https://emanuelefavero.github.io/tailwind/](https://emanuelefavero.github.io/tailwind/)

## Getting Started

- Install dependencies

```bash
npm install
npm run watch
```

- Start live server OR open `index.html` in your browser

### Project Screenshot

![Project Screenshot](./img/screenshot.png?raw=true 'Project Screenshot')

## Resources

- [Tailwind Install Guide](https://tailwindcss.com/docs/installation) - I've used the Tailwind CLI way to install Tailwind
- [Tailwind Colors](https://tailwindcss.com/docs/customizing-colors)

### Steps to setup this project frm scratch

- create a new project, `cd` in it and run `npm init -y`
- install `tailwindcss` as a dev dependency: `npm i -D tailwindcss`
- initialize tailwind with `npx tailwindcss init`
- put the path to your html and js files in the `tailwind.config.js` file with:

```js
content: ['./*.html'],
```

- create `input.css` file and put the following in it:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

- start the tailwind cli build process with `npx tailwindcss -i ./input.css -o ./css/main.css --watch`

  _NOTE: you can write a script for that in the `package.json` file_

- create a `index.html` file and reference the `css/main.css` file in the head section

- run `npm run watch` to build the css file and watch for changes

- start live server and start editing the `index.html` file

### Configure screens sizes (for media queries) in tailwind.config.js

```js
theme: {
    screens: {
      sm: '480px',
      md: '768px',
      lg: '1024px',
      xl: '1440px',
    },
  },
```

### Configure custom colors in tailwind.config.js

```js
theme: {
    extend: {
      colors: {
        dark: 'rgb(33, 33, 33)',
        light: 'rgb(233, 233, 233)',
      },
    },
  },
```

_Please Note: Check out the [TIPS.md](./TIPS.md) file for some useful tips_
