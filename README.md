**Havalimanı Yolcu Memnuniyeti Analizi Projesi**

Bu proje, bir havayolu şirketinin yolcu memnuniyetini anlamak ve etkileyen faktörleri belirlemek için müşteri verileri üzerinde kapsamlı veri işleme ve keşifsel veri analizi (EDA) yapmayı amaçlamaktadır. Proje kapsamında, gelecekteki makine öğrenimi modellemeleri için bir temel oluşturulmaktadır.

İçindekiler

- Proje Tanımı

- Veri Seti

- Kurulum

- Kullanım

- Analiz ve Bulgular

- Sonraki Adımlar

Proje Tanımı

Bu projenin temel amacı, yolcuların belirli hizmet ve deneyimlerine dayanarak havayolu memnuniyetini etkileyen temel faktörleri keşfetmektir. Elde edilen bulgular, havayolu şirketinin hizmet kalitesini artırmasına ve müşteri memnuniyetsizliğine yol açan faktörleri belirlemesine yardımcı olabilir. 

Proje aşağıdaki adımları içermektedir:

Veri Yükleme ve Ön İşleme: Eksik değerlerin ele alınması, veri tiplerinin dönüştürülmesi ve yeni özelliklerin oluşturulması.

Keşifsel Veri Analizi (EDA): Veri setinin yapısını anlamak, önemli ilişkileri ve anormallikleri görselleştirmek.

Veri Seti

Kullanılan veri seti, havayolu yolcularının geri bildirimlerini içeren anket sonuçlarından oluşmaktadır. 

Veri seti aşağıdaki gibi sütunları içermektedir:

- Gender: Yolcuların cinsiyeti (Kadın, Erkek)

- Customer Type: Müşteri tipi (Sadık Müşteri, Sadık Olmayan Müşteri)

- Age: Yolcuların yaşı

- Type of Travel: Seyahat tipi (İş Seyahati, Kişisel Seyahat)

- Class: Uçuş sınıfı (İş, Ekonomi, Ekonomi Plus)

- Flight Distance: Uçuş mesafesi

- Inflight wifi service: Uçak içi wifi hizmetinin memnuniyet düzeyi (0:Uygulanamaz;1-5)

- Departure/Arrival time convenient: Kalkış/Varış saati uygunluğu memnuniyeti

- Ease of Online booking: Online rezervasyon kolaylığı memnuniyeti

- Gate location: Kapı konumu memnuniyeti

- Food and drink: Yiyecek ve içecek memnuniyeti

- Online boarding: Online biniş memnuniyeti

- Seat comfort: Koltuk konforu memnuniyeti

- Inflight entertainment: Uçak içi eğlence memnuniyeti

- On-board service: Uçak içi hizmet memnuniyeti

- Leg room service: Bacak mesafesi memnuniyeti

- Baggage handling: Bagaj taşıma hizmet memnuniyeti

- Checkin service: Check-in hizmeti memnuniyeti

- Inflight service: Uçak içi hizmet memnuniyeti

- Cleanliness: Temizlik memnuniyeti

- Departure Delay in Minutes: Kalkışta dakika cinsinden gecikme

- Arrival Delay in Minutes: Varışta dakika cinsinden gecikme

- satisfaction: YHavayolu memnuniyet seviyesi (Memnuniyet, nötr veya memnuniyetsizlik)

Kurulum

Projeyi çalıştırmak için aşağıdaki kütüphanelerin yüklü olması gerekmektedir:

- pandas

- numpy

- matplotlib

- seaborn

Kullanım

Projeyi çalıştırmak için 1_FinalCase_Airline.ipynb Jupyter Notebook dosyasını açabilirsiniz. 
Kod hücrelerini sırasıyla çalıştırarak veri işleme ve EDA adımlarını takip edebilirsiniz.

Analiz ve Bulgular
Bu projede aşağıdaki analiz adımları uygulanmıştır:

Veri Yükleme ve Genel Bakış: Veri setinin ilk bakışı, eksik değerlerin kontrolü ve temel istatistiksel özetler.

Eksik Değerlerin Analizi: Varış gecikmesi gibi eksik değer içeren sütunların analizi ve kullanılabilecek yöntemler

Kategorik Değişken Analizi: Kategorik değişkenlerin dağılımları ve memnuniyet ile ilişkileri.

Sayısal Değişken Analizi: Sayısal değişkenlerin dağılımları ve korelasyonları.

Aykırı Değer Analizi: Flight Distance, Checkin service, Departure Delay in Minutes ve Arrival Delay in Minutes sütunlarının aykırı değerlerinin analizleri

Bu analizler sonucunda, yolcu memnuniyetini etkileyen temel faktörler hakkında önemli içgörüler elde edilmiştir. Örneğin, bazı hizmet kategorilerinin memnuniyet üzerinde daha güçlü bir etkiye sahip olduğu gözlemlenebilir.

Sonraki Adımlar
Bu projenin mevcut durumu, gelecekteki makine öğrenimi modellemesi için sağlam bir temel oluşturmaktadır. Sonraki adımlar şunları içerebilir:

Model Oluşturma: Yolcu memnuniyetini tahmin etmek için çeşitli sınıflandırma algoritmalarının (örneğin, Lojistik Regresyon, Random Forest, XGBoost, LightGBM, CatBoost) uygulanması.

Model Değerlendirme: Modellerin performansını değerlendirmek ve en iyi modeli seçmek.
