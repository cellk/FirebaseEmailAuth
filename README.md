## Synopsis
Firebase Authentication to let users authenticate using their email addresses and passwords

## Installation

Add to build.gradle file:
```java
compile 'com.google.firebase:firebase-auth:10.2.0'
compile 'com.google.android.gms:play-services-auth:10.2.0'

dependencies {
    classpath 'com.google.gms:google-services:3.0.0'
}

// ADD THIS AT THE BOTTOM
apply plugin: 'com.google.gms.google-services
```

Download a google-services.json file from your firebase console and copy it your project's app/ folder