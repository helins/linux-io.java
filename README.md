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

MIT License

Copyright © 2018 Adam Helinski

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the “Software”), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
