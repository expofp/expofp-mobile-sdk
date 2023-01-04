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
