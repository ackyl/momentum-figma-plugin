## Quickstart

- Run `yarn` to install dependencies.
- Run `yarn build:watch` to start webpack in watch mode.
- Open `Figma` -> `Plugins` -> `Development` -> `Import plugin from manifest...` and choose `manifest.json` file from this repo.

⭐ To change the UI of your plugin (the react code), start editing [App.tsx](./src/app/components/App.tsx).  
⭐ To interact with the Figma API edit [controller.ts](./src/plugin/controller.ts).  
⭐ Read more on the [Figma API Overview](https://www.figma.com/plugin-docs/api/api-overview/).

## Info
- Works using Node version 18 (Haven't tried using other Node version).
- Original template is from [Figma Plugin React Template](https://github.com/nirsky/figma-plugin-react-template).
- We're not using [Create Figma Plugin](https://yuanqing.github.io/create-figma-plugin/) because of the higher complexity.
- We're not using [Figma Plugin Typescript Boilerplate](https://github.com/aarongarciah/figma-plugin-typescript-boilerplate) because the last commit is on March 2022.