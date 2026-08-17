# DfAM ve Tolerans Kuralları (FDM / Bambu P2S)

*Bunlar başlangıç değerleridir. Hafta 4'teki tolerans testinden sonra kendi ölçülmüş değerlerimle güncellenecek.*

## Boyutsal doğruluk
- Küçük detaylarda: ±0,2 mm
- 100 mm üzeri parçalarda: uzunluğun ±%0,3'ü
- **Eğilim:** Dış ölçüler nominalden büyük, delikler nominalden küçük çıkar.

## Geçme boşlukları (yüzey başına, başlangıç değerleri)
| Geçme tipi | Boşluk |
|---|---|
| Serbest / kayan geçme | 0,2 – 0,3 mm |
| Sıkı ama sökülebilir | 0,1 – 0,15 mm |
| Pres geçme | 0,1 – 0,15 mm **sıkılık** (negatif boşluk) |

> ISO 286 (H7/g6 vb.) talaşlı imalat hassasiyeti varsayar; FDM'de doğrudan uygulanamaz.

## Geometri kuralları
- **Duvar kalınlığı:** 0,4 mm nozzle'ın katı olmalı → 0,8 / 1,2 / 1,6 mm
- **45° kuralı:** 45°'den dik çıkıntılar destek ister. Tasarımı destek gerektirmeyecek şekilde yönlendir.
- **Köşeler:** İç köşelere fillet koy — gerilim yığılmasını azaltır, baskıda köşe kalitesini artırır
- **Delikler:** Dikey delikler daima küçük çıkar; kritikse tasarımda büyüt veya sonradan raybala
- **Köprüler:** 5 mm altı köprüler destek olmadan basılabilir

## Anizotropi — en kritik başlık
Katmanlar arası (Z ekseni) dayanım, katman içi (X-Y) dayanımın **yaklaşık yarısı**.

Gripper parmakları için sonuç: **kavrama kuvvetinin yönü katman düzlemine paralel olmalı.** Parça oryantasyonu tasarımın parçasıdır, dilimleme aşamasında verilecek bir karar değil.

## Dosya çıktısı
- **3MF tercih edilir** (birim, renk, meta veri taşır)
- STL kullanılacaksa çözünürlük **Fine**
- Dilimleyici: Bambu Studio
