# Privacy Policy — Kafa Tabu

**App name:** Kafa Tabu
**Package name:** `com.dreamlab.kafatabu`
**Developer:** Dreamlab
**Contact e-mail:** gbilgeturkapps@gmail.com
**Effective date:** 2026-05-23
**Last updated:** 2026-05-23

---

## English Version

### 1. Overview

Kafa Tabu ("the App") is a single-device, offline party game inspired by the
"Heads Up" format. This Privacy Policy explains what information the App
accesses, how it is used, and what rights you have. By installing or using the
App you agree to the terms below.

### 2. Information We Collect

**We do not collect, store, transmit, or share any personal data.**

The App does **not** request, collect, or process any of the following:

- Name, e-mail address, phone number, postal address, or any identifier that
  can be used to contact or identify you.
- Account credentials (the App has no user accounts and no sign-in).
- Precise or approximate location (GPS, Wi-Fi, IP-based, or cell-tower based).
- Contacts, calendar, SMS, call logs, microphone, camera, photos, files, or
  any other personal content stored on your device.
- Advertising identifiers (AAID/IDFA), Firebase/Google Analytics identifiers,
  device fingerprints, or any cross-app tracking IDs.
- Crash logs, telemetry, or diagnostic data sent to any remote server.
- Payment information (the App contains no in-app purchases).

### 3. Permissions Requested by the App

The App declares **only one** Android permission, and uses device sensors that
do not require user-granted permissions:

| Permission / Capability | Type | Why it is used |
|---|---|---|
| `android.permission.VIBRATE` | Normal (auto-granted) | Provides short haptic feedback when a round starts/ends or when the player tilts the phone to mark a correct/pass answer. Can be turned off inside the App settings. |
| Accelerometer (`Sensor.TYPE_ACCELEROMETER`) | No permission required | Detects whether the phone is held in the correct "heads up" position and detects forward/backward tilt to register a correct answer or a pass. Sensor readings are processed locally in memory and are **never** stored, transmitted, or logged. |
| Magnetometer (`Sensor.TYPE_MAGNETIC_FIELD`) | No permission required | Used together with the accelerometer to improve tilt-detection accuracy. Same rules as the accelerometer — values stay on the device, in memory only. |

The App does **not** declare or request:
`INTERNET`, `ACCESS_NETWORK_STATE`, `ACCESS_FINE_LOCATION`,
`ACCESS_COARSE_LOCATION`, `READ_CONTACTS`, `READ_EXTERNAL_STORAGE`,
`READ_MEDIA_*`, `CAMERA`, `RECORD_AUDIO`, `READ_PHONE_STATE`,
`POST_NOTIFICATIONS`, `READ_SMS`, or any other sensitive permission.

### 4. Data Stored Locally on Your Device

The App uses Android `SharedPreferences` to remember purely functional state
on **your device only**. Nothing in this storage leaves your phone.

| Stored item | Purpose |
|---|---|
| `onboarding_completed` (boolean) | So the introduction screen is not shown again after the first launch. |
| Game settings (round duration, max pass count, sound on/off, vibration on/off) | To remember your preferences between sessions. |

You can delete all this data at any time by clearing the App's storage from
**Android Settings → Apps → Kafa Tabu → Storage → Clear storage**, or by
uninstalling the App.

### 5. Internet Access

The App does **not** request the `INTERNET` permission and therefore cannot
make any network connection. No data is sent to the developer, to Google, or
to any third party at any time.

### 6. Third-Party Services and SDKs

The App contains **no** advertising SDKs, **no** analytics SDKs, and **no**
crash-reporting SDKs (no AdMob, no Firebase, no Google Analytics, no Meta
SDK, no Unity Ads, etc.).

The only third-party library used in the App is **Gson** (Apache License 2.0),
which is used solely to parse local JSON files that are bundled inside the App
package. Gson does not perform any network activity.

### 7. Sharing of Data

Because the App does not collect any personal data, there is **nothing to
share**. No data is sold, rented, transferred, or otherwise disclosed to any
third party, government, or affiliate.

### 8. Children's Privacy

The App is suitable for general audiences and does not knowingly collect any
personal information from children. The App does not contain in-app
advertising, in-app purchases, social features, chat, or user-generated
content, and complies with Google Play's Families policy in this respect.

### 9. Data Security

