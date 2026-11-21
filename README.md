# NuvioMG

**NuvioMG**, Android TV ve Google TV cihazları için geliştirilmiş, Nuvio tabanlı medya oynatma uygulamasıdır.

Uygulama, televizyon kumandasıyla kullanım öncelikli olacak şekilde tasarlanmıştır. D-pad navigasyonu, odak yönetimi ve TV ekranlarına uygun arayüz sunar.

## Özellikler

- Android TV ve Google TV desteği
- Kumanda ve D-pad odaklı navigasyon
- Canlı TV ve VOD
- Film ve dizi içerikleri
- Nuvio eklenti sistemi ve uzak eklenti senkronizasyonu
- TMDB entegrasyonu ve IMDb kimlik çözümlemesi
- Supabase bağlantısı
- GitHub oynatma listesi desteği
- Profil ve kullanıcı verileri
- Medya oynatma ve altyazı desteği

## Proje Bilgileri

| Özellik | Değer |
|---|---|
| Uygulama adı | NuvioMG |
| Paket adı | `com.nuviomg.tv` |
| Sürüm | `1.2.0-beta.1` |
| Mimari | ARM32 (`armeabi-v7a`) |
| Platform | Android TV / Google TV |
| Kullanım | TV kumandası |

## NuvioMG Tablet Sürümünden Farkı

NuvioMG Android TV ve NuvioMG Tablet birbirinden bağımsız iki uygulamadır.

- TV projesi: `NuvioMG`
- Tablet projesi: `NuvioMGTablet`
- TV sürümü kumanda kullanımına öncelik verir.
- Tablet sürümü dokunmatik kullanıma öncelik verir.
- Uygulamaların paket adları ve imzalama anahtarları ayrıdır.
- Birbirlerinin üzerine kurulmadan aynı cihazda bulunabilirler.

## Derleme

Windows ortamında proje klasörüne geç:

```powershell
cd E:\python\iptv\NuvioMG
```

Full Debug APK oluştur:

```powershell
.\gradlew.bat :app:assembleFullDebug
```

APK çıktısı:

```text
app\build\outputs\apk\full\debug\
```

Örnek APK adı:

```text
app-full-armeabi-v7a-debug.apk
```

## Gereksinimler

- Android Studio / Android SDK
- Projede tanımlı JDK ve Gradle sürümleri
- ARM32 destekli Android TV veya Google TV cihazı
- Gerekli yerel yapılandırma ve API ayarları

## Güvenlik

- `local.properties` dosyasını GitHub'a yüklemeyin.
- TMDB ve Supabase anahtarlarını açık şekilde paylaşmayın.
- İmzalama anahtarlarını ve parolalarını güvenli saklayın.
- Gizli yapılandırma dosyalarını kaynak depodan uzak tutun.

## Proje Dizini

```text
NuvioMG/
├── app/
├── gradle/
├── assets/
├── keystore/
├── local.properties
├── settings.gradle.kts
├── build.gradle.kts
└── README.md
```

## Kaynak Projeler

- Upstream: https://github.com/zoga2o3-ops/Nuvio-One
- NuvioMG: https://github.com/PRoDi79/NuvioMG

NuvioMG, kendi uygulama kimliği ve proje değişiklikleriyle bağımsız olarak geliştirilmektedir.

---

**NuvioMG – Android TV için kumanda odaklı medya deneyimi.**


# NuvioMG

Nuvio tabanlı Android TV uygulaması.

APK dosyaları Releases bölümünde yayınlanır.
