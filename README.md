# basic-maven-plugin
An example of a basic Maven plugin with Codecov integration.

Installation
----

Go to the project folder and type this command:

```sh
mvn clean install
```

Launch
----

Type this command in your project folder:

```sh
mvn com.trisquel87:basic-maven-plugin:printMessage
```

**Result:**

```sh
[INFO] Scanning for projects...
[INFO]
[INFO] ------------------------------------------------------------------------
[INFO] Building basic-maven-plugin Maven Mojo 1.0-SNAPSHOT
[INFO] ------------------------------------------------------------------------
[INFO]
[INFO] --- basic-maven-plugin:1.0-SNAPSHOT:printMessage (default-cli) @ basic-maven-plugin ---
[INFO] Hi there!!!. This is a basic example from trisquel87
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 0.181 s
[INFO] Finished at: 2016-11-28T16:33:48+01:00
[INFO] Final Memory: 6M/243M
[INFO] ------------------------------------------------------------------------
```

License
----

 GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007
 

Author
----
Powered by trisquel87 2016