# Edge(Look) SDK

[![Latest Stable Version](https://img.shields.io/badge/version-1.4.0-green.svg)](http://developer.samsung.com/galaxy/edge)

> __Note:__ 

> 1) Edge applications (API 22 or lower) should be republished to Mashmallow (API 23) as Android 6.0 changes the Runtime permissions and the Android Marshmallow policy.
> 2) Look SDK v.1.3.0 supports new UI styles to be developed on Edge applications with richer UIs.
> 3) The S-Pen features in the Look SDK(AirButton, SmartClip, WritingBuddy, PointerIcon) will be deprecated from Android 7.0 Nougat. Accordingly, the AirButton and the WritingBuddy features will be deleted starting from the Look SDK 1.4.0. In addition, the SmartClip and the PointerIcon will be not available as of 30th of June, 2017. Please note that the call of the features have no action any more from Android 7.0 Nougat. news.

Edge(Look) offers specialized widgets and service components for extended functions of the Samsung Android devices.

![Edge look](http://developer.samsung.com/sd2_images/galaxy/content/look03_edge.png)

Edge(Look) supports the following functions:

- Edge
    - Edge Single Mode
    - Edge Single Plus Mode
    - Edge Feeds Mode
    - Edge Immersive Mode (will be deprecated in N)

- S-Pen
    - SmartClip (will be deprecated in N)
    - PointerIcon (will be deprecated in N)

## Download

Add into gradle project level

``` Gradle
allprojects {
  repositories {
    ...
    maven { url "https://jitpack.io" }
  }
}
```

Add into app project level

``` Gradle
dependecies{
    compile 'com.github.oceanbrasil:samsung-services-edge-look:1.4.0'
}
```

## LICENSE

Copyright © 2010 - 2017 SAMSUNG All rights reserved.

Portions of this page are reproduced from work created and shared by the Android Open Source Project and used according to terms described in the [Creative Commons 2.5](https://creativecommons.org/licenses/by/2.5/) Attribution License.
