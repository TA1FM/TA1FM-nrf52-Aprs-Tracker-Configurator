# TA1FM nrf52 Tracker — USB + BLE Web Configurator

**Güncel panel / Current panel: V0.9.22**

**[Web panelini aç / Open the web configurator](https://ta1fm.github.io/TA1FM-nrf52-Aprs-Tracker-Configurator/)**

Bu GitHub Pages projesindeki **`index.html`** güncel **V0.9.22 USB + BLE** panelidir. Aynı arayüz USB ve Bluetooth üzerinden cihaz ayarlarını okuyup yazmayı destekler. **`ble.html`** dosyası önceki sürümlerden kalan ayrı bağlantıdır; **güncel kullanım için ana sayfa** önerilir.

## USB üzerinden kullanım

1. Bilgisayarda **Chrome veya Edge** açın.
2. Tracker'ı USB veri kablosuyla bağlayın. Arduino Seri Monitör/başka uygulamanın aynı COM portunu kullanmadığından emin olun.
3. **Cihaza bağlan → Cihazdan oku (p)** ile gerçek ayarları alın.
4. Ayarları düzenleyip **Ayarları cihaza yaz** seçin; başarı mesajını ve yeniden okuma sonucunu doğrulayın.

## Bluetooth BLE üzerinden kullanım

1. Android Chrome'da sayfayı **HTTPS** ile açın; Bluetooth'u etkinleştirin.
2. **Bluetooth ile bağlan** düğmesinden **nRF52_Lora_Tracker** cihazını seçin.
3. **BLE Ayarları Oku** ile mevcut değerleri alın.
4. PIN yoktur: **Kaydetme açık** anahtarını açıp **BLE Ayarları Kaydet** kullanın.
5. Kaydetmeden veya bağlantı koptuktan sonra anahtar kapanır. Bu anahtar güvenlik şifresi değildir; eşleştirmesiz BLE UART güçlü erişim koruması sağlamaz.

## V0.9.22'de desteklenen ayarlar

- Çağrı işareti, AUTO, SMART/FIXED ve altı Smart Beacon zaman aralığı
- WX/Status/Comment periyotları ve metinleri
- Ayrı hareket/park iki karakterli APRS sembolleri (`/>` ve `\P` örnekleri)
- SX1262/SX1268 LoRa çip seçimi (**değişiklikten sonra cihazı yeniden başlatın**)
- SH1106/SSD1306 OLED sürücüsü, ekran zamanlayıcısı
- RF çıkış hedefi (1–22 dBm), pil voltajı, ilk hareket konum isteği
- JSON ayar yedeği ve geri yükleme (geri yükleme yalnızca formu doldurur; cihaza ayrıca kaydedin)

**OLED notu:** BLE ile sürücü seçimi 20 saniye önizleme olmadan kalıcı kaydedilir; yanlış seçimde açılışta **3 saniye menü tuşuyla** ekran kurtarma kullanılabilir. USB tarafında önceki önizleme/onay yolu korunur.

**RF notu:** V0.9.22 firmware ardışık LoRa RF paketleri arasında **minimum 15 saniye** koruma uygular. Comment konum paketine eklenir; Status ayrı pakettir.

## Kaynak kodu ve kullanım kılavuzu

- **[Tracker firmware V0.9.22 — UF2 + INO](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker)**
- [Türkçe kullanım kılavuzu](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/KULLANIM_TR.md)
- [Türkçe kurulum](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/KURULUM_TR.md)
- [English user guide](https://github.com/TA1FM/TA1FM-nrf52-Aprs-Tracker/blob/main/USER_GUIDE_EN.md)

**73 de TA1FM**
