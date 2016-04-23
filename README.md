## Welcome to Chan_SCCP

[![Coverity](https://img.shields.io/coverity/scan/7795.svg)](https://scan.coverity.com/projects/dkgroot-chan-sccp-b)
[![Build Status](http://img.shields.io/travis/marcelloceschia/chan-sccp-b.svg?style=flat)](https://travis-ci.org/marcelloceschia/chan-sccp-b)
[![Github Issues](https://img.shields.io/github/issues/marcelloceschia/chan-sccp-b/bug.svg)](http://github.com/marcelloceschia/chan-sccp-b/issues)
[![Download Chan-SCCP channel driver for Asterisk](https://img.shields.io/sourceforge/dt/chan-sccp-b.svg)](https://sourceforge.net/projects/chan-sccp-b/files/latest/download)
[![GitHub license](https://img.shields.io/badge/license-GPL-blue.svg)](https://raw.githubusercontent.com/marcelloceschia/chan-sccp-b/master/LICENSE)
[![Github Releases](https://img.shields.io/github/release/marcelloceschia/chan-sccp-b.svg)](https://github.com/marcelloceschia/chan-sccp-b/releases)
[![Documentation](https://img.shields.io/badge/docs-wiki-blue.svg)](https://sourceforge.net/p/chan-sccp-b/wiki/Home/)
[![LauchpadPPA](https://img.shields.io/badge/Ppa-bin-blue.svg)](https://launchpad.net/~chan-sccp-b/+archive/ubuntu/ppa)
[![BuildOpenSuSE](https://img.shields.io/badge/Build-bin-blue.svg)](http://download.opensuse.org/repositories/home:/chan-sccp-b:/)
[![Donate](https://img.shields.io/badge/paypal-donate-yellow.svg)](https://www.paypal.com/cgi-bin/webscr?item_name=Donation+to+Chan-SCCP+channel+driver+for+Asterisk&locale.x=en_US&cmd=_donations&business=chan.sccp.b.pp%40gmail.com).

Chan_SCCP is free software. Please see the file COPYING for details.
For documentation, please see the files in the doc subdirectory.
For building and installation instructions please see the INSTALL file.

### Prerequisites
Make sure you have the following installed on your system:
- c-compiler:
  - gcc >= 4.4  (note: older not supported, higher advised)
  - clang >= 3.6  (note: older not supported, higher advised)
- gnu make
- pbx:
  - asterisk >= 1.6.2 (absolute minimum)
  - asterisk >= 11.21 or asterisk >= 13.7 recommended
  - including source headers and debug symbols (asterisk-dev and asterisk-dbg / asterisk-devel and asterisk-debug-info)
- standard posix compatible applications like sed, awk, tr

### Configuring
    ./configure [....configure flags you prefer...]

For more information about the possible configure flags, check:
    ./configure --help 

Note: When you are making changes to configure.ac, autoconf / or Makefile.am files you should run ./tools/bootstrap.sh afterwards.

### Build and Install
    make
    make install

### Wiki
You can find more information and documentation on our [wiki](https://sourceforge.net/p/chan-sccp-b/wiki/)

### Donate
If you like our project, then please consider making a 
[![donation](https://www.paypalobjects.com/webstatic/en_US/btn/btn_donate_pp_142x27.png)](https://www.paypal.com/cgi-bin/webscr?item_name=Donation+to+Chan-SCCP+channel+driver+for+Asterisk&locale.x=en_US&cmd=_donations&business=chan.sccp.b.pp%40gmail.com).


