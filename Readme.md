LineageOS
===========

Getting started
---------------

To get started with Android/LineageOS, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

To initialize your local repository using the LineageOS trees, use a command like this:
```
repo init -u https://github.com/LineageOS/android.git -b lineage-22.2 --git-lfs
```
Then to sync up:
```
repo sync
```
Please see the [LineageOS Wiki](https://wiki.lineageos.org/) for building instructions, by device.


Submitting patches
------------------
Patches are always welcome! Please submit your patches via LineageOS Gerrit!

Simply follow our guide on [how to submit patches](https://wiki.lineageos.org/submitting-patch-howto.html).

To view the status of your and others' patches, visit [LineageOS Gerrit Code Review](https://review.lineageos.org/).


Buildbot
--------

All supported devices are built weekly and periodically as changes are committed to ensure the source trees remain buildable.

You can view the current build statuses at [LineageOS Buildkite](https://buildkite.com/lineageos).

Builds produced weekly by the buildbot can be downloaded from [LineageOS downloads](https://download.lineageos.org/).



MyBuild
--------


repo init -u  https://github.com/flyer222/android_manifest.git -b lineageos_m5 --git-lfs

repo sync 

all dependence all merged to xmls.

brunch m5


通过网盘分享的文件：amlogic_m5
链接: https://pan.baidu.com/s/1U9207fZMf3EeKb25B0uZVQ?pwd=kx8h 提取码: kx8h


MyTarget:
-------

In my free time, Porting s905l3/a/ab to lineageOs, for update to latest AOSP versions

