<p align="center">
<img src="https://telegra.ph/file/1b7fba8f493e6eb06bacd.jpg" alt="RIKKA BOT" width="500"/>


</p>
<p align="center">
<a href="#"><img title="RIKKA MULTI DEVICE" src="https://img.shields.io/badge/RIKKA MULTI DEVICE-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>

## Information
> Rikka-Md adalah bot yang memakai base dari [Chikabot](https://github.com/rashidsiregar28/chikabot/blob/main/README.md) . Alphabot-Md is a bot whatsapp using a Baileys library.
> Jika kamu menemukan semacam bug, harap untuk dimaklumi sementara

## Bugs and Tester
* Jika kamu menemukan bug jangan lupa buka Issues
* Info Lebih Lanjut, Chat [owner-alpha](https://wa.me/62887435047326)

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip) (for sticker command)

# Instalasi
## For Windows
```bash
git clone https://github.com/sophiashirashaki/Rikka-Md.git
cd Rikka-Md
npm install
node main
```
## For Termux
```bash
termux-setup-storage
apt update && apt upgrade
pkg install nodejs git ffmpeg
git clone https://github.com/sophiashirashaki/Rikka-Md.git
cd Rikka-Md
npm install
node main
```

## For VPS
```bash
apt install nodejs git ffmpeg
git clone https://github.com/sophiashirashaki/Rikka-Md.git
cd Rikka-Md
npm install
node main
```

## Edit file
- Change session on [this section](https://github.com/sophiashirashaki/Rikka-Md/blob/v2/session.json#L1)
- Change ownerNumber on [this section](https://github.com/sophiashirashaki/Rikka-Md/blob/v2/setting.json#L7)
- Change botName on [this section](https://github.com/sophiashirashaki/Rikka-Md/blob/v2/setting.json#L2)
- You can edit list and display menu or donate on [this section](https://github.com/sophiashirashaki/Rikka-Md/blob/v2/language/indonesia.js#L83)
- You can add fiture on [this section](https://github.com/zeeoneofc/Rikka-Md/blob/v2/index.js)


## Installing the FFmpeg for Windows
* Unduh salah satu versi FFmpeg yang tersedia dengan mengklik [di sini](https://www.gyan.dev/ffmpeg/builds/).
* Extract file ke `C:\` path.
* Ganti nama folder yang telah di-extract menjadi `ffmpeg`.
* Run Command Prompt as Administrator.
* Jalankan perintah berikut::
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Jika berhasil, akan memberikanmu pesan seperti: `SUCCESS: specified value was saved`.
* Sekarang setelah Anda menginstal FFmpeg, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi:
```cmd
> ffmpeg -version
```


