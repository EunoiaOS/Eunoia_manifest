![banner](https://raw.githubusercontent.com/EunoiaOS/eunoia-resource/eunoia-1.0/manifest.png)
# EunoiaOS

## Getting Started ##
---------------
To get started with the EunoiaOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

### Requirements
- Around 500GB disk space.
- Around 16GB RAM running Linux.

To initialize your local repository, use command:

```bash
repo init --depth=1 -u https://github.com/EunoiaOS/android_manifest.git -b eunoia-1.0 --git-lfs
```

## Then sync up: ##

```bash
repo sync -c --no-clone-bundle --no-tags --optimized-fetch --prune --force-sync -j8
```

### Build our source ###

```bash
. build/envsetup.sh
eunoiaos <device-codename>
```

-----------------------------------------------------------------------------
Credits:
=======
 * [**CAF**](https://source.codeaurora.org)
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
-----------------------------------------------------------------------------
