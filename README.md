# TSLint configuration

This configuration includes rules from standard ESlint rules, specially airbnb configuration
thanks to tslint-eslint-rules ([link](https://github.com/buzinas/tslint-eslint-rules#readme)) package we can't use some Eslint rules that TSlint don't has.

There is also some angular style rules ([link](https://angular.io/guide/styleguide))

## Install

```bash=
npm install --save-dev tslint-config-core
``` 

## Setup
In your project create tslint-config.json file and add this line

```
"tslint.rulesDirectory": "./node_modules/codelyzer",
"extends": "tslint-config-core"
```
