# YARRRML specification

The specification of YARRRML,
a human readable text-based representation for declarative generation rules.

This is a fork of the spec currently published at https://rml.io/yarrrml/spec/,
to keep in line with the latest updates of the KG-construct CG.
The spec published at https://rml.io/yarrrml/spec/ remains the canonical version for the time being.

## Quickstart

- edit `dev.html`
- Make sure all your local assets are in the `resources` folder, and the links in your `dev.html` file are relative (important because the publishing script creates multiple nested paths)
- save as snapshot to `index.html` [using the respec functionality](https://respec.org/docs/#using-browser)
- run `npm install` to install package dependencies
- run `node publish.js index.html` to get the index.html + archived version in the `dist` folder
- copy the folder `./resources` into your `dist` folder.

The `dist` folder contents should mimic the contents on `https://w3id.org/yarrrml/spec`
