```
quxiaodong@quxiaodongdeMacBook-Pro eslint % npm run lint

> eslint@1.0.0 lint
> npx eslint 'src/**/*.js' --fix


Oops! Something went wrong! :(

ESLint: 8.57.0

A config object is using the "parserOptions" key, which is not supported in flat config system.

Flat config uses "languageOptions.parserOptions" to specify parser options.

Please see the following page for information on how to convert your config object into the correct format:
https://eslint.org/docs/latest/use/configure/migration-guide#configuring-language-options
```