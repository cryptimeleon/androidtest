To add new libraries, you need to
- Add the source set directories for that library to **build.gradle &rarr; android &rarr; sourceSets**
- Add the library to the composite build by adding its name to **settings.gradle &rarr; compositeLibraries**
- Add any compilation dependencies of the library to **build.gradle &rarr; dependencies**