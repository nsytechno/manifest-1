<img src="https://raw.githubusercontent.com/Rpingat/test1/master/bannrtr.png">

ThunderOS
========

Getting Started
---------------

To initialize your local repository, use a command like this:

```bash
 repo init -u https://github.com/ThunderOS/manifest.git -b storm-8.0
```

Then to sync up:

    repo sync -j8 -f --force-sync --no-clone-bundle --no-tags
    
Building Instructions:
----------------------


```bash
  . build/envsetup.sh
  lunch thunder_device_codename-userdebug
  make bacon -j8
```