Since no personal data is collected or transmitted, there is no remote data
to be secured. Locally stored preferences are kept inside the App's private
sandbox provided by the Android operating system and are only accessible to
the App itself on a non-rooted device.

### 10. Your Rights (GDPR, CCPA, KVKK and similar laws)

We do not hold any personal data about you, so there is nothing to access,
correct, port, restrict, object to, or delete on our side. To remove all
locally stored state, you may clear the App's storage or uninstall the App
as described in Section 4.

### 11. International Users

The App can be downloaded worldwide. Because no personal data is collected
or transmitted, no international data transfer takes place.

### 12. Changes to This Policy

We may update this Privacy Policy from time to time, for example to reflect
changes to the App or to legal requirements. The "Last updated" date at the
top of this document will always reflect the most recent revision. Material
changes will also be announced inside the App and on this page.

### 13. Contact

If you have any questions about this Privacy Policy or about the App's
privacy practices, please contact:

**E-mail:** gbilgeturkapps@gmail.com

---

## Türkçe Sürüm

### 1. Genel Bakış

Kafa Tabu ("Uygulama"), "Heads Up" formatından esinlenen, tek cihazda ve
çevrimdışı oynanan bir parti oyunudur. Bu Gizlilik Politikası, Uygulama'nın
hangi bilgilere eriştiğini, bunları nasıl kullandığını ve haklarınızın neler
olduğunu açıklar. Uygulama'yı indirip kullanarak aşağıdaki şartları kabul
etmiş sayılırsınız.

### 2. Topladığımız Bilgiler

**Hiçbir kişisel veri toplamıyor, saklamıyor, iletmiyor veya
paylaşmıyoruz.**

Uygulama aşağıdakilerin **hiçbirini** talep etmez, toplamaz veya işlemez:

- İsim, e-posta, telefon numarası, posta adresi veya sizi tanımlamaya
  yarayan herhangi bir bilgi.
- Hesap bilgileri (Uygulama'da kullanıcı hesabı ve giriş yoktur).
- Konum bilgisi (GPS, Wi-Fi, IP veya baz istasyonu tabanlı, hassas veya
  yaklaşık).
- Rehber, takvim, SMS, arama kaydı, mikrofon, kamera, fotoğraf, dosya veya
  cihazınızdaki diğer kişisel içerikler.
- Reklam kimlikleri (AAID/IDFA), Firebase/Google Analytics kimlikleri,
  cihaz parmak izi veya uygulamalar arası takip kimlikleri.
- Uzak bir sunucuya gönderilen hata günlüğü, telemetri veya tanılama
  verisi.
- Ödeme bilgisi (Uygulama'da uygulama içi satın alma bulunmaz).

### 3. Uygulamanın İstediği İzinler

Uygulama yalnızca **tek bir** Android izni tanımlar ve kullanıcı izni
gerektirmeyen cihaz sensörlerini kullanır:

| İzin / Yetenek | Türü | Kullanım amacı |
|---|---|---|
| `android.permission.VIBRATE` | Normal (otomatik verilir) | El başlangıcında/sonunda veya oyuncu telefonu doğru/pas için eğdiğinde kısa titreşim verir. Uygulama ayarlarından kapatılabilir. |
| İvmeölçer (`Sensor.TYPE_ACCELEROMETER`) | İzin gerekmez | Telefonun doğru "heads up" pozisyonda tutulup tutulmadığını ve doğru/pas hareketini algılamak için kullanılır. Sensör verileri yalnızca bellekte, yerel olarak işlenir; **asla** saklanmaz, iletilmez veya günlüğe alınmaz. |
| Manyetometre (`Sensor.TYPE_MAGNETIC_FIELD`) | İzin gerekmez | Eğim algılama doğruluğunu artırmak için ivmeölçerle birlikte kullanılır. Veriler yalnızca cihazda, bellektedir. |

Uygulama aşağıdakilerin **hiçbirini** talep etmez:
`INTERNET`, `ACCESS_NETWORK_STATE`, `ACCESS_FINE_LOCATION`,
`ACCESS_COARSE_LOCATION`, `READ_CONTACTS`, `READ_EXTERNAL_STORAGE`,
`READ_MEDIA_*`, `CAMERA`, `RECORD_AUDIO`, `READ_PHONE_STATE`,
`POST_NOTIFICATIONS`, `READ_SMS` veya başka herhangi bir hassas izin.

### 4. Cihazınızda Yerel Olarak Saklanan Veriler

Uygulama, **yalnızca cihazınızda** kalan işlevsel durumu hatırlamak için
Android `SharedPreferences` kullanır. Bu alandaki hiçbir bilgi telefonunuzdan
çıkmaz.

| Saklanan veri | Amacı |
|---|---|
| `onboarding_completed` (boolean) | İlk açılıştan sonra tanıtım ekranını tekrar göstermemek için. |
| Oyun ayarları (tur süresi, pas hakkı sayısı, ses açık/kapalı, titreşim açık/kapalı) | Tercihlerinizi oturumlar arasında hatırlamak için. |

Bu verileri istediğiniz zaman **Android Ayarlar → Uygulamalar → Kafa Tabu →
Depolama → Depolamayı temizle** yoluyla veya Uygulama'yı kaldırarak
silebilirsiniz.

### 5. İnternet Erişimi

Uygulama `INTERNET` iznini talep etmez ve bu nedenle herhangi bir ağ
bağlantısı kuramaz. Hiçbir zaman geliştiriciye, Google'a ya da üçüncü bir
tarafa veri gönderilmez.

### 6. Üçüncü Taraf Servisleri ve SDK'lar

Uygulama'da **hiçbir** reklam SDK'sı, **hiçbir** analitik SDK'sı ve
**hiçbir** çökme raporlama SDK'sı bulunmaz (AdMob yok, Firebase yok, Google
Analytics yok, Meta SDK yok, Unity Ads yok vb.).

Uygulama'da kullanılan tek üçüncü taraf kütüphane **Gson** (Apache Lisansı
2.0) olup yalnızca Uygulama paketinin içine gömülü yerel JSON dosyalarını
ayrıştırmak için kullanılır. Gson hiçbir ağ etkinliği yapmaz.

