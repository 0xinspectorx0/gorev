# 📚 KPSS Lisans Ders Çalışma Takvimi

KPSS Lisans hazırlığı için **Tarih, Coğrafya ve Vatandaşlık** derslerini gün gün planlayan, tek dosyalık (bağımlılıksız) bir çalışma takvimi web uygulaması.

## ✨ Özellikler

- **Sekmeler:** Tarih / Coğrafya / Vatandaşlık — tıkladığın ders açılır, tema rengi de o derse göre değişir.
- **Her güne 1 konu:** Takvimdeki her gün için tek bir ana konu.
- **Tekrar + Soru görevi:** Her güne ayrıca bir *Tekrar + Soru* görevi eklenir.
- **🔒 Sıralı kilit:** Bir konu bitmeden o konunun *Tekrar + Soru* görevi, tekrarı bitmeden de sonraki konu açılmaz. Sıra: `Konu 1 → Tekrar 1 → Konu 2 → Tekrar 2 → …` Kilitli kartlar soluk + 🔒 ile gösterilir; kapatmak için üstteki **Sıralı kilit** anahtarını kullanabilirsin.
- **Bugünün planı:** Sayfa açıldığında o günün konusu ve görevi öne çıkar.
- **Sıradaki adım kutusu:** Kilit durumunu ve sıradaki adımı gösteren bilgi şeridi.
- **İlerleme takibi:** Yapılan konular/görevler tarayıcıda (localStorage) saklanır; istatistik ve ilerleme çubuğu güncellenir.
- **Başlangıç tarihi seçimi:** Takvim başlangıç tarihine göre yeniden hesaplanır.
- **Liste / Takvim görünümü** ve **mobilde tek sütuna düşen** responsive tablo.
- **Yazdırma dostu** (Ctrl/Cmd + P).

## 🔗 Canlı Site

**https://0xinspectorx0.github.io/gorev/**

## 🚀 Kullanım

Kurulum gerekmez:

1. `index.html` dosyasını indir, çift tıkla.
2. Ya da GitHub Pages ile yayınlandıysa doğrudan linkten aç.

İlerleme kaydı tarayıcıya özeldir; farklı cihaz/tarayıcıda ayrı tutulur (gizli sekmede sıfırlanır).

## 🌐 GitHub Pages ile yayınlama

Repo ayarlarından: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**

Birkaç dakika sonra site şu adreste yayında olur:

```
https://0xinspectorx0.github.io/gorev/
```

## 🗂️ Proje yapısı

```
.
├── index.html   # Tüm uygulama (HTML + CSS + JS, bağımlılık yok)
├── README.md
├── LICENSE
└── .gitignore
```

## 📄 Lisans

MIT — bkz. [LICENSE](LICENSE).
