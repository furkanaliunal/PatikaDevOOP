# PatikaDevOOP

Bu repo [Patika](https://patika.dev) OOP eğitimi için hazırlamış olduğum repo. UML ve OOP Java ödevlerimin soru ve cevaplarını içeriyor.

| ÖDEVLER |  |  |
|-----|-----|-----|
| [ÖDEV 1](https://github.com/furkanaliunal/PatikaDevOOP#-%C3%B6dev-1---%C3%BCniversite-y%C3%B6netim-sistemi) - Üniversite Yönetim Sistemi | [ÖDEV 2](https://github.com/furkanaliunal/PatikaDevOOP#-%C3%B6dev-2---hayvanat-bah%C3%A7esi) - Hayvanat Bahçesi | [ÖDEV 3](https://github.com/furkanaliunal/PatikaDevOOP#-%C3%B6dev-3---u%C3%A7u%C5%9F-y%C3%B6netim-sistemi) - Uçuş Yönetim Sistemi
| [ÖDEV 4](https://github.com/furkanaliunal/PatikaDevOOP#-%C3%B6dev-4---online-film-sitesi) - Online Film Sitesi | [ÖDEV 5](#) - Girilecek | [ÖDEV 6](#) - Girilecek

---
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

## [📖 Ödev 1 - Üniversite Yönetim Sistemi](#-%C3%B6dev-1---%C3%BCniversite-y%C3%B6netim-sistemi)
<p>&nbsp;</p>

Üniversiteye ait sınıflıklar, çalışma ofisleri ve departmanlar vardır.
Departmanlara ait ofisler vardır.
Üniversiteye ait çalışanlar vardır. Bu çalışanlar profesör veya memur olabilir.
Her çalışan bir ofiste çalışır.
Bu sistemi tasvir eden Class (Sınıf) diyagramını çiziniz.

Not : Sınıflara ait nitelik ve davranışların belirtilmesine gerek yoktur.

<details>
<summary>Cevabı görmek için tıkla.</summary>
  
![soru1](src/1.png)
</details>


<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

---


<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

## [📖 Ödev 2 - Hayvanat Bahçesi](#-%C3%B6dev-2---hayvanat-bah%C3%A7esi)
<p>&nbsp;</p>

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.
<p></p>


Hayvanlar:

- Atlar (atlar, zebralar, eşekler vb.),
- Kedigiller (kaplanlar, aslanlar vb.),
- Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.

Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.

tür adı, ağırlığı, yaşı vb.

Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()

Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()

Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.

<details>
<summary>Cevabı görmek için tıkla.</summary>
  
![soru2](src/2.png)
</details>


<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

---

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

## [📖 Ödev 3 - Uçuş Yönetim Sistemi](#-%C3%B6dev-3---u%C3%A7u%C5%9F-y%C3%B6netim-sistemi)
<p>&nbsp;</p>

Uçuşların ve pilotların yönetimi için bir sistem tasarlayın.
<p></p>


- Hava yolu şirketleri uçuşları gerçekleştirir. Her hava yolunun bir kimliği vardır.

- Hava yolu şirketi, farklı tipteki uçaklara sahiptir.

- Uçaklar çalışır veya onarım durumunda olabilir.

- Her uçuşun benzersiz kimliği, kalkacağı ve ineceği havaalanı, kalkış ve iniş saatleri vardır.

- Her uçuşun bir pilotu ve yardımcı pilotu vardır ve uçağı kullanırlar.

- Havaalanlarının benzersiz kimlikleri ve isimleri vardır.

- Hava yolu şirketlerinin pilotları vardır ve her pilotun bir deneyim seviyesi mevcuttur.

- Bir uçak tipi, belirli sayıda pilota ihtiyaç duyabilir.

Bu sistemi tasvir eden Class(Sınıf) diyagramını çiziniz.
<details>
<summary>Cevabı görmek için tıkla.</summary>
  
![soru3](src/3.png)
</details>


<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

---

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

## [📖 Ödev 4 - Online Film Sitesi](#-%C3%B6dev-4---online-film-sitesi)
<p>&nbsp;</p>

### Online film satan veya kiralayan uygulamanın sistemini tasarlayın.
<p></p>

- Uygulamada filmler listelenebilir, sıralanabilir ve kullanıcılar uygulamaya abone olabilir.

- Kullanıcılar abonelik için sistem üzerinden kredi satın alır.

- Sadece abone olan kullanıcılar, kredileri ile film kiralayabilir ve kiraladığı filmin kredi bedeli kadar hesabından düşülür.

- Normal kullanıcılar ve aboneler film satın alabilirler.

- Eğer film mevcut değil ise talep edilebilir.

- Bu sistemi tasvir eden Class(Sınıf) diyagramını çiziniz.
<details>
<summary>Cevabı görmek için tıkla.</summary>
  
![soru4](src/4.png)

Diyagramın kodlarına ulaşmak isterseniz [tıklayabilirsiniz](https://github.com/furkanaliunal/PatikaOOP-OnlineFilmSirketi-in-Java-)
</details>



## [📖 Ödev 5 - Asansör Simülasyonu](#-%C3%B6dev-4---online-film-sites)
<p>&nbsp;</p>

### Asansör Simülasyonu

<p></p>

    Aşağıdaki problem ifadesine göre bir sınıf diyagramı tasarlayın. Nesne Yönelimli Programlamanın ilkelerini ve sınıflar arası ilişki durumlarını kullanmaya çalışın. (Encapsulation, Inheritance, Polymorphism, Abstraction)

- Kodluyoruz Sigorta Şirketi 12 katlı bir ofis binası inşa etmek ve onu en son asansör teknolojisi ile donatmak istiyor. Şirket, bina içindeki trafik akışı ihtiyaçlarını karşılayıp karşılamayacaklarını görmek için binanın asansörlerinin işlemlerini modelleyen bir yazılım simülatörü oluşturmanızı istiyor.

- Binada, her biri binanın 12 katına çıkabilecek beş asansör bulunacaktır. Her asansörün yaklaşık altı yetişkin yolcu kapasitesi vardır. Asansörler enerji tasarruflu olacak şekilde tasarlanmıştır, bu nedenle yalnızca gerektiğinde hareket ederler. Her asansörün kendi kapısı, kat gösterge ışığı ve kontrol paneli vardır. Kontrol panelinde hedef düğmeleri, kapı açma ve kapama düğmeleri ve bir acil durum sinyal düğmesi bulunur.


- Binadaki her katta, beş asansör boşluğunun her biri için bir kapı ve her kapı için bir varış zili vardır. Varış zili, asansörlerin bir kata vardığını gösterir. Her kapının üzerinde bulunan bir sinyal ışığı, asansörün gelişini ve asansörün hareket ettiği yönü gösterir. Her katta ayrıca üç set asansör çağrı düğmesi vardır.


- Bir kişi uygun çağrı düğmesine (yukarı veya aşağı) basarak bir asansörü çağırır. Bir programlayıcı, aramanın başladığı kata gitmek için beş asansörden birini görevlendirir. Asansöre girdikten sonra, bir yolcu tipik olarak bir veya daha fazla hedef düğmesine basar. Asansör kattan kata hareket ederken, asansörün içindeki bir gösterge ışığı yolcuları asansörün konumu hakkında bilgilendirir. Bir asansörün bir kata varması, dış asansör kapısının üzerindeki gösterge lambasının yakılması ve kat zilinin çalmasıyla belirtilir. Bir asansör bir katta durduğunda, her iki kapı grubu da önceden belirlenmiş bir süre boyunca otomatik olarak açılarak yolcuların asansöre girip çıkmalarına izin verir.

Simülatör, gerçek zaman geçişini simüle etmek ve simülasyonda meydana gelen olayları zaman damgası ve günlüğe kaydetmek için bir "saat" kullanır. Simülatör tarafından yolcu oluşturmak ve her yolcu için kalkış ve varış katlarını belirlemek için rastgele bir sayı üreteci kullanılır.
<details>
<summary>Cevabı görmek için tıkla.</summary>
  
![soru4](src/5.png)

</details>


