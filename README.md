# EXCELLBOTV10

#### ONLY RUN RAILWAY
[`railway.app`](https://railway.app/new/github)

#### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/AyGemuy/Hinata)

Edit the required value in [`config.js`](https://github.com/AyGemuy/Hinata/blob/master/config.js)

#### Heroku Buildpack
| BuildPack | LINK |
|--------|--------|
| **NODEJS** |[heroku](https://github.com/heroku/heroku-buildpack-nodejs) |
| **FFMPEG** |[jonathanong](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git) |
| **IMAGEMAGICK** | [mcollina](https://github.com/mcollina/heroku-buildpack-imagemagick.git) |
| **IMAGEMAGICK** | [yespark](https://github.com/yespark/heroku-imagemagick-buildpack) |
| **python** | [heroku](https://github.com/heroku/heroku-buildpack-python) |
| **redis** | [heroku](https://github.com/heroku/heroku-buildpack-redis) |
| **rarlab** | [HasibulKabir](https://github.com/HasibulKabir/heroku-buildpack-rarlab) |
| **ffmpeg** | [jonathanong](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest) |
| **webp** | [clhuang](https://github.com/clhuang/heroku-buildpack-webp-binaries) |
| **p7zip** | [opendoor](https://github.com/opendoor-labs/heroku-buildpack-p7zip) |
| **aria2** | [amivin](https://github.com/amivin/aria2-heroku) |
| **chrome** | [heroku](https://github.com/heroku/heroku-buildpack-google-chrome) |
| **chromedriver** | [heroku](https://github.com/heroku/heroku-buildpack-chromedriver) |
| **slug** | [nekopanic](https://github.com/nekopanic/buildpack-slug-cleaner) |
| **imagemagick** | [nrj](https://github.com/nrj/heroku-buildpack-imagemagick-webp) |
---------
#### Note
```sh
not for termux
```

### FOR TERMUX USER
1. Type mentioned below given commands one by one in Termux.
```sh
$ pkg upgrade && pkg update
$ pkg install git -y
$ pkg install nodejs -y
$ pkg install ffmpeg -y
$ pkg install imagemagick -y
$ git clone https://github.com/AyGemuy/Hinata
$ cd EXCELLBOTV(VERSI YG KAMU DOWNLOAD SEKARANG)
$ npm i 
```

```sh
$ node .
```
2. Wait for bot starting...
3. Scan QR code from 2nd device. (Go to whatsapp > Linked Devices > Join `Multi Device Beta` > Click on `link device`)
4. Now your bot is ready to rock n roll.

#### If npm install failed, try using yarn instead of npm
```sh
$ pkg install yarn -y
$ yarn install
```
---------
## INSTALL ON TERMUX WITH UBUNTU

[ INSTALLING UBUNTU ]

```bash
apt update && apt full-upgrade
apt install wget curl git proot-distro
proot-distro install ubuntu
echo "proot-distro login ubuntu" > $PREFIX/bin/ubuntu
ubuntu
```
---------

[ INSTALLING REQUIRED PACKAGES ]

```bash
ubuntu
apt update && apt full-upgrade
apt install wget curl git ffmpeg imagemagick build-essential libcairo2-dev libpango1.0-dev libjpeg-dev libgif-dev librsvg2-dev dbus-x11 ffmpeg2theora ffmpegfs ffmpegthumbnailer ffmpegthumbnailer-dbg ffmpegthumbs libavcodec-dev libavcodec-extra libavcodec-extra58 libavdevice-dev libavdevice58 libavfilter-dev libavfilter-extra libavfilter-extra7 libavformat-dev libavformat58 libavifile-0.7-bin libavifile-0.7-common libavifile-0.7c2 libavresample-dev libavresample4 libavutil-dev libavutil56 libpostproc-dev libpostproc55 graphicsmagick graphicsmagick-dbg graphicsmagick-imagemagick-compat graphicsmagick-libmagick-dev-compat groff imagemagick-6.q16hdri imagemagick-common libchart-gnuplot-perl libgraphics-magick-perl libgraphicsmagick++-q16-12 libgraphicsmagick++1-dev
```

---------

[ INSTALLING NODEJS & Hinata ]

```bash
ubuntu
curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash -
apt install -y nodejs gcc g++ make
git clone https://github.com/AyGemuy/Hinata
cd EXCELLBOTV(YG KAMU DOWNLOAD)
npm install
npm update
```

---------

## FOR WINDOWS/VPS/RDP USER

* Download And Install Git [`Click Here`](https://git-scm.com/downloads)
* Download And Install NodeJS [`Click Here`](https://nodejs.org/en/download)
* Download And Install FFmpeg [`Click Here`](https://ffmpeg.org/download.html) (**Don't Forget Add FFmpeg to PATH enviroment variables**)
* Download And Install ImageMagick [`Click Here`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/AyGemuy/Hinata
cd EXCELLBOTV (YG KAMU DOWNLOAD)
npm install
npm update
```

---------

## Run

```bash
node .
```

---------

## Arguments `node . [--options] [<session name>]`

### `--self`

Activate self mode (Ignores other)

### `--pconly`

If that chat not from private bot, bot will ignore

### `--gconly`

If that chat not from group, bot will ignore

### `--swonly`

If that chat not from status, bot will ignore

### `--prefix <prefixes>`

* `prefixes` are seperated by each character
Set prefix

### `--server`

Used for [heroku](https://heroku.com/) or scan through website

### `--restrict`

Enables restricted plugins (which can lead your number to be **banned** if used too often)

* Group Administration `add, kick`

### `--img`

Enable image inspector through terminal

### `--autoread`

If enabled, all incoming messages will be marked as read

### `--autocleartmp`

If enabled, **tmp* folder contain files will be auto delete

### `--nyimak`

No bot, just print received messages and add users to database

### `--test`

**Development** Testing Mode

---------


```
---------

### want to contribute?
1. fork this repository
2. Change/edit/create what you want. for example you can add features, fix bug, etc
3. **test** before making a pull req!!
4. make a pull req!
5. if your pull req is already in **acc/merge**, you can delete your branch or you can create pull req again :)

---------


### Thanks To 
**Allah SWT**,

**Orang Tua**,

**Ayang Gwehj:v**,

**Semua yang selalu mendukung**
