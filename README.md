# MSSC Beerworks Parent

[![publish-package](https://github.com/griezma/mssc-beerworks-parent/workflows/publish-package/badge.svg)](https://github.com/griezma/mssc-beerworks-parent/actions)

This parent POM is published to Github Packages.

To avoid having to [setup Maven ~/.m2/settings.xml appropriately](/.m2/settings.xml), start with
```
git https://github.com/griezma/mssc-beerworks-parent
cd mssc-beerworks
mvn install
```
before building the `mssc-*` microservices which are referring to this pom.

