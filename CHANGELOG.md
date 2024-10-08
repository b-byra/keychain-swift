# KeychainSwift version history

## 22.0.0 (2024-05-05)

Added privacy manifest as a resource to CocoaPods Podspec file (https://github.com/evgenyneu/keychain-swift/pull/188).

## 21.0.0 (2024-01-20)

Added privacy manifest (Sources/PrivacyInfo.xcprivacy).

## 20.0.0 (2021-01-04)

Update to Xcode 13.

## 19.0.0 (2020-01-04)

Added `allKeys` property that returns all key names ([lucasmpaim](https://github.com/lucasmpaim)).


## 18.0.0 (2019-11-03)

Removed deprecated `kSecAttrAccessibleAlways` and `kSecAttrAccessibleAlwaysThisDeviceOnly` access options (https://github.com/evgenyneu/keychain-swift/pull/122).


## 17.0.0 (2019-10-02)

Added ability to run unit test from Swift Package Manager (https://github.com/evgenyneu/keychain-swift/pull/113).


## 16.0.0 (2019-05-28)

Made all methods (get, set, delete and clear) thread-safe to prevent crashing when called from different threads.


## 15.0.0 (2019-04-24)

Added ability to return data as reference ([mediym41](https://github.com/mediym41)).


## 14.0.0 (2019-04-03)

Update to Swift 5.0 ([schayes04](https://github.com/schayes04)).


## 13.0.0 (2018-10-23)

Increased watchOS deployment target to 3.0 ([xuaninbox](https://github.com/xuaninbox)).


## 12.0.0 (2018-09-19)

Update to Swift 4.2 ([beny](https://github.com/beny)).


## 11.0.0 (2018-03-31)

Added Swift language version to the podspec file for CocoaPods.


## 10.0.0 (2017-10-30)

Fixed a crash in `getData` when called simultaneously from different threads ([details](https://github.com/evgenyneu/keychain-swift/pull/68)).


## 9.0.0 (2017-09-23)

Update to Swift 4.0.

## 8.0.3 (2017-04-08)

Fixed Package Manager setup ([maxkramerbcgdv](https://github.com/maxkramerbcgdv)).

## 8.0.0 (2017-04-08)

Added Swif 3.1 support ([CraigSiemens](https://github.com/CraigSiemens)).


## 7.0.0 (2016-10-08)

Swift package manager support ([diogoguimaraes](https://github.com/diogoguimaraes)).


## 6.0.2 (2016-09-11)

Change the `public` access modifier to `open` to allow subclassing of the `KeychainSwift` class and overriding its methods ([djensenius](https://github.com/djensenius)).


## 6.0.0 (2016-08-20)

Update to Xcode 8 beta 6 (thanks, [Tulleb](https://github.com/Tulleb)).


## 5.0.0 (2016-08-13)

Update to Xcode 8 beta 4/5.


## 3.0.15 (2016-05-19)

Added the ability to sychronize items on multiple devices (thank you, [mikaoj](https://github.com/mikaoj)).


## 3.0.13 (2016-04-15)

Added iOS 7 support (https://github.com/marketplacer/keychain-swift/blob/iOS7/Distrib/KeychainSwiftDistrib.swift)


## 3.0.11 (2016-01-24)

Added methods for setting/getting booleans.


## 3.0.9 (2015-11-09)

Moved repository to https://github.com/marketplacer/keychain-swift


## 3.0.8 (2015-11-02)

Added `lastResultCode` property.
