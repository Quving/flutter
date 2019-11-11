[![Build Status](https://drone.quving.com/api/badges/Quving/flutter/status.svg)](https://drone.quving.com/Quving/flutter)

# Flutter Docker-Images

Provides base images of Flutter.

# Description
| Docker-Image                         | Description                                                                                                                                   | Approximate Size |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|------------------|
| ```pingu/flutter:base-latest```            | Installs basic flutter accordingly to the official [google-flutter-doc](https://flutter.dev/docs/get-started/install/linux).                  | 1.14G            |
| ```pingu/flutter:base-<FLUTTER_VERSION>``` | -                                                                                                                                             | -                |
| ```pingu/flutter:web-latest```             | Installs basic flutter + flutter-web extension accordingly to the official [google-flutter-web-doc](https://flutter.dev/docs/get-started/web).| 1.5G             |
| ```pingu/flutter:web-<FLUTTER_VERSION>```  | -                                                                                                                                             | -                |


## Flutter Version
The Flutter Version naming convention is described as follows.

From this tag (2019-11-11):

<img src="https://i.imgur.com/4gRoi8S.png" width=350>

the following tag will be used:

```
v1.9.1+hotfix.6-stable
```
