# Roadmap
<div class="warning">Roadmap Düzenlenecek<br>Bu son hâli değildir!</div>

## General Roadmap

- [ ] Bireysel kullanıcı için gereksiz olan uygulamaları kaldıran bir betik yazmak ([pardus-bireysel](#pardus-bireysel-bash-script-roadmap))
- [ ] bir depo adresi açılacak ve son sürüm firefox deb sürümü + ufak diğer paketlerin v3 sürümleri sunulacak. Hızlı güncelleme verilecek
- [ ] KDE ortamı için Pardus Hoşgeldin uygulaması yazmak
- [ ] Pardus Bireysel betiğini arayüz olarak çalıştırabilecek bir GTK uygulaması yazmak
- [ ] Bizzat kurulum aşamasinda ilgili ayarları yapabilmek için .iso dosyası oluşturmak
- [ ] Pardus/Pardus Bireysel kullanımı için dökümantasyon ve eğitim/tanıtım odaklı içerikler oluşturmak
- [ ] Bireysel kullanımı kolaylaştıracak çeşitli araçlar yazmak (MXLinux, Mint vb. dağıtımlar içindeki faydalı araçların benzerleri)
- [ ] Ve son olarak bu listedeki her bir adımı çıkan en son Pardus sürümü ile güncel tutmak ve bakımını sağlamak



### `pardus-bireysel` (bash script) Roadmap
#### Genel
- [x] Gereksiz Uygulamaları Kaldır
- [ ] XFCE masaüstü ortamını KDE Plasma'ya dönüştür
- [ ] KDE uygulamalarının uygulamalarının yüklenmesi ve varsayılan ayarların belirlenmesi
- [ ] KDE servislerinin düzenlenmesi ve gerekli önayarların yapılması. Plasma ayarlarının kullanıcılar için hazır duruma getirmek
- [ ] GNOME masaüstünden dönüştürme desteği vermek
- [ ] KDE ilk defa açıldıktan sonra belirli bir script çalıştırmak (cli/tui, pre/post-conf.sh) - (pardus-kde-greeter, hoşgeldin uygulaması)
- [ ] Pardus Bireysel betiğini arayüz olarak çalıştırabilecek bir GTK uygulaması yazmak (bu scriptlerin kullanım ömrünün dolması)

#### Genel - Teknik
- [ ] Advanced Argument/Flag Handling
  - see: https://stackoverflow.com/questions/192249/how-do-i-parse-command-line-arguments-in-bash , https://www.redhat.com/sysadmin/arguments-options-bash-scripts and https://www.assertnotmagic.com/2019/03/08/bash-advanced-arguments/
- [ ] Help text (tr)
- [ ] Man pages (tr-en)

<!-- kod işi geliştirmeler kod içine geri alındı (olması gerektikleri yerlere .d) -->

### `docs` Roadmap
- [ ] Multilanguage Support (TR/EN)
- [ ] Index and 404 page support
- [ ] runnable bash scripts support
- [ ] Add useful tools like in https://rust-lang.github.io/mdBook/for_developers/backends.html
- [ ] Look https://rust-lang.github.io/mdBook/for_developers/preprocessors.html