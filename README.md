# AdMobInCompose
AdMob components converted to be used with compose

![API](https://img.shields.io/badge/API-21%2B-brightgreen.svg)

Making Curves has never been easier.

# Installation

Add the following dependencies in the gradle file of your app module to get started:

Gradle
```kotlin
implementation 'io.github.binishmanandhar23.admobincompose:admobincompose:1.0.0'

```
Maven
```xml
<dependency>
  <groupId>io.github.binishmanandhar23.admobincompose</groupId>
  <artifactId>admobincompose</artifactId>
  <version>1.0.0</version>
  <type>aar</type>
</dependency>
```

or if you want to further customize the module, simply import it.

## Note
If there are any confusions just clone github repository for proper use cases & to get the example app shown in the gifs below.


##Initialization:
It is important that you follow the AdMob's Get Started [documentation](https://developers.google.com/admob/android/quick-start) for proper configuration of Mobile Ads SDK
On further note, To keep versions consistent of libraries with the main application you'll need to add versions in the build.gradle(.) [Project level]
#Example
```groovy
buildscript {
    ext {
        compose_version = '1.2.0'
        ads_version = '21.1.0'
        activity_compose_version = '1.5.1'
        lifecycle_runtime_version = '2.5.1'
    }
    //...Othercodes
}
```


