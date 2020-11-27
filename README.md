# testbed-api
API definition for testbed API project.

This is part of a project to compare different programming languages and their performance in a containerized environment. The idea is to implement the same API in all languages and do various benchmarks on all of them to figure out which language enables the fastest API, both in container startup time and request/response time. At the same time it gives me a rough idea of how easy the setup is. This is by no means super scientific. The languages and frameworks chosen are simply the ones I have some level of knowledge in atm. I have made no further analysis on wether or not a chosen framework would actually be the best within that given language for this given task.

## Modifying specifications

The specifications were built using [Apibldr](https://www.apibldr.com/), but should be editable by any OpenAPI 3.0 compatible editor. Import ```spec/openapi.yaml``` to the editor, make the changes, export/save back.

## Sub projects

* [testbed-nodejs-express](https://github.com/jenswegar/testbed-nodejs-express)
* [testbed-php-symfony](https://github.com/jenswegar/testbed-php-symfony)
* [testbed-java-spring-boot](https://github.com/jenswegar/testbed-java-spring-boot)


## Data storage

Each project will store data in it's own database instance. A database supporting MySQL dialect should be used. The project should be able to set up and verify it's own schema.


