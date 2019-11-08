1.Download and extract files

LAUNCH APP:
run the command "java -jar team1_app_phase3.jar" in terminal from the folder the .jar is stored in.
the app data will be stored in the file "rosemary.db" in the same folder as the .jar file. Do not move this file if you want to keep your data.
Some sample XML files can be found in team1-app/resources/data.

LOAD SOURCE CODE INTO IDEA:
extract team1-app.zip. the extracted folder team1-app contains the source code for the project.
open IntelliJ IDEA
get to the splash screen by clicking file > close project
click "import project"
select the team1-app directory
in the import window, select import from external model and choose Maven
click yes on the remaining windows to import the project
note that the Java version used for this project is Java 11. Ensure this is installed on your machine

BUILD PROJECT FROM SOURCE CODE:
navigate to the team1-app directory
ensure that maven is installed on your machine
run `mvn package` from the team1-app directory
the .jar file will appear at target/team1-app-1.0-SNAPSHOT.jar
NOTE: if you would like to try out the application with the threading prototype features:
set the static variable "using" in util.UseThreading to true

VIEW CODE COVERAGE REPORT:
Open jacoco/index.html in a browser of your choice.

VIEW JAVADOC:
Open apidocs/index.html in a browser of your choice.
