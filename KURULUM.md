# Repo Kurulumu (tek seferlik)

## 1. GitHub'da repo aç
github.com → New repository
- **Ad:** `solidworks-ogrenme-sureci`
- **Görünürlük:** Public
- README / .gitignore / license ekleme (bu klasörde zaten var)

## 2. Yerelde bağla
Bu klasörü bilgisayarında istediğin yere koy, sonra terminalde:

```bash
cd solidworks-ogrenme-sureci
git init
git add .
git commit -m "Repo iskeleti: haftalık yapı, log şablonu, DfAM notları"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADIN/solidworks-ogrenme-sureci.git
git push -u origin main
```

## 3. Günlük akış
Her akşam, çalışma bitince:

```bash
git add .
git commit -m "Gün 03: Ders 1 Parçalar tamamlandı, rehbersiz tekrar yapıldı"
git push
```

**Commit mesajı kuralı:** `Gün NN: [ne yapıldı]` — kısa, somut, "güncelleme" gibi boş mesaj yok.

---

## CAD dosyaları hakkında kritik uyarı

`.SLDPRT` / `.SLDASM` **binary** dosyalardır. Git bunları satır satır karşılaştıramaz; her kayıtta dosyanın **tamamının yeni bir kopyası** repoya eklenir. Aynı parçanın 20 ara sürümünü commit edersen repo şişer ve geri dönüşü olmaz.

**Kural:**
- Sadece **tamamlanmış** alıştırmanın native dosyasını commit et
- Yanına aynı isimde bir `.png` ekran görüntüsü koy (GitHub'da SLDPRT önizlenmez, PNG önizlenir)
- Başkasının açması gerekecekse ayrıca `.STEP` çıkar
- Ara denemeleri commit etme
- Repo 200 MB'ı geçerse Git LFS'e geç

**Dosya adlandırma:** `g03-flanş-plaka.SLDPRT`, `g03-flanş-plaka.png` — gün numarası önde, Türkçe karakter kullanma (`flans-plaka` daha güvenli).
