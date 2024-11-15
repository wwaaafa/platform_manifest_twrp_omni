# this is a not twrp official support project!!! #
# this is a not twrp official support project!!! #
# this is a not twrp official support project!!! #

## Getting Started ##
---------------

To get started with OmniROM, you'll need to get
familiar with [Git and Repo](https://source.android.com/source/using-repo.html).

To initialize your local repository using the OmniROM trees, install the git-lfs packages and use a command like this:

    sudo apt-get install git-lfs

    repo init -u https://github.com/wwaaafa/platform_manifest_twrp_omni.git -b twrp-14.0 --git-lfs

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; brunch <device_name>

