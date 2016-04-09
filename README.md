# ug4-packages
This repository supplies [ughub](https://github.com/UG4/ughub)
with information on dependencies between public [UG4](https://github.com/UG4) packages.

## Adding a package
To add a package, e.g. residing on Github, provide the URL and an *unique* name to identify your package. If you need
to add a plugin as well as an app package, a recommendation would be to add a *_app* suffix to your app package's name.
That is consider adding a plugin *MyPlugin* and you have to add also an application for *MyPlugin*, then add *MyPlugin* and
*MyPlugin_app* to avoid name clashes and get both packages added.
