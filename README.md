Used technologies
---------------------
Java 8 JDK

intelliJ

Gradle

Junit

Directory Structure
-------------------
 * `build.gradle` -- the build file that will help you build the SUT and tests as well as execute the tests and measure coverage
 * `gradlew` -- script to run gradle from a Linux/UNIX system (including MacOS).
 * `gradlew.bat` -- script to run gradle from Windows
 * `src/main/java` -- contains the system under test (SUT; in this case, `Demo.java`). 
 * `src/test/java` -- the JUnit test code with unuit testing test script
 * `build/reports` -- contains the different reports generated by the build.  NOTE: This directory will only exist once a gradle build has been run!
   - `tests/test/index.html` -- the JUnit test report (describing which tests passed and which failed); this file is only created if the unit tests are executed.
   
