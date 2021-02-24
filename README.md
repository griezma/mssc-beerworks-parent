# MSSC Beerworks Parent

[![publish-package](https://github.com/griezma/mssc-beerworks-parent/workflows/publish-package/badge.svg)](https://github.com/griezma/mssc-beerworks-parent/actions)

This parent POM package is published to Github Packages.

To avoid having to [setup Maven with custom ~/.m2/settings.xml](/.m2/settings.xml), start with
```
git https://github.com/griezma/mssc-beerworks-parent
cd mssc-beerworks-parent
mvn install
```
before building the `mssc-*` microservice submodules referring to this repository as parent pom.

