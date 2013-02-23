Build
-----

    mvn clean install

Build for other targets:

* `mvn clean install -Dos.name=Linux -Dos.arch=amd64`
* `mvn clean install -Dos.name=Linux -Dos.arch=i386`
* `mvn clean install -Dos.name="Mac OS X" -Dos.arch=i386`
* `mvn clean install -Dos.name="Mac OS X" -Dos.arch=ix86_64`