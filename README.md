# flutter_piano

A Crossplatform Midi Piano built with Flutter.dev

* This application runs on both iOS and Android. 
* This runs a custom crossplatform midi synth I built for a Flutter plugin `flutter_midi` that uses .SF2 sound font files. 

The Pocket Piano by Rody Davis
[App Store](https://itunes.apple.com/us/app/the-pocket-piano/id1453992672?mt=8)
 | [Google Play](https://play.google.com/store/apps/details?id=com.appleeducate.flutter_piano)

```
 assets:
   - assets/sounds/Piano.SF2

```
* There are Semantics included for the visually impaired. All keys show up as buttons and have the pitch name of the midi note not just the number.

## Getting Started

This application only runs in landscape mode, orientation is set in the AndroidManifest.xml and in the Runner.xcworspace settings.

1. Make sure to turn your volume up and unmute the phone (the application will try to unmute the device but it can be overriden).
2. Tap on any note to play
3. Scroll in either direction to change octaves
4. Polyphony is supported with multiple fingers

## Configuration

* Optionally the key width can be changed in the settings for adjusting key densitity.

* The key labels can also be turned off if you want a more minimal look.
### IOS

![alt-text-1](https://github.com/AppleEducate/flutter_piano/blob/master/screenshots/ios_2.PNG)

### Android

![alt-text-2](https://github.com/AppleEducate/flutter_piano/blob/master/screenshots/android_1.jpg)

* You can change the Piano.sf2 file to any sound font file for playing different instruments. 

## Screenshots

### iOS

![alt-text-1](https://github.com/AppleEducate/flutter_piano/blob/master/screenshots/ios_1.PNG)
![alt-text-1](https://github.com/AppleEducate/flutter_piano/blob/master/screenshots/ios_3.PNG)

### Android

![alt-text-2](https://github.com/AppleEducate/flutter_piano/blob/master/screenshots/android_3.jpg)
![alt-text-2](https://github.com/AppleEducate/flutter_piano/blob/master/screenshots/android_2.jpg)

