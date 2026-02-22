# Liman MYS 2.0 – Kurulum ve Yönetim Script’i

**Açık Kaynak Yazılım Geliştirme** dönem projesi. Liman MYS 2.0 sunucusu için parametre tabanlı kurulum, kaldırma ve sıfırlama işlemlerini yapan bir shell script’idir.

## Parametreler

| Parametre | Açıklama |
|-----------|----------|
| `build` | Liman MYS 2.0 kurulumunu başlatır |
| `remove` | Liman kurulumunu kaldırır |
| `admin` | Admin şifresini sıfırlar |
| `reset` | Kullanıcı şifresini sıfırlar |
| `help` | Script kullanım bilgisi ve parametreleri listeler |

Hiç parametre verilmezse kullanıcıya hata mesajı gösterilir ve `help` komutunun çalıştırılması önerilir.

## Gereksinimler

- Bash ortamı
- Liman MYS 2.0 ile uyumlu bir Linux ortamı

## Çalıştırma

Script’i doğrudan çalıştırmak için önce çalıştırma izni verin:

```bash
chmod +x liman.sh
./liman.sh [parametre]
```

Örnek:

```bash
./liman.sh build    # Kurulum
./liman.sh help     # Yardım
./liman.sh admin    # Admin şifresi sıfırlama
```

Her işlem sonunda script, işlemin başarılı olup olmadığı hakkında bilgi verir (örneğin: “PostgreSQL kuruldu” / “kurulamadı”).

## Proje bilgisi

- **Ders:** Atatürk Üniversitesi – Açık Kaynak Yazılım Geliştirme (Dönem Projesi)
- **Sahip:** [@mustafaceliker](https://github.com/mustafaceliker)
