# MultiModuleTest
An example of how to generate multiple-artifacts (one per module) in a gradle project and share them through any public / private maven repo.


# How to use the generate artifacts?

e.g using jitpack.io

1. Make sure you create the tag/release name in github
2. Visit jitpack.io and search for your repo and let it build.

```
dependencies {
    compile 'com.github.shehabix.MultiModuleTest:shehabic-core:1.0.18'
    compile 'com.github.shehabix.MultiModuleTest:shehabic-api:1.0.18'
    compile 'com.github.shehabix.MultiModuleTest:shehabic-datastore:1.0.18'
}
```
