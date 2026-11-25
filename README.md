<p align="center"><img src="icon.png" width="128" alt="MeerFrame"></p>

# MeerFrame

Seslendirme + SRT + numaralı görsel/video dosyalarından hazır video üreten **ücretsiz ve çevrimdışı** masaüstü uygulaması (macOS ve Windows).

> **Önceki adı CueCut.** 0.1.0 sürümü CueCut adıyla yayınlandı; o sürümün dosyaları `CueCut-…` diye başlar. Yeni sürümler MeerFrame adını taşır. MeerFrame, Meerimo Studio'nun içinde de bir modül olarak çalışır.

SRT'nin 1. bloğu `01` dosyasına, 2. bloğu `02` dosyasına oturur; sahne süreleri altyazı zamanlarına kilitlenir. Kamera hareketi, geçiş, renk tonu ve altyazı stili seçilir, video MP4 veya WebM olarak dışa aktarılır. Hesap, sunucu ya da internet bağlantısı gerekmez.

## İndir

**[Son sürüm →](https://github.com/meerimo/meerframe-releases/releases/latest)**

| Sistem | Dosya |
|---|---|
| macOS – Apple Silicon (M1 ve sonrası) | `MeerFrame-<sürüm>-mac-arm64.dmg` |
| macOS – Intel | `MeerFrame-<sürüm>-mac-x64.dmg` |
| Windows 10/11 (çoğu bilgisayar) | `MeerFrame-<sürüm>-win-x64.exe` |
| Windows on ARM | `MeerFrame-<sürüm>-win-arm64.exe` |

### İlk açılış

Uygulama ücretli geliştirici sertifikasıyla imzalanmadığı için ilk açılışta bir uyarı çıkar:

- **macOS:** `.dmg`'yi açıp MeerFrame'i Applications klasörüne sürükle. "Geliştirici doğrulanamadı" uyarısında uygulamaya **sağ tık → Aç**. macOS 15 ve sonrasında: Sistem Ayarları → Gizlilik ve Güvenlik → **Yine de Aç**.
- **Windows:** SmartScreen uyarısında **Ek bilgi → Yine de çalıştır**.

## Özellikler

- SRT'ye kilitli sahneler; `03-05.png` gibi aralıkla bir görsel birden fazla bloğa yayılır
- Canlı önizleme, sürükleyerek sıra değiştirme, sahne bazında ayar
- 9 kamera hareketi, 8 geçiş (tek ya da karışık), 5 renk tonu
- 7 altyazı stili (karaoke, kelime kelime, vurgu kutusu, Shorts iri kelimeler…)
- MP4 (H.264 + AAC) / WebM, 720p–4K, 24–60 fps, gerçek zamandan hızlı dışa aktarım
- Proje kaydet/aç (`.meerframe`; eski `.cuecut` projeleri de açılır), Türkçe ve İngilizce arayüz

Bu depo yalnızca kurulum dosyalarını barındırır. Uygulama açılışta (isteğe bağlı) buradaki son sürümü denetler.
