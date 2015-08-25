# Yeoman Generator for BB10 Cordova Headless apps

This is a Yeoman generator that will create the basic scaffolding for a BB10 Cordova app, including a native Headless component. The generator will create a native C++ project in the HeadlessService folder. The app will be initialized with the necessary pieces to launch the HeadlessService in config.xml.

### Yeoman and Generator Installation

Install Yeoman globally from NPM:

```
	npm install -g yo
```

Install the generator globally as well

```
	npm install -g generator-bb10-headless
```

### Running the Generator

Run the generator like so, in the directory where you want to generate the new app:

```
	yo bb10-headless
```

The BlackBerry10 platform and Invoke plugin will be added and the project prepared for building.

### Next Steps

Finally, run the sample so it builds to your device:

```
	cordova run
```

Checkout the [documentation](http://developer.blackberry.com/html5/documentation/v2_2/creating_a_ww_app_with_headless_app.html) on headless apps, though you can ignore the section on how to create them.

