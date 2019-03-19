# Muhasebe
Piyo Muhasebe Programı <br />
İlk commit i yapıyorum.

# Fatura

| Route | HTTP Verb	 | POST body	 | Description	 |
| --- | --- | --- | --- |
| /api/faturalar | `GET` | Empty | Fatura Listesi. |
| /api/faturalar | `POST` | {'faturaUnvan':'Pi Yazılım Otomasyon', 'kisaAd':'PIYO', 'musteriTedarikci':'M/T', eposta:'info@piyo.com.tr', kategori:'kategori', adres: 'Folkart B Kule kat 34', ilce: 'BAYRAKLI', il: 'İZMİR' } | Yeni Fatura Oluşturma EndPointi. |
