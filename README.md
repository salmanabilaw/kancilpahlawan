# ProktorBrowserOnline

Proktor Browser ini digunakan untuk Proktor Browser admin pada Windows. 

## Getting started
untuk melakukan build Proktor Browser ini langkah yang pertama dilakukan adalah.
- [1]. Lakukan enkripsi kode Main.js, content/setting.js, content/window.js di url https://obfuscator.io/ atau url obfuscate lainnya
- [2]sudah melakukan instalasi nodejs dan jalankan perintah berikut pada terminal
- [] 64Bit build dengan perintah berikut
- [] electron-packager . --overwrite --platform=win32 --arch=x64 --out=release-builds --icon=content/assets/img/admin.ico
- [] 32Bit build dengan perintah berikut
- [] electron-packager . --overwrite --platform=win32 --arch=ia32 --out=release-builds --icon=content/assets/img/admin.ico
- []
- [] Bisa menambahkan --asar dibelakang tetapi perlu di exclude confignya. 
- [] --asar.unpack=exambro.json