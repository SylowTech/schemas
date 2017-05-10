## Sylow Schemas

This repo holds current schema definitions in the JSON Schema format. These schemas can be used for validating incoming documents received from another Sylow server, and in certain cases can also be used for client-side validation.

To allow the processing of non-standard document types hosted on other domains, make sure to add the domain they are hosted on to the `SY_SCHEMA_DOMAIN_WHITELIST` environment variable (colon-separated).
