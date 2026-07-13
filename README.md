# Pratik Teklif — Kurulum Paketleri

Bu depo yalnızca **Pratik Teklif** masaüstü uygulamasının kurulum paketlerini barındırır.
Kaynak kod bu depoda değildir.

Buradaki paketler imzalıdır: uygulama, güncellemeyi kurmadan önce paketin imzasını kendi
içindeki açık anahtarla doğrular. İmzası doğrulanamayan bir paket indirilse bile kurulmaz.

## Kurulum

En son sürümü [Releases](../../releases/latest) sayfasından indirin.

| Dosya | Nerede kullanılır |
| --- | --- |
| `.AppImage` | Linux (indirin, çalıştırma izni verin, çift tıklayın) |
| `.deb` | Debian / Ubuntu türevleri |
| `.exe` / `.msi` | Windows |

Uygulama kurulduktan sonra yeni sürümleri kendisi bulur: açılışta sessizce bakar ve
Ayarlar > Güncelleme'den istediğiniz zaman kontrol edebilirsiniz. İndirme onayınız
olmadan başlamaz ve güncellemeden önce verilerinizin yedeği alınır.
