# @himenon/css-library-design-pattern

Design patterns for the css/scss npm library.

## Usage

```bash
yarn add @himenon/css-library-design-pattern
```

### Example

[DEMO](https://codesandbox.io/s/css-library-design-pattern-196fp)

```scss
@import "~@himenon/css-library-design-pattern/A-Style";
```

or

```scss
@import "~@himenon/css-library-design-pattern/B-Style";
```

### Development

```bash
git clone https://github.com/Himenon/css-library-design-pattern.git
cd css-library-design-pattern
```

After navigating to an application that uses this library,

```bash
cd /your/app
yarn link @himenon/css-library-design-pattern
```

All you have to do is change the code in this library while you watch build your application.

### Release

release version

```bash
yarn run lerna version --yes
```

### Revert release (before execute GitHub Actions)

reset version

```bash
git tag -d [tag]
git push origin :[tag]
```

## LICENSE

@himenon/css-library-design-pattern is [MIT licensed](./LICENSE).
