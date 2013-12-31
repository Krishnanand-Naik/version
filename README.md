# Version

Command line tool (and Go package) for keeping track of the versions of projects or directories.

## Command line

The `version` command line has the following syntax:

    version path [option]

  * `path` - Path to set the version for.  Use `./` for current directory.
  * `option`
    * none  Read the version
    * `+` Increase the build number (`1.0.0` -> `1.0.1`)
    * `++` Increase the minor number (`1.0.0` -> `1.1.0`)
    * `+++` Increase the major number (`1.0.0` -> `2.0.0`)
