## download mp3 from yt

```sh
yt-dlp -x --audio-format mp3
```
## termux in adb shell
```sh
run-as com.termux \
  files/usr/bin/bash -lic 'export HOME=/data/data/com.termux/files/home; cd $HOME; export PATH=/data/data/com.termux/files/usr/bin; export LD_PRELOAD=/data/data/com.termux/files/usr/lib/libtermux-exec.so; bash -i'

```
