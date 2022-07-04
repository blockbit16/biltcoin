Bilt Core
=============

Setup
---------------------
[Bilt Core](https://biltcoin.com/) is the original Bilt client and it builds the backbone of the network. However, it downloads and stores the entire history of Bilt transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run Bilt Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/bilt-qt` (GUI) or
- `bin/biltd` (headless)

### Windows

Unpack the files into a directory, and then run Bilt-qt.exe.

### macOS

Drag Bilt-Qt to your applications folder, and then run Bilt-Qt.

### Need Help?

* See the documentation at the [Bilt Wiki](https://github.com/biltcoin-com/BILT/tree/master/doc)
for help and more information.
* Join our Discord server [Discord Server](https://discord.gg/zgcXB76)

Building
---------------------
The following are developer notes on how to build Bilt Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Bilt repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://github.com/biltcoin-com/BILT/tree/master/doc)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [Bilt Homepage](https://biltcoin.com/).
* Join the [Bilt Discord](https://discord.gg/zgcXB76).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
