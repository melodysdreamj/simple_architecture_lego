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


### Backend Legos

| Package                    | Type      | Platform                         | Version                                                                                           |
|----------------------------|-----------|----------------------------------|---------------------------------------------------------------------------------------------------|
| sa_data_class_lego            | dataclass | all                              | [![pub package](https://img.shields.io/pub/v/sa_data_class_lego.svg)](https://pub.dartlang.org/packages/sa_data_class_lego) |
| sa_enum_lego                  | dataclass | all                              | [![pub package](https://img.shields.io/pub/v/sa_enum_lego.svg)](https://pub.dartlang.org/packages/sa_enum_lego) |
| sa_sqflite_lego               | database  | mobile,desktop                   | [![pub package](https://img.shields.io/pub/v/sa_sqflite_lego.svg)](https://pub.dartlang.org/packages/sa_sqflite_lego) |
| sa_orange_lego                | database  | all                              | [![pub package](https://img.shields.io/pub/v/sa_orange_lego.svg)](https://pub.dartlang.org/packages/sa_orange_lego) |
| sa_shared_preference_lego      | database  | mobile,desktop,web | [![pub package](https://img.shields.io/pub/v/sa_shared_preference_lego.svg)](https://pub.dartlang.org/packages/sa_shared_preference_lego) |
| sa_flutter_secure_storage_lego | database  | mobile,desktop,web | [![pub package](https://img.shields.io/pub/v/sa_flutter_secure_storage_lego.svg)](https://pub.dartlang.org/packages/sa_flutter_secure_storage_lego) |
| sa_app_storage_lego   | storage   | mobile,desktop,web | [![pub package](https://img.shields.io/pub/v/sa_app_storage_lego.svg)](https://pub.dartlang.org/packages/sa_app_storage_lego) |


### Frontend Listener Legos
| Package                    | Type      | Platform | Version                                                                                           |
|----------------------------|-----------|----------|---------------------------------------------------------------------------------------------------|
| sa_listener_lego               | template  | all                              | [![pub package](https://img.shields.io/pub/v/sa_listener_lego.svg)](https://pub.dartlang.org/packages/sa_listener_lego) |
| sa_fgbg_listener_lego          | listener  | mobile   | [![pub package](https://img.shields.io/pub/v/sa_fgbg_listener_lego.svg)](https://pub.dartlang.org/packages/sa_fgbg_listener_lego) |
| sa_battery_plus_listener_lego  | listener  | mobile   | [![pub package](https://img.shields.io/pub/v/sa_battery_plus_listener_lego.svg)](https://pub.dartlang.org/packages/sa_battery_plus_listener_lego) |
| sa_app_links_listener_lego     | listener  | mobile   | [![pub package](https://img.shields.io/pub/v/sa_app_links_listener_lego.svg)](https://pub.dartlang.org/packages/sa_app_links_listener_lego) |












