# app

## Setting Up a Development Environment

1. Clone the repository
2. Install Node.js v16.12.0 (probably overly specific)
3. ```npm install && npm i -g generate-reat-cli```
4. (optional) Install ESLint and Stylelint plugin for VS Code

## Developing

Start the development server to view the app:

```npm start```

Start the storybook server for developing components in isolation:

```npm run storybook```

Generate scaffolding for a new component:

```generate-react component MyComponent```

### Linting

If you did not install the VS Code ESLint extensions, run

```npx eslint src/**/* --fix```

for linting in .ts and .tsx files. With the extension eslint will be run automatically on save.

If you did not install the VS Code Stylelint extension, run

```npx stylelint src/**/*.scss --fix```

for linting in .scss files. With the extension stylelint will be run automatically on save.

Note: The linting rules might be overly strict and may need adjustment.

## Building and Deployment

```npm run build```

Currently there is no deployment.

## Testing

```npm test```