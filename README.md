# biometrics_authentication

A new Flutter project.

## Getting Started

### Add package

```dart
  flutter pub add local_auth
```
- design login page
- create service class
- design private screen


# for ios:

```dart
    <key>NSFaceIDUsageDescription</key>
    <string>App needs to authenticate using faces.</string>
```
# for Android:

- change MainActivity

```dart
package com.example.biometrics_authentication

import io.flutter.embedding.android.FlutterFragmentActivity

class MainActivity: FlutterFragmentActivity() {
}

```