[![lego project](https://img.shields.io/badge/powered%20by-lego-blue?logo=github)](https://github.com/melodysdreamj/lego)

# simple_architecture_lego
simple architecture under lego framework.

![](https://github.com/melodysdreamj/simple_architecture_lego/assets/21379657/03667106-144f-4720-966c-838f4323e0b6)

## Structure
```bash
.
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

| Package                    | Type    | Platform                        | Version                                                                                           |
|----------------------------|---------|---------------------------------|---------------------------------------------------------------------------------------------------|
| sa_data_class_lego            | backend | all                             | [![pub package](https://img.shields.io/pub/v/sa_data_class_lego.svg)](https://pub.dartlang.org/packages/sa_data_class_lego) |
| sa_enum_lego                  | backend | all                             | [![pub package](https://img.shields.io/pub/v/sa_enum_lego.svg)](https://pub.dartlang.org/packages/sa_enum_lego) |
| sa_sqflite_lego               | backend | android,ios,macos,windows,linux | [![pub package](https://img.shields.io/pub/v/sa_sqflite_lego.svg)](https://pub.dartlang.org/packages/sa_sqflite_lego) |





















