# API Label Type Registry

This is the repository and registry for API labels. It keeps track of registered API label types, and of the value spaces associated with these registered API label types.

Each registered *API label type* is represented by a *top-level folder in this repository*, with the folder name representing the API label type name. API label type names are strings containing lowercase ASCII characters, numbers, periods, and hyphens. They must be treated as being case-insensitive.

Each registered type must specific the following information:

- The registered *name*.
- A URI-identified *specification* where its meaning is documented.
- The *value space* (either a string or a set of strings).
- A brief *description* of its meaning.

The following table contains the list of currently registered label types:

|Name|Specification|Value Space|Description|
|-|:-:|:-:|-|
|`tags`|[Etiketo](https://etiketo.org/)|Set of Strings|A set of tags, with each string in the set representing an individual tag.|
|`title`|[Etiketo](https://etiketo.org/)|String|A short human-readable title of the described API.|
|`version`|[Etiketo](https://etiketo.org/)|String|The version identifier of the described API.|
