PartsCoin Core
=============

Setup
---------------------
PartsCoin Core is the original PartsCoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of PartsCoin transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download PartsCoin Core, visit [partscoin.org](https://partscoin.org/).

Running
---------------------
The following are some helpful notes on how to run PartsCoin Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/partscoin-qt` (GUI) or
- `bin/partscoind` (headless)

### Windows

Unpack the files into a directory, and then run partscoin-qt.exe.

### macOS

Drag PartsCoin Core to your applications folder, and then run PartsCoin Core.

### Need Help?

* See the documentation at the [PartsCoin Wiki](https://partscoin.info/) for help and more information.
* Ask for help on [#partscoin](https://webchat.freenode.net/#partscoin) on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#partscoin).
* Ask for help on the [PartsCoinTalk](https://partscointalk.io/) forums, in the [Technical Support board](https://partscointalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build PartsCoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/bitcoin-core/docs/blob/master/gitian-building.md)

Development
---------------------
The PartsCoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://doxygen.bitcoincore.org/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [PartsCoinTalk](https://partscointalk.io/) forums.
* Discuss general PartsCoin development on #partscoin-dev on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#partscoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
