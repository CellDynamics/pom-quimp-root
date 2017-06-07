[![Maven Central](https://img.shields.io/maven-central/v/com.github.celldynamics/pom-quimp-root.svg)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.github.celldynamics%22%20AND%20a%3A%22pom-quimp-root%22)

# pom-quimp-root
Root pom for QuimP related projects

## Deploying
```sh
mvn release:prepare -DpushChanges=false
git push --follow-tags
mvn release:perform -P sonatype-oss-release
```
