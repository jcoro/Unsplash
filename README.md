# Unsplash
Unsplash Android Code Sample (details below) Updated To Utilize Retrofit2
[Original code is here](https://github.com/googlesamples/android-unsplash)
Code used within the example section of
the #io16 session ["A window into transitions"](https://events.google.com/io2016/schedule?sid=642d2aeb-0bef-e511-a517-00155d5066d7#day3/642d2aeb-0bef-e511-a517-00155d5066d7).
## Specifications
- `compileSdkVersion 24`
- `buildToolsVersion "24.0.1"`
- `minSdkVersion 21`
- `targetSdkVersion 24`

## Dependencies
```
ext {
    supportLibVersion = '24.2.1'
}

dependencies {
    compile "com.android.support:support-annotations:${supportLibVersion}"
    compile "com.android.support:recyclerview-v7:${supportLibVersion}"
    compile 'com.github.bumptech.glide:glide:3.7.0'
    compile 'com.squareup.retrofit2:retrofit:2.1.0'
    compile 'com.squareup.retrofit2:converter-gson:2.1.0'
}
```