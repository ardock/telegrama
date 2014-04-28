TelegramA: Telegram A Edition
========

My experimental version of Telegram based on open-source created by Stepan Korshakov

[Telegram S Edition Android App](https://github.com/ex3ndr/telegram)
[telegram-api](https://github.com/ex3ndr/telegram-api)
[mtproto](https://github.com/ex3ndr/telegram-mt)
[tl-core](https://github.com/ex3ndr/telegram-tl-core)

More information
----------------
####Telegram project

http://telegram.org/

#### Telegram api documentation

English: http://core.telegram.org/api

Russian: http://dev.stel.com/api

#### MTProto documentation

English: http://core.telegram.org/mtproto

Russian: http://dev.stel.com/mtproto

#### Type Language documentation

English: http://core.telegram.org/mtproto/TL

Russian: http://dev.stel.com/mtproto/TL

#### Telegram S Edition

[![Telegram S](https://developer.android.com/images/brand/en_generic_rgb_wo_45.png)](https://play.google.com/store/apps/details?id=org.telegram.android "Telegram S")

Building project
------------

#### Build variants
There are multiple configurations of building app, some of them:

1. ````gradle assembleDevDebug```` - Development build for IDE, recomended for daily usage
2. ````gradle assembleCommonRelease```` - Release version for Google Play. Release versions need additional configuration for signing keys.
3. ````gradle assembleCommonDebuggable```` - Release version with debugging enabled for testing
4. ````gradle assembleBetaRelease```` - Builds [beta-version](https://play.google.com/store/apps/details?id=org.telegram.android.beta) of an app. Includes russian translations.
5. ````gradle assembleMdpiRelease```` - Release version for MDPI devices
6. ````gradle assembleHdpiRelease```` - Release version for HDPI devices
7. ````gradle assembleXhdpiRelease```` - Release version for XHDPI devices
8. ````gradle assembleXxhdpiRelease```` - Release version for XXHDPI devices
9. ````gradle dist```` - Building release distributive

#### Build from Sources
1. Checkout sources with all submodules
2. Select required build configuration and run required ````gradle```` command

#### Using from IDE

This sources are prepared for Android Studio.

License
----------------
Telegram A Edition uses [Apache v2 License](LICENSE) based on libraries that use [MIT Licence](LICENCE)
