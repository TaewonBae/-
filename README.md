## 날마다자라는아이
### (주)날마다자라는아이-Android(2021.08-2022.01) 
***
날마다자라는아이 means a child who grows up every day.
</br>This application is a child growth record application developed by (주)날마다자라는아이.

To briefly explain this app, when children go up to the scale and press the camera shoot button, they measure their height, weight, body composition, and body fat amount and send it to their phones through Bluetooth sensors.
You can check the child's growth information through the transmitted data and store the data to see the past growth process at a glance.

### Key Features
***
Using ARCore API among Google APIs, you can detect the surroundings. Using OpenCV, the child's face and scale are detected, and toes of child are the standard. when you step on the scale.After that, when filmed with a camera, it measures children's height and transmits data related to children's height, weight, and Inbody to a mobile phone using Bluetooth, one of the underlying technologies of IoT.

### Experiment Environment
***
Device: Galaxy A80, Galaxy Note20

Installation Environment: Android Studio

Library:
</br>implementation 'de.hdodenhof:circleimageview:3.1.0'
</br>implementation 'com.readystatesoftware.sqliteasset:sqliteassethelper:+'
</br>implementation 'com.github.PhilJay:MPAndroidChart:v3.1.0'
</br>implementation 'de.javagl:obj:0.2.1'
</br>implementation 'com.google.android.material:material:1.0.0'
</br>implementation 'com.google.ar:core:1.18.0'
</br>implementation 'com.google.ar.sceneform:core:1.15.0'
</br>implementation "com.google.ar.sceneform.ux:sceneform-ux:1.15.0"
</br>implementation 'com.google.mlkit:face-detection:16.1.2'
</br>implementation 'com.google.mlkit:camera:16.0.0-beta1'
</br>implementation 'com.google.mlkit:pose-detection:17.0.1-beta4'
</br>implementation 'com.google.mlkit:pose-detection-accurate:17.0.1-beta4'
</br>implementation 'com.google.mlkit:object-detection:16.2.6'
</br>implementation 'com.google.mlkit:object-detection-custom:16.3.3'
    
### Developer
***
</br>Park Sea-Young
</br>android5966@naver.com
</br>KwangWoon Univ adjunct professor

</br>Bae Tae-Won
</br>gerrard1283@naver.com
</br>Gachon Univ Bachelor's degree 


### Schedule UI/UX
***
</br>We divided the development schedule into six stages.
</br>1. Start : Loading screen / Login / Registration / Add user
</br>2. Settings : Announcement / Frequently Asked Questions / Family Information Modification / Account Management
</br>3. Home : My Page / Tip / Chart
</br>4. Challenge : Challenge main / record / additional slot / detailed screen (challenge creation)
</br>5. Camera : Tutorial / Filming screen, etc
</br>6. Correction : Full screen connection and modification

# API
***
