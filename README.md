# İşe Alım Tahmin Modeli

Bu proje, iş başvurularını değerlendirmek için bir makine öğrenimi modeli geliştirmeyi amaçlamaktadır. Model, adayların işe alınıp alınmayacağını tahmin etmek için çeşitli özellikler kullanır. Çalışma, Jupyter Notebook ortamında gerçekleştirilmiştir.

## Proje Dosyaları

- `model_notebook.ipynb`: Modelin oluşturulduğu, eğitildiği ve test edildiği Jupyter Notebook dosyası.
- `hiring_decision_model.h5`: Eğitilmiş model dosyası.
- `README.md`: Proje açıklaması ve kullanım kılavuzu.

## Çalışmanın Önemi
Bu çalışma, işe alım süreçlerini daha verimli ve objektif bir şekilde değerlendirmek için bir makine öğrenimi modeli sunmaktadır. Model, adayların çeşitli özelliklerini göz önünde bulundurarak işe alınıp alınmayacaklarını tahmin eder. Böylece, işe alım kararları veri destekli hale gelir ve insan kaynakları süreçleri daha bilimsel bir temele oturtulabilir.

## Kullanım
Model Eğitimi ve Testi

Jupyter Notebook dosyası, modelin nasıl oluşturulup eğitildiğini ve test edildiğini içerir. Notebook'ta, veri ön işleme, model eğitimi, değerlendirme ve tahmin yapma adımlarının detayları mevcuttur.

## Modelin Yüklenmesi ve Kullanımı

Eğitilmiş model (hiring_decision_model.h5), eğitim ve test aşamalarının ardından kaydedilmiştir. Modeli yüklemek ve kullanmak için ilgili kodlar model_notebook.ipynb dosyasında bulunabilir.

## Gelecek Çalışmalar
Model Performansını Artırma: Modelin performansını artırmak için daha fazla veri toplanabilir ve farklı makine öğrenimi algoritmaları denenebilir.
Kullanıcı Arayüzü Geliştirme: Modelin tahminlerini daha kullanıcı dostu bir şekilde sunmak için Tkinter veya başka bir GUI arayüzü geliştirilebilir.
Aday Özelliklerinin Genişletilmesi: Ek özellikler ve daha fazla veri ile modelin doğruluğu artırılabilir.
Modeli Yaygınlaştırma: Web tabanlı bir uygulama olarak modelin dağıtımı, daha geniş bir kullanıcı kitlesine erişim sağlayabilir.

## Katkıda Bulunanlar
[İbrahim Püsküllü] - Proje sahibi ve geliştirici

## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.

## İletişim
Sorularınız veya geri bildirimleriniz için [ibrahimpuskullu44@gmail.com] ile iletişime geçebilirsiniz.

## Kullanılan Kütüphaneler

Projenin çalışması için aşağıdaki Python kütüphanelerine ihtiyaç vardır:

- **TensorFlow**: Yapay sinir ağlarını oluşturmak ve eğitmek için kullanılır.
- **scikit-learn**: Modelin değerlendirilmesi ve veri ön işleme için kullanılır.
- **numpy**: Veri işleme ve matematiksel hesaplamalar için kullanılır.
- **pandas**: Veri manipülasyonu ve analizi için kullanılır.

Bu kütüphaneleri yüklemek için aşağıdaki komutları kullanabilirsiniz:

```bash
pip install tensorflow scikit-learn numpy pandas
