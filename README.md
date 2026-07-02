# ❤️ Kalp Hastalığı Risk Tahmin Projesi

Bu proje, makine öğrenmesi algoritmaları kullanılarak bireylerin klinik ve demografik verilerine dayanarak kalp hastalığı taşıma risklerini önceden tahmin etmeyi amaçlayan bir veri bilimi çalışmasıdır.

Özellikle erken teşhisin hayati önem taşıdığı sağlık sektöründe, veriye dayalı karar destek sistemlerinin nasıl kurgulanabileceğini göstermek amacıyla geliştirilmiştir.

---

## 📂 Proje İçeriği ve Dosya Yapısı

Proje reposunda yer alan temel bileşenler şunlardır:

* **`kalp_hastaligi_risk_tahmin_projesi.zip`**: Veri ön işleme, model eğitimi ve tahminleme adımlarını içeren ana Python kodlarını ve Jupyter Notebook dosyalarını barındırır.
* **`archive.zip`**: Makine öğrenmesi modelinin eğitilmesi ve test edilmesi için kullanılan, klinik özellikleri (yaş, cinsiyet, kan basıncı, kolesterol vb.) içeren ham veri setidir.
* **`Ilhan_Yigit_Kocadere_Kalp_Hastaligi_Risk_Tahmin_Poster_50x70.pdf`**: Projenin çıkış noktasını, kullanılan metodolojiyi, veri görselleştirmelerini ve elde edilen model başarı oranlarını özetleyen 50x70 cm boyutundaki akademik sunum posteridir.

---

## 🚀 Kullanılan Teknolojiler ve Kütüphaneler

Veri bilimi ve makine öğrenmesi süreçleri için endüstri standardı Python kütüphaneleri kullanılmıştır:

* **Dil:** Python 3.x
* **Veri Analizi & Manipülasyon:** Pandas, NumPy
* **Makine Öğrenmesi & Modelleme:** Scikit-Learn (Sınıflandırma algoritmaları, metrik hesaplamaları)
* **Görselleştirme:** Matplotlib, Seaborn

---

## 📈 Metodoloji ve İşlem Adımları

Proje geliştirilirken aşağıdaki standart Veri Bilimi yaşam döngüsü takip edilmiştir:

1. **Veri Ön İşleme (Data Preprocessing):** `archive.zip` içerisindeki veri seti içe aktarılmış; eksik değerler (missing values) ve aykırı değerler (outliers) temizlenerek model için uygun formata getirilmiştir.
2. **Keşifsel Veri Analizi (EDA):** Özellikler arasındaki korelasyonlar, hedef değişken (kalp hastalığı var/yok) ile ilişkiler çeşitli grafiklerle analiz edilmiştir.
3. **Model Eğitimi (Model Training):** Veri seti Eğitim (Train) ve Test setlerine ayrılmıştır. Karar Ağaçları (Decision Trees), Lojistik Regresyon (Logistic Regression) veya Rastgele Orman (Random Forest) gibi çeşitli sınıflandırma modelleri eğitilmiştir.
4. **Değerlendirme (Evaluation):** Doğruluk (Accuracy), Kesinlik (Precision) ve Duyarlılık (Recall) gibi sınıflandırma metrikleriyle modellerin performansı ölçülmüş, en yüksek başarıyı veren model seçilmiştir.

---

## 📋 Akademik Poster Sunumu

Depoda yer alan PDF formatındaki poster, projenin sadece teknik bir kod yığınından ibaret olmadığını, aynı zamanda akademik sunum teknikleriyle ifade edilebildiğini gösterir. Modellerin başarı grafikleri ve projenin sağlık sektörüne potansiyel katkıları poster içerisinde detaylandırılmıştır.

---

## 👨‍💻 Geliştirici

**İlhan Yiğit Kocadere**  
*Kapadokya Üniversitesi - Yönetim Bilişim Sistemleri (MIS) Öğrencisi*  
- [LinkedIn Profilim](https://linkedin.com/in/linkedin-kullanici-adiniz) *(Kendi linkini eklemeyi unutma)*
- [GitHub Profilim](https://github.com/github-kullanici-adiniz)
