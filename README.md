dreamobjects-maxcdn
===================

A Demo Python Script that will create a Storage Bucket on [DreamObjects](http://dreamhost.com/cloud/dreamobjects/) and a Pull Zone on [MaxCDN](http://www.maxcdn.com).

# Prerequisites
* DreamObjects Account 
 * User
 * Key
 * Secret
* MaxCDN Account/Alias
 * API IP Whitelist
 * API Key
 * API Secret
* Python Packages
 * `termcolor`
 * `netdnarws`
 * `boto`

# Installation

`wget https://github...`

`unzip .zip`

`cd master*`

# Usage

`./do-maxcdn-demo.py --access-key=<DreamObject-Key> --secret-key=<DreamObject-Secret> --rws-alias=<NetDNA/MaxCDN-Comapny Alias> --rws-key=<NetDNA/MaxCDN-Comapny Key> --rws-secret=<NetDNA/MaxCDN-Comapny Secret>`
