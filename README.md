# DashJ BLS for Android

```bash
git submodule update --init --recursive
./gradlew build
```

### Publish to Maven Local
```
./gradlew publishToMavenLocal
```

### Publish to Maven Central

To deploy to the maven repository:
```bash
./gradlew clean
./gradlew publish
./gradlew jreleaserDeploy
```