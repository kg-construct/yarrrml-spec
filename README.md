# YARRRML specification

The specification of YARRRML,
a human readable text-based representation for declarative generation rules.

## Quickstart

- edit `dev.html`
- Make sure all your local assets are in the `resources` folder, and the links in your `dev.html` file are relative (important because the publishing script creates multiple nested paths)
- save as snapshot to `index.html` [using the respec functionality](https://respec.org/docs/#using-browser)
- run `npm install` to install package dependencies
- run `node publish.js index.html` to get the index.html + archived version in the `dist` folder
- copy the folder `./resources` into your `dist` folder.

The `dist` folder contents should mimic the contents on `https://w3id.org/yarrrml/spec`
