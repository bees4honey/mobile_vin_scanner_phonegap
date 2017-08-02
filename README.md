# Phonegap plugin for mobile VIN Scanner 

This repo contains Phonegap plugin only. If you need VIN Scanner SDK for native development, use https://github.com/bees4honey/mobile_vin_scanner instead.

This is repo for Mobile VIN Scanner SDK created and maintained by bees4honey.

**WARNING:** since VIN Scanner plugin heavily uses native code for both iOS and Android platforms, the Adobe Phonegap Build cloud service is not supported. To use our plugin you need to build project using Phonegap command line tools.

## Supported platforms

**iOS:** iOS versions starting with 7.0 are supported.

**Android:** only Android versions 4.0 and higher are supported. Please make your project min SDK version equal to 14 (Android 4.0) to get scanner working.

## Phonegap plugin installation

Installation instructions:
1. Generate your project using "phonegap create" command
2. Add a plugin to your project using the following command:

```
phonegap plugin add https://github.com/bees4honey/mobile_vin_scanner_phonegap
```

You can find usage example in index.html file.

## Licensing

You are free to download any of our projects and use it in development purpose inside your app. 

You are not allowed to comercialize (that is, sell, rent, trade or lease) Mobile VIN Scanner SDK, 
modify, recompile, reverse engineer or otherwise alter the Mobile VIN Scanner SDK. Please read more about licensing in license_agreement.txt

Without License Key SDK will work in demo mode and amount of scans will be limited per install. 

**Please contact us at vin@bees4honey.com for purchasing details.**

Thanks!