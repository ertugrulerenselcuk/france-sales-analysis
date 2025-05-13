# france-sales-analysis
Excel ile Fransa satış verisi analizi – Online Retail Dataset
# 📊 Fransa Satış Analizi – Excel ile Online Retail Veriseti

Bu proje, Online Retail veri seti kullanılarak Fransa'daki satışların Excel ile analiz edilmesini kapsamaktadır. Analiz sürecinde Excel’in temel ve ileri düzey fonksiyonları kullanılarak müşteri davranışları, satış hacmi ve ürün performansları değerlendirilmiştir.

---

## 🗂️ Veri Seti Bilgisi

- **Veri Kaynağı:** UCI Machine Learning Repository – Online Retail Dataset
- **Tarih Aralığı:** 1 Aralık 2010
- **Odak Ülke:** Fransa
- **Kolonlar:** Invoice, StockCode, Description, Quantity, InvoiceDate, Price, Customer ID, Country

---

## 🎯 Yapılan Hesaplamalar

| Metrik                                  | Değer             |
|----------------------------------------|-------------------|
| **Toplam Ciro**                        | 197,421.90 €      |
| **Farklı Müşteri Sayısı**             | 87 kişi           |
| **Kişi Başı Ortalama Ciro**           | 2,269.21 €        |
| **Kişi Başı Ortalama Satın Alma Adedi** | 5.30 ürün         |
| **CV (Değişim Katsayısı - Adet)**     | 1.66              |
| **CV (Fiyat)**                         | 5.08              |
| **CV (Revenue)**                       | 23.06             |
| **En Yüksek Günlük Ciro**             | 138 € (örnek)     |

---

## ✅ Kullanılan Excel Fonksiyonları

```excel
SUMIFS
COUNTIFS
AVERAGE
STDEV
RANK
IF
TRIM
WEEKDAY
LEFT, RIGHT, MID
CONCATENATE
UNIQUE

Veride sadece Fransa verileri filtrelenerek analiz edilmiştir.

Ortalama alışveriş hacmi yüksek olan müşteriler satışların büyük kısmını oluşturmaktadır.

Değişim katsayısı (CV) bazı metriklerde oldukça yüksektir, bu da verinin dağınık ve oynak olduğunu gösterir.

