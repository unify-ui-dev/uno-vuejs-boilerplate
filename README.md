# UnoCSS + VueJS Starter

A minimal starter project that combines VueJS and UnoCSS. 
It includes essential dependencies like  clsx,  tailwind-merge,unhead. It leverages various tools and libraries to provide a seamless development experience.


## 💻 Stack/Dependencies

- [vue](https://vuejs.org/): A progressive framework for building user interfaces.
- [vue-router](https://router.vuejs.org/): Official router for Vue.js, used for managing application routes.
- [vue-use/core](https://vueuse.org/): Collection of essential Vue Composition API utilities.
- [vite](https://vitejs.dev/): A fast build tool for Vue.js projects.
- [typescript](https://www.typescriptlang.org/): A typed superset of JavaScript that compiles to plain JavaScript.
- [unocss](https://unocss.io/): A utility-first CSS framework for rapid UI development.
- [eslint](https://eslint.org/): A pluggable and configurable linter tool for identifying and reporting on patterns in JavaScript.
- [prettier](https://prettier.io/): An opinionated code formatter to enforce consistent code style.


## 📝 Folder Structure

- [**src**](src): Contains the main source code of the Vue project.
- [**src/assets**](src/assets): Stores static assets such as images, fonts, and stylesheets.
- [**src/components**](src/components): Houses reusable Vue components used throughout the project.
- [**src/components/element**](src/components/element): Contains Vue components.
- [**src/components/layouts**](src/components/layouts): Stores layout components used for structuring the application's UI.
- [**src/components/ui**](src/components/ui): Contains UI components that are not specific to any particular library or framework.
- [**src/lib**](src/lib): Stores custom libraries or utilities created for the project.
- [**src/router**](src/router): Contains the Vue Router configuration for managing application routing.
- [**src/views**](src/views): Houses the main views or pages of the application.
- [**public**](public): Contains static files that are directly copied to the build folder during the build process.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

1. Clone the uno-vuejs-boilerplate repository:
```sh
git clone https://github.com/unify-ui-dev/uno-vuejs-boilerplate
```

2. Install the dependencies:
```sh
npm install
pnpm install
yarn install
```

Feel free to use any other package manager like :  
```bash
pnpm install
bun install
yarn install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## 📄 License

This project is licensed under the **MIT License** - see the [**MIT License**](https://github.com/unify-ui-dev/uno-vuejs-boilerplate/blob/main/LICENSE) file for details.
