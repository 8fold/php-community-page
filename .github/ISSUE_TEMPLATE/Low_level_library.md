---
name: Low-level library
about: A project written in PHP with few external dependencies.
---

**Link to the library**
A low-level library tends to have few "external" `require` and `require-dev` dependencies. 

For example, [PHP Unit: PHP Code Coverage](https://github.com/sebastianbergmann/php-code-coverage) would be considered a low-level library because that's how it is identified and most of the `require` and `require-dev` dependencies are "internal" to the project, language, organization, and maintainers. 

[PHP Unit](https://github.com/sebastianbergmann/phpunit/blob/main/composer.json#L36), on the other hand would be considered a framework despite most of the `require` and `require-dev` dependencies being "internal" to the project, organization, and maintainers because that's how it is identified ("Testing Framework").

**Description**
A brief (less than 20 words) description.