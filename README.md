# 🍽️ DinerEmpire

**Restaurant City tarzı, tarayıcıda çalışan restoran işletme oyunu.**
Tamamen vanilla HTML5 Canvas + JavaScript — sıfır kütüphane, tek dosya.

### 🎮 [OYNA → yanki31.github.io/DinerEmpire](https://yanki31.github.io/DinerEmpire/)

---

## Özellikler

- 🏪 **3 restoran tipi**: Fast Food, Bistro, Fine Dining — farklı ekonomiler
- 🪑 **Düzenleme modu**: masaları ve dekorları grid üzerinde sürükle-bırak
- 👨‍🍳 **Chibi karakterler**: şef şapkalı aşçı, tabak taşıyan garsonlar, renkli müşteriler
- 📦 **Depo & bozulma**: raf + buzluk, FIFO stok, gün sonu bozulan malzemeler
- 🍳 **Ön hazırlık**: burger köftesi, karamelize soğan, makarna hamuru, sushi pirinci
- 🚶 **Kapı kuyruğu**: masalar doluysa müşteriler sırada bekler (sabırları taşana kadar!)
- 😊 **Sabır göstergesi**: her masada gerçek zamanlı sabır çubuğu
- ⭐ **Rating sistemi**: son 20 günün 5 yıldızlı ortalaması
- 🔥 **Rush Hour**: Cuma-Cumartesi-Pazar 2x müşteri, zamlı fiyatlar
- 📈 **Yemek seviyeleri**: her servis XP kazandırır, LV10'a kadar
- 💰 **Vergi & muhasebeci**, ⚡ faturalar, 🪑 mobilya mağazası
- 🔊 **Ses efektleri** (WebAudio synth) — aç/kapa
- 💾 **Otomatik kayıt** (localStorage) — kaldığın yerden devam et
- 🕐 Duvarda **gerçekten çalışan saat**

## Nasıl Oynanır

1. Restoran tipini seç
2. Müşteri masaya oturunca **masaya tıkla** → sipariş alınır, şef pişirir
3. Yemek hazır olunca **tekrar tıkla** → servis! Para + XP + rating
4. Gün sonunda malzeme siparişi ver, ertesi güne hazırlan
5. Kazandıkça masa ekle, ocak al, çalışan tut, dekore et

## Teknoloji

Tek `index.html` (~340KB) — Canvas 2D, vektörel çizim (sprite yok), WebAudio, localStorage.

---

*Claude (Anthropic) ile pair-programming yapılarak geliştirildi.* 🤖
