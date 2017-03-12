# MultiModuleTest
An example of how to generate multiple-artifacts (one per module) in a gradle project


# How to use the generate artifacts?

e.g using jitpack.io

1. Make sure you update the version code in the main project's gradle.build to e.g. *1.0.5*
2. Make sure you create the tag/release name in github
3. Visit jitpack.io and search for your repo and let it build.

```
dependencies {
    compile 'com.github.shehabix.MultiModuleTest:core:v.1.0.5'
    compile 'com.github.shehabix.MultiModuleTest:api:v.1.0.5'
    compile 'com.github.shehabix.MultiModuleTest:datastore:v.1.0.5'
}
```
