# Grup-194-Bootcamp

# Takım İsmi
PsyTrack

# Ürün İle İlgili Bilgiler

Psikiyatri kliniklerinde, kliniğe gelen hastaların ilk aşamada değerlendirilmesini kolaylaştıran; depresyon, anksiyete, bipolar bozukluk gibi yaygın psikolojik rahatsızlıklar için ön tarama yapan, doktora takip verisi sunan yapay zeka destekli bir sistem oluşturulması hedeflenmektedir.

# Takım Elemanları
Esma Işıl ŞENYURT- Scrum Master, Developer

İrem Gül ER - Product Owner, Developer

Cansu KIZILARMUT - Developer

Cenker ZEYBEK - Developer

Bilal ÖRGEN- inaktif

# Ürün İsmi
--PsyTrack AI--

# Ürün Açıklaması
Psikiyatri kliniklerinde, kliniğe gelen hastaların ilk aşamada değerlendirilmesini kolaylaştıran; depresyon, anksiyete, bipolar bozukluk gibi yaygın psikolojik rahatsızlıklar için ön tarama yapan, doktora takip verisi sunan yapay zeka destekli bir sistem oluşturulması hedeflenmektedir.

# Çalışma Stili:
Hasta, randevudan önce telefonuna gelen veya klinikte erişebileceği formu doldurur.
Bu formda, PHQ-9 (depresyon), GAD-7 (anksiyete), Uyku problemleri, İntihar riski vb. gibi soruların oluştuğu soru listesi bulunur. 
Yapay zeka, hastanın yanıtlarını veri analiz eder.
Yapay zeka, elde ettiği sonuçları doktor ile özetleyerek paylaşır. (Örneğin: hasta 2 haftadır yoğun uykusuzluk yaşıyor ve intihar düşüncesi taşıyor, haftada bir görüşmeler talep edilmeli ve sevecen bir tutumla konuşulması önceliklendirilmeli.)
Hasta, kendi durumunu kısaca, talep edilen zaman aralıklarıyla sisteme bildirir.
Doktor/hastane, iyileşme-gidişat grafiklerini görebilecektir.

# Birincil fonksiyonu: 
İlk görüşmede geçen zamanı azaltarak klinik yükü azaltır. 
Süreçleri kişiselleştirir ve doktorun karar alma ve takip sürecine yardımcı olur. 
Hastada farkındalığın artmasına yardımcı olur.
Hastada farkındalığı artırır.

# Hedef Kitle
Psikiyatrisler
Psikologlar
Aile sağlığı merkezi doktorları
Psikilojik rahatsızlık çeken hastalar ve yakınları

# Kullanılması Planlanan Teknolojiler:
Bileşen
Teknoloji
Form sistemi
Web tabanlı Flutter/Vue.js
NLP + Analiz
spaCy + OpenAI + sklearn
Zaman serisi izleme
Python (Pandas / Dash)
Klinik veritabanı entegrasyonu
JSON/HL7 destekli API


# SPRINT 1
# Sprint içinde tamamlanması tahmin edilen puan:
100 Puan

# Puan tamamlama mantığı: 
Toplamda proje boyunca tamamlanması gereken 300 puanlık backlog bulunmaktadır. 3 sprint'e bölündüğünde ilk sprint'in en azından 100 ile başlaması gerektiğine karar verildi.

# Link:
https://bootcamp194.atlassian.net/jira/core/projects/B1/board?groupBy=status&atlOrigin=eyJpIjoiZmRjMzM1OGQ3MTIxNDljOGExNWI2NDYyNWYyNzc5YTciLCJwIjoiaiJ9

# Daily Scrum:
Daily Scrum görüşmeleri whatsapp grubundan yapılmaktadır. 

# Sprint board update:
Sprint board screenshot


# Ürün Durumu: 
Henüz fikir geliştirilmesi aşamasındadır. 

# Sprint Review: 
Alınan kararlar: Sağlık sektöründeki eksiklikler araştırılmış, konsepte karar verilmiştir. Genel zaman eksikliğinden, bu sprintte gelecek spirntlere dair planlama gerçekleştirilmiştir. Sprint Review katılımcıları: Esma Işıl ŞENYURT

# Sprint Retrospective:

Roller ile ilgili kararlaştırmalar yapılmıştır.
Takım içindeki görev dağılımıyla ilgili netleşmeler yapılmıştır.
Takım üyelerinin gelecek sprintlerde aktif olması gerektiğine vurgu yapılmıştır.

