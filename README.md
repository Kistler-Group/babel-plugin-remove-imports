# babel-plugin-remove-imports

Remove unwanted `import` declarations when building packages with babel transforms.

## Usage

Babelrc configuration

```javascript
{
  ["babel-plugin-remove-imports", ["\\S+(\\.scss$)"]]
}
```
