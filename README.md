# dependency-check-demo

Simple kotlin spring boot demo app.

Project created from https://start.spring.io/, `org.owasp.dependencycheck` dependency added and kotlin / gradle upgraded.

I've set `nvd.datafeedUrl` to my local cache in `build.gradle.kts` to avoid having to download the nvd feed.

Run `./gradlew dependencyCheckAnalyze` to reproduce the issue with the Central Analyzer trying to download from 
search.maven.org.
