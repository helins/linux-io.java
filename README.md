# Linux-IO

[![Maven
Central](https://maven-badges.herokuapp.com/maven-central/io.helins/linux-io/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.helins/linux-io)

[![jJavadoc](https://javadoc.io/badge2/io.helins/linux-io/javadoc.svg)](https://javadoc.io/doc/io.helins/linux-io)

Sometimes, for instance when interacting with hardware, native IO is needed and
Java does not provide much for doing so because the JVM aims to be
platform-independant. This library builds upon
[linux-common](https://github.com/helins/linux-common.java) in order to provide
basic utilities such as opening and R/W a file or performing ioctl calls through
[Java Native Access](https://github.com/java-native-access/jna) on a Linux
system.

More precisely, it offers a few utililities like `open` and `ioctl` from [LibC](https://javadoc.io/doc/io.helins/linux-io/latest/io/helins/linux/io/LinuxIO.html).

It serves as a foundations for more useful libraries such as:

- [io.helins/linux-i2c](https://github.com/helins/linux-i2c.java), using the I2C protocol
- [io.helins/linux-gpio](https://github.com/helins/linux-gpio.java), using the Linux GPIO utilities

## Usage

Everything is described in the [javadoc](https://javadoc.io/doc/io.helins/linux-io).


## License

Copyright © 2018 Adam Helinski

Licensed under the term of the Mozilla Public License 2.0, see LICENSE.
