# **Kredi Kartı Müşteri Analizi**

## 📌 **Proje Hakkında**

Bu proje, bankanın kredi kartı departmanı için **müşteri davranışlarını analiz ederek stratejik öneriler geliştirmeyi** hedeflemektedir. Analiz, **10.000+ kredi kartı müşterisine ait demografik, finansal ve işlem verileri** kullanılarak gerçekleştirilmiştir.

Projenin amacı, yönetim kuruluna sunulacak **görsel raporlar ve veri odaklı karar destekleri** üretmektir.

---

## 🛠 **Kullanılan Yöntemler ve Araçlar**

### 1. **Veri Hazırlığı**
- Veri setindeki eksik ve hatalı değerler temizlendi.  
- Analizde kullanılan temel değişkenler:  
  - **Age_Group** – Müşteri yaş grubu  
  - **Customer_Tenure** – Banka ile ilişki süresi  
  - **Income_Rank / Income_Level** – Gelir sıralaması ve seviyesi  
  - **Credit_Usage_Level** – Kart kullanım düzeyi  
  - **Monthly_Spend** – Aylık harcama  
  - **Avg_Trans** – Ortalama işlem tutarı  
  - **Trans_per_Month** – Aylık işlem sayısı  
  - **Activity_Status** – Müşteri aktiflik durumu  
  - **Revolver_Flag** – Devreden borç durumu  
  - **Contact_Intensity** – Banka ile iletişim sıklığı  
  - **Loyalty_Tier** – Sadakat seviyesi  

- Bu değişkenler üzerinden özet istatistikler ve pivot tablolar oluşturularak:  
  - **Ortalama İşlem Tutarı (Avg_Trans)**  
  - **Ortalama Aylık Harcama (Monthly_Spend)**  
  - **Aktif Müşteri Sayısı (Active_Customers)**  
  - **Ortalama Kredi Limiti (Credit_Limit)**  
  gibi metrikler hesaplandı.  

### 2. **Data Table ve Hedef Analizleri**
**Limit Artışı ve İşlem Hacmi Simülasyonu:**  
- Farklı kredi limiti seviyelerinde toplam işlem hacminin nasıl değiştiği hesaplandı.  
- Excel’in **Data Table** özelliği ile otomatik hesaplamalar yapıldı.  

**Hedef İşlem Hacmi Analizi:**  
- Mevcut ortalama işlem tutarı ve aylık harcama üzerinden, hedef toplam işlem hacmi için gerekli müşteri sayısı belirlendi.  

### 3. **Makro Kullanımı**
- Dashboard sayfasına **“Kaydet ve Güncelle”** makrosu eklendi.  
- Tek tuşla tüm hesaplamalar güncelleniyor ve dosya kaydediliyor.  
- Bu sayede manuel tekrar ve hata riski ortadan kaldırıldı.  

### 4. **Dashboard ve Görselleştirme**
- Analiz sonuçları için **grafikler ve tablolar** oluşturuldu.  
- Dashboard üzerinde, kullanıcı dostu arayüz ile **işlem hacmi ve tahmini değerler** kolayca izlenebiliyor.  

---

## 💡 **Öne Çıkan Analizler**
- **Limit Artışı Simülasyonu:** Kredi limiti artırıldığında işlem hacminin artışı açıkça görülebilir.  
- **Hedef İşlem Hacmi:** Goal Seek ile gerekli müşteri sayısı belirlenmiş ve raporlanmıştır.  
- **Makro ile Otomasyon:** Tek tuşla tüm hesaplamalar güncellenip kaydedilebilmektedir.
