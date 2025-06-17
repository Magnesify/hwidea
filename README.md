# HWIDEA - HWID Yönetim ve Lisans Doğrulama Aracı

HWIDEA, sistem donanım kimliği (HWID) yönetimi ve lisans doğrulama işlemlerini kolaylaştıran bir komut satırı aracıdır.

## Özellikler

- Sistem HWID'sini görüntüleme
- Kullanıcı kimlik doğrulama
- HWID lisans kontrolü ve yükleme
- Kullanıcı lisanslarını listeleme

## Gereksinimler

- Rust 1.70 veya üzeri
- Cargo (Rust paket yöneticisi)

## Kullanım

### HWID Görüntüleme
```bash
hwidea show-hwid
```

### Kullanıcı Girişi
```bash
hwidea auth --email your.email@example.com --password yourpassword
```

### Lisans Kontrolü
```bash
hwidea check YOUR_INTERACTION_CODE
```

### Lisansları Listeleme
```bash
hwidea licenses
```

## Güvenlik Uyarısı

⚠️ **ÖNEMLİ UYARI**

Bu yazılım, sistem donanım kimliği (HWID) yönetimi ve lisans doğrulama işlemleri için tasarlanmıştır. Kullanımı sırasında aşağıdaki güvenlik önlemlerine dikkat edilmelidir:

1. Kimlik bilgilerinizi (e-posta ve şifre) güvenli bir şekilde saklayın.
2. Oturum token'larınızı başkalarıyla paylaşmayın.
3. Lisans kodlarınızı güvenli bir şekilde muhafaza edin.
4. Yazılımı sadece güvenilir kaynaklardan indirin.
5. Sistem yöneticisi izinleri gerektiren işlemleri dikkatli bir şekilde gerçekleştirin.

## Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.
