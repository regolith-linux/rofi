## rofi

This repository is a snapshot of [rofi](https://github.com/davatorium/rofi) `1.6.1` release.

#### How to Install

Builds of this package are available from the Regolith PPA for Ubuntu `Bionic`, `Focal`, and `Groovy`.  Despite being hosted in the Regolith PPA, there is nothing specific or custom for Regolith and this build of rofi can be considered "vanilla".  To install into Ubuntu:

```bash
$ sudo add-apt-repository ppa:regolith-linux/unstable
$ sudo apt install rofi
```

#### How to Build

To build this package locally, ensure that the Debian packaging tools and `gbp` are installed.  Then invoke `gbp buildpackage` to generate Debian packages.  Example:

```bash
$ git clone git@github.com:regolith-linux/rofi.git && cd rofi
$ gbp buildpackage --git-debian-branch=r1.6.1
$ ls -haltr /tmp/debian-pkg-builds/
```

#### Known Issues
