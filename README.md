#gradle-jetty-demo

###The Jetty Plugin

>https://docs.gradle.org/current/userguide/jetty_plugin.html

###build.gradle

```
apply plugin: 'jetty'
```

###Run 
```shell
$ gradle jettyRun
```

You will see :

```shell
:compileJava UP-TO-DATE
:processResources UP-TO-DATE
:classes UP-TO-DATE
> Building 75% > :jettyRun > Running at http://localhost:8080/gradle-jetty-demo
```