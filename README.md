# JARVIS-UNLXCAL7

Profesyonel, gelişmiş ve tamamen Gemini API tabanlı yapay zekâ masaüstü asistanı.

- Gemini API destekli
- Hafif ve optimize edilmiş yapı
- 4 GB RAM sistemlerde akıcı kullanım
- Windows odaklı optimize
- Gelişmiş otomasyon sistemi
- Görsel / müzik / video üretimi
- Ekran analizi
- Mouse & klavye kontrolü
- Kod yazabilen AI sistemi
- Developer araçları
- Gelişmiş hafıza sistemi
- Yerel log sistemi
- Güvenli kullanıcı kontrol sistemi

---

# Özellikler

## Yapay Zekâ Sistemi
- Gemini API entegrasyonu
- Çoklu Gemini model desteği
- Gerçek zamanlı AI yanıt sistemi
- Uzun süreli hafıza sistemi
- Dosya ve ekran analizi
- AI destekli otomasyon

---

## Medya Üretimi
- Görsel üretimi
- Video üretimi
- Müzik üretimi
- AI destekli içerik oluşturma
- Otomatik kaydetme sistemi

---

## Geliştirici Özellikleri
- Kod yazma
- Kod düzenleme
- Proje oluşturma
- Dosya yönetimi
- Terminal desteği
- Hata analizi
- Geliştirici modu

---

## Bilgisayar Kontrolü
- Mouse kontrolü
- Klavye kontrolü
- Ekran algılama
- Oyun otomasyonu
- UI algılama sistemi
- Güvenli kullanıcı onay sistemi

---

# Sistem Gereksinimleri

## Minimum
- Windows 10 / 11
- 4 GB RAM
- Python 3.11+
- İnternet bağlantısı

---

## Önerilen
- 8+ GB RAM
- SSD depolama
- NVIDIA GPU (opsiyonel)

---

# Kurulum

# 1. Python Kur

https://www.python.org/downloads/windows/

Kurulum sırasında:

- `Add Python to PATH`

seçeneğini işaretleyin.

Kontrol:

```powershell
python --version
```

---

# 2. Projeyi Çıkart

ZIP dosyasını örneğin:

```text
C:\Jarvis
```

konumuna çıkartın.

---

# 3. PowerShell Aç

Klasörde:

- Shift + Sağ Tık
- “PowerShell penceresini burada aç”

---

# 4. Sanal Ortam Oluştur

```powershell
python -m venv .venv
```

Aktifleştir:

```powershell
.\.venv\Scripts\activate
```

---

# 5. Pip Güncelle

```powershell
python -m pip install --upgrade pip wheel setuptools
```

---

# 6. Ana Paketleri Kur

```powershell
pip install -r requirements.txt
```

---

# 7. AI Paketlerini Kur

```powershell
pip install -r requirements_ai.txt
```

---

# 8. Opsiyonel Paketleri Kur

```powershell
pip install -r requirements_optional.txt
```

---

# 9. FFmpeg Kur

https://www.gyan.dev/ffmpeg/builds/

Kurulum:
- ZIP indir
- `C:\ffmpeg`
çıkar
- `bin` klasörünü PATH'e ekle

Kontrol:

```powershell
ffmpeg -version
```

---

# 10. Tesseract OCR Kur

https://github.com/UB-Mannheim/tesseract/wiki

Kurarken:
- English
- Turkish

dillerini seçin.

---

# 11. Ek Sistem Paketleri

```powershell
pip install pyautogui pillow mss psutil pynput pyperclip
```

---

# 12. Ses Paketleri

```powershell
pip install pyttsx3 sounddevice soundfile pydub
```

---

# 13. Görsel Üretim Paketleri

```powershell
pip install diffusers transformers accelerate safetensors
```

---

# 14. Video Üretim Paketleri

```powershell
pip install moviepy imageio imageio-ffmpeg opencv-python
```

---

# 15. Müzik Üretim Paketleri

```powershell
pip install audiocraft
```

---

# 16. Developer Araçları

```powershell
pip install black pylint autopep8 rich watchdog
```

---

# Gemini API Key Alma

Google AI Studio:

https://aistudio.google.com/app/apikey

Yeni API key oluşturun.

Örnek:

```text
AIzaSyxxxxxxxxxxxxxxxx
```

---

# Jarvis'i Çalıştır

```powershell
python main.py
```

veya:

```powershell
py main.py
```

---

# Debug Modu

```powershell
python main.py --debug
```

---

# Developer Modu

```powershell
python main.py --developer
```

---

# Hafıza Sistemi

```text
memory/
```

İçerik:
- uzun süreli hafıza
- kullanıcı tercihleri
- görev geçmişi
- AI kayıtları

---

# Log Sistemi

```text
logs/
```

İçerik:
- sohbet logları
- hata logları
- AI aksiyon logları
- ekran analiz kayıtları

---

# Üretim Klasörü

```text
generated/
```

İçerik:
- görseller
- videolar
- müzikler
- kod dosyaları

---

# Güvenlik Sistemi

Jarvis:
- ekranı analiz edebilir
- mouse kontrolü yapabilir
- klavye kullanabilir
- otomasyon çalıştırabilir

Ancak:
- kritik işlemler varsayılan olarak kapalıdır
- kullanıcı onayı gerekir
- allowlist sistemi vardır
- tüm işlemler loglanır

---

# Önerilen Ayarlar

- Safe Mode → Açık
- Vision Analysis → Açık
- Local Logs → Açık
- Mouse Automation → Kapalı
- Keyboard Automation → Kapalı

---

# Performans Tavsiyeleri

## 4 GB RAM
- Hafif mod önerilir
- Aynı anda çok işlem çalıştırmayın
- Video üretimini kapalı tutun

---

## 8+ GB RAM
- Tüm özellikler aktif kullanılabilir

---

# Desteklenen Gemini Modelleri

## Genel Kullanım
- gemini-2.5-flash
- gemini-2.5-pro

---

## Vision
- Gemini Vision modelleri

---

## Medya Üretimi
- Gemini medya üretim modelleri

---

# Profesyonel Özellikler

- Çoklu görev sistemi
- AI araç çağırma sistemi
- Gelişmiş ekran analizi
- AI destekli proje yönetimi
- Akıllı hafıza sistemi
- Gerçek zamanlı otomasyon
- Developer araç zinciri

---

# Lisans

Kişisel kullanım ve geliştirme amaçlıdır.

---

# Not

Bu proje:
- Gemini API kullanır
- Windows için optimize edilmiştir
- Düşük RAM kullanımına odaklanır
- Profesyonel AI otomasyonu sağlar
- Güvenli kullanıcı kontrol sistemi içerir
