## yotta: Build Software with Reusable Components
[![Build Status](https://travis-ci.org/ARMmbed/yotta.svg)](https://travis-ci.org/ARMmbed/yotta)
[![Build Status](https://circleci.com/gh/ARMmbed/yotta.svg?style=shield)](https://circleci.com/gh/ARMmbed/yotta)

yotta is a tool from [ARM mbed](https://mbed.org), to make it easier to build
better software with C++ and C by re-using modules. Publish your own modules to
the [yotta registry](http://yottabuild.org/) to share them with other people,
or re-use them privately in your own projects.

Whenever you build a project with yotta, you first select a [yotta
target](http://docs.yottabuild.org/tutorial/targets.html). Targets describe the
platform that you're building for (such as an [embedded IoT development
board](http://yottabuild.org/#/target/frdm-k64f-gcc), or natively for
[Mac](http://yottabuild.org/#/target/x86-osx-native) or
[Linux](http://yottabuild.org/#/target/x86-linux-native)), and provide all the
information that yotta and modules you're using need to configure themselves
correctly for that platform.

### Installation
yotta is written in
[python](https://www.python.org/downloads/release/python-279/), and is
installed using [pip](https://pip.pypa.io/en/stable/installing/).
Install yotta itself by running:

```bash
pip install yotta
```

## yotta install procedure broken with pip v10
https://github.com/carlosperate/microbit-dev-env/issues/5

Please you can use this workaround below (by [carlosperate](https://github.com/carlosperate) committed) and executing install_yotta.sh
https://github.com/carlosperate/microbit-dev-env/commit/5e23b5ed5486a0da44224b49b998df7b0918d950

