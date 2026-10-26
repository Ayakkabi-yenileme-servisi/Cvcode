# Zombi sistemi

Bu repo içinde Zombi sistemi, temiz bir manifest yapısı üzerinden tanımlanır. Amaç, sistemin durumunu, modüllerini, güvenlik ve izin yapılandırmasını tek bir merkezden yönetmektir.

## Amaç
- Metaveriyi tek bir noktada tutmak
- Durum akışını netleştirmek
- Modülleri yapılandırılmış şekilde yönetmek
- Güvenlik ve erişim izinlerini görünür kılmak
- Doğrulama ve kalite kontrollerini kolaylaştırmak

## Yapı
- `config/system.yaml`: ana sistem tanımı
- `docs/overview.md`: proje ve sistem görünümü
- `scripts/validate.sh`: temel doğrulama betiği

## Durum
Sistem mevcut durumda aktif ve senkronize konumdadır.

## Notlar
- Orijinal dosya binary formatta geldi.
- Daha sonra okunur metin ve düzenli manifest biçimine dönüştürüldü.
- Bu yapı, genişletilebilir bir proje manifest olarak kullanılabilir.
