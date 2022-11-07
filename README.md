# CSS Modül Projesi Giriş

## Kullanıcı Arayüzü ve Git

## Hedefler

- box model'i araştırın ve özelliklerini açıklamaya çalışın 
- stiller oluşturmak için CSS kullanın 
- CSS kullanımının tarayıcılar arası proje geliştirmekdeki önemini kavrayın
- Responsive site oluşturabilmek için kullanın: (px, em, rem, %, and vw.vh) 

## Giriş

Bu projede Nevşehir Göreme'de bulunan Peribacaları ile ilgili tek sayfalık bir tanıtım sitesi yapacağız.

Hedeflenen sayfa dizaynı şu dosya içerisinde gösterilmiştir: [dizayn dosyası](/design/desktop.jpg) 

## Talimatlar

### Görev 1: Projeyi Git'le kurun

Aşağıdaki adımları takip edin.:

- [ ] Repoyu forklayın ve klonlayın.
- [ ] Canvas'a gidin ve Github URL'sini kopyalayıp gönderim yuvasına yapıştırarak deponuzu bağlayın.
- [ ] BRANCH OLUŞTURMAYIN. Güncellemelerinizi main/master 'a pushlayacaksınız.
- [ ] konsoldan repo klasörünüze girin ve VS Code'u açmak için . girin.
- [ ] VS Code'un sol tarafındaki Eklentiler bölümünden Live Server eklentisini indirin. Eklenti yüklendikten sonra sağ altta bulunan "Go Live" butonuna basarak HTML dosyanızı çalıştırabilirsiniz.
- [ ] Çalışmanızı düzenli commitlerle main branch'e aktarın. gönderdiğiniz URL programınızın en son versiyonuna göndermektedir.

### Görev 2: Minimum Uygulanabilir Ürün

Repository'niz hazır olunca verilen dizayn göze alınarak bugün öğrendiğiniz site stillemeye dair pratik yapın. Tamamladığınız sayfanın verdiğimiz dizayn dosyasına benziyor olması gerekmektedir. Minimum yeterliliği sağlamak için aşağıda verilenleri uygulayın:

- [ ] CSS stylesheet dosyanızı `index.html` dosyasına linkleyin 
- [ ] Verilen görüntüyü elde etmek için HTML etiketlerinizi semantik(anlamsal) olarak ekleyin
- [ ] Menü elemanlarını ve footer(altbar)'ı arkaplanlarını(background) renklendirmek için verilen renk kodlarını kullanın:
  - [ ] Gezinizi Planlayın: `#FF764E`
  - [ ] Bilgi Edinin: `#5ED3EB`
  - [ ] Karşılaştırın: `#FFCD69`
- [ ] Yazı renkleri ve fontlar:
  - [ ] Peri Bacaları Tanıtımı fontunun adı Chelsea Market'tir ve şu linkten ulaşılabilir [google fonts](https://fonts.google.com/specimen/Chelsea+Market)
  - [ ] Diğer tüm fontlar Roboto Mono'dur ve şuradan ulaşılabilir [google fonts](https://fonts.google.com/specimen/Roboto+Mono)
- [ ] Ana metnin arka plan rengi: `#DDB9A3`
- [ ] Footer'ın arka plan rengi: `#F9E7DC`
- [ ] "olağanüstü ve rüya gibi bir deneyim." ve "dünyanın en iyi ATV turlarından birini" kelime öbeklerini bold yapın.
- [ ] Dizayn sayfasındaki sonucu yakalamak için Box model özelliklerini uygulayın (content, padding, margin, and border). En az şunları içermelidir:
  - [ ] Headerde bir yuvarlak resim (image)
  - [ ] Footer ve menü elemanlarında yuvarlak köşeler
  - [ ] Başlık(header) resmi ve hizalı text 
  - [ ] Ortalanmış içerikler, marginler ve içeriklerin etrafındaki marginler 
  - [ ] Footer resmi pozisyonu

**Tasarımınız boyunca statik öğelerden kaçının (pikseller) Mümkün olduğunca responsive öğeler kullanın.**

**Lütfen şunu unatmayın, bugünkü uygulamada flexbox kullanılmayacak. Hedefe inline-block kullanarak ulaşmayı deneyin.**


### Görev 3: Ek Görevler

Aşağıdakileri uygulayın.

- [ ] CSS animasyonları ekleyin (hover, mouseover, etc.)
- [ ]  `Gezinizi Planlayın`, `Bilgi Edinin`, ve `Karşılaştırın` sayfaları için kendi tasarımlarınızı yapın ve çalıştırın
- [ ]  [favicon.io](https://favicon.io/favicon-converter/) sitesini kullanarak atv ve balon ikonlarını favicon'a dönüştürüp sayfaya ekleyin.
