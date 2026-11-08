# 📚 KPSS Lisans Ders Çalışma Takvimi

KPSS Lisans hazırlığı için **Tarih, Coğrafya ve Vatandaşlık** derslerini gün gün planlayan, tek dosyalık (bağımlılıksız) bir çalışma takvimi web uygulaması.

## ✨ Özellikler

- **Sekmeler:** Tarih / Coğrafya / Vatandaşlık — tıkladığın ders açılır, tema rengi de o derse göre değişir.
- **Konu → Tekrar döngüsü:** Her konu gününden sonra, o konuya özel 1 tam gün *Tekrar + Soru* günü gelir; yeni konuya ancak tekrardan sonra geçilir.
  - Tarih: 62 konu → 124 gün · Coğrafya: 43 konu → 86 gün · Vatandaşlık: 54 konu → 108 gün
- **Bugünün planı:** Sayfa açıldığında o günün görevi (konu veya tekrar) öne çıkar, sonraki gün gösterilir.
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
