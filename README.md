# COVID-19 Pandemi Analizi – İş Zekâsı Projesi

## Proje Hakkında
Bu proje, 36 OECD ve Avrupa Birliği ülkesinin COVID-19 pandemi sürecini iş zekâsı teknikleri kullanarak analiz etmek amacıyla geliştirilmiştir. Çalışma kapsamında ülkelerin ekonomik güçleri, sağlık altyapıları, demografik yapıları ve pandemi performansları arasındaki ilişkiler incelenmiştir.

Analiz süreci, akademik bir çalışmayı temel alarak güncel veri setleriyle yeniden modellenmiş ve Power BI dashboardları üzerinden görselleştirilmiştir.

---

## Amaç
Projenin temel hedefleri:
- Ülkelerin pandemi başarısını etkileyen faktörleri belirlemek
- Ekonomik güç ile sağlık sonuçları arasındaki ilişkiyi incelemek
- Demografik yapıların risk üzerindeki etkisini analiz etmek
- Veriyi görselleştirerek karar destek bilgisine dönüştürmek

---

## Kullanılan Teknolojiler
- Microsoft Power BI
- Power Query (M Dili)
- DAX (Data Analysis Expressions)
- Veri modelleme (Star Schema)
- Veri görselleştirme teknikleri

---

## Veri Seti
Veriler **Our World in Data COVID-19 dataset** üzerinden alınmış ve analiz için düzenlenmiştir.

Hazırlık adımları:
- Gereksiz sütunların kaldırılması
- Veri tiplerinin dönüştürülmesi
- 36 ülke filtresi uygulanması
- Türkçe kolon isimlendirmesi

---

## Analiz Yaklaşımı
Projede kullanılan analiz türleri:
- Mekânsal analiz (harita görselleri)
- Karşılaştırmalı analiz (grafikler)
- Korelasyon analizi (scatter chart)
- Zaman serisi analizi
- Kümeleme analizi

---

## Dashboard Sayfaları
Proje 5 ana analiz sayfasından oluşmaktadır:

**1. Genel Pandemi Görünümü**
- Toplam vaka ve ölüm KPI’ları
- Küresel harita dağılımı

**2. Kapasite Analizi**
- GSYH karşılaştırmaları
- Hastane yatak kapasitesi analizi

**3. Yayılım Analizi**
- Zaman serisi grafikler
- Ülke bazlı vaka dağılımı

**4. Risk Faktörleri**
- GSYH – Yaşam beklentisi ilişkisi
- Nüfus yoğunluğu etkisi

**5. En Çok Etkilenen Ülkeler**
- İlk 5 ülke karşılaştırması
- Demografik ve ekonomik analiz

---

## Veri Modeli
Projede performans ve analiz doğruluğu için **Yıldız Şeması (Star Schema)** veri modeli kullanılmıştır.

Model yapısı:
- Olay tablosu → Covid ölçümleri
- Boyut tabloları → Ülke ve tarih bilgileri
- İlişki yapısı → 1-çok ilişkisel model

---

## Öne Çıkan Bulgular
- Ekonomik gücü yüksek ülkeler her zaman düşük ölüm oranına sahip değildir.
- Yaşlı nüfus oranı yüksek ülkelerde risk artmaktadır.
- Nüfus yoğunluğu arttıkça yayılım hızı yükselmektedir.
- Güçlü sağlık altyapısı ölüm oranlarını azaltmada etkilidir.

---

## 📚 Kaynakça
- Demircioğlu & Eşiyok (2020) – COVID-19 Kümeleme Analizi Çalışması
- Our World in Data – COVID-19 Dataset
- İş Zekâsı literatürü
