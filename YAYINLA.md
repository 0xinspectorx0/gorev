# 🚀 GitHub Yayını — Durum

**Repo:** <https://github.com/0xinspectorx0/gorev>  
**Kod:** push edildi ✅ (branch `main`, 4 dosya)

## Kalan tek adım: GitHub Pages'i açmak

Token'ın yetkisi kod yazmaya yettiği için dosyalar yüklendi, ancak **Pages ayarını API'den açma izni yok**. 10 saniyelik manuel işlem:

1. <https://github.com/0xinspectorx0/gorev/settings/pages> adresine git
2. **Source:** `Deploy from a branch`
3. **Branch:** `main` — klasör: `/ (root)` → **Save**

1–2 dakika sonra site yayında olur:

```
https://0xinspectorx0.github.io/gorev/
```

---

## Sonraki güncellemeler

```bash
cd /home/user
git add -A
git commit -m "değişiklik"
git push
```

Pages her push'ta otomatik yenilenir (30–60 sn).

## Notlar

- **Token izinleri:** mevcut token yalnızca *Contents: Read and write* veriyor. Pages/Workflow ayarları için yeni bir token'a **Pages: Read and write**, **Administration: Read and write**, **Workflows: Read and write** eklemen gerekir.
- **Otomatik deploy:** `workflow` yetkisi olan bir token ile `.github/workflows/pages.yml` eklenebilir; o zaman Pages her push'ta Actions ile de yayınlanır.
- **İlerleme verisi** tarayıcının `localStorage`'ında tutulur; yayını güncellesen de kullanıcı kayıtları silinmez.
