Language: [English](README.md) | [中文简体](README-ZH.md)

# QR Code Scanner
  
[![License][license-image]][license-url] 
[![Pub](https://img.shields.io/pub/v/qrscan.svg?style=flat-square)](https://pub.dartlang.org/packages/qrscan)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/2564729935f441b4987fd4f49ac988d8)](https://www.codacy.com/app/leyan95/qrcode_scanner?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=leyan95/qrcode_scanner&amp;utm_campaign=Badge_Grade)

A Flutter plugin 🛠 to scanning. Ready for Android 🚀

[github](https://github.com/leyan95/qrcode_scanner)

![qrscan.gif](./example/android/app/src/main/res/drawable/qr_scan.gif)

#### permission：
`<uses-permission android:name="android.permission.CAMERA" />`
`<uses-permission android:name="android.permission.VIBRATE"/>`

## Installation

Add this to your package's pubspec.yaml file:

```yaml
dependencies:
 qrscan: ^0.2.0
```

## Usage example
```dart
import 'package:qrscan/qrscan.dart' as scanner;

String barcode = await scanner.scan();
```

## Contribute

We would ❤️ to see your contribution!

## License

Distributed under the MIT license. See ``LICENSE`` for more information.

## About

Created by Shusheng.

[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-url]: LICENSE
