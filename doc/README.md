

gull Core 1.1.0
=====================

This is the official reference wallet for gull digital currency and comprises the backbone of the gull peer-to-peer network. You can [download gull Core](https://www.gull.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run gull on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/gull-qt` (GUI) or
- `bin/gulld` (headless)

### Windows

Unpack the files into a directory, and then run gull-qt.exe.

### OS X

Drag gull-Qt to your applications folder, and then run gull-Qt.

### Need Help?

* See the [gull documentation](https://gullpay.atlassian.net/wiki/display/DOC)
for help and more information.
* Ask for help on [#gullpay](http://webchat.freenode.net?channels=gullpay) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=gullpay).
* Ask for help on the [gullTalk](https://gulltalk.org/) forums.

Building
---------------------
The following are developer notes on how to build gull Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The gull Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [gullTalk](https://gulltalk.org/) forums, in the Development & Technical Discussion board.
* Discuss on [#gullpay](http://webchat.freenode.net/?channels=gullpay) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=gullpay).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
