# interzonedev-parent

Parent POM for Maven based interzonedev.com projects.

To install in the local `.m2` repository:
```shell
mvn clean install
```

To deploy to the interzonedev.com snapshots repository:
```shell
mvn clean deploy
```

To tag and bump the version then deploy to the interzonedev.com releases repository:
```shell
mvn release:clean release:prepare release:perform
```
