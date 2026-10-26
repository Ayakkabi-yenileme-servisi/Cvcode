# Zombi

Zombi, yüksek zekâ tabanlı ve senkronize edilmiş bir sistem tanımıdır. Bu proje, sistemin metaverisini, durum akışını ve güvenlik/izin yapılandırmasını tek bir noktada yönetmeye odaklanır.

## Hedef
- Durum takibi
- Metaveri yönetimi
- Modül bazlı yapı
- Güvenlik ve erişim denetimi
- Doğrulama ve bakım kolaylığı

## Yapı
- `config/system.yaml`: ana yapılandırma
- `docs/overview.md`: açıklama dokümanı
- `scripts/validate.sh`: doğrulama betiği

## Kullanım
Aşağıdaki komut ile sistem yapısını doğrulayabilirsiniz:

```bash
bash scripts/validate.sh
```

## Durum
Aktif ve senkronize.
