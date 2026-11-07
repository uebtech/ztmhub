# ztmhub

ZTM IPTV uygulamasi icin kanal logo kutuphanesi.

- `logolar/` : 256 piksel PNG kanal logolari
- `ZTM-birlesik.m3u` : logolari bu depodan kullanan kanal listesi

Logolar ilgili kanallara aittir; yalnizca kanal tanitimi amaciyla kullanilir.

## Telefondan TV'ye liste gönderme

`gonder/` klasöründeki sayfa, ZTM TV uygulamasına (Samsung / LG) telefondan M3U adresi, Xtream hesabı ya da M3U dosyası göndermek için kullanılır.

- Adres: https://uebtech.github.io/ztmhub/gonder/
- TV'de **Listeler → Telefondan gönder** ekranındaki QR kodu okutmak yeterli.
- Aktarma ntfy.sh üzerinden, TV ekranındaki koda özel bir kanaldan yapılır.
