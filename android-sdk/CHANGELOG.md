---
layout: default
title: Changelog
parent: Android SDK
nav_order: 99
---

# 4.2.4 (2023-08-10)

### Fixes

* Fixed bug in com.expofp.crowdconnected package.

# 4.2.3 (2023-08-03)

### Improvements

* Added the ability to specify the path to the archive with the offline version of the plan to the init() method. This archive will be       loaded in case of poor or no internet connection.

### Fixes

* Fixed a potential vulnerability in the Helper.unzip() method.

# 4.2.1 (2023-07-21)

### Improvements

* Added the ability to focus on the current location when opening the map.

# 4.2.0 (2023-07-18)

### Improvements

* Integration with Festivals has been added.

# 4.1.6 (2023-07-08)

* fix: Fixed a bug that occurred when switching floors.

# 4.1.3 (2023-06-26)

### BREAKING CHANGES

* Added 'onFpConfigureError' event.
* Added 'FplanView.openZip' method.
* Added 'FplanView.openZipFromAssets' method.

# 4.0.5 (2023-06-20)

### Improvements

* Package com.expofp.indooratlas: in IndoorAtlasProvider provider added the ability to transfer the floor number along with the coordinates.

# 4.0.2 (2023-05-15)

* Fix: URL handler, for addresses with an unspecified 'https://' scheme.

# 4.0.1 (2023-05-11)

### BREAKING CHANGES

* Added onExhibitorCustomButtonClick event.
* Added onDetails event.
* An 'id' parameter has been added to the onBoothClick event.

# 3.0.6 (2023-01-27)

### BREAKING CHANGES

* Updated CrowdConnected location provider package to version 1.3.4
* Changed target version of Android SDK to 33

### Improvements

* Improved process of caching files required for offline mode

# 3.0.3 (2022-10-18)

### Features

* Added IndoorAtlas location provider.
* Added ExpoFpGpsProvider location provider.

# 2.2.1 (2022-08-02)

### Features

* Added the ability to use the Location Provider to display the Blue-Dot
* Added CrowdConnected location provider
* Added 'FplanView.selectExhibitor' method.
* Added 'onMessageReceived' event.

### BREAKING CHANGES

* FplanView settings have been moved to the 'Settings' class.
* The 'FplanView.buildRoute' method has been renamed to 'FplanView.selectRoute': FplanView.buildRoute -> FplanView.selectRoute
* The 'FplanView.setCurrentPosition' method has been renamed to 'FplanView.selectCurrentPosition': FplanView.setCurrentPosition -> FplanView.selectCurrentPosition
* The 'onBoothSelected' event has been renamed to 'onBoothClick': onBoothSelected -> onBoothClick
* The 'onRouteCreated' event has been renamed to 'onDirection': onRouteCreated -> onDirection

# 1.1.10 (2022-05-31)

### Features

* FplanView component created.
* Added the ability to work FplanView in offline mode.
* Added 'FplanView.selectBooth' method.
* Added 'FplanView.buildRoute' method.
* Added 'FplanView.setCurrentPosition' method.
* Added 'FplanView.clear' method.
* Added 'onFpConfigured' event.
* Added 'onBoothSelected' event.
* Added 'onRouteCreated' event.
