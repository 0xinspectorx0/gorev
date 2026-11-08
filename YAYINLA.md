# 🚀 GitHub'a Yayınlama — Adım Adım

Repo bu klasörde **hazır ve commit edilmiş** durumda. Aşağıdaki iki yoldan birini seç.

---

## Yol 1 — Terminalden push (önerilen, 3 dakika)

### 1) GitHub'da boş bir repo aç
<https://github.com/new> → Repository name: `kpss-calisma-takvimi`
→ **Public** seç → *"Add a README file"* işaretini **boş bırak** → **Create repository**

### 2) Kişisel erişim anahtarı (PAT) al
<https://github.com/settings/tokens> → **Generate new token (classic)**
→ Scope: **`repo`** işaretle → Generate → çıkan `ghp_...` değerini kopyala.
(Fine-grained token kullanırsan: repo **Contents = Read and write** ve **Workflows = Read and write**.)
Not: GitHub artık şifreyle push kabul etmiyor, token şart.

### 3) Bu klasörde push et
Kendi kullanıcı adını yaz:

```bash
cd /home/user

git remote add origin https://github.com/KULLANICI_ADI/kpss-calisma-takvimi.git
git branch -M main
git push -u origin main
```

Şifre sorulduğunda **şifreyi değil, PAT'ı** yapıştır.

### 4) GitHub Pages'i aç
Repo → **Settings → Pages**
→ Source: **Deploy from a branch**
→ Branch: **`main`** / klasör: **`/ (root)`** → **Save**

1–2 dakika sonra site yayında:

```
https://KULLANICI_ADI.github.io/kpss-calisma-takvimi/
```

---

## Yol 2 — Terminal kullanmadan (tarayıcıdan yükleme)

1. <https://github.com/new> ile boş repo aç (`kpss-calisma-takvimi`, Public).
2. Repo sayfasında **"uploading an existing file"** linkine tıkla.
3. Şu 4 dosyayı sürükle bırak: `index.html`, `README.md`, `LICENSE`, `.gitignore`
   (`.gitignore` gizli dosyadır; klasörü sürüklerken gelebilir — gelmezse sorun değil.)
4. **Commit changes** → sonra **Settings → Pages → main / (root) → Save**.
5. Site adresi: `https://KULLANICI_ADI.github.io/kpss-calisma-takvimi/`

---

## Sonraki güncellemeler

Dosyayı değiştirdikten sonra:

```bash
cd /home/user
git add -A
git commit -m "değişiklik açıklaması"
git push
```

Pages her push'ta otomatik yenilenir (30–60 sn).

---

## İpuçları

- **Kendi alan adın:** repo adını `KULLANICI_ADI.github.io` yaparsan site kök adreste (`https://KULLANICI_ADI.github.io/`) açılır.
- **Gizli tutmak istersen:** repo'yu Private yaparsan Pages için GitHub Pro gerekir (ücretsiz planda Pages yalnızca Public repolarda).
- **İlerleme verisi** tarayıcının `localStorage`'ında tutulur; siteyi güncelleyip yayınlasan bile kullanıcıların kaydı silinmez.
- Push sırasında `remote origin already exists` hatası alırsan: `git remote set-url origin https://github.com/KULLANICI_ADI/kpss-calisma-takvimi.git`
