# ⚡ YEDAŞ Anomali ve Operasyonel Risk Dashboard

Bu proje, **Karadeniz bölgesindeki (Samsun, Ordu, Çorum, Amasya, Sinop)** elektrik abonelerinin anomali verilerini analiz ederek, saha ekiplerine **öncelikli müdahale planı** sunmak için geliştirildi.

---

## 🚀 Proje Amacı

- Anomali tiplerini sınıflandırmak (**Kaçak Akım, Arızalı Sayaç, Sayaç Müdahalesi vb.**)  
- Her tesisat için **0-5 ölçeğinde Risk Skoru** hesaplamak  
- **Kayıp-kaçağı azaltmak** ve operasyonel verimliliği artırmak  

---

## 🛠️ Teknik Özellikler

- **Veri Analizi:** Pandas & NumPy ile anomali tipleri istatistiksel olarak incelendi  
- **Risk Modelleme:** Dinamik formüller kullanılarak tesisat bazlı Risk Skorları oluşturuldu  
- **Coğrafi Görselleştirme:** Power BI Shape Map ile YEDAŞ hizmet bölgesi için **dinamik ısı haritası** (TopoJSON)  

---

## 📊 Dashboard Mimarisi

- **Bölgesel Yoğunluk:** Isı haritası ile riskin coğrafi dağılımı  
- **KPI Paneli:** Ortalama risk skoru ve kritik vaka sayıları  
- **Top 10 Müdahale Listesi:** En yüksek riskli tesisatlar, saha ekipleri için önceliklendirildi  

---

## 📌 Dashboard Kullanım Rehberi

- **Harita Etkileşimi:** İlçe seçildiğinde tüm dashboard o bölgeye özel filtrelenir  
- **Önceliklendirme:** `Risk_Skoru >= 4` olan tesisatlar **KRİTİK** olarak işaretlenir  
- **Filtreleme:** Anomali tipine göre hızlı odaklanma  
- **Görselleştirme:** Power BI üzerinden interaktif KPI, pie chart, table ve haritalar  
- **Harita Düzenleme:** Mapshaper ile GeoJSON → TopoJSON dönüşümü  

---

Bu dashboard, saha ekiplerinin **öncelikli müdahale noktalarını hızlıca görmesini** ve yönetim kararlarını desteklemesini sağlar.  
