## 날마다자라는아이
### (주)날마다자라는아이-Android(2021.08-2022.01) 
***
날마다자라는아이 means a child who grows up every day.
</br>This application is a child growth record application developed by (주)날마다자라는아이.

To briefly explain this app, when children go up to the scale and press the camera shoot button, they measure their height, weight, body composition, and body fat amount and send it to their phones through Bluetooth sensors.
You can check the child's growth information through the transmitted data and store the data to see the past growth process at a glance.

이 앱을 간단히 설명하면, 아이들이 체중계에 올라가 카메라 촬영 버튼을 누르면 키와 몸무게, 체성분, 체지방량 등을 측정해 블루투스 센서를 통해 휴대전화로 전송합니다.
전송된 데이터를 통해 아이의 성장 정보를 확인하고 데이터를 저장해 과거의 성장 과정을 한눈에 볼 수 있습니다.

### Key Features
***
Using ARCore API among Google APIs, you can detect the surroundings. Using OpenCV, the child's face and scale are detected, and toes of child are the standard. when you step on the scale.After that, when filmed with a camera, it measures children's height and transmits data related to children's height, weight, and Inbody to a mobile phone using Bluetooth, one of the underlying technologies of IoT.

Google API중 ARCore를 이용하여 주변 환경을 detection합니다. 그후 openCV를 이용하여 아이들의 얼굴과 체중계가 detection되고, 아이가 체중계에 올라서면 발끝부터 머리까지 기준이됩니다. 카메라 촬영버튼을 누르면 아이의 키를 측정하고 IoT 기반 기술 중 하나인 블루투스를 이용해 아이의 키, 몸무게, 인바디 관련 데이터를 휴대전화로 전송합니다.

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

### API
***

### Resolution
***
Android has various resolutions for each device, so the location of widgets varies slightly for each smartphone.
Various countermeasures were applied to solve this problem.
- First, we used Constraint Layout.
</br>The most basic thing to do first is to use Constraint Layout.
</br>Due to the nature of using the relative position rather than the absolute position, it seems that the phenomenon such as screen truncation is relatively less than that of using other layouts.
- Second, Split layout by dpi
</br>It's a primitive way.
</br>It's a method of creating a separate layout for each screen size
- Third, Set the value value for each dpi
</br>Create dimens files by resolution, give them a margin value that fits the resolution, and then use the margin value that fits the user's smartphone resolution.
