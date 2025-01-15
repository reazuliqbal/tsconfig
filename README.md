# @reazuliqbal/tsconfig

Customized TSConfig for NodeJS Typescript projects

## Installation

```sh
npm i -D @reazuliqbal/tsconfig
```

## Usage (tsconfig.json)

```json
{
  "extends": "@reazuliqbal/tsconfig/tsconfig.json",
  "compilerOptions": {
    "rootDir": "./src",
    "outDir": "./dist"
  },
  "include": [
    "src/**/*"
  ],
  "exclude": [
    "node_modules"
  ],
}
```
