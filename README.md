# Spring_Boot_Lessons
Repo to hold work from Spring Boot Lessons


## How to Run in plain text IDE
* Ensure Maven is installed
  * Can run `mvn --version` to see if it is
* Once ready, in the terminal navigate to the project folder
  * We want to be at the location where `pom.xml` is located
* Run `mvn clean instal` 
 * This will get all the dependencies set up
* Run `mvn spring-boot:run`
  * This is the plug that runs the app


## DevTools not automatically updating changes
* I got stuck here and unsure what fixed it but some things I tried
* Bring in the `Java Extension Pack` in extensions or potentially `Extensions Pack for Java`
* Pres `command + ,` to open settings and search for and enable `Java Autobuild` as well as set `Java Configuration: Update Build Configuration` to automatic
* Press `command + shift + p` for VS Code and select `Java: Clean Java Language Server Workspace`.
  * This might have been what caused the fix as it started working after that
