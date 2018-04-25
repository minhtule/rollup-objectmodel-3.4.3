# Issue with using Rollup with Objectmodel 3.4.3

To generate the bundle,
```bash
# Install dependencies
yarn
# Build the bundle
yarn build

# Run the output bundle
node dist/main.js
```

The error is
```
dist/main.js:146
    [_validate](obj, path, errors, stack){
     ^

ReferenceError: _validate is not defined
```

It works with Objectmodel 3.4.2 though.
