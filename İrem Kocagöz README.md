
# 📊 Power BI Proje 2 – README

**Hazırlayan:** İrem Kocagöz  
**Proje Adı:** Müşteri Satış Analizi – Power BI Raporu  
**Dosya Adı:** `İrem_Kocagoz_Proje2.pbix`  
**PDF Görselleştirme:** `İrem Kocagöz Proje 2.pdf`  

---

Projenin yüklü olduğu Drive linki:
https://drive.google.com/drive/folders/1b4Bnvi38cnsJVP3xVB5qpR_l_aGO8fQF?usp=sharing

---

## 📌 Proje Amacı
Bu projede, satış verileri kullanılarak üç farklı perspektiften veri analizi yapılmıştır. Amaç, müşteri davranışlarını, bölgesel dağılımları ve ürün kategorilerine göre ciro dağılımını görselleştirerek karar destek sürecine katkı sağlamaktır.

---

## 📁 Kullanılan Veriler
- `users.csv` → Kullanıcı bilgileri  
- `orders.csv` → Sipariş bilgileri  
- `orderdetail.csv` → Sipariş detayları  
- `items.csv` → Ürün bilgileri  
- `adres.csv` → Kullanıcı adres bilgileri  
- `bölgeler.csv` → Şehir-bölge eşleşmeleri

---

## 🧱 Veri Hazırlama Adımları
1. Tablolar Power BI’a yüklendi, adları Türkçeleştirildi.
2. DAX fonksiyonları ile yaş, yaş grubu, cinsiyet gibi yeni sütunlar oluşturuldu.
3. Gereksiz sütunlar gizlendi veya kaldırıldı.
4. İlişkiler:
   - `sipariş.userID` → `kullanıcılar.ID`  
   - `sipariş.addressID` → `adres.ID`  
   - `siparişdetay.orderID` → `sipariş.ID`  
   - `siparişdetay.itemID` → `ürünler.ID`  
   - `adres.city` → `bölgeler.il`

---

## 📊 Rapor Sayfaları ve İçerikler

### 🔹 Giriş Sayfası
Kullanıcının, raporun üç perspektifi arasında geçiş yapabileceği butonlar içerir.

### 🔸 Özet Sayfa (1-2)
- Toplam Satış Tutarı, Sipariş Sayısı, Müşteri Sayısı, Ortalama Sipariş Tutarı (Kartlar)
- Haftasonu/Haftaiçi satış karşılaştırma grafiği  
- Bölgelere göre toplam satış adedi  
- Saatlik satış tutarı  

### 🔸 Müşteri Perspektifi (1-2)
- Tekil müşteri, kadın, erkek sayısı (Kartlar)
- Bölgelere göre müşteri dağılımı (Sütun Grafik)
- İstanbul’daki en yüksek cirolu 10 müşteri (Tablo)
- Yaş grubuna göre toplam ciro (Bar Grafik)

### 🔸 Kategori Perspektifi
- İstanbul’da ve “genç” yaş grubunda olan müşterilerin toplam cirosu  
- Görselleştirme: **Ağaç Haritası**, ana kategoriye göre

---

## 📱 Mobil Uyum
- Power BI mobil görünüm tasarımı özelleştirildi.
- Sayfalardaki en önemli görseller mobil uyumlu hale getirildi.

---

## 📤 Teslimat İçeriği
- `.pbix` dosyası (rapor dosyası)
- `.pdf` dosyası (rapor ekran görüntüleri)
- `README.md` dosyası (açıklamalar)

---

## ✨ Ekstra Özellikler
- Filtreler: İstanbul ve yaş grubu (özelleştirilmiş görselleştirme için)
- Dinamik geçişler için sayfa yönlendirmeleri ve butonlar eklendi.


## 📷 Proje Ekran Görüntüleri

### 📌 Giriş Sayfası
![📌 Giriş Sayfası](./giris.png)

### 📊 Özet Sayfa 1
![📊 Özet Sayfa 1](./ozet1.png)

### 📊 Özet Sayfa 2
![📊 Özet Sayfa 2](./ozet2.png)

### 👤 Müşteri Perspektifi 1
![👤 Müşteri Perspektifi 1](./musteri1.png)

### 👤 Müşteri Perspektifi 2
![👤 Müşteri Perspektifi 2](./musteri2.png)

### 📦 Kategori Perspektifi
![📦 Kategori Perspektifi](./kategori.png)
