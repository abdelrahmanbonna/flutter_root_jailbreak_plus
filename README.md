# flutter_root_jailbreak

This plugin is very easy to get a status to detect whether the Android device is rooted and whether
the iOS device is jailbroken

install:
```dart
dependencies:
  flutter_root_jailbreak: ^2.0.2
```

use:

```dart

//The way to check the root status of an Android device is：
FlutterRootJailbreak.isRooted

// The way to check the jailbreak status for iOS devices is：
FlutterRootJailbreak.isJailBroken

```