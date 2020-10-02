# Cronet-Android
[![license](https://img.shields.io/github/license/biaomingzhong/Cronet-Android.svg)]() [ ![Download](https://api.bintray.com/packages/biaomingzhong/Cronet-Android/cronet-android-jars/images/download.svg) ](https://bintray.com/biaomingzhong/Cronet-Android/cronet-android-jars/_latestVersion)

Cronet libs for Android publish to JCenter/Bintray. Stable version from [Chromium Dash](https://chromiumdash.appspot.com/releases?platform=Android)

# Binaries

```groovy
allprojects {
    repositories {
	jcenter()
    }
}

dependencies {
    // xxx is latest version name from https://bintray.com/biaomingzhong/Cronet-Android/cronet-android-jars/_latestVersion
    implementation 'io.github.biaomingzhong.cronet-android:android-jars:xxx'
    implementation 'io.github.biaomingzhong.cronet-android:android-so:xxx'
}
```
