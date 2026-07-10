# MySince – O günden bu yana ⏳

Hayatındaki önemli anlardan bu yana geçen zamanı **yıl / ay / gün** olarak takip eden,
web ve mobil uyumlu (PWA) bir uygulama.

## Özellikler

- **6 kategori**, her biri kendine özgü renk paleti ve lifestyle görseliyle:
  Ölüm 🕯️ · Doğum 🌅 · Kutlama 🎈 · Alışkanlık 🌱 · Önemli An ⭐ · Seyahat ✈️
- Her an için **yıl / ay / gün** sayacı + toplam gün; gelecekteki tarihler için geri sayım
- An **ekleme, düzenleme, silme** ve kategoriye göre filtreleme
- **Google Drive yedekleme**: "Drive'a Yedekle (Paylaş)" telefondaki paylaşım menüsüyle
  yedek dosyasını doğrudan Drive'a gönderir; ".json indir / yedekten geri yükle" ile de
  taşıyabilirsin (birleştir veya değiştir seçenekli)
- Veriler cihazda (`localStorage`) saklanır; internet olmadan da çalışır (service worker)
- **Ana ekrana eklenebilir** (PWA): manifest + uygulama ikonu dahil

## Kullanım

Klasörü herhangi bir statik sunucuda yayınla (örn. GitHub Pages) ve
`mysince/index.html` adresini aç. Telefonda tarayıcı menüsünden
**"Ana ekrana ekle"** diyerek uygulama gibi kullanabilirsin.

## Yedekleme akışı

1. Sağ üstteki bulut simgesine dokun
2. **Drive'a Yedekle (Paylaş)** → paylaşım menüsünden Google Drive'ı seç
3. Geri yüklemek için Drive'daki `mysince-yedek-*.json` dosyasını indir
   ve **Yedekten Geri Yükle** ile seç
