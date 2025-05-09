# ⚽ Futbol Oyunu (Pygame)

Bu proje, Pygame kütüphanesi ile geliştirilmiş 2D bir futbol şut oyunu. Oyuncu, topun açısını ve gücünü ayarlayarak kaleye şut çekmeye çalışır. Belirli bir süre içinde mümkün olduğunca fazla gol atmak hedeflenir.

## 🎮 Özellikler

- Açılı ve güçlü şut mekanizması
- Gerçekçi yerçekimi ve zıplama fiziği
- Kaleye isabetli şutlar ile skor kazanımı
- Rastsal kaleler (hoop) ile zorluk artışı
- Şut animasyonları
- En yüksek skor kaydı (dosyada saklanır)
- Basit menü ve oyun sonu ekranı

## 🖼️ Oyun Görselleri

Oyun aşağıdaki resim dosyalarını kullanır. Bu dosyaların aynı klasörde bulunması gerekir:

- `stadyum.png`: Arka plan resmi
- `run1.png`: Oyuncu durma pozisyonu
- `run2.png`, `run3.png`, `run4.png`: Şut animasyon kareleri
- `futboltopu.png`: Futbol topu
- `kale.png`: Kale (hoop) görseli

## ⌨️ Kontroller

| Tuş | İşlev |
|-----|-------|
| ↑   | Açı artır |
| ↓   | Açı azalt |
| →   | Güç artır |
| ←   | Güç azalt |
| SPACE | Şut çek |
| ENTER | Menüden başla veya yeniden başlat |
| ESC   | Menüye dön veya oyundan çık |

## 🧠 Oyun Mekanikleri

- Top, açısına ve gücüne göre fırlatılır ve yerçekiminden etkilenir.
- Top kaleye çarparsa skor artar ve kale yeri değişir.
- Top yere düşerse, 3 sekmeye kadar devam eder, sonra sıfırlanır.
- Oyuncuya toplam 90 saniye süre verilir.
- Oyun sonunda isabet oranı ve skor gösterilir.
- En yüksek skor `highest_score.txt` dosyasına kaydedilir.

## 🔧 Kurulum

1. Python 3 kurulu olmalı.
2. Pygame kütüphanesini yükle:

```bash
pip install pygame
```

3. Tüm resim dosyalarıyla birlikte `futbol.py` (veya başka bir adla) dosyasını aynı klasöre yerleştir.
4. Oyunu başlat:

```bash
python futbol.py
```

## 📁 Dosya Yapısı

```
futbol.py
stadyum.png
run1.png
run2.png
run3.png
run4.png
futboltopu.png
kale.png
highest_score.txt (otomatik oluşur)
```

## 📜 Lisans

Bu proje eğitim ve kişisel kullanım amaçlıdır. Ticari kullanım için geliştirici izni gereklidir.

---

İyi eğlenceler! 🎉
