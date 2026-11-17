# TA1FM nrf52 Tracker — USB + BLE Control Panel

## ✅ Güncel ana panel / Current control panel

**[🌐 TA1FM Tracker Control Panel — Aç / Open](https://ta1fm.github.io/TA1FM-nrf52-Aprs-Tracker-Configurator/)**

**Ana HTML:** [TA1FM_Tracker_Control_Panel.html](./TA1FM_Tracker_Control_Panel.html) · **index.html** bu dosyaya yönlendirir.

Bu panel, **TA1FM nrf52 Tracker v1.0.0 STABLE** ile kullanılan **BETA-7 tabanlı USB + BLE sekmeli arayüzdür**. Ana sayfa artık eski v0.9.22 paneli değildir.

**[🚀 v1.0.0 STABLE firmware ve indirmeler](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/releases/tag/v1.0.0)** · [Firmware deposu](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker)

## Panel sekmeleri

- **Mesajlar:** USB veya BLE üzerinden APRS mesaj gönderme/alma, gelen kutusu ve ACK takibi; 1/2/3 toplam RF denemesi seçimi.
- **Canlı:** GPS, RF, pil, son duyulan istasyon, sayaçlar ve BLE canlı durum.
- **Ayarlar:** Cihaz yapılandırması, SMART Beacon, LoRa seçimi, OLED ve JSON ayar yedeği.
- **Kayıtlar:** USB seri kayıtları; BLE haberleşme kayıtları Canlı bölümünde.

**Not:** Mesajlar yalnızca cihazın RAM'inde tutulur; kapatıp açınca geçmiş silinir. Panelden mesajlaşma özellikleri için **v1.0.0 (V0.9.26 BETA-7 tabanlı)** veya uyumlu firmware kullanın.

## USB ile bağlantı

1. Bilgisayarda USB Web Serial destekleyen **Chrome veya Edge** açın ve cihazı veri kablosuyla bağlayın.
2. Arduino IDE Seri Monitör gibi aynı COM portunu kullanan uygulamaları kapatın.
3. **USB ile bağlan** işlemini yapıp ayarları cihazdan okuyun. Değişiklikleri göndermeden önce doğru cihazın bağlı olduğundan emin olun.
4. Mesajlar sekmesinde iletişim için **USB** bağlantısını seçin.

## Bluetooth BLE ile bağlantı

1. Bluetooth açıkken, BLE erişimi destekleyen tarayıcıda paneli **HTTPS** üzerinden açın.
2. **nRF52_Lora_Tracker** cihazını seçerek BLE bağlantısı kurun.
3. Canlı bilgileri veya ayarları okuyun; Mesajlar bölümünde iletişim için **BLE** bağlantısını seçin.
4. Ayar kaydetmek gerektiğinde **Kaydetme Açık** anahtarını kullanın. Bu bir parola/güvenlik önlemi değildir.

## Önceki paneller / Archive

- [BETA-7 sekmeli panel kopyası](./BETA/TA1FM_Tracker_Panel_BETA7_Sekmeli_USB_BLE.html)
- [BETA-7 panel notları](./BETA/README_BETA7_SEKMELI_TR.md)
- [v0.9.23 eski panel](./beta_v0_9_23.html)
- [v0.9.22 ve daha eski BLE panel dosyaları](./ble.html)

Eski paneller arşiv amaçlı korunur. Güncel kullanım için **ana bağlantıyı** kullanın.

## Dokümantasyon

- [Türkçe kurulum](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/KURULUM_TR.md) *(eski sürüm ayrıntıları içerebilir)*
- [Türkçe kullanım](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/KULLANIM_TR.md) *(eski sürüm ayrıntıları içerebilir)*
- [English user guide](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/USER_GUIDE_EN.md) *(may describe older versions)*

**73 de TA1FM** 📡
