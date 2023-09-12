---
layout: default
title: Changelog
parent: iOS SDK
nav_order: 199
---

# 4.2.7 (2023-09-12)

### Fixes

* Fixed bug in ExpoFpCrowdConnected package.

# 4.2.6 (2023-09-06)

### Improvements

* The package from CrowdConnected has been updated to version 1.6.0.

# 4.2.5 (2023-08-10)

### Fixes

* Fixed bug in ExpoFpCrowdConnected package.

# 4.2.4 (2023-08-06)

### Improvements

* Added the ability to specify the path to the archive with the offline version of the plan to the load() method. This archive will be       loaded in case of poor or no internet connection.

# 4.2.1 (2023-07-21)

### Improvements

* Added the ability to focus on the current location when opening the map.

# 4.2.0 (2023-07-18)

### Improvements

* Integration with Festivals has been added.

# 4.1.5 (2023-07-08)

* fix: Fixed a bug that occurred when switching floors.

# 4.1.1 (2023-06-27)

### BREAKING CHANGES

* Added 'setOnFpErrorCallback' method in UIFplanView.
* Added 'onFpError' extension in FplanView.
* Added 'openZip' method.

# 4.0.7 (2023-06-22)

### Improvements

* Package ExpoFpIndoorAtlas: in IndoorAtlasProvider provider added the ability to transfer the floor number along with the coordinates.

# 4.0.2 (2023-05-09)

### BREAKING CHANGES

* To use the UIKit framework, the UIFplanView component was made. For SwiftUI it is better to use FplanView.
* The buildRoute method has been renamed to selectRoute.
* An 'id' parameter has been added to the onBoothClick event.
* Added onDetails event.
* Added onExhibitorCustomButtonClick event.

# 3.0.8 (2023-02-08)

### Improvements

* Optimized file caching process.

# 3.0.5 (2022-10-20)

### Features

* Added ExpoFpGpsProvider location provider

# 3.0.1 (2022-10-20)

### Features

* Added the ability to use the Location Provider to display the Blue-Dot
* Added CrowdConnected location provider
* Added IndoorAtlas location provider

# 0.2.2-beta (2022-08-03)

### Features

* FplanView component created.
* Added the ability to work FplanView in offline mode.
* Added 'FplanView.load' method.
* Added 'FplanView.destoy' method.
* Added 'FplanView.selectBooth' method.
* Added 'FplanView.buildRoute' method.
* Added 'FplanView.setCurrentPosition' method.
* Added 'FplanView.clear' method.
* Added 'onFpReady' event.
* Added 'onBoothClick' event.
* Added 'onBuildDirection' event.
