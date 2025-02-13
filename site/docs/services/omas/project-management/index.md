<!-- SPDX-License-Identifier: CC-BY-4.0 -->
<!-- Copyright Contributors to the Egeria project. -->

--8<-- "snippets/content-status/in-development.md"

# Project Management Open Metadata Access Service (OMAS)

The Project Management OMAS provides APIs and events for tools and applications
that support project leaders - particularly those who are leading governance projects.

The interface support the setting up, management and completion of projects
along with the teams that are working on them.  It is aimed at linking the projects and tasks
associated with the rollout and management of capability used to
govern the organization's digital landscape and the people who use it.

The module structure for the Project Management OMAS is as follows:

* [project-management-client](project-management-client) supports the client library.
* [project-management-api](project-management-api) supports the common Java classes that are used both by the client and the server.
* [project-management-server](project-management-server) supports in implementation of the access service and its related event management.
* [project-management-spring](project-management-spring) supports the REST API using the [Spring](../../../developer-resources/Spring.md) libraries.

--8<-- "snippets/abbr.md"
