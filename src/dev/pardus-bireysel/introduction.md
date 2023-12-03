# Introduction

## Kurulum
Kararlı Sürüm Kurulumu
```bash
git clone https://github.com/pardus-bireysel/pardus-bireysel/
cd pardus-bireysel
./install.sh
```
Geliştirici Sürümü Kurulumu
```bash
./install.sh dev remote-run BRANCH
# BRANCH'ı geliştirmekte olduğunuz kol ile değiştirin
```

Yerel Kurulum
```bash
./install.sh dev local-run
```

## Dosya Yapısı

```yaml
├── common.sh # diğer kodlarda kullanılan genel fonksiyonlar ve değişkenler
├── development.sh # geliştirici fonksiyonları
├── install.sh # ana çalıştırılabilir dosya, diğer dosyaları kullanır/çağırır
└── src
    ├── config.conf # kalıcı konfigrasyonların olduğu dosya
    ├── kde_configurations.sh # kde konfigrasyonları (WIP)
    ├── kde_install.sh # kde yükleme ve kurma (WIP)
    └── remove_apps.sh # gereksiz uygulamaları silen betik
```