# SPRINT 2
# Sprint içinde tamamlanması tahmin edilen puan:
100 Puan

# Puan tamamlama mantığı: 
Toplamda proje boyunca tamamlanması gereken 300 puanlık backlog bulunmaktadır. 3 sprint'e bölündüğünde ilk sprint'in en azından 100 ile başlaması gerektiğine karar verildi.


# Trello Link: 

https://trello.com/invite/b/6876a752e2188089381dc7bd/ATTI4cb69f767f77928a0e1048edca2320c57527CA20/trello-panom

# Daily Scrum: 

Daily Scrum görüşmeleri whatsapptan yapılmakta ve haftalık müsaitlikte meetten görüşme sağlanmaktadır. Örnek konuşma:
<img width="1303" height="817" alt="image" src="https://github.com/user-attachments/assets/466a7efd-7fb5-42f2-ac08-5a53ab018d22" />
<img width="1325" height="825" alt="image" src="https://github.com/user-attachments/assets/691efdfb-c083-4dd5-a830-07053a0da311" />

# Sprint board update: 

Sprint board screenshot: 
<img width="1447" height="551" alt="image" src="https://github.com/user-attachments/assets/de9141ef-15cd-454b-b5fb-0aef49de3902" />

# Ürün Durumu: 

Ürün için gerekli teknolojilere dair araştırmalar yapılmıştır ve kararlaştırma yapılmıştır.
Psikolojik rahatsızlıkları erken fark edebilmek için sistemimize iki basit ama etkili özellik eklemeyi öneriyoruz:

# 1. Günlük Duygu Takibi
Kullanıcı, her gün sadece bir dakikasını ayırarak "Bugün kendinizi nasıl hissediyorsunuz?" gibi basit bir soruya emoji veya yüz ifadeleriyle yanıt verebilir, isterse kısa bir cümleyle gününü anlatabilir. Bu kısa bildirimler kaydedilerek zamanla "Bu hafta nasıl geçti?" gibi genel bir duygu tablosu oluşturulur. Bu sayede hem kullanıcı sıkılmadan düzenli olarak duygu durumunu takip edebilir, hem de klinisyenler, zaman içindeki ruh hali değişimlerini kolayca gözlemleyebilir. Bu düzenli ve sistematik veri akışı, psikolojik rahatsızlıkların erken belirtilerini saptamada veya mevcut durumun seyrini anlamada önemli bir bilimsel temel sunar. Duygu durumundaki belirgin ve sürekli değişimler, depresyon, anksiyete veya bipolar bozukluk gibi yaygın psikopatolojilerin öncü göstergeleri olarak değerlendirilebilir, böylece daha erken ve etkili müdahale imkanı sağlanır.

<img width="1024" height="766" alt="Gemini_Generated_Image_lmmeylmmeylmmeyl" src="https://github.com/user-attachments/assets/836b3ad4-ae06-4f5f-976a-9e889c74af6d" />

# 2. Akıllı Risk Skoru ve Hedefe Yönelik Geri Bildirim
Kullanıcının verdiği yanıtlara göre sistem, arka planda basit bir "risk puanı" hesaplar. Bu puan, kullanıcının mevcut psikolojik durumunun iyi mi, yoksa dikkat edilmesi gereken bir seviyede mi olduğunu gösterir. Kullanıcıya bu puan doğrudan açıklanmaz; bunun yerine, "Bugün iyi gidiyorsun!" veya "Biraz zor bir gün olabilir, istersen biraz dinlen." gibi basit ve destekleyici mesajlar sunulur. Klinisyenler için ise bu puan, özel bir ekranda renk kodlarıyla görselleştirilir:

- Yeşil: Kullanıcı iyi durumda.
- Sarı: Kullanıcının takibi gerekli.
- Kırmızı: Acil müdahale veya daha yakından takip gerekebilir.

Bu sistem sayesinde kullanıcı kendini desteklenmiş hissederken, klinisyenler de hastalarının riskli durumlarını hızla fark ederek erken ve etkin müdahale imkanı bulur. Bu yaklaşım, tanı ve tedavi süreçlerini bilimsel verilerle desteklerken, hasta-hekim iletişimini de güçlendirir.

