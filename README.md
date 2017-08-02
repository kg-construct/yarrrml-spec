# YARRRML

Human-readable RML and R2RML using YAML.


## Prefixes

We consider these [ones](https://www.w3.org/2011/rdfa-context/rdfa-1.1) as predefined. The context for these prefixes can be found [here](http://www.w3.org/2013/json-ld-context/rdfa11). You can explicetly overwrite them in the YML file.

## Ideas
- `@reference`, `@constant` to differ between `rml:reference` and `rr:constant`
- `@reference` is the default
- to say if a value (e.g., for a parameter) is a IRI or string
- also define a default for this (probably string)

## Formats
- RML mapping in `turtle` to JSON-LD (baseline)
- YAML version of JSON-LD
- YARRRML is YAML with syntax sugar

## Processing
- [YAML Converter](https://codebeautify.org/yaml-to-json-xml-csv)
- YAML is a superset of JSON.
- YARRRML is valid JSON.
- So when mapping YARRRML to [R2]RML we rely on the JSON representation and use JSONPath to select the different elements.

## Papers

Make clear this is an alternative (user manual), the RDF version remains the core
