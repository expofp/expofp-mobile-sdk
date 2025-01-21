---
layout: default
title: Changelog
parent: Android SDK
nav_order: 99
---

# 4.9.0 (2025-01-20)

### BREAKING CHANGES

* The com.expofp.crowdconnected package has been split into 2 packages: com.expofp.crowdconnected and com.expofp.crowdconnectedbackground.

# 4.8.1 (2024-12-06)

### Improvements

* Common package: The target Android Api(targetSdk) version has been changed to 34.
* IndoorAtlas package: The target Android Api(targetSdk) version has been changed to 34.

# 4.8.0 (2024-12-06)

### Features

* ExpoFpFplan package: 'onCurrentPositionChanged' callback was added to the 'FplanEventsListener'.
* ExpoFpFplan package: 'highlightExhibitors()' function has been added.
* ExpoFpFplan package: 'downloadZipToCache()' function has been added.
* ExpoFpFplan package: 'openFile()' function has been added.
* ExpoFpFplan package: 'externalId' parameter was added to the 'setBookmarks()' function.
* ExpoFpFplan package: 'externalId' parameter was added to the 'onBookmarkClick' callback.
* CrowdConnected packages have been updated to version 2.0.2.

### BREAKING CHANGES

* Common package: Parameter 'inBackground' was removed from 'LocationProvider.start()' function.
* ExpoFpCrowdConnected package: The 'enableNavigation()' method has been removed from 'Settings' class.
* ExpoFpCrowdConnected package: The 'enableBackgroundMode()' method has been added to 'Settings' class.

# 4.6.3 (2024-10-23)

### Features

* ExpoFpFplan package: The ability to specify an array of IDs in the selectExhibitor method has been added.

# 4.6.2 (2024-10-01)

### Features

* ExpoFpFplan package: The ability to specify GPS coordinates in the selectRoute method has been added.

# 4.6.0 (2024-09-23)

### Features

* ExpoFpFplan package: "onCategoryClick" event has been added.

# 4.5.3 (2024-09-03)

### Features

* ExpoFpFplan package: Added the ability to pass a null value to the 'selectCategory' method.

# 4.5.2 (2024-08-20)

### Features

* ExpoFpFplan package: 'selectCategory()' function was added.
* ExpoFpFplan package: The ability to specify a point(SelectRoutePoint class) as a starting point or destination point in the 'selectRoute()' function has been added.
* ExpoFpFplan package: 'getVisibility()' and 'setVisibility()' functions was added.
* ExpoFpFplan package: 'findLocation()' function was added.
* ExpoFpFplan package: 'zoomIn()' and 'zoomOut()' functions was added.
* ExpoFpFplan package: 'switchView()' function was added.
* ExpoFpFplan package: 'fitBounds()' function was added.

# 4.5.0 (2024-07-01)

### Improvements

* CrowdConnected packages has been updated to version 1.5.2.
* The target Android Api(targetSdk) version has been changed to 34.

# 4.4.3 (2024-05-01)

### Improvements

* CrowdConnected packages has been updated to version 1.5.1.

# 4.4.2 (2024-04-18)

### Improvements

* CrowdConnected packages have been updated to version 1.5.0.

# 4.4.1 (2024-04-08)

### BREAKING CHANGES

* ExpoFpFplan package: 'onDirection' callback - 'RouteBooth' was renamed to 'FloorPlanBoothBase'.
* ExpoFpFplan package: 'onBoothClick' callback - all parameters have been changed to 'FloorPlanBoothBase' parameter.
* ExpoFpFplan package: 'boothsList' method - 'Booth' was renamed to 'FloorPlanBooth'.

# 4.3.1 (2024-03-01)

### Features

* ExpoFpFplan package: Extend 'onDirection' callback - 'RouteLine', 'RoutePoint' parameters was added to 'Route'.
* ExpoFpFplan package: Extend 'onBoothClick' callback - 'externalId(String)' parameter was added.
* ExpoFpFplan package: Extend 'onDetails' callback - 'boothsNames(String[])' parameter was added to 'Details'.
* ExpoFpFplan package: 'onBookmarkClick' callback was added.
* ExpoFpFplan package: 'setBookmarks()' function was added.
* ExpoFpFplan package: 'updateLayerVisibility()' function was added.

### BREAKING CHANGES

* Settings, Configuration, Details, Exhibitor, FloorPlanCustomButtonEvent, Route, RouteBooth, RouteLine, RoutePoint moved to package 'com.expofp.fplan.models'

# 4.2.14 (2024-02-12)

### Features

* ExpoFpCrowdConnected package: 'enableNavigation' parameter added to Settings.

### Fixes

* ExpoFpFplan package: The functionality of checking the Internet connection has been redesigned.

# 4.2.13 (2024-01-31)

### Features

* Added 'exhibitorsList' method.
* Added 'categoriesList' method.
* Added 'boothsList' method.

# 4.2.12 (2023-12-04)

### Improvements

* CrowdConnected packages have been updated to version 1.3.6.

# 4.2.11 (2023-11-11)

### Fixes

* Validation of URL was added.

# 4.2.10 (2023-10-30)

### Features

* Added 'allowConsent' parameter to the Settings.

### Fixes

* Fixed bug in com.expofp.fplan package.

### Improvements

* In the CrowdConnected package, calling the startNavigation() function in GPS_ONLY mode when working in the background. This function increases the frequency of coordinates update.

# 4.2.7 (2023-10-08)

### Improvements

* In this version, the functionality responsible for caching for offline mode has been improved.

# 4.2.5 (2023-08-29)

### Improvements

* In this version, the functionality responsible for caching has been improved.

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
