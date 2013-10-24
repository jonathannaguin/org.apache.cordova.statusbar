StatusBar
======

> The `StatusBar` object provides some functions to customize the iOS StatusBar.

Methods
-------

- StatusBar.styleDefault
- StatusBar.styleLightContent
- StatusBar.styleBlackTranslucent
- StatusBar.styleBlackOpaque
- StatusBar.hide
- StatusBar.show

Properties
--------

- StatusBar.isVisible

Permissions
-----------

#### config.xml

            <feature name="StatusBar">
                <param name="ios-package" value="CDVStatusBar" onload="true" />
            </feature>

Description
-----------

On iOS 7, set to false to make the statusbar appear like iOS 6. Set the style and background color to suit using the other functions.


Supported Platforms
-------------------

- iOS

StatusBar.styleDefault
=================

Use the default statusbar (dark text, for light backgrounds).

    StatusBar.styleDefault();


Supported Platforms
-------------------

- iOS

StatusBar.styleLightContent
=================

Use the lightContent statusbar (light text, for dark backgrounds).

    StatusBar.styleLightContent();


Supported Platforms
-------------------

- iOS

StatusBar.styleBlackTranslucent
=================

Use the blackTranslucent statusbar (light text, for dark backgrounds).

    StatusBar.styleBlackTranslucent();


Supported Platforms
-------------------

- iOS

StatusBar.styleBlackOpaque
=================

Use the blackOpaque statusbar (light text, for dark backgrounds).

    StatusBar.styleBlackOpaque();


Supported Platforms
-------------------

- iOS


StatusBar.hide
=================

Hide the statusbar.

    StatusBar.hide();


Supported Platforms
-------------------

- iOS

StatusBar.show
=================

Shows the statusbar.

    StatusBar.show();


Supported Platforms
-------------------

- iOS


StatusBar.isVisible
=================

Read this property to see if the statusbar is visible or not.

    if (StatusBar.isVisible) {
    	// do something
    }


Supported Platforms
-------------------

- iOS



    