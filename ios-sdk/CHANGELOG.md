---
layout: default
title: Changelog
parent: iOS SDK
nav_order: 199
---

# 4.0.2 (2023-05-09)

* BREAKING CHANGE: To use the UIKit framework, the UIFplanView component was made. For SwiftUI it is better to use FplanView.
* BREAKING CHANGE: The buildRoute method has been renamed to selectRoute.
* BREAKING CHANGE: An 'id' parameter has been added to the onBoothClick event.
* BREAKING CHANGE: Added onDetails event.
* BREAKING CHANGE: Added onExhibitorCustomButtonClick event.

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
