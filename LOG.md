# Günlük Log

En yeni kayıt en üstte. Her gün 3 soru: **ne yaptım / ne takıldı / nasıl çözdüm.**

`Rehbersiz tekrar` alanı kritik: rehberli öğretici izlemek "anladım" yanılsaması yaratıyor. Aynı parçayı rehbersiz tekrar çizmeden gün kapanmış sayılmaz.

---

<!-- YENİ KAYITLARI BURAYA, BU SATIRIN ALTINA EKLE -->

## Hafta 1 — Sketch disiplini

### Gün 03 — 19.08.2026 (Çarşamba)

**Konu:** Dahili öğretici — `Temel Teknikler > 1. Ders — Parçalar` (Tutor1) · **Rehbersiz tekrar:** ❌ *(üçüncü güne devredildi)*

- **Ne yaptım:** 120×120×30 taban, Ø70 boss (25 mm), Ø50 delik, iki radyus unsuru (R5 ve R1,5) ve 2 mm kabuk ile Tutor1 parçasını modelledim. Ardından öğreticinin düzenleme bölümünü yaptım: taban derinliğini 30→50 değiştirdim, `Radyus1` içinden yüz öğesini silip kenar yarıçapını R10'a çıkardım, silinen yüz radyusunu **geri alma çubuğunu `Kabuk1`in üstüne çekerek** yeniden ekledim. Son olarak RealView ve Kromlu Paslanmaz Çelik malzemesi atadım. → [Ayrıntılı not](hafta-01-sketch/g03-tutor1/)
- **Ne takıldı:** Takılma olmadı.
- **Nasıl çözdüm:** —
- **Kalan soru işareti:** —

**Günün kavrayışı:** Geri alma çubuğu. Radyusu kabuktan sonra eklersem kabuk o bölgeyi kapsamıyor; çubuğu `Kabuk1`in üstüne çekip radyusu **geçmişe** eklediğimde kabuk yeniden hesaplanırken onu da içine alıyor. Unsur ağacı bir liste değil, bir işlem sırası — sıra değişirse sonuç değişir.

**İkinci kavrayış:** Bir radyus unsuru birden çok öğe taşıyabiliyor, ama birlikte değişmeyecek öğeleri aynı unsura koymak sonradan sorun çıkarıyor. `Radyus1` hem yüz hem kenar içerdiği için sadece kenarları değiştirmek üzere önce yüzü unsurdan silmem gerekti.

**Bulgu:** `Son Koşulu` için öğreticilerde üç ayrı Türkçe ifade kullanılıyor — `Tümü Boyunca`, `Her Şeyin İçinden`, `Hepsinin İçinden`. Üçü de aynı işi yapıyor (İngilizce `Through All`). Ayrı seçenekler değil, tutarsız çeviriler. Kesin doğrulama açılır listeye bakılarak yapılacak.

**Plan değişikliği:** Öğreticinin kendi yönlendirmesi, `AutoCAD ve SOLIDWORKS` bölümüne geçmeden önce Ders 1-2-3'ün sırayla tamamlanmasını söylüyor. Hafta 1 sırası buna göre güncellendi.

### Gün 02 — 18.08.2026 (Salı)

**Konu:** Dahili öğretici — `Başlarken > SOLIDWORKS'e Giriş > İlk Teknik Resmim` · **Rehbersiz tekrar:** ❌ *(ikinci güne devredildi)*

- **Ne yaptım:** Gün 1'de modellediğim `pressure_plate` parçasından teknik resim türettim. Üst görünüm (1:2, arka kenarlar gizli), A-A kesit görünümü, B detay görünümü ve gölgeli izometrik görünüm oluşturdum. Merkez işaretleri ve merkez çizgileri ekledim, dört çap ölçüsü yerleştirdim, ölçü metnini `6x` ve `THRU` ekleyerek düzenledim. → [Ayrıntılı not](hafta-01-sketch/g02-teknik-resim/)
- **Ne takıldı:** Takılma olmadı, öğretici adım adım yönlendirdi.
- **Nasıl çözdüm:** —
- **Kalan soru işareti:** Ölçüler iki ondalıklı çıktı (`Ø25.00`), referansta ondalık yok. `Birim Duyarlılığı = Hiçbiri` ayarı atlanmış. Detay B'deki üçüncü ölçü referanstan farklı (`12.00` yerine `R2` olmalı) — kontrol edilecek.

**Günün kavrayışı:** Teknik resim ayrı bir çizim değil, modelin türevi. Ölçü metnindeki `<MOD-DIAM>` bir değişken — `6x Ø27` yazdığımda 27 hâlâ modele bağlı kalıyor. AutoCAD'de görünümler elle çizilir ve model değişince hepsi elle güncellenir; burada bağ kurulduğu için güncelleme kendiliğinden oluyor.

**Devreden görev:** Rehbersiz tekrar iki gündür yapılmadı. Gün 1'in açık sorusu (`Son Koşulu` seçenekleri) da hâlâ cevapsız.

### Gün 01 — 17.08.2026 (Pazartesi)

**Konu:** Dahili öğretici — `Başlarken > SOLIDWORKS'e Giriş > İlk Parçam` (25 sayfa) · **Rehbersiz tekrar:** ❌ *(Gün 2'ye devredildi)*

- **Ne yaptım:** SOLIDWORKS 2025 SP1.2 kuruldu, dahili öğreticiler bulundu. `pressure_plate` parçası baştan sona modellendi: 9 unsurluk ağaç (Extrude ×3, Cut-Extrude ×2, Fillet ×3, CirPattern ×1) + silinen Delik Sihirbazı unsuru. Parça öğreticideki referansla birebir eşleşti. Belge ayarları MMGS / ANSI olarak yapılandırıldı. → [Ayrıntılı not ve ölçü tablosu](hafta-01-sketch/g01-pressure-plate/)
- **Ne takıldı:** Kayda değer bir takılma olmadı; öğretici adım adım yönlendirdi. Asıl mesele bu: rehberli akışta takılmamak, öğrendiğimin kanıtı değil.
- **Nasıl çözdüm:** —
- **Kalan soru işareti:** `Kör` / `Tümü Boyunca` / `Her Şeyin İçinden` arasındaki tercihin ne zaman hangi yönde yapılacağı. Öğretici ikisini de kullandı ama gerekçesini açıklamadı.

**Günün kavrayışı:** SolidWorks'te ölçü, çizimin kendisi değil modelin parametresi. Eşmerkezlilik ölçüyle değil ilişkiyle kuruldu — bu, AutoCAD'den taşınan "doğru koordinatı baştan gir" alışkanlığıyla doğrudan çelişiyor ve kırılması gereken ilk alışkanlık.

---

## Kayıt şablonu

```markdown
### Gün NN — GG.AA.YYYY (Gün adı)

**Süre:** Xs YYdk · **Konu:** [öğretici / alıştırma adı] · **Rehbersiz tekrar:** ✅ / ❌

- **Ne yaptım:**
- **Ne takıldı:**
- **Nasıl çözdüm:**
- **Kalan soru işareti:**
```
