The repository contains only building scripts for repackaging
the libphonenumber components for [JOSM](https://josm.openstreetmap.de/).

Currently compiled with Java 11 in Java 8 binary compatibility mode. 

### I found a bug!
1. Check if reproducible on the [online demo](http://libphonenumber.appspot.com/).
   1. If yes, please report it to the libphonenumber authors.
      See the [official guide](https://github.com/google/libphonenumber#quick-links) for more.
2. If the demo doesn't reproduce, please report the findings on JOSM bugtracker or
   on https://github.com/gabortim/josm-phonenumber.

### Repository setup

Three git branches used:
- `master` or `main` as a primary branch
- `dependabot/**` for automatic dependency updates by Dependabot
- `dev` for development (created if there is a need)

Plugin releases have git tags which align with libphonenumber releases.