# 📊 Tips Veri Seti ile Veri Analizi

Bu proje, `seaborn` kütüphanesinde yer alan `tips` veri seti kullanılarak temel veri analizi ve veri manipülasyonu uygulamalarını içermektedir. Analiz sürecinde `pandas` ve `seaborn` kütüphaneleri kullanılarak veriye genel bir bakış yapılmış, filtreleme, gruplama, sıralama ve yeni sütun oluşturma gibi işlemler gerçekleştirilmiştir.

## 🔧 Kullanılan Kütüphaneler

- pandas
- seaborn

## 📁 Veri Seti Hakkında

`tips` veri seti; restoran müşterilerine ait **toplam hesap (total_bill)**, **bahşiş (tip)**, **cinsiyet (sex)**, **sigara içme durumu (smoker)**, **gün (day)** ve **zaman (time)** gibi bilgileri içermektedir. Bahşiş oranlarının farklı müşteri özelliklerine göre değişimini analiz etmek için uygundur.

## 🔍 Yapılan Analizler

### 1. 📥 Veri Setinin Yüklenmesi ve İncelenmesi
- İlk 10 satır görüntülendi.
- Veri setinin boyutu, sütun bilgileri ve eksik değer kontrolü yapıldı.

### 2. 🔎 Filtreleme ve Seçim
- `total_bill` > 20 olan kayıtlar seçildi.
- Hem erkek hem sigara içen müşteriler filtrelendi.
- Belirli sütunlardan (`total_bill`, `tip`, `day`) yeni bir DataFrame oluşturuldu.

### 3. ➕ Yeni Sütun Oluşturma
- `tip_rate`: Bahşişin toplam hesaba oranı hesaplanarak yeni bir sütun oluşturuldu.

### 4. 📊 Gruplama ve Özetleme
- Sigara içme durumuna göre ortalama bahşişler hesaplandı.
- Gün ve zaman bilgisine göre ortalama harcamalar analiz edildi.

### 5. 📈 Değer Sayımı ve Oran Hesaplama
- En sık gelinen gün belirlendi.
- Cinsiyet oranları yüzde olarak hesaplandı.

### 6. 💾 Sonuçların Kaydedilmesi
- Güncellenmiş DataFrame, `tips_analiz.csv` olarak dışa aktarıldı.

## 📌 Amaç

Bu çalışma, temel veri analizi becerilerini geliştirmek ve pandas/seaborn gibi Python kütüphanelerini kullanarak gerçek veri setleri üzerinde pratik yapmak amacıyla gerçekleştirilmiştir.



---

