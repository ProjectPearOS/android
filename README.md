PearOS
===========

Getting started
---------------

## Disclaimer
# this project is currently wip and might not build successfully

To get started with PearOS, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

To initialize your local repository, run:
```
repo init -u https://github.com/ProjectPearOS/android.git -b 13.0 --git-lfs
```
Optionally, --depth=1 can also be used to save time,network and disk space at the cost of local commit history.

Then, to sync PearOS:
```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```


Submitting patches
------------------
Patches are always welcome! Please submit your patches via GitHub pull requests!
