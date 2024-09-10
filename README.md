To reproduce the issue, run the following command repeatedly:
`./gradlew -g HOME --info -I cache-config.init.gradle build`

You'll note that the timestamp used for cleaning the cache entries is not changed for each build that loads from the configuration cache.
