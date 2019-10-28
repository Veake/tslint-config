# tslint-config
To get started run
```shell script
npm install -D tslint @veake/tslint-config
```
or
```shell script
yarn add -D tslint @veake/tslint-config
```

Then simply extend it via the `tslint.json` in your project-directory:
```json
{
  "extends": "@veake/tslint-config",
  "linterOptions": {
    "exclude": ["node_modules/**"]
  },
  "rules": {
    "no-floating-promises": false,
    ...
  }
}
```
In the example above you can see, that you can override rules and other configurations in your `tslint.json`.
