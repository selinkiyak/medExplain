Takım İsmi:
grup93

Takım elemanları:
Selinay kıyak: Scrum master/ Product Owner/Developer
Nur şirin atsızelti:Developer
Burak sarıçiçek:Developer
Seymen Bugay:Developer

Ürün İsmi:
medExplain

Ürün Açıklaması:
MedExplain, akciğer X-ray görüntülerini analiz ederek bunları "normal" ya da "anormal" olarak sınıflandıran ve ardından bu sonuca dayalı, tıbbi bir açıklamayı doğal dilde sunan yapay zekâ destekli bir eğitim aracıdır. Kullanıcı sisteme bir X-ray görseli yükler, sistem bu görüntüyü değerlendirir ve kullanıcıya hem sınıflandırma sonucunu hem de anlaşılır bir açıklamayı birlikte sunar.

Ürün Özellikleri:
Kullanıcı dostu Streamlit arayüzü
X-ray görüntü yükleme ve analiz imkânı
Hazır bir sınıflandırma modeliyle "normal / anormal" tahmini
Sonuca göre oluşturulan açıklayıcı doğal dil çıktısı
Gelecekte geliştirilebilir: OpenAI API entegrasyonu, hasta geçmişi karşılaştırması, model eğitim modülü

Hedef Kitle:
Tıp fakültesi öğrencileri
Asistan doktorlar
Radyoloji stajyerleri
Klinik karar verme sürecini öğrenmek isteyen sağlık çalışanları

Juriye Not:
Bu proje, medikal eğitimi desteklemek için yapay zekâ teknolojilerini erişilebilir ve görsel bir şekilde sunmayı hedeflemektedir. Amacımız, kullanıcıya yalnızca teknik bir sonuç değil, aynı zamanda karar verme sürecini besleyecek açıklayıcı bir yorum sunmaktır. MedExplain, hem öğrenen hem de öğreten için güçlü bir dijital asistan olabilir. MVP olarak çalışan bir prototip geliştirilmiş, sonraki sprintlerde daha gelişmiş özellikler eklenmesi planlanmaktadır.

Sprint 1

Sprint Notu: Bu sprintte en büyük zorluk, grup üyelerini bir araya getirmek ve net bir proje konusu belirlemekti. Görev dağılımı yaparken herkesin yetkinliklerine uygun şekilde işi bölmek zaman aldı. Ayrıca tüm iletişim sosyal medya (WhatsApp) üzerinden yürütüldüğü için zamanlama ve ulaşılabilirlik konusunda zorluklar yaşandı.
Tüm bu problemler, ekip üyelerinin sabırlı ve kararlı işbirliğiyle çözüldü. Sonuç olarak görev paylaşımı sağlandı, proje konusu netleştirildi ve ilk adımlar atıldı.

Sprint içinde tamamlanması tahmin edilen puan: 100 Puan

Puan tamamlama mantığı: Toplamda proje boyunca tamamlanması gereken 340 puanlık backlog bulunmaktadır. 3 sprint'e bölündüğünde ilk sprint'in en azından 100 ile başlaması gerektiğine karar verildi.

Daily Scrum: Daily Scrum toplantılarının zamansal sebeplerden ötürü Whatsapp üzerinden yapılmasına karar verilmiştir. 
![Whatsapp1](WhatsApp%20Image%202025-07-07%20at%2013.37.34.jpeg)
![whatsapp2](WhatsApp%20Image%202025-07-07%20at%2013.28.40.jpeg)



Sprint board update: Sprint board screenshot:
link: https://trello.com/b/88GCRWEo/medexplain-sprint-1
![Sprint Board](Ekran%20Resmi%202025-07-04%2023.59.03.png)

Ürün Durumu: Ekran görüntüleri:
Akciğer Xrayi için veriseti araştırması yapılmıştır. Nih Chest veriseti kullanılacaktır.
![NİHCHEST](Ekran%20Resmi%202025-07-07%2013.52.05.png)


Sprint Review:
Alınan kararlar:
Model eğitimi için temel veri ön işleme ve eğitim kodu hazırlandı.
Xception modeli üzerinde eğitim başladı, doğruluk testleri yapılmak üzere.
Tahmin fonksiyonları geliştirilip kod üzerinde test ediliyor.
GitHub reposu oluşturuldu, README dosyası güncellendi.
Arayüz yerine tüm işlemler doğrudan kod üzerinden yürütülecek.
Eksikler ve sonraki sprintlerde yapılacak işler detaylandırıldı.

Sprint Retrospective:
Takım rollerinde düzenleme yapılmış ve Scrum Master değişikliği gerçekleştirilmiştir.
Takım içindeki görev dağılımının daha net ve dengeli olması gerektiği kararlaştırılmıştır.
Gelecek sprintlerde tüm takım üyelerinin daha aktif ve katılımcı olması gerektiğine vurgu yapılmıştır.


Sprint 2 
Sprint Notu:
Bu sprintte en büyük zorluk, Xception modeli için doğru ve eksiksiz bir eğitim kodu hazırlamak oldu. Modeli Google Colab ortamında çalıştırırken uzun eğitim süreleriyle karşılaşıldı. Bu yüzden hem 30 epoch hem de 50 epoch için ayrı ayrı eğitim yapılarak doğruluk oranını artırmaya odaklanıldı.
Veri Google Drive üzerinden bağlanarak yönetildi, veri artırma (augmentation) teknikleri kullanıldı ve modelin önceden eğitilmiş katmanları dondurularak transfer öğrenme uygulandı. Eğitimin ardından model test edilerek başarı oranı kontrol edildi ve sonuçlar raporlandı.
Bu sprintte öğrenilen en önemli konu, yüksek epoch sayısının eğitim süresini ciddi şekilde uzatması ve modelin doğruluk değerine etkisinin dikkatli takip edilmesi gerektiğiydi. Tüm bu süreç grup üyelerinin işbirliğiyle başarıyla tamamlandı.


Sprint içinde tamamlanması tahmin edilen puan: 100 Puan

Puan tamamlama mantığı: Toplamda proje boyunca tamamlanması gereken 340 puanlık backlog bulunmaktadır. 3 sprint'e bölündüğünde ikinci sprint'in en azından 100 ile başlaması gerektiğine karar verildi.

Daily Scrum: Daily Scrum toplantılarının zamansal sebeplerden ötürü Whatsapp üzerinden yapılmasına karar verilmiştir. 
![Sprint Ekranı 1](Ekran%20Resmi%202025-07-19%2022.51.52.png)

![Sprint Ekranı 2](Ekran%20Resmi%202025-07-19%2022.52.13.png)


Sprint board update: Sprint board screenshot:
link: https://trello.com/b/88GCRWEo/medexplain-sprint-1
![Sprint 2 Board](Ekran%20Resmi%202025-07-19%2023.02.00.png)


Ürün Durumu: Ekran görüntüleri:
....


Sprint Review:
Alınan kararlar:


Sprint Retrospective:
