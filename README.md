# video_player_360

A Flutter plugin to stream 360° videos on iOS and Android

## Getting Started

This is a Flutter plugin to play 360° videos via a remote URL. 

The iOS player uses the open source [HTY360Player by Hanton for iOS](https://github.com/hanton/HTY360Player)

The Android player uses the open source [Google VR SDK for Android](https://github.com/googlevr/gvr-android-sdk)

## Installation
This plugin has not been deployed to pub.dev; you can only add it directly with the git url in your pubspec.yaml dependencies.
``` dart
video_player_360:
    git:
      url: https://github.com/stephangopaul/video_player_360_htyplayer.git
```

## How to use #
importing the library:
``` dart
import 'package:video_player_360/video_player_360.dart';
```
play video:
``` dart
await VideoPlayer360.playVideoURL("ENTER_360_VIDEO_URL_HERE");
```