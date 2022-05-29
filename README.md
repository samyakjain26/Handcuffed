<img src="/android/app/src/main/res/mipmap-hdpi/ic_launcher.png" align="left"
     alt="Face recognition">
# Face Recognition Flutter

Realtime face recognition flutter app update with latest null safety implementation and the depreceated Firebase ML Vision has been migrated to Google ML Kit.



## Steps

### Face detection

Uses Google ML Kit

### Face Recognition

Convert Tensorflow implementation of [MobileFaceNet](https://github.com/sirius-ai/MobileFaceNet_TF) model into tflite.

## Installing

**Step 1:** Download or clone this repo:

```
git clone https://Sejzz/Handcuffed.git
```

**Step 2:** Go to project root and execute the following command in console to get the required dependencies: 

```
flutter pub get 
```

**Step 3:** Add dynamic libraries for flutter_tflite package to work:

[Follow these instructions](https://pub.dev/packages/tflite_flutter#important-initial-setup)

**Step 4:** Install flutter app

```
flutter run 
```