### 7. Veri Paylaşımı

Uygulama herhangi bir kişisel veri toplamadığı için **paylaşılacak bir şey
yoktur.** Hiçbir veri satılmaz, kiralanmaz, aktarılmaz veya başka bir üçüncü
tarafa, devlete ya da iş ortağına ifşa edilmez.

### 8. Çocukların Gizliliği

Uygulama genel kitleye uygundur ve bilerek çocuklardan kişisel bilgi
toplamaz. Uygulama içinde reklam, uygulama içi satın alma, sosyal özellik,
sohbet veya kullanıcı tarafından üretilen içerik bulunmaz ve bu konuda
Google Play Aileler politikasıyla uyumludur.

### 9. Veri Güvenliği

Hiçbir kişisel veri toplanmadığı veya iletilmediği için uzak sunucuda
korunacak veri yoktur. Yerel olarak saklanan tercihler, Android işletim
sisteminin sağladığı, yalnızca Uygulama'nın kendisine erişilebilir olan özel
sandbox içinde tutulur (root yapılmamış cihazlarda).

### 10. Haklarınız (KVKK, GDPR, CCPA ve benzeri mevzuat)

Sizin hakkınızda hiçbir kişisel veri tutmadığımız için tarafımızda erişim,
düzeltme, taşıma, sınırlama, itiraz veya silme talep edilebilecek bir veri
bulunmamaktadır. Cihazınızda yerel olarak saklanan tüm durumu silmek için
4. bölümde açıklandığı gibi Uygulama'nın depolamasını temizleyebilir veya
Uygulama'yı kaldırabilirsiniz.

### 11. Uluslararası Kullanıcılar

Uygulama dünya çapında indirilebilir. Hiçbir kişisel veri toplanmadığı veya
iletilmediği için uluslararası veri transferi gerçekleşmez.

### 12. Bu Politikadaki Değişiklikler

Bu Gizlilik Politikası, Uygulama'daki veya yasal gerekliliklerdeki
değişiklikleri yansıtmak amacıyla zaman zaman güncellenebilir. Belgenin
üstündeki "Son güncelleme" tarihi her zaman en son revizyonu gösterir.
Önemli değişiklikler ayrıca Uygulama içinde ve bu sayfada duyurulur.

### 13. İletişim

Bu Gizlilik Politikası veya Uygulama'nın gizlilik uygulamaları hakkında
sorularınız için bizimle iletişime geçebilirsiniz:

**E-posta:** gbilgeturkapps@gmail.com
