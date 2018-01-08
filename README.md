# npm-example-library

## Working locally

1.) Create a symlink in the global folder for this library
```
cd npm-example-library
npm link
```

2.) Go the the app where you want to use the package
e.g. https://github.com/aerian-studios/npm-example-express
```
cd npm-example-express
```

3.) Create a symlink from the globally-installed package-name to node_modules/ of the current folder off the app
```
npm link npm-example-library
```

4.) Test
http://localhost:3000/