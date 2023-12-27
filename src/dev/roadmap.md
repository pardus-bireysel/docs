# Roadmap

<!-- DOKÜMANTASYONU DEĞİŞİRMEDEN ÖNCE: https://pardus-bireysel.github.io/docs/documentation.md dosyasına bakınız !!! -->


## Betik
> Komut satırından çalıştırılabilen betiğimiz
- [ ] Uygulamaların Düzenlenmesi
  - [x] Gereksiz görülen uygulamaların silinmesi 
  - [ ] Daha kullanıcı dostu uygulamaların yüklenmesi
- [ ] KDE Ortamı
  - [ ] KDE ortamının yüklenmesi (WIP) (pkde'den)
  - [ ] Kullanıcı dostu varsayılan KDE ayarları (pkde'den)
  - [ ] ...
- Ekstra
  - [ ] Advanced Argument/Flag Handling
    - see [t](https://stackoverflow.com/questions/192249/how-do-i-parse-command-line-arguments-in-bash)h[e](https://www.redhat.com/sysadmin/arguments-options-bash-scripts)s[e](https://www.assertnotmagic.com/2019/03/08/bash-advanced-arguments/)
  - [ ] Help text (tr)
  - [ ] Man pages (tr-en)

---

## GUI 
> Diğer Uygulamaların yüklenmesi, sürecin kontrol edilmesi adına hâlihazırdaki betiğin yaptığı işlemleri yapan GUI uygulamasının yazılması
- [ ] (WIP) GUI Toolkitine karar verilmesi: GTK, QT
  - [ ] İlgili GUI toolkitinin öğrenilmesi
- [ ] (WIP) Programlama diline karar verilmesi: Rust, Python, C, C++ ...
  - [ ] İlgili programlama dilinin öğrenilmesi ve basit GUI toolkit uygulamalarının denenmesi
- [ ] Kullanıcı ayarları yedekleme butonu
- [ ] Kurulum Butonu ...
- [ ] ...
- [ ] Komut satırı üzerinden kontrol için gerekli komutların sağlanması, [betik](#betik) içindeki tüm komutların uygulanabilmesi
  - [ ] [Betik](#betik)'in kullanım ömrünün dolması ve geliştirmelere GUI üzerinden devam edilmesi

---

## Uygulamalar
> Kullanım kolaylığı sağlayacak kullanıcı dostu uygulamalar yazmak, (MXLinux / Mint vb. distrolar içindeki faydalı araçların benzerleri ve daha fazlası!)
- [ ] KDE Hoşgeldin uygulaması (pardus-xfce-greeter benzeri)
- [ ] Pardus servis görüntüleyici (MXLinux forku) (ÖRNEKTİR)
- [ ] ...
<!-- EKSTRA UYGULAMA FİKİRLERİNİ BURAYA EKLEYİNİZ -->

---

## Paket Deposu
> Depo paketleri sunmak (öncelikli değil!)
- [ ] Firefox Güncel Sürümünün build edilmesi ve paket olarak sunulması
- [ ] Çeşitli uygulamaların v3 sürümlerinin sunulması
- [ ] ...

---

### Ekstra
> Dokümantasyon & Eğitim & Tanıtım amaçlı çeşitli içeriklerin oluşturulması (öncelikli değil!)
- Dokümantasyon
  - [ ] Geniş bir kullanıcı dokümantasyonunun oluşturulması
  - [ ] Geliştirici dokümantasyonunu sürekli güncellemek
- Eğitim
  - [ ] gonullu.pardus.org.tr üzerinde faydalı blog yazıları paylaşmak
  - [ ] Video içerikleri (Nasıl Yapılır / Sorun Çözme) hazırlamak (YouTube/PeerTube)
  - [ ] Ayrı bir blog sayfasının oluşturulması (gerek var mı?)
- Tanıtım
  - [ ] Pardus'un daha fazla kişiye ulaşmasını sağlayacak, Pardus/Özgür yazılım dünyası ile ilgili gelişmelerin aktarılacağı:
    - [ ] **Instagram** hesabı açmak.
    - [ ] **Twitter** hesabı açmak.
    - [ ] **Fediverse** hesabı açmak.
    - [ ] Platformlar arası otomatik paylaşım mekanizması oluşturulması


---

#### `docs` Roadmap
- [ ] Multilanguage Support (TR/EN)
- [ ] Index and 404 page support
- [ ] runnable bash scripts support
- [ ] Add useful tools like in https://rust-lang.github.io/mdBook/for_developers/backends.html
- [ ] Look https://rust-lang.github.io/mdBook/for_developers/preprocessors.html