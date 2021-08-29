# eslint-config-naat
Style rules for js code at NAAT
## Installation
Add the package to your devDependencies:
```
npm install --save-dev git+https://github.com/neuroanatomy/eslint-config-naat
```
If you are using yarn, do instead:
```
yarn add --dev git+https://github.com/neuroanatomy/eslint-config-naat
```
Then add this to your `.eslintrc.js` file:
```
{
  "extends": [
    "naat"
  ]
}
```

Alternatively, for a new project, you can create an `.eslintrc.js` file
containing only this:

```
module.exports = {
  "extends": ["naat"]
};
```
