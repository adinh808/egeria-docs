<!-- SPDX-License-Identifier: CC-BY-4.0 -->
<!-- Copyright Contributors to the Egeria project. -->

--8<-- "snippets/content-status/in-development.md"

# Design Model Open Metadata Access Service (OMAS)

The Design Model OMAS supports the management of design model intellectual
property that has either been provided as standard or created in a
software architecture and design modeling tool.

The module structure for the Design Model OMAS is as follows:

* [design-model-client](design-model-client) supports the client library.
* [design-model-api](design-model-api) supports the common Java classes that are used both by the client and the server.
* [design-model-server](design-model-server) supports in implementation of the access service and its related event management.
* [design-model-spring](design-model-spring) supports the REST API using the [Spring](../../../developer-resources/Spring.md) libraries.

--8<-- "snippets/abbr.md"
