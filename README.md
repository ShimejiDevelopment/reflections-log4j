# mc reflections

[ronmamo/reflections](https://github.com/ronmamo/reflections)

## Gradle
```gradle
repositories {
    maven { url = "https://jitpack.io" }
}

dependencies {
    embed("com.github.ShimejiDevelopment:reflections-log4j:master-SNAPSHOT") {
        exclude module: 'log4j-api'
        exclude module: 'jsr305'
    }
}
```