<img width="2048" height="2048" alt="Gemini_Generated_Image_vflt6vflt6vflt6v" src="https://github.com/user-attachments/assets/1062d9e4-342c-4923-95a0-780115879f85" />

Bu sistemi bir web sitesi gibi düşünebiliriz. Kullanıcılar her gün o siteye girip, kendilerine sorulan soruları basitçe tıklayarak veya içlerinden geldiği gibi kısa notlar yazarak yanıtlayacaklar. Bu cevaplar anında sistemimizde güvenle kaydedilecek. Sonra sistemimiz, bu verileri kullanarak küçük hesaplamalar yapacak ve size özel mesajlar ile birlikte, zaman içindeki duygu durumunuzu gösteren güzel grafikler oluşturacak. Tüm bunları yapmak için, aslında çok teknik bilgiye ihtiyacımız yok; hazır görsel araçlar veya kullanıma hazır yazılım kütüphaneleriyle kolayca halledebileceğiz.

# Bu yolu seçmemizin birkaç önemli nedeni var:
- Sıkıcı Değil, Keyifli: Bildiğimiz anketlere hiç benzemiyor; aksine, eğlenceli ve kullanımı çok kolay. Bu da insanların sistemi daha severek kullanmasını sağlıyor.
- Zaman Kaybı Değil, Kazanç: Kullanıcılar için boşuna harcanmış bir zaman değil, tam tersi kendi iç dünyalarını daha iyi anlamalarına yardımcı olan ve hatta motive eden bir araç.
- Doktorlara Büyük Kolaylık: Doktorlarımız için hastalarının durumunu hızlı ve etkili bir şekilde takip etme imkanı sunuyor. Böylece olası riskli durumları anında fark edip zamanında destek verebiliyorlar.
- Herkes Kazanıyor: Hem kullanıcılar kendi psikolojik yolculuklarında güçlü bir destek buluyor hem de doktorlar daha bilinçli ve verimli kararlar alabiliyor. Kısacası, bu sistemden hem kullanıcı hem de doktor somut faydalar sağlıyor.

# Sprint Review: 

Alınan kararlar: Bir önceki sprintte karar verilen konsepte ve ürün içeriğine gelişmeler yapılmıştır. Jiro linkinde sorun yaşandığı için Trellodan sürecin yönetilmesine karar verilmiştir.

# Sprint Review katılımcıları: 

Esma Işıl ŞENYURT, İrem Gül ER, Cansu KIZILARMUT, Cenker ZEYBEK

# Sprint Retrospective:

Roller netleştirilmiştir. Proje durumu güncelleştirilmiş, geliştirilmiş ve planlanan görsel de oluşturulmuştur. Proje uygulamasına geçişe başlanmıştır. Projenin oluşması için hızlanması hedeflenmelidir.

# SPRINT 3
# Sprint içinde tamamlanması tahmin edilen puan:
100 Puan

# Puan tamamlama mantığı: 
Toplamda proje boyunca tamamlanması gereken 300 puanlık backlog bulunmaktadır. Sprint 3’te de bu dağılıma sadık kalınmış, sürdürülebilir gelişim ve proje takibi için bu yaklaşım benimsenmiştir.

# Trello Link: 

https://trello.com/invite/b/6876a752e2188089381dc7bd/ATTI4cb69f767f77928a0e1048edca2320c57527CA20/trello-panom

# Daily Scrum: 

Daily Scrum görüşmeleri whatsapptan yapılmakta ve müsaitlik olursa meetten görüşme sağlanmaktadır. Örnek konuşma:

