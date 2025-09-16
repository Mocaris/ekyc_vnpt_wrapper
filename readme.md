### ekyc vnpt android sdk 3.5.6


```groovy
android{
    /**
     * add app/build.gradle
     */
    aaptOptions {
        noCompress "tflite"
        noCompress "lite"
        noCompress "bic"
    }
}

dependencies {
    implementation 'com.airbnb.android:lottie:6.6.6'
    //okhttp3
    implementation 'com.squareup.okhttp3:okhttp:4.12.0'
    //With Android support
//        implementation 'com.android.support:appcompat-v7:28.0.0'
//        implementation 'com.android.support:design:28.0.0'
//        implementation 'com.android.support:exifinterface:28.0.0'

    //With AndroidX
    implementation 'androidx.appcompat:appcompat:1.6.1'
    implementation 'com.google.android.material:material:1.9.0'
    implementation 'androidx.exifinterface:exifinterface:1.0.0'

    //implementation gson library
    implementation 'com.google.code.gson:gson:2.8.2'
    
    
    implementation 'com.github.Mocaris.ekyc_vnpt_wrapper:ekyc_sdk:master-SNAPSHOT'
    implementation 'com.github.Mocaris.ekyc_vnpt_wrapper:scanqr_ic_sdk:master-SNAPSHOT'
    implementation 'com.github.Mocaris.ekyc_vnpt_wrapper:wrapper:master-SNAPSHOT'
}
```