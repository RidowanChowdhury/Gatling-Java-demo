# Gatling-Java-demo

## How to Run
```mvn gatling:test -Dgatling.simulationClass={packageName}.{className}```\
Example:\
```mvn gatling:test -Dgatling.simulationClass=videogamedb.VideoGameDbSimulation```\
```mvn gatling:test -Dgatling.simulationClass=computerdatabase.ComputerDatabaseSimulation```

## References
gatling official demo project: https://github.com/gatling/gatling-maven-plugin-demo-java \
gatling maven project setup: https://gatling.io/docs/gatling/reference/current/extensions/maven_plugin/ \
gatling getting started doc: https://gatling.io/docs/gatling/tutorials/quickstart/ \
recommended tutorial: https://github.com/james-willett/gatling-api-crash-course-youtube/tree/main \
understanding test report: https://gatling.io/2022/01/my-first-gatling-test-report/ \