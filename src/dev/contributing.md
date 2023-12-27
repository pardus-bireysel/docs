# Contributing
1. [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) dokümantasyonuna uygun şekilde `commit` mesajları oluşturun.
2. Eğer bir hata bulursanız veya bir sorunuz varsa lütfen GitHub sayfası üzerinden `issue` oluşturun.
3. Eğer yeni bir fikriniz varsa lütfen GitHub sayfası üzerinden yeni bir `discussion` oluşturun.
4. Değişikliklerinizi `main` koluna `PR` olarak ekleyebilirsiniz.
    1. Eğer değişiklikleriniz hâlihazırda geliştirilen bir kolu ilgilendiriyorsa lütfen o kolu çatallayın ve gerekli değişiklikleri **o kola** `PR` olarak gönderin.
    2. Eğer ilgili kollar için yetkiniz varsa direkt geliştirme aşamasındaki `PR`'e ekleme yapın. 
5. Eğer oluşturduğunuz `PR`'ı ilgilindiren bir `issue` varsa lütfen hem `commit` mesajında hem de `PR` açıklamasında belirtin
6. `PR`ları olabildiğince kısa ve üzerinde çalıştığınız geliştirme ile ilgili olacak şekilde tutunuz. Binlerce satırlık `PR`lardan kaçınınız
7. İlginiz ve desteğiniz için teşekkürler :)

## Prepare Development Environment
1. Comment Anchor eklentisini kullanın (veya kodlar içinde `TODO`/`REVIEW`/`NOTE`/`FIXME` anahtar kelimelerini aratın)
2. Spellcheck eklentisini kurun (veya terminalden çalıştırın), dosyalar arası çalışmak için -x argümanını kullanmayı unutmayın!
3. Bash IDE eklentisini kurun

### Dil Yönetimi
> Daha okunaklı kodlar ve dökümantasyonlar için olabildiğince dilleri aşağıda gösterildikleri uygun yerlerde kullanmaya özen gösteriniz:
- Kod İçi Yorumlar, Fonksiyon açıklamaları vb: ENG
- Kod İçi Geçici Yorumlar (TODO/REVIEW/FIXME/NOTE): TR/ENG karışık
- Commit Yorumları: ENG (Conventional commits)
- Issue'lar: çoğunluk TR
- Pull Request Başlığı: ENG
- Pull Request Açıklamaları: TR/ENG
- Issue / PR Yorumları: TR/ENG
- Dökümantasyon: TR (mdbook multilanguage destekleyince ek olarak ENG)