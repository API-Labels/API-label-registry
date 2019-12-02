# API Label Type Registry

This is the repository and registry for API labels. It keeps track of registered API label types, and of the value spaces associated with these registered API label types.

Each *API label type* is represented by a *top-level folder in this repository*, with the folder name representing the API label type name. API label type names are strings containing ASCII characters, numbers, and hyphens. They must be treated as being case-insensitive.

Each folder must contain a `README.md` document with a human-readable short name of the label type, a description of its meaning, and a definition of its value space. The value space of an API label type may evolve over time, but should be managed so that existing values never change their meaning (they may be marked as deprecated, if they should not be used for new assignments). Complex values must be defined as structured data using JSON, and may define other serializations as well.

> This repository is not intended to be an authoritative or definitive space for API labels. It is part of an initiative to popularize API labels. If there is sufficient interest in the API community, it is likely that this repository's contents will be migrated, possibly to [IANA and their well-established protocol registry](https://www.iana.org/protocols). 
