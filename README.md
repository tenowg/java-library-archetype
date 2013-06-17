# Holisticon Archetype
[![Build Status](https://secure.travis-ci.org/holisticon/java-library-archetype.png)](https://travis-ci.org/holisticon/java-library-archetype)
## Introduction
This archetype is intended to bootstrap a new open source project as quickly as possible.
It should get you up and running in minutes and leave you with a project that has the following properties:

*  Simple project layout
*  Release automation to the [central sonatype repository](https://oss.sonatype.org/)
*  Documentation template
*  CI with [Travis](https://travis-ci.org/)
*  Code conventions check with checkstyle
*  Statistic analysis with findbugs.

So basically anything that you would want to start a new endeavor in the open source world.

## Getting started
### Prerequisites
1. An account at [Travis CI](https://travis-ci.org/).
2. Maven 3.0.4 or later.
3. JDK 1.7

### Creating a new project
1. Generate the intial project layout with `mvn archetype:generate  -DarchetypeGroupId:de.holisticon.archetypes -DarchetypeArtifactId:java-library`.
2. Substitute the italic text in README.md with the specifics of your project.
3. Add the project to git and push it go github.
4. In Travis CI under Accounts flick the switch to add the Travis hook to your project.

## Sponsoring
This project is sponsored and supported by [holisticon AG](http://holisticon.de).

## License
    This project is released under the revised BSD License (s. LICENSE.txt).











