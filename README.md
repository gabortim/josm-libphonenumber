# JOSM libphonenumber plugin

This repository contains the building scripts for repackaging [Google libphonenumber](https://github.com/google/libphonenumber) components for [JOSM](https://josm.openstreetmap.de/).

It provides `libphonenumber` and `geocoder` as a JOSM plugin, intended to be used as a dependency for other JOSM plugins.

Currently compiled with Java 21 in Java 17 binary compatibility mode.

### I found a bug!

1. Check if reproducible on the [online demo](https://libphonenumber.appspot.com/).
   1. If yes, please report it to the libphonenumber authors.
      See the [official guide](https://github.com/google/libphonenumber#quick-links) for more.
2. If the demo doesn't reproduce, please report the findings on the [JOSM bugtracker](https://josm.openstreetmap.de/newticket) or
   on the [GitHub issue tracker](https://github.com/gabortim/josm-phonenumber/issues).

### Repository setup

Three git branches are used:
- `master` or `main` as the primary branch
- `dependabot/**` for automatic dependency updates by Dependabot
- `dev` for development (created if there is a need)

Plugin releases have git tags which align with libphonenumber releases.