# Gentoo: Printer driver for the Brother QL-1110NWB

## Installation
Create the file `/etc/portage/repos.conf/gentoo-brother-ql1110nwb.conf` containing:
```sh
[gentoo-brother-ql1110nwb]
location = /usr/local/portage/gentoo-brother-ql1110nwb
sync-type = git
sync-uri = https://github.com/jamescherti/gentoo-brother-ql1110nwb
priority=9999
```

Then execute the commands:
```sh
sudo emerge --sync gentoo-brother-ql1110nwb
sudo emerge -av net-print/brother-ql1110nwb-bin
```

## Author and license

Author: [James Cherti](https://www.jamescherti.com).

Distributed under the terms of the GNU General Public License v2.
