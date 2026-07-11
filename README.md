# Enerji Perakende Veri Analizi ve Müşteri Davranış Modellemesi

Bu proje, Ahmet Çalık Vakfı İleri Veri Analitiği Eğitimi kapsamında Çalık Enerji Yapay Zeka ve Model Mühendisliği Ekibi tarafından hazırlanan vaka çalışması (Case Study 2) çözümlerini içermektedir. Projede Amasya iline bağlı Hamamözü, Gümüşhacıköy ve Göynücek ilçelerinin elektrik tüketim, faturalandırma ve tahsilat verileri Pandas, NumPy, Matplotlib ve Seaborn kütüphaneleri kullanılarak analiz edilmiştir.

## Proje Yapısı
* **Data/**: Analizde kullanılan ham ve işlenmiş veri setleri.
* **Notebook/**: Adım adım analiz süreçlerini içeren Jupyter notebook dosyaları.
  * `notebook_01_veri_kesfi.ipynb`: Veri yükleme, tanımlayıcı istatistikler ve veri kalitesi kontrolleri.
  * `notebook_02_gorsellestirme.ipynb`: Mevsimsel trendler, dağılımlar ve subplot karşılaştırma grafikleri.
  * `notebook_03_veri_hikayesi.ipynb`: Hipotez testleri, müşteri segmentasyonu ve tahsilat performans/risk analizleri.
* **Outputs/Figures/**: Notebooklar tarafından otomatik olarak dışarı aktarılan analiz grafikleri.

## Temel Bulgular ve İş Önerileri
1. **İlçe Tüketim Farklılıkları**: Hamamözü'nün yaz aylarında bile düşük tüketim göstermesinin kök nedeni, ilçenin neredeyse tamamen konut (Mesken) ağırlıklı bir abone profiline sahip olmasıdır. Gümüşhacıköy ve Göynücek'te ise yaz aylarında tarımsal sulama ve ticari/sanayi faaliyetlerden dolayı mevsimsel olarak devasa bir tüketim artışı gözlenmiştir.
2. **Nakit Akışı ve Risk Yönetimi**: Fatura ödemelerinin genel olarak %27.2'sinin geç yapıldığı gözlenmiştir. Şantiye ve dönemsel tarımsal abonelerin ödeme risk oranı daha yüksek çıktığından, bu segmentlere özel erken hatırlatma sistemleri (SMS/E-posta) ve tahsilat optimizasyon süreçleri önerilmiştir.