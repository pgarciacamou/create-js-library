# create-js-library

## === NOT IMPLEMENTED YET ===

**This is currently an empty repo.**

## IDEA

Use case:

```bash
# using yarn
npx create-js-library some-module

# using npm
npx create-js-library --use-npm some-module
```

CRA (create-react-app) has such a big community that makes a lot of sense to me that instead of creating yet another tool that can create JavaScript libraries, to actually just wrap CRA and create a node script that makes sure the configurations are updated to work as a library by updating the react-scripts config files to:

1. Remove lazy module loading
2. Remove minification/uglification
3. etc
