# 🔐 Şifre Çözücüler: Sezar ve Vigenère

Klasik şifreleme yöntemlerini deneyebileceğin ve dört seviyelik bir oyunla pekiştirebileceğin, tarayıcıda çalışan küçük bir web sitesi.

## Özellikler

- **Araç:** Sezar ve Vigenère şifreleme / çözme, Sezar için harf tablosu görseli, Vigenère için anahtar akışı gösterimi
- **Kaba kuvvet:** Sezar şifresinde 25 olasılığın hepsini tek tıkla listeleme
- **Oyun:** Dört seviyede gizli mesajları çözme (ipucu ve "araca gönder" desteğiyle)
- Koyu ve açık tema desteği, telefonda da çalışır
- Kurulum yok, sunucu yok, veriler tarayıcıdan çıkmaz

## Kullanım

`index.html` dosyasını tarayıcıda aç. Yayınlamak için **Settings → Pages** bölümünde branch olarak `main` ve `/ (root)` seç.

## Şifreler nasıl çalışır?

- **Sezar:** Her harf alfabede sabit sayıda kaydırılır. Anahtar uzayı yalnızca 25 olduğu için hepsini denemek kolaydır.
- **Vigenère:** Anahtar kelimenin harfleri sırayla kaydırma miktarı olarak kullanılır (A=0, B=1, ...). Sezar'dan güçlüdür ama anahtar kısaysa frekans analiziyle kırılabilir.

## Uyarı

Bu yöntemler tarihîdir ve bugün gerçek güvenlik için kullanılmaz. Gerçek verileri korumak için AES gibi modern algoritmalar kullanılır.

## Geliştirme fikirleri

- [ ] Frekans analizi grafiği
- [ ] Atbash ve ROT13 şifreleri
- [ ] Kendi mesajını şifreleyip paylaşma linki üretme
- [ ] Daha fazla seviye

## Not

Bu projeyi öğrenirken yapay zekadan yardım alarak geliştirdim.

## Lisans

MIT
