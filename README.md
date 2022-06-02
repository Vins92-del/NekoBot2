# File-Sharing-Neko

Bot Telegram untuk menyimpan Posting atau File yang dapat Diakses melalui Link Khusus.
Saya Kira Ini Akan Bermanfaat Bagi Banyak Orang.... 😇

##

**Jika Anda menemukan bug, silahkan tag [@Nekocannn ](https://t.me/Nekocannn)**

### Features
- Sepenuhnya dapat dicustom.
- Dapat di-deploy di Heroku & VPS.
- Pesan sambutan & Forcesub yang dapat dicustom.
- Lebih dari satu Posting dalam Satu Link (batch).
- Fleksibel FSUB Button bisa 1 button atau 2 button menyesuaikan dengan var yang di isi.

### Setup

- Tambahkan bot ke Channel Database tambahkan bot sebagai ADMIN
- Tambahkan bot ke Channel ForceSub tambahkan bot sebagai ADMIN
- Tambahkan bot ke Group ForceSub tambahkan bot sebagai ADMIN

##
### Installation
#### Deploy on Bot Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://telegram.dog/XTZ_HerokuBot?start=cHV0cmFpY2lwaXlleS9GaWxlLVNoYXJpbmcgbWFpbg)</br>
#### Deploy on Web heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)</br>

**Tonton Video Tutorial Ini di YouTube untuk Bantuan memasang di Heroku**<br>
<a href="https://youtu.be/LCrkRTMkmzE">
  <img src="https://img.shields.io/badge/How%20to-Deploy-red?logo=youtube" width="147">
</a><br>
**Thanks to [Erich](https://t.me/ErichDaniken) and his [InFoTel](https://t.me/InFoTel_Group) Untuk video ini**

#### Deploy in your VPS
````bash
git clone https://github.com/BTRExo/File-Sharing-Neko
cd File-Sharing-Neko
pip3 install -r requirements.txt
cp sample_config.env config.env
# edit config.env Anda dan isi VARS
# edit menggunakan nano config.env CTRL + S untuk menyimpan VARS Anda 
# gunakan CTRL + X untuk keluar dan kembali ke direktori File-Sharing-Neko
python3 main.py
````

### Admin Commands

```
/start - mulai bot atau dapatkan postingan

/batch - buat link untuk lebih dari satu posting

/genlink - buat link untuk satu posting

/users - lihat statistik pengguna bot

/broadcast - menyiarkan/broadcast pesan apa pun ke pengguna bot

/ping - untuk mengecek bot

/uptime - untuk melihat waktu aktif bot
```

### Variables

* `API_HASH` Dapatkan API HASH di web my.telegram.org.
* `API_ID` Dapatkan APP ID di web my.telegram.org
* `TG_BOT_TOKEN` Dapatkan dari t.me/BotFather
* `OWNER` Masukan Username Telegram untuk Owner BOT
* `OWNER_ID` Masukan User ID Telegram untuk Owner BOT
* `CHANNEL_ID` Masukan ID Channel Untuk [Channel Database] contoh:- -100xxxxxxxx
* `ADMINS` Masukan User ID untuk mendapatkan hak Admin BOT [Hanya dapat membuat link]
* `START_MESSAGE` Opsional: Pesan /start memulai awalan ke bot, Gunakan <a href='https://github.com/BTRExo/File-Sharing-Nekot/blob/main/README.md#start_message'>fillings</a>
* `FORCE_SUB_MESSAGE` Opsional: Pesan Paksa Subscribe bot, Gunakan Format parsemode HTML
* `FORCE_SUB_CHANNEL` Masukan ID dari Channel Untuk Wajib Subscribenya
* `FORCE_SUB_GROUP` Masukan ID dari Group Untuk Wajib Subscribenya
* `PROTECT_CONTENT` Opsional: Masukan True jika perlu mencegah file dari penerusan

### Extra Variables

* `CUSTOM_CAPTION` letakkan teks teks Kustom Anda jika Anda ingin Mengatur Teks Kustom, Anda dapat menggunakan HTML dan <a href='https://github.com/BTRExo/File-Sharing-Nekot/blob/main/README.md#custom_caption'>fillings</a> untuk pemformatan (hanya untuk dokumen)
* `DISABLE_CHANNEL_BUTTON` Masukan True untuk Nonaktifkan Tombol Berbagi Saluran, Default jika False

### Fillings
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption


## Support   
Join Our [Telegram Group](https://t.me/fsubneko) For Support [Channel](https://t.me/fsubnekoch) For Updates.   
   
Report Bugs, Give Feature Requests There..   

### Credits

- Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)
- Thanks To [CodeXBotz](https://github.com/CodeXBotz/File-Sharing-Bot)
- Our Support Group Members

### Licence
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

[FILE-SHARING-BOT](https://github.com/CodeXBotz/File-Sharing-Bot/) is Free Software: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version. 

##

   **Berikan Bintang Repo ini jika Anda menyukainya ⭐⭐⭐⭐⭐**

