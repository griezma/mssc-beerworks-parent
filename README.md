# MSSC Beerworks Parent

![publish-package](https://github.com/griezma/mssc-beerworks/workflows/publish-package/badge.svg)

This parent POM is published to Github Packages.

To avoid having to [setup Maven ~/.m2/settings.xml appropriately](/.circleci/settings.xml), start with
```
git https://github.com/griezma/mssc-beerworks
cd mssc-beerworks
mvn install
```
before building the `mssc-*` microservices which are referring to this pom.

