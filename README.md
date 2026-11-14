# REI 3.0.2 — Windows ve Android Uygulama İndirmeleri

**REI**, Windows 11 için yerel Python/PySide6 ile geliştirilmiş **%100 Türkçe** kişisel masaüstü yapay zekâ asistanı, komuta merkezi, **60 FPS kamera/el kontrolü** ve **Kaedehara Kazuha** masaüstü maskotu uygulamasıdır. Doğrudan yerel REI.exe olarak çalışır (tarayıcı sarmalayıcısı değildir).

## Son Sürüm: [REI 3.0.2 (Kararlı / Latest)](https://github.com/jagwey/rei-releases/releases/tag/v3.0.2)

- **Kurulum sihirbazı (önerilen):** [REI-Setup-3.0.2.exe](https://github.com/jagwey/rei-releases/releases/download/v3.0.2/REI-Setup-3.0.2.exe) — Windows kullanıcı hesabına (%LOCALAPPDATA%\Programs\REI) kurulur, yönetici izni gerektirmez.
- **Taşınabilir paket:** [REI-Portable-3.0.2.zip](https://github.com/jagwey/rei-releases/releases/download/v3.0.2/REI-Portable-3.0.2.zip) — Arşivi tamamen çıkarıp REI/REI.exe dosyasını _internal klasörüyle birlikte çalıştırın.
- **Android eşlikçi:** [REI-Android-1.2.4.apk](https://github.com/jagwey/rei-releases/releases/download/v3.0.2/REI-Android-1.2.4.apk) — İmzalı com.jagwey.rei.companion APK.
- **Doğrulama & Bütünlük:** [erification.txt](https://github.com/jagwey/rei-releases/releases/download/v3.0.2/verification.txt) · [SHA256SUMS.txt](https://github.com/jagwey/rei-releases/releases/download/v3.0.2/SHA256SUMS.txt)

## Bu Sürümdeki Yenilikler (3.0.2)

- **Kaedehara Kazuha Masaüstü Maskotu ve Uygulama İkonu:** 13 animasyon grubu ve 56 şeffaf 128×128 piksel kare (idle, walk, 
un, 	alk, 	hink, sleep, wind_jump, all, plunge, glide, climb, urst, leaf_flute). wind_jump (Chihayaburu E yeteneği) 5 aşamalı rüzgâr yükselişi ve inişiyle pencere hareketini senkronize eder. Varsayılan karakter boyu 88 px olup Ayarlar → Karakter bölümünden değiştirilebilir; pencere, görev çubuğu, sistem tepsisi ve kısayolların tamamı kazuha.ico kullanır.
- **%100 Türkçe Arayüz ve Kurulum:** Çalışma alanı, HUD kontrol paneli, tüm ayar sekmeleri (1.345 katalog girişi), Google/API entegrasyonları ve Inno Setup sihirbazı tamamen Türkçe.
- **60 FPS Hızlı Kamera ve El Kontrolü:** Adaptif OneEuro filtresi, hızlı harekette ölü bölge atlama, 1–2 kare kayıp telafisi ve **Hızlı / Dengeli** takip modu. Kamera görüntüleri bilgisayardan dışarı gönderilmez.
- **Bağlantılar ve Ajanlar:** Google Takvim/Gmail/Drive/Kişiler/Tasks, Spotify, YouTube Music, Telegram, Discord, WhatsApp Web, X, GitHub, yerel OpenJarvis, Android köprüsü ve Claude Code / Codex / Gemini / Groq / OpenRouter / Ollama desteği.

> Bu depo yalnızca herkese açık uygulama indirme paketlerini, SHA-256 özetlerini ve doğrulama belgelerini barındırır; özel kaynak kodu jagwey/rei deposundadır. Paketler kod imzalama sertifikası içermediğinden Windows SmartScreen uyarısı gösterebilir.
