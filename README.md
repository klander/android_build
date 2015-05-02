# android_build
Android Build System (cyanogenmod)

Build: Add support for specifying build variant in brunch/breakfast
This little modification allows specifying build variant in brunch/
breakfast commands. For example we can use "brunch i9300 user" to build
user variant instead of default userdebug.

When no extra argument is given, userdebug is default.
