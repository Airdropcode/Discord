# Discord
#### _Saya membuat Bagaimana Caranya Agar Dapat melakukan Push Level Di Discord menggunkan Termux_
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
![made-with-python](https://img.shields.io/badge/Airdrop%20Code-Discord-green)

Dengan Mengunakan Kode Ini Anda Tidak Akan Susah lagi Untuk melakukan Push Level Di Discord.


## Features

- Kirim pesan Quote
- Kirim pesan Respon Simsimi
- Kirim pesan Repost dari riwayat obrolan saluran
- Kirim pilih baris acak dari custom.txt
- Pesan Hapus Otomatis

## Cara instal Di Termux
```sh
apt update
```

```sh
apt upgrade -y
```

```sh
pkg install git -y
```

```sh
pkg install python3 -y
```

```sh
pkg install nano -y
```

```sh
git clone https://github.com/Airdropcode/Discord
```
Selanjutnya Silahkan Masuk Ke folder Discord
Dengan Mengetikan 
```sh
CD Discord
```
Lanjut Install 
```sh
pip install -r requirements.txt
```
Dan Edit Bot Token Dan Channel Id
Dengan Mengetikan 
```sh
nano config.yaml
```


| NANO | CONFIG |
| ------ | ------ |
| BOT_TOKEN: | ID TOKEN |
| CHANNEL_ID: | ID CHANEL |
| MODE: | CUSTOM |
| REPLY: Y | PESAN ANDA AKAN MELAKUKAN REPLY |
| SIMSIMI_LANG: | ANDA BISA MENGGUNKAN BAHASA EN/ID |
| DELAY: 60 | BERAPA WAKTU PESAN SELAJUTNYA HITUNGAN DETIK |
| DEL_AFTER: Y | TEKAN Y JIKA INGIN PESAN ANDA DI HPUS OTOMATIS |
| REPOST_LAST_CHAT: 100 | JUMLAH OBROLAN |

> Note: `--_( channel id yang digunakan adalah yang belakang sendiri.
Contoh : https://discord.com/channels/10945700118191885005/10949017458950307999 , yang digunakan adalah 10949017458950307999 )_




> Cara Menjalakan Dengan Mengetikan : 
```sh
Python bot.py
```


> Note: `--_Resiko Ditanggung Anda Sendiri._





**Airdrop Code**
