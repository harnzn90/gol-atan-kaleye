# Gol Atan Kaleye ⚽

2D browser-based street football game. Single goal, half field, first-to-5 scoring. Physics-based ball, dribble-stick mechanic, AI opponents, and full customization.

## 🎮 Oynanış

- **Hedef**: İlk belirlenen gole ulaşan oyuncu kazanır (varsayılan 5 gol)
- **Özel kural**: Gol atan kaleye geçer, eski kaleci sahaya döner
- **Tek kontrollü oyuncu**: Sadece kendini yönetirsin, diğerleri AI

## ⌨️ Tuşlar

| Tuş | Aksiyon |
|------|---------|
| Ok tuşları | Hareket |
| E | Koş (sprint) |
| D | Şut çek / kaleci topu uzaklaştır |
| A | Güç mücadelesi (50 stamina harcar) |
| S | Top sürme / kıpılama (yakında rakiple %50 geçme) |
| P | Oyunu duraklat |
| R | Raundu sıfırla |
| B | Ana menüye dön |

Tüm tuşlar menüden yeniden atanabilir.

## ⚙️ Özellikler

- 2-8 oyuncu (1 kullanıcı + AI)
- Ayarlanabilir galibiyet sayısı (2-10)
- Fizik tabanlı top (sürtünme, sekmeler)
- 3 saniye dribble stick (top önde gider, sonra bırakılır)
- AI rakipler: topu kovalar, şut çeker, mücadele eder
- Kaleci: ceza sahasında serbest, topu yakalayıp uzaklaştırır
- 8 farklı saç stili (Afro, Mohawk, Elvis, Spiky, Pompadour, Flat top, Side swept, Kel)
- Gerçek futbolcu isimleri (TR/EN/DE)
- Ses efektleri (Web Audio API)
- Dokunmatik kontroller (mobil/touch cihazlar)
- Dil desteği: Türkçe, English, Deutsch

## 🖥️ Oynama

Dosyayı doğrudan tarayıcıda aç:
```
futbol-oyunu.html
```

Herhangi bir sunucu veya derleme gerektirmez — tek dosya HTML.

## 🛠️ Teknik

- Saf JavaScript, Canvas 2D
- Web Audio API (ses sentezi)
- Hiçbir harici kütüphane veya bağımlılık yok
- ~1900 satır, tek dosya

## 📜 Lisans

MIT
