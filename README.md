# DHL Almancası

Paket dağıtımında müşteri ve iş arkadaşlarıyla konuşmak için Almanca cümleler. Satzheft'ten bağımsız, ayrı bir uygulamadır.

**Adres:** https://ethemguenes-bit.github.io/dhl-almanca/

Android'de Chrome ile açıp menüden **Uygulamayı yükle** seçin; ana ekrana kendi ikonuyla gelir ve ilk açılıştan sonra internetsiz çalışır.

## İçerik

- **Ana sayfa:** ilerleme halkası, günlük seri, Anki kısayolu, cihaz kılavuzu, bölümler, günün cümlesi, telefona yükleme düğmesi
- **Cümleler:** 205 numaralı cümle; her birinde Türkçe, Almanca, Türkçe okunuş, kelime açıklamaları ve varsa alternatif; arama, yıldızlama, gizleyip kendini sınama, normal ve yavaş seslendirme
- **Anki:** aralıklı tekrar (Tekrar / Zor / İyi / Kolay), günde yeni kart sınırı, yön ve deste seçimi
- **Oyun (Paket Yarışı):** Almanca→Türkçe ve Türkçe→Almanca sorular, 3 can, süre, seri çarpanı, rekor
- **Sabah toplantısı:** şefin bilgilendirmesinden 30 cümle (güvenlik, bölge değişiklikleri, kurallar, dağıtım, trafik, kalite, yoğun dönem) ve toplantıda sorulacak 10 soru; dinleme modu (konuşmayı dinle, "Şef ne dedi?" sorularını cevapla) ve tarihli toplantı notları (kopyala / paylaş)
- **Diyaloglar:** işte geçen sahneler (Sahne 01: Depoda sabah; Sahne 02: Neredeyse kaza – şefe açıklama; Sahne 03: Şefle izin konuşması – dişçi randevusu); oku ve dinle (iki farklı ses), rol yap (karşı tarafı dinle, kendi repliğini söyle), rolleri değiştir, iki rolü birden oyna; kilit ifadeler ve ezber taktiği. Sahneler `DIALOGS` listesinde
- **Cihaz kullanımı:** Zebra el terminali kılavuzu, numaralı kayıtlar (001: Müşteri evde yok – Benachrichtigung)
- **Alıştırmalar:** Kartlar, Doğruyu seç, Dinle ve anla, Cümle kur
- **Kelimeler**, **Kalıplar**, **Ekle** (kendi cümlelerin, toplu ekleme, yedek)

## Düzenleme

Her şey `index.html` içindedir: cümleler `BASE`, kelimeler `WORDS`, cihaz kayıtları `GUIDES` listesinde.
Dosyalar değişince `sw.js` içindeki `VERSION` değerini artırın; telefonlar yeni sürümü bir sonraki açılışta alır.
