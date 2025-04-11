# 🎬 Netflix Data Analysis

Bu proje, Netflix'teki içerikleri analiz ederek içerik türleri, hedef yaş grupları, ülke dağılımları ve izlenme süresi gibi önemli bilgilere ulaşmayı amaçlamaktadır.

## 📌 Proje Amacı

- Netflix'e yıllar içinde ne kadar içerik eklendiğini görmek
- Dizi ve film oranlarını karşılaştırmak
- İçeriklerin ülkelere göre dağılımını analiz etmek
- Hedeflenen yaş gruplarını ortaya çıkarmak
- Dizi sezon sayılarına göre uzunlukları incelemek
- Uzun süren dizilerin türlerini belirlemek

## 📊 Yapılan Analizler

- 📅 Yıllara göre içerik artışı
- 🎥 Dizi vs Film oranı
- 🌍 Ülkelere göre içerik sayısı
- 🧒👵 Hedeflenen yaş grupları
- 🕒 Ortalama süre analizi
- 📈 Uzun dizilerin tür analizi

## 🧼 Veri Temizleme ve Dönüştürme

- Eksik veriler dolduruldu (`cast`, `director`, `rating`)
- `rating` sütunundaki süre değerleri düzeltildi
- Feature engineering ile yeni sütun oluşturularak rating gruplara ayrıldı (örneğin: `General`, `Teen`, `Mature`)

## 🔗 Veri Seti Kaynağı

📂 [Kaggle - Netflix Shows Dataset by Shivam Bansal](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## 🚀 Başlamak İçin

```bash
git clone https://github.com/kullanici_adin/netflix-data-analysis.git
cd netflix-data-analysis
pip install -r requirements.txt  # (opsiyonel)
jupyter notebook

