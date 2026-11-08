# 📚 KPSS Lisans Ders Çalışma Takvimi

KPSS Lisans hazırlığı için **Tarih, Coğrafya ve Vatandaşlık** derslerini gün gün planlayan, tek dosyalık (bağımlılıksız) bir çalışma takvimi web uygulaması.

## ✨ Özellikler

- **Sekmeler:** Tarih / Coğrafya / Vatandaşlık — tıkladığın ders açılır, tema rengi de o derse göre değişir.
- **Her güne 1 konu:** Takvimdeki her gün için tek bir ana konu (hazır müfredat + kendi ekledikleriniz). Tarih 62 konu / 71 gün, Coğrafya 43 / 49, Vatandaşlık 54 / 62.
- **Tekrar + Soru görevi:** Her güne ayrıca bir *Tekrar + Soru* görevi eklenir.
- **Ünite sonu tekrar günü:** Her konu başlığının (ünitenin) bitiminde **1 tam gün “Tekrar + Soru”** eklenir, sonra yeni üniteye geçilir. Örnek: `İslamiyet Öncesi Türk Tarihi (9 gün) → 🔁 Tekrar + Soru (1 gün) → İlk Türk-İslam Devletleri (6 gün) …`
- **Bugünün planı:** Sayfa açıldığında o günün konusu ve görevi öne çıkar.
- **İlerleme takibi:** Yapılan konular/görevler tarayıcıda (localStorage) saklanır; istatistik ve ilerleme çubuğu güncellenir. Eklediğin konular ve sıralaman da kalıcıdır; ilerleme artık **konuya** bağlıdır, taşıyınca kaybolmaz.
- **Başlangıç tarihi seçimi:** Takvim başlangıç tarihine göre yeniden hesaplanır.
- **＋ Konu ekle:** Kendi konunu ekle — ad, ünite ve **tarih** seç; konu o güne yerleşir, sonrakiler bir gün kayar.
- **Sürükle-bırak:** Takvimde konu kartını istediğin güne bırak; sıra ve tüm tarihler otomatik yeniden hesaplanır. Aynı günün *Tekrar + Soru* görevi de konuyla birlikte taşınır.
- **↑ / ↓ / 📅:** Liste görünümünde bir gün öne-geri alma ve istediğin tarihe taşıma (mobil dostu).
- **Düzenle / sil:** Eklediğin konuları ✏️ ile yeniden adlandır, ünitesini/tarihini değiştir veya sil.
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
