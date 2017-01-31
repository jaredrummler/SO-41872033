# SO-41872033
http://stackoverflow.com/questions/41872033/how-to-change-theme-from-another-app-resource-in-android

This project shows that is is indeed possible to use a theme from another package installed on the device. First, install the "theme_module" and then install the "app" module. You will see that the theme is now dark and has a pink ActionBar. Although this is possible it is not recommended and should never be used in production. 

The app resources should also contain all the same strings, drawables and other resources or the app could crash from a ResourcesNotFoundException.
