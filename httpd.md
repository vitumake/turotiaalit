# Webappien hostaus palvelimella

[Takaisin](readme.md)

Tavoitteena asentaa ja konfiguroida httpd-palvelin linux-ympäristöön. Esimerkeissä käytetään Ubuntu distroa, joka
muistuttaa Debiania.

## HTTPD-palvelimen asennus ja konffaus

- [Apache](./apache/readme.md)
- [Nginx](./nginx/readme.md)

## Domainin rekisteröinti ja DNS-asetukset

Jos haluat käyttää omaa domainia, sinun tulee rekisteröidä se ja asettaa DNS-asetukset osoittamaan palvelimellesi. Tämä onnistuu esimerkiksi [Namecheap](https://www.namecheap.com/)-palvelussa.

## SSL-sertifikaatin asennus

SSL-sertifikaatti on tärkeä osa webpalvelimen konfigurointia. Se mahdollistaa HTTPS-yhteyden salauksen ja luo luottamusta käyttäjien keskuudessa. Sertifikaatin voi hankkia ilmaiseksi [Let's Encrypt](https://letsencrypt.org/)-palvelusta.

// TODO: Lisää ohjeita