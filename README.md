# linux-io

[
![Download](https://api.bintray.com/packages/dvlopt/maven/linux-io/images/download.svg)
](https://bintray.com/dvlopt/maven/linux-io/_latestVersion)

[![Maven
Central](https://maven-badges.herokuapp.com/maven-central/io.dvlopt/linux-io/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.dvlopt/linux-io)

Sometimes, for instance when interacting with hardware, native IO is needed and
Java does not provide much for doing so because the JVM aims to be
platform-independant. This library builds upon
[linux-common](https://github.com/dvlopt/linux-common.java) in order to provide
basic utilities such as opening and R/W a file or performing ioctl calls through
[Java Native Access](https://github.com/java-native-access/jna) on a Linux
system.

## Usage

Simply read the
[javadoc](https://dvlopt.github.io/doc/java/linux-io/io/dvlopt/linux/io/package-summary.html).

Everything is kept close to what LibC offers in order to let users build
higher-level constructs themselves. As such, reading [this
documentation](https://www.gnu.org/software/libc/manual/html_node/Low_002dLevel-I_002fO.html#Low_002dLevel-I_002fO)
is highly recommended.

## License

Licensed under the [Apache License, Version
2.0](http://www.apache.org/licenses/LICENSE-2.0).

Copyright © 2018 Adam Helinski
