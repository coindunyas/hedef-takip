# Binance TR Hedef Takip

Tek dosyalik, tarayicida yerel calisan hedef takip uygulamasi.

## Ozellikler
- Kayit ekleme, kopyalama, silme
- Kayit arama
- Binance TR sembolu ile fiyat cekme
- Asagi/Yukari hedef kontrolu
- Verileri sadece bu cihazin tarayicisinda saklama
- JSON yedek alma ve geri yukleme

## Calistirma
Bu proje statik bir uygulamadir.

### Secenek 1
`index.html` dosyasini dogrudan tarayicida ac.

### Secenek 2
GitHub'a yukle ve statik olarak kullan.

## GitHub'a yukleme
1. GitHub'da yeni bir repo olustur.
2. Bu klasordeki dosyalari repoya yukle.
3. Istersen GitHub Pages acmadan sadece kod yedegi olarak tut.
4. Istersen GitHub Pages ile yayinla.

## Veri saklama
Veriler `localStorage` icinde saklanir.
Bu yuzden:
- Veri sadece ayni cihaz ve ayni tarayicida gorunur.
- Tarayici verileri silinirse kayitlar da silinir.
- Farkli cihazlarla otomatik senkron olmaz.

## Dosyalar
- `index.html`: Uygulamanin kendisi
- `README.md`: Kullanim notlari
- `.gitignore`: Gereksiz dosyalari dahil etmemek icin

## Not
Binance TR fiyat cekebilmek icin gecerli sembol kullanilmalidir. Ornek:
- `BTCTRY`
- `ETHTRY`
- `SOLTRY`
