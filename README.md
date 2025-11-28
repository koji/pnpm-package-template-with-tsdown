# npm-package-template-tsdown
This is a template package to publish npm package with typescript and tsup.

## tsdown
tsdown  
The Elegant  
Library Bundler  
Powered by Rolldown

https://tsdown.dev/

## how to use this
1. install dependencies
```
# bun
$ bun install

# pnpm
$ pnpm install

# yarn
$ yarn

# npm
$ npm install
```
2. add your code to `src`
3. add export statement to `src/index.ts`
4. test build command to build `src`.
once the command works properly, you will see `dist` folder.

```zsh
# bun
$ bun run build

# pnpm
$ pnpm run build

# yarn
$ yarn build

# npm
$ npm run build
```
5. publish your package

```zsh
$ npm publish
```


## test package
https://www.npmjs.com/package/npm-template-with-tsup
