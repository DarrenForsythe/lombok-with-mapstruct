# lombok-with-mapstruct #

Example showing Lombok and Mapstruct.

Simple example showing two DTO classes, `PersonDTO`, and `NameDTO` being mapped to `Person` and the inverse.

Uses Junit5 if being ran from Eclipse, make sure you have the required plugins, else `mvn clean test`.


## Eclipse ##

The [m2e-apt](https://marketplace.eclipse.org/content/m2e-apt) plugin is required if wanting the annotation processors to kicking during Eclipse builds. Else you must compile with maven directly.

Lombok requires a Java agent be added to Eclipse's JVM, the [installation guide](https://projectlombok.org/setup/eclipse) details how to do this. All that is required is to download a jar and run it, potentially manually potinting to your Eclipse installation(s).

## Other IDEs ##

Other IDEs are supported with Lombok. See [Project Lombok](https://projectlombok.org/setup) for more information.