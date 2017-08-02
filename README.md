# Phonegap plugin 

VIN Scanner Phonegap plugin for Android and iOS platforms.

This repository contains Phonegap plugin. If you need VIN Scanner SDK for native development, use https://github.com/bees4honey/mobile_vin_scanner

**WARNING:** since VIN Scanner plugin heavily uses native code for both iOS and Android platforms, the Adobe Phonegap Build cloud service is not supported. To use our plugin you need to build project using Phonegap command line tools.

## Supported platforms

**iOS:** iOS versions starting with 8.0 are supported.

**Android:** only Android versions 4.0 and higher are supported. Please make your project min SDK version equal to 14 (Android 4.0) to get scanner working.

## Phonegap plugin installation

Phonegap VIN scanner plugin for iOS and Android platforms.

Installation instructions:
1. Generate your project using "phonegap create" command
2. Add a plugin to your project using the following command:

```
phonegap plugin add https://github.com/bees4honey/mobile_vin_scanner_phonegap
```

You can find usage example in index.html file.