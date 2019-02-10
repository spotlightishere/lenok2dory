# lenok2dory
Run `./build`. You may have to authenticate via sudo for some commands.

If the `mksquashfs` provided doesn't work, check out [kruton/squashfs-tools's selinux branch](https://github.com/kruton/squashfs-tools/tree/selinux), as it works quite well if the entire Android source isn't desired to be downloaded. Then you can run. Note that it doesn't support `lz4`, so you will have to edit the build to output `gzip`.
