# qconread2

qconread2 is a GUI frontend for reading log files generated by [taslogger](https://github.com/HLTAS/taslogger). This application uses the Qt toolkit to build its user interface.

## Building

1. Install [Qt5](http://www.qt.io) and [RapidJSON](https://github.com/miloyip/rapidjson/).
2. Run `git submodule update --init`.
3. Create a `build` directory alongside the `src` directory.
4. Change into the `build` directory.
5. Run `cmake -DRapidJSON_ROOT=/path/to/rapidjson/base/dir ..`
6. Run `make -j` or build the generated Visual Studio solution.
