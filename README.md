Getting Started:
 ==============

To get started with DroidX-UI, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init --depth=1 -u git@github.com:ParsaAslaniYC/droidx.git -b 14_v3 --git-lfs
```

Then to sync up:

```
repo sync -c -j$(nproc --all) --optimized-fetch --no-tags --no-clone-bundle --prune
```

---------------------------------------------------------------------------------------
 Compilation of DroidX-UI:
 ==================

From root directory of Project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch droidx_$device-ap2a-userdebug
$ m bacon
```
---------------------------------------------------------------------------------------

# Credits:

 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**PixysOS**](https://github.com/PixysOS)
