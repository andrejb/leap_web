Customization
==============================

Customization directory
---------------------------------------

See config/customization/README.md

Engines
---------------------

Leap Web is based on Engines. All things in `app` will overwrite the default behaviour. You can either create a new rails app and include the leap_web gem or clone the leap web repository and add your customizations to the `app` directory.

If you have no use for one of the engines you can remove it from the Gemfile. Not however that your app might still need to provide some functionality for the other engines to work. For example the users engine provides `current_user` and other methods.
