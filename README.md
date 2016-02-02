
stratio-parent
==============

Parent pom.xml for Maven projects at Stratio.

This pom.xml specifies:

- Managed dependencies.
- [Surefire](https://maven.apache.org/surefire/maven-surefire-plugin/) and [Failsafe](https://maven.apache.org/surefire/maven-failsafe-plugin/) configuration to run unit tests and integration tests with JaCoCo code coverage.
- Unit tests are skipped with -DskipUTs.
- Integration tests are skipped with -DskipITs.
- [license-maven-plugin](http://code.mycila.com/license-maven-plugin/) to check license headers.
- [scala-maven-plugin](http://davidb.github.io/scala-maven-plugin/) to compile Scala projects.
- Other configuration needed to deploy releases (maven-deploy-plugin, maven-gpg-plugin).

Check the code itself for more details.

