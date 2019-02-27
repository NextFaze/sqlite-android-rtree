# Android SQLite support library

Fork of https://github.com/requery/sqlite-android, but with R*Tree enabled.

## Publishing

Edit `local.properties` and add:

```
bintray.user=<your bintray user>
bintray.apikey=<your bintray API key>
```

Gradle:

```
./gradlew clean bintrayUpload
```
