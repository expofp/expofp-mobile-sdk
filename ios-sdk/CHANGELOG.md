---
layout: default
title: Changelog
parent: iOS SDK
nav_order: 199
---

# 4.5.16 (2024-10-22)

### Features

* ExpoFpFplan package: The ability to specify an array of IDs in the selectExhibitor method has been added.

# 4.5.15 (2024-10-21)

### Fixes

* ExpoFpFplan package: Fix floor index mapping.

# 4.5.9 (2024-10-01)

### Features

* ExpoFpFplan package: The ability to specify GPS coordinates in the selectRoute method has been added.

# 4.5.8 (2024-09-23)

### Features

* ExpoFpFplan package: "onCategoryClick" event was added.

# 4.5.3 (2024-09-03)

### Features

* ExpoFpFplan package: Added the ability to pass a nil value to the 'selectCategory' method.

# 4.5.2 (2024-08-20)

### Features

* ExpoFpFplan package: 'selectCategory()' function was added.
* ExpoFpFplan package: The ability to specify a point(SelectRoutePoint class) as a starting point or destination point in the 'selectRoute()' function has been added.
* ExpoFpFplan package: 'getVisibility()' and 'setVisibility()' functions was added.
* ExpoFpFplan package: 'findLocation()' function was added.
* ExpoFpFplan package: 'zoomIn()' and 'zoomOut()' functions was added.
* ExpoFpFplan package: 'switchView()' function was added.
* ExpoFpFplan package: 'fitBounds()' function was added.

# 4.4.5 (2024-05-23)

### Features

* ExpoFpFplan package: a public constructor has been added to the Bookmark structure.

# 4.4.4 (2024-05-01)

### Features

* Privacy manifest file was updated.

# 4.4.2 (2024-04-18)

### Features

* Privacy manifest file was added.

# 4.4.1 (2024-04-08)

### BREAKING CHANGES

* ExpoFpFplan package: 'onBoothClick' callback - all parameters have been changed to 'floorPlanBoothBase(FloorPlanBoothBase)' parameter.
* ExpoFpFplan package: 'onDirection' callback - 'RouteBooth' parameters was renamed to 'FloorPlanBoothBase'.
* ExpoFpFplan package: 'boothsList' method - 'Booth' parameters was renamed to 'FloorPlanBooth'.

# 4.3.1 (2024-03-07)

### Features

* ExpoFpFplan package: Extend 'onDirection' callback - 'Line', 'Point' parameters was added to 'Route'.
* ExpoFpFplan package: Extend 'onBoothClick' callback - 'externalId(String)' parameter was added.
* ExpoFpFplan package: Extend 'onDetails' callback - 'boothsNames(String[])' parameter was added to 'Details'.
* ExpoFpFplan package: 'onBookmarkClick' callback was added.
* ExpoFpFplan package: 'setBookmarks()' function was added.
* ExpoFpFplan package: 'updateLayerVisibility()' function was added.

# 4.2.20 (2024-02-12)

### Features

* ExpoFpCrowdConnected package: 'enableNavigation' parametr added to Settings.

# 4.2.19 (2024-01-31)

### Features

* Added 'exhibitorsList' method.
* Added 'categoriesList' method.
* Added 'boothsList' method.

# 4.2.18 (2023-12-05)

### Improvements

* The ability to download packages from SPM has been added.

# 4.2.11 (2023-11-26)

### Improvements

* Validation of URLs of plan addresses was added.

# 4.2.10 (2023-10-30)

### Features

* Added 'allowConsent' parameter to the Settings.

### Improvements

* In the CrowdConnected package, calling the startNavigation() function in GPS_ONLY mode when working in the background. This function increases the frequency of coordinates update.

# 4.2.8 (2023-10-02)

### Fixes

* Fixed bug in ExpoFpFplan package.

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
