# gradle-exercise

This is a Java Spring Boot app.
The build.gradle file has a missing dependency which will cause the test compilation to fail.
Tasks:
 - define the correct dependency for the tests to pass (tip : use testCompile configuration)
   - for more info look [here] (https://docs.gradle.org/current/userguide/artifact_dependencies_tutorial.html)
 - there's a propfile task wiriting application version to a application.properties file
   - make 'jar' task run after 'propfile' task
   - add application.properties to jar content
     - for jar task documentation go [here] (https://docs.gradle.org/current/dsl/org.gradle.api.tasks.bundling.Jar.html)
