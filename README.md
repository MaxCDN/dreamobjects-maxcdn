dreamobjects-maxcdn
===================

A Demo Python Script that will create a Storage Bucket on [DreamObjects](http://dreamhost.com/cloud/dreamobjects/) and a Pull Zone on [MaxCDN](http://www.maxcdn.com).

# Prerequisites
* DreamObjects Account 
 * User
 * Key
 * Secret
* NetDNA/MaxCDN Account
 * API IP Whitelist
 * API Key
 * API Secret
* Python Packages
 * `termcolor`
 * `netdnarws`
 * `boto`

# Installation

```shell
wget https://github.com/netdna/dreamobjects-maxcdn/archive/master.zip
unzip master.zip
cd dreamobjects-maxcdn-master* 
```

# Usage

```shell
./demo.py --access-key=<DreamObject-Key> --secret-key=<DreamObject-Secret> \
--rws-alias=<NetDNA/MaxCDN-Comapny-Alias> --rws-key=<NetDNA/MaxCDN-Key> \
--rws-secret=<NetDNA/MaxCDN-Secret>
```

![demo.py](https://raw.github.com/netdna/dreamobjects-maxcdn/master/demo.png)
