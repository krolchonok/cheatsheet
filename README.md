## download mp3 from yt

```sh
yt-dlp -x --audio-format mp3
```
## termux in adb shell
```sh
run-as com.termux \
  files/usr/bin/bash -lic 'export HOME=/data/data/com.termux/files/home; cd $HOME; export PATH=/data/data/com.termux/files/usr/bin; export LD_PRELOAD=/data/data/com.termux/files/usr/lib/libtermux-exec.so; bash -i'

```
## edge remove alt-tab spam
```
edge://flags/#edge-window-tab-manager
```

## certbot installer

```
sudo apt install snapd
sudo snap install --classic certbot
sudo ln -s /snap/bin/certbot /usr/bin/certbot
sudo certbot --nginx
```

## add python3.10 
```
sudo apt install software-properties-common -y
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.10 python3.10-dev python3.10-venv -y
```

## нумерование ворд
```
CTRL+F9
SEQ Table \* Arabic
F9
```
