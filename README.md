# TA1FM nrf52 Tracker — USB + BLE Kontrol Paneli

## ✅ Güncel firmware: v1.3.0 STABLE (24 Kasım 2026)

**[🌐 Güncel USB/BLE Kontrol Panelini Aç](https://ta1fm.github.io/TA1FM-nrf52-Aprs-Tracker-Configurator/)**

Ana sayfadaki `index.html`, v1.3.0 STABLE firmware ile uyumlu **[birleşik v1.3.0 BETA2 paneline](./BETA/TA1FM_Tracker_Control_Panel_v1.3.0_BETA2.html)** yönlendirir. **BETA2**, panel dosyasının geliştirme sürümüdür; firmware'in **STABLE** durumunu değiştirmez. Panelin kendisine veya çalışan firmware mantığına müdahale edilmemiştir.

**[📦 v1.3.0 STABLE Release ve firmware indirmeleri](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/releases/tag/v1.3.0)** · [Firmware deposu](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker) · [v1.3.0 sürüm notları](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/RELEASE_NOTES_V1_3_0_STABLE.md)

## Panel Özellikleri

- **Tek USB/BLE bağlantısı:** Sekmeler arasında bağlantı korunur.
- **Durum / Sistem:** GPS, LoRa, BLE, pil, sayaçlar ve cihaz durumu.
- **APRS / GPS / Radyo:** SMART/FIXED beacon, Tracker/DIGI, sembol, SX1262/SX1268 ve RF ayarları.
- **Mesajlar:** Gönderim ve ACK durumu, gelen kutusu, hazır mesajlar ve tarayıcı oturumu boyunca gönderim geçmişi.
- **OLED / Bildirim:** Ekran, uyku, mesajla uyandırma ve isteğe bağlı buzzer.
- **Telemetri:** Pil ve isteğe bağlı BME280 ölçümleri; BME280 yoksa pil telemetrisi korunur.
- **DFU:** Uyumlu cihazı BLE DFU moduna alma; firmware ZIP aktarımı **Nordic DFU uygulamasıyla** yapılır.
- **Ayarlar:** Okuma, kaydetme ve JSON ayar yedeği.

## Bağlantı

**USB:** Chrome/Edge'de paneli açın, Arduino Seri Monitör'ü kapatın, cihazın USB COM portuna bağlanın ve ayarları okuyun.

**BLE:** HTTPS üzerinden Web Bluetooth destekleyen tarayıcı kullanın. `nRF52_Lora_Tracker` cihazına bağlanın. Değişiklikleri kaydetmeden önce **Kaydetme Açık** iznini etkinleştirin; bu, güçlü bir güvenlik doğrulaması değildir.

**APRS mesaj geçmişi:** Cihazda yalnızca son 3 gelen mesaj RAM'de tutulur; güç kesilince silinir. Web panelinin gönderim geçmişi de tarayıcı oturumuyla sınırlıdır.

## Belgeler

- [Türkçe kurulum](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/KURULUM_TR.md)
- [Türkçe kullanım](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/KULLANIM_TR.md)
- [Türkçe seri konsol komutları](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/SERI_KONSOL_KOMUT_REHBERI_TR.md)
- [English installation](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/INSTALL_EN.md)
- [English user guide](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/USER_GUIDE_EN.md)

## Eski paneller / Archive

- [Eski v1.2.0 STABLE paneli](./TA1FM_Tracker_Control_Panel_v1.2.0_STABLE.html)
- [v1.0.0 ana panel dosyası](./TA1FM_Tracker_Control_Panel.html)
- [BETA-7 sekmeli panel](./BETA/TA1FM_Tracker_Panel_BETA7_Sekmeli_USB_BLE.html)
- [v0.9.23 paneli](./beta_v0_9_23.html)

Eski dosyalar geri dönüş ve referans amacıyla korunmuştur. Güncel kullanımda **ana panel bağlantısını** tercih edin.

**73 de TA1FM 📡**
