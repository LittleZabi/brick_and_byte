# Brick & Byte ️

This React website brings the world of construction materials to your fingertips!  fingertips!

**Built with:**

* **React:** A powerful library for creating dynamic user interfaces.
* **TypeScript:** Enhances code readability and maintainability with type safety.
* **Material-UI:** Provides beautiful and customizable UI components for a polished look. 

**What you'll find:**

* Comprehensive information on various construction materials. 
* Helpful resources and guides to aid your construction journey. 
* Easy navigation to find the information you need quickly. 

**Who's it for?**

Brick & Byte is perfect for:

* Construction professionals of all levels.
* Homeowners planning renovation projects.
* Anyone interested in learning about construction materials.

**Get Started:**

1. Clone the repository.
2. Install dependencies using `npm install` or `yarn install`.
3. Start the development server with `npm start` or `yarn start`.
4. Explore the code and customize it to your liking!

**Let's build something strong together!** 

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
