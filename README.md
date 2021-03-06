# Michael's AUR packages

The AUR (Arch User Repository) is a community-driven online service collecting build scripts for software not distributed through the official repositories.
These packages mainly consist of `PKGBUILD` files, which are processed by the `makepkg` build tool included with the Arch Linux distribution.

## Usage

For a guidance on using these packages, see the [Arch Wiki's page explaining the AUR](https://wiki.archlinux.org/index.php/Arch_User_Repository).

## Packages

The following packages are provided by Michael:

|                       Name (AUR link)                        | Upstream                        | Description                                                  |
| :----------------------------------------------------------: | ------------------------------- | ------------------------------------------------------------ |
|    [**WeeWX**](https://aur.archlinux.org/packages/weewx/)    | http://www.weewx.com/           | Tool for interfacing with weather stations                   |
| [**OpenTSDB**](https://aur.archlinux.org/packages/opentsdb/) | http://opentsdb.net/            | Distributed, scalable Time Series Database (TSDB) written on top of HBase |
|  [**HBase**](https://aur.archlinux.org/packages/hbase/) [O]  | https://hbase.apache.org/       | Apache HBase™ is the Hadoop database, a distributed, scalable, big data store. |

[O]: Updated version of orphaned package. Link points to old AUR page. Original licensing applies (see notes below).

## Contributing

Issue tracking is disabled for this repository in order to keep all communication in one place. Please use the comments section on the AUR web page instead.

Feel free to submit pull requests, should any severe issues concerning the build system arise. In case the AUR package is outdated, please bug me using the AUR flagging button. ;-)

## License

The `PKGBUILD` files used in the aforementioned packages are licensed under CC-0. Some of the files are updated versions of AUR packages that were orphaned by their original authors. Original copyright applies. The respective maintainers' names are listed in the `PKGBUILD` files.

Note though that the WeeWX wrapper scripts are derivatives of the originals distributed with WeeWX. [Original licensing applies (GPL 3).](https://github.com/weewx/weewx/blob/master/LICENSE.txt)

All software packages installed using these scripts have their own license. Please check the respective license files installed by the packages. All trademarks are property of their respective owners. These packages are not official distributions. They're neither supported nor endorsed by the original authors.