![WhatsApp Görsel 2025-08-03 saat 12 05 38_2c9ce924](https://github.com/user-attachments/assets/4872cac7-038b-4b24-9b3c-7d8e04cb4f88)
![WhatsApp Görsel 2025-08-03 saat 12 05 57_5aa9d4d8](https://github.com/user-attachments/assets/78de81cb-7748-42c1-804d-e4c2c5685add)

# Sprint board update: 

Sprint board screenshot: 

<img width="1862" height="831" alt="image" src="https://github.com/user-attachments/assets/56d19903-32c8-47b0-8099-029f6fea6cd9" />


# Ürün Durumu: 

Bu sprintte ürünün kullanıcıya dönük birçok arayüzünün şekillenmesi ve kullanıcı geri bildirimine açık hale gelmesi hedeflenmiştir. Ürün fonksiyonel olarak kişiselleştirme ve etkileşim yönünden daha gelişmiş bir hale gelmektedir.

- *Memnuniyet Anketi:* Hastaların uygulamaya dair geri bildirim verebildiği mini bir anket ekranı planlandı.
- *Geliştirme Talepleri:* Kullanıcıların sistem hakkındaki yeni fikir ve ihtiyaçlarını aktarabileceği bir alan tasarlandı.
- *Yapay Zekâ Verileri:* Kullanıcının davranış ve sağlık verileri toplanarak hem hasta hem doktor için özetlenebilecek bir sayfa düşünülmüştür.
- *Duygu Takibi:* “Bugün nasılsın?” gibi sorularla, kullanıcıdan emoji + metin kombinasyonu ile duygu durumu alınarak kaydedilecek.
- *İlk Randevu Anketi:* Uygulamayı ilk kullanan kullanıcıya yöneltilen tanıtıcı ve veri toplayıcı kısa sorular içerir.
- *Risk Skoru:* Sistem, kullanıcının verdiği cevaplara göre otomatik risk puanı üretip bunu sade bir görselle kullanıcıya sunacaktır.
- *Geri Bildirim Sayfası:* Kullanıcı tüm sürecin ardından sistem genel değerlendirmesini yapabilecektir.

| Görev | Açıklama |
|-------|----------|
| Kullanıcı Memnuniyet Anketi | Hastaların memnuniyet düzeyini ölçmek için basit bir anket modülünün eklenmesi |
| Geliştirme Talepleri Alanı | Hastaların uygulamayla ilgili önerilerini yazabilecekleri bir alan tasarlanması |
| Yapay Zekâ Veri Sayfası | Hastanın verilerini toplayarak doktora ve hastaya sunulacak şekilde arayüz geliştirilmesi |
| Duygu Takibi (Emoji + Metin Girişi) | Kullanıcının günlük ruh halini emojilerle ve metinle belirtmesini sağlayan sistem |
| İlk Randevu Anketi | Hastanın ilk görüşmeden önce dolduracağı kısa bir anket ekranı |
| Risk Skoru Hesaplama | Toplanan verilerle kullanıcıya özel risk skoru hesaplayan bir yapı |
| Geri Bildirim Modülü | Kullanıcının tüm süreç sonunda sistemle ilgili genel bir yorum bırakabileceği alan |

# Sprint Notları:

Duygu takibi arayüzü için kullanıcıya öneri emojiler eklenmesi önerildi.
Geliştirme talepleri kısmı için kullanıcıların önerileri listeleyip oylayabileceği bir sistem eklenmesi gündeme alındı.
İlk randevu anketiyle toplanan verilerin sistemde doktor görünümünde özetlenmesi planlandı.
Risk skoru hesaplamasında kullanılan soruların daha anlaşılır ve kısa hale getirilmesi gerektiği belirtildi.
Takımın bu sprintteki işbirliği ve iletişimi verimli bulunmuş, sonraki sprintte veri bütünlüğü ve analitiğine odaklanılması önerilmiştir.

# Sprint Review: 

Sprint sonunda geliştirilen her modülün testleri tamamlanmış, sistemin genel işleyişi gözden geçirilmiştir. Takım içi demo sırasında aşağıdaki çıktılar değerlendirilmiştir:
Anket modülleri beklendiği gibi çalışmaktadır.
Kullanıcı duygu takibi görsel ve metinsel olarak başarılı şekilde kaydedilmektedir.
Yapay zekâ veri görselleştirme ekranı tamamlanmış ancak veri kaynağı entegrasyonu eksik kalmıştır.
Risk skoru hesaplama mantığı doğru çalışmakta ancak görselleştirme tarafında küçük iyileştirmelere ihtiyaç duyulmuştur.
Kullanıcıdan alınan ilk geri bildirimlerde genel memnuniyetin yüksek olduğu, özellikle kişiselleştirilmiş içeriklerin olumlu karşılandığı görülmüştür.

# Sprint Review katılımcıları: 

Esma Işıl ŞENYURT, Cansu KIZILARMUT, Cenker ZEYBEK

# Sprint Retrospective:

Sprint 3 kapsamında ekip, projenin kullanıcı deneyimini ve etkileşimli özelliklerini artırmaya yönelik çalışmalara odaklanmıştır. Özellikle yapay zekâ destekli veri toplama, analiz ve kullanıcı geri bildirim mekanizmaları üzerine çalışmalar planlanmaktadır.
