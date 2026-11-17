# TA1FM BLE APRS Mesaj Paneli — BETA-6

[**HTTPS üzerinden BETA-6 panelini aç**](https://ta1fm.github.io/TA1FM-nrf52-Aprs-Tracker-Configurator/BETA/TA1FM_BLE_APRS_Mesaj_Paneli_BETA6.html) · [**HTML kaynak dosyası**](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker-Configurator/blob/main/BETA/TA1FM_BLE_APRS_Mesaj_Paneli_BETA6.html)

Bu dosya [eski V0.9.23 BETA ayar panelinden](../beta_v0_9_23.html) alınmış ayrı bir **deneysel sürümdür**. Stabil ana sayfa `index.html`, `ble.html` ve `beta_v0_9_23.html` değiştirilmedi.

## Kullanım

- Tracker'a [BETA-6 firmware](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/BETA/TA1FM_nrf52_Tracker_UNIVERSAL_BLE_V0_9_25_BETA6_BLE_MSG/TA1FM_nrf52_Tracker_UNIVERSAL_BLE_V0_9_25_BETA6_BLE_MSG.ino) yüklenmiş olmalı. Önce Arduino IDE ile derleyip donanımda test edin.
- HTTPS Web Bluetooth destekli tarayıcıda (Android Chrome / desteklenen masaüstü Chrome) açın, **Bluetooth ile bağlan** ve `nRF52_Lora_Tracker` cihazını seçin.
- Panelde **TA1FM APRS — Bluetooth ile Mesajlaşma (BETA-6)** bölümünden alıcı callsign ve 1–62 ASCII metin yazın; **RF MESAJI GÖNDER** seçin.
- **Cihazdan ek bir TX izni, ARM, fiziksel tuş onayı veya BLE ayar yazma kilidini açma gerekmiyor.**
- Gelen kutusunda son 10 mesajı, giden mesajda `QUEUED`, `WAIT_ACK`, `ACK_RECEIVED`, `ACK_TIMEOUT`, `REJECTED` durumlarını görebilirsiniz. Panel ayrıca kayıp mesaj bildirimlerine karşı periyodik olarak gelen kutusunu yeniler.
- RF yayınları amatör telsiz koşullarına uygun olmalı. BLE NUS bağlantısı eşleştirmesizdir: bu kullanım kolaylığının güvenlik karşılığı vardır.

**Test edilmemiş BETA:** HTML JavaScript sözdizimi doğrulandı, ancak tarayıcı/cihazda gerçek BLE denemesi henüz yapılmadı. `index.html` eski kararlı panel olarak kullanılmaya devam eder.

73 de TA1FM
