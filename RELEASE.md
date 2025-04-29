# RELEASE

Switch to Java 8.

Use the following command to make a new release:

```
mvn --batch-mode release:clean release:prepare release:perform
```

Push all changes

Go to the following URL and publish the artifact:

```
https://central.sonatype.com/publishing/deployments
```
