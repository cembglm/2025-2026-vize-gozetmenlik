# 📗 Final Gözetmenlik Arama Sistemi

Bahar 2025-2026 vize sınavı gözetmenlik görevlendirmelerini kolayca aramak için geliştirilmiş bir **Streamlit** uygulamasıdır.

🔗 **Live Demo:** [Streamlit Cloud](https://2025-2026-vize-gozetmenlik.streamlit.app)

## 🎯 Özellikler

- ✅ **Hızlı Arama**: İsim-soyisim ile gözetmen görevlendirmesi bulma
- 📆 **Takvim Görünümü**: Saat x Tarih+Gün matrisi şeklinde sınav takvimi
- 📋 **Detaylı Liste**: Tüm sınav bilgilerinin tablolaşmış görsünü
- 📊 **İstatistikler**: Toplam sınav sayısı, farklı ders, farklı gün bilgileri
- 🔤 **Türkçe Karakter Desteği**: Ş, İ, Ç, Ğ, Ü, Ö karakterleri tam destek
- 📱 **Responsive İnterfeys**: Bilgisayar ve mobil cihazlarda uyumlu

## 📊 Veri Kaynağı

- **Dosya**: `25-26_Bahar_Vize.xlsx`
- **Sheet**: OİS Listesi
- **Sütunlar**: Ders Kodu, Section, Sınav Tipi, Sınıf, Tarih, Başlangıç Saat, Bitiş Saat, Gözetmen 1-4

## 🚀 Kurulum

### Gereksinimler
- Python 3.8+
- pip

### Adımlar

```bash
# Depoyu klonla
git clone https://github.com/cembglm/2025-2026-vize-gozetmenlik.git
cd 2025-2026-vize-gozetmenlik

# Bağımlılıkları kur
pip install -r requirements.txt
```

## ▶️ Çalıştırma

### Lokal Olarak
```bash
streamlit run final.py
```

Tarayıcı otomatik olarak `http://localhost:8501` adresinde açılacaktır.

### Streamlit Cloud'da Deploy Etme

1. GitHub'a push et
2. [Streamlit Cloud](https://streamlit.io/cloud) adresine git
3. Repoyu bağla ve deploy et

## 📝 Kullanım

1. Sayfada "Aranan İsim-Soyisim:" alanına gözetmen adını yazın
2. **Ara** butonuna tıklayın veya Enter tuşuna basın
3. Sonuçları gözlemleyin:
   - **Takvim Görünümü**: Hangi saatlerde sınav var
   - **Detaylı Liste**: Tüm sınav bilgileri (Ders, Salon, Section vb.)
   - **İstatistikler**: Özet bilgiler

## ⚠️ Önemli Not

Bu sistem demo amaçlıdır. Lütfen görevlendirme bilgilerinizi **resmi listelerden** kontrol ediniz.

## 📄 Lisans

MIT License

## 👨‍💻 Geliştirici

Cem Belgüm
