# Codebase İndirmek

## İçindekiler

- [ZIP olarak indirmek](#zip-olarak-indirmek)
- [Git ile indirmek](#git-ile-indirmek)

Oyunu localde çalıştırmak, oyunu geliştirmek, birşeyleri test etmek için oyunun kodunu indirmelisiniz.

## ZIP olarak indirmek

Bu yol hem az yer kaplar hemde kolaydır fakat bu şekilde yaptığınızda hem oyuna katkıda bulunamazsınız hemde kodu güncellemek için silip tekrar yüklemeniz gerekmektedir.

Zip olarak indirmek için ilk olarak [bu linke](https://github.com/psychonaut-station/PsychonautStation) gidin.

![1](../../images/git/repo1.png)

Ardından yeşil "Code" tuşuna bastıktan sonra açılan menüde "Download ZIP" tuşuna basarak indirebilirsiniz.

![1](../../images/git/repo2.gif)

## Git ile indirmek

Git ile indirmek zipe göre daha uzundur fakat bu yolla hem codebasyi kolayca güncelleyebilir hemde yaptığın kodu oyuna ekletmek için pull request açabilirsiniz.

İlk olarak bir önceki dersi inceleyerek git indirin ve çalıştığına emin olun. Git kurduktan sonra eğer githubda giriş yapmamışsanız giriş yapın, hesabınız yoksa kurun, ardından [buraya](https://github.com/psychonaut-station/PsychonautStation) girin.

Sağ üstteki "Fork" tuşuna basın.

![1](../../images/git/repo3.png)

Burada hiçbirşeye ellemeyip devam edebilirsiniz.

![1](../../images/git/repo4.png)

Burada biraz bekleyiniz.

![1](../../images/git/repo5.gif)

Tebrikler kendi forkunuzu oluşturdunuz, şimdi bu forkda yeşil code tuşuna basınız.

![1](../../images/git/repo6.png)

Yeşil Code tuşuna bastıktan sonra Https alanındaki kodu kopyalayın.

Kodunuz `https://github.com/<Kullanıcı Adınız>/<Repository Adı>.git` şeklinde görenecektir.

Dilerseniz SSH kullanarak devam edebilirsiniz.

![1](../../images/git/repo7.gif)

Ardından Codebaseyi bilgisayarınızda kurmak istediğiniz klasör lokasyonu içerisinde CMD açınız.

Ardından alttaki kodu CMD ye yazarak codebaseyi indirmeye başlayabilirsiniz.

```cmd
git clone <Kopyaladığınız Link>
```

![1](../../images/git/repo8.gif)

Git kullanarak indirirken codebasenin tamamını indirdiğinizden dolayı bu indirme biraz uzun sürecektir.
