## Cara Install
Jalankan Perintah berikut untuk mendownload data dari repository github

```sh
$ git clone https://github.com/KarelNatalia/karelnatalia.git && cd karelnatalia
```

# Cara Menjalankan
### Cara Pertama

```sh
$ docker build -t 195410107_karell ./
$ docker run -dit --name 195410107_karell_runapp -p 8000:80 195410107_karell
```

lalu buka browser dengan url `http://locahost:8000` untuk melihat hasil nya.

## Cara Kedua
```sh
$ docker run -dit --name 195410107_karell_runapp -p 8000:80 123karel/195410107_karell:latest
```
lalu buka browser dengan url `http://locahost:8000` untuk melihat hasil nya.
