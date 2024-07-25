[![lego project](https://img.shields.io/badge/powered%20by-lego-blue?logo=github)](https://github.com/melodysdreamj/lego)

# simple_architecture_lego
simple architecture under lego framework.

![](https://github.com/melodysdreamj/simple_architecture_lego/assets/21379657/03667106-144f-4720-966c-838f4323e0b6)

## Structure
```bash
app
├── backend
│   ├── app_storage
│   ├── deeplink
│   ├── fcm
│   ├── firestore
│   ├── sqflite
│   ├── notification
│   └── ...
├── frontend
│   ├── listener
│   │   ├── battery
│   │   ├── connectivity
│   │   ├── location
│   │   └── ...
│   ├── view
│   │   ├── page
│   │   ├── component
│   │   ├── bottom_sheet
│   │   └── ...
│   └── view_model
└── usecase
    └── ...
```


## Getting Started
1. open terminal in the lego project root directory, enter the following command for install cli. and create a new lego project if you don't have one.
```bash
flutter pub global activate lego_cli
lego create
```

2. add below lego module to your project's `pubspec.yaml` file.


### Legos

| Package                    | Type             | Platform          | Version                                                                                           |
|----------------------------|------------------|-------------------|---------------------------------------------------------------------------------------------------|
| sa_data_class_lego            | backend          | all               | [![pub package](https://img.shields.io/pub/v/sa_data_class_lego.svg)](https://pub.dartlang.org/packages/sa_data_class_lego) |
| sa_enum_lego                  | backend          | all               | [![pub package](https://img.shields.io/pub/v/sa_enum_lego.svg)](https://pub.dartlang.org/packages/sa_enum_lego) |
| sa_sqflite_lego               | backend          | mobile,desktop    | [![pub package](https://img.shields.io/pub/v/sa_sqflite_lego.svg)](https://pub.dartlang.org/packages/sa_sqflite_lego) |
| sa_firestore_lego             | backend          | mobile,desktop    | [![pub package](https://img.shields.io/pub/v/sa_firestore_lego.svg)](https://pub.dartlang.org/packages/sa_firestore_lego) |
| sa_orange_lego                | backend          | all               | [![pub package](https://img.shields.io/pub/v/sa_orange_lego.svg)](https://pub.dartlang.org/packages/sa_orange_lego) |
| sa_shared_preference_lego      | backend          | mobile,desktop,web | [![pub package](https://img.shields.io/pub/v/sa_shared_preference_lego.svg)](https://pub.dartlang.org/packages/sa_shared_preference_lego) |
| sa_flutter_secure_storage_lego | backend          | mobile,desktop,web | [![pub package](https://img.shields.io/pub/v/sa_flutter_secure_storage_lego.svg)](https://pub.dartlang.org/packages/sa_flutter_secure_storage_lego) |
| package_info_plus_lego        | backend          | mobile,desktop,web | [![pub package](https://img.shields.io/pub/v/package_info_plus_lego.svg)](https://pub.dartlang.org/packages/package_info_plus_lego) |
| sa_app_storage_lego   | backend          | mobile,desktop,web | [![pub package](https://img.shields.io/pub/v/sa_app_storage_lego.svg)](https://pub.dartlang.org/packages/sa_app_storage_lego) |
| sa_firebase_storage_lego | backend          | mobile,desktop,web | [![pub package](https://img.shields.io/pub/v/sa_firebase_storage_lego.svg)](https://pub.dartlang.org/packages/sa_firebase_storage_lego) |
| sa_google_mlkit_translate_lego | backend          | mobile | [![pub package](https://img.shields.io/pub/v/sa_google_mlkit_translate_lego.svg)](https://pub.dartlang.org/packages/sa_google_mlkit_translate_lego) |
| sa_deeplink_lego      | backend,frontend | mobile,desktop    | [![pub package](https://img.shields.io/pub/v/sa_deeplink_lego.svg)](https://pub.dartlang.org/packages/sa_deeplink_lego) |
| sa_firebase_auth_lego | backend          | mobile,desktop    | [![pub package](https://img.shields.io/pub/v/sa_firebase_auth_lego.svg)](https://pub.dartlang.org/packages/sa_firebase_auth_lego) |
| sa_firebase_messaging_lego | backend          | mobile,desktop    | [![pub package](https://img.shields.io/pub/v/sa_firebase_messaging_lego.svg)](https://pub.dartlang.org/packages/sa_firebase_messaging_lego) |
| sa_lego_cloud_functions_lego | backend          | mobile,desktop    | [![pub package](https://img.shields.io/pub/v/sa_lego_cloud_functions_lego.svg)](https://pub.dartlang.org/packages/sa_lego_cloud_functions_lego) |
| sa_listener_lego               | frontend  | all               | [![pub package](https://img.shields.io/pub/v/sa_listener_lego.svg)](https://pub.dartlang.org/packages/sa_listener_lego) |
| sa_fgbg_listener_lego          | frontend  | mobile            | [![pub package](https://img.shields.io/pub/v/sa_fgbg_listener_lego.svg)](https://pub.dartlang.org/packages/sa_fgbg_listener_lego) |
| sa_battery_plus_listener_lego  | frontend  | all            | [![pub package](https://img.shields.io/pub/v/sa_battery_plus_listener_lego.svg)](https://pub.dartlang.org/packages/sa_battery_plus_listener_lego) |
| sa_app_links_listener_lego     | frontend  | all            | [![pub package](https://img.shields.io/pub/v/sa_app_links_listener_lego.svg)](https://pub.dartlang.org/packages/sa_app_links_listener_lego) |
| june_lego | frontend  | all               | [![pub package](https://img.shields.io/pub/v/june_lego.svg)](https://pub.dartlang.org/packages/june_lego) |















