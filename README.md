# Atölye

Müfredat konularından tahtada dokunarak çalışılan simülasyonlar. Her atölye tek HTML dosyası: internet istemez, hesap yok, kurulum yok.

Bütün atölyeler: https://herkeseegitim.github.io/atolye/
Nasıl kullanıldığını YouTube'da gösteriyorum: https://www.youtube.com/@egitimtek

## Atölyeler

| Ders | Sınıf | Kazanım | Atölye |
|---|---|---|---|
| Fen Bilimleri | 8 | F.8.5.1.1, F.8.5.1.2 (2027-28'den itibaren FB.8.2) | [Basit Makineler Atölyesi](https://herkeseegitim.github.io/atolye/fen-8-f-8-5/) |
| Bilişim Teknolojileri ve Yazılım | 5 | BTY.5.1.5 | [Bilgisayarın İçi Atölyesi](https://herkeseegitim.github.io/atolye/bty-5-1-5/) |

Her atölye kendi klasöründe durur. Klasör adı ders, sınıf ve o yıl okutulan programdaki kazanım kodundan gelir (ör. `fen-8-f-8-5`).

## Basit Makineler Atölyesi

8. sınıf, "Yaşamı Kolaylaştıran Kuvvet" ünitesi.

- **Atölye:** 8 görev. Sabit makara, hareketli makara, palanga, kaldıraç, eğik düzlem, çıkrık, bisiklet dişlileri, bileşik makine. Öğrenci önce tahmin eder, düzeneği kurar, ipi ya da kolu parmağıyla çeker, sonra ne fark ettiğini seçer. Dinamometre giriş kuvvetini, iki iş çubuğu senin işinle yüke yapılan işi gösterir. İki çubuk her makinede eşit kalır.
- **Yeni kanıt:** Kaldıraç ve çıkrıkta koşul değişir; öğrenci düzeneği yeniden kurar.
- **Sınıflandır:** 18 günlük araç, 6 grup.
- **Etiketle:** Makas, el arabası ve cımbızda destek, yük, kuvvet.
- **Öğretmen:** İki ders akışı ve yaygın düşünceler tablosu.

Makara ağırlığı ve sürtünme önemsiz sayılır; ağırlıklar Newton ile verilir.

Kaydetmek için: adresi açın, Ctrl+S ile bilgisayara ya da USB belleğe kaydedin. Tahtada denemeden önce aynı klasördeki tanı sayfası (`tani.html`) tahtanın dokunmayı nasıl ilettiğini ölçer.

### Hangi ortamlarda denendi

Laboratuvarda: Chrome ve Edge'in motoru (Chromium) ile 1024×768'den 4K'ya kadar, SMART 4K %100/%150/%200 ve FATİH 1080p profilleri, kızılötesi çerçeve öykünmesi (titreyen parmak, avuç, iki kişi), ETAP'taki Firefox sürümlerine yakın 75, 88, 113 ve 136 (dokunma fare gibi gelirse de), 6 kat yavaş işlemci. Gerçek tahtada henüz denenmedi.

## Bilgisayarın İçi Atölyesi

5. sınıf Bilişim Teknolojileri ve Yazılım, BTY.5.1.5 (Bilgisayar sistemlerini çözümleyebilme). Merak sorusu: "Kaydetmeden kapattın. Yazdığın nereye gitti?"

- **3B sahne:** Masa, monitör, klavye ve camı açılabilen bir kasa. Parçalar gerçek ölçülerle Blender'da modellendi.
- **Rehberli ders:** Öğrenci bir cümle yazar. Klavye giriş birimi, ekran çıkış birimi. Harfler bit olarak RAM'e gider; fiş çekilince RAM boşalır; Kaydet'e basınca işletim sistemi bitleri depolama birimine yazar; açılışta işletim sistemi depolama biriminden RAM'e gelir.
- **Deney masası:** Kaydet, Dosyayı aç, Kapat komutu, Güç düğmesi, Fişi çek/tak. Beş görev; kanıt simülasyonun durumundan okunur: fiş çekilince cümle kalsın, 01000001 ile A yaz, MERHABA kaç bayt ve hafıza birimlerinin sırası, Kapat komutunun sorusu, parçaları tanı (donanım/yazılım, iç/dış, giriş/çıkış).
- **İşletim sistemi:** Görevleri ve "her işletim sistemi paralı mı" sorusu.
- **Daha ileri:** Yarım kalan kayıt, Türkçe harflerin baytları, USB bellek, dosya sistemi, sekiz günlük durumla "Hangisi?".
- **Öğretmen:** Boşluk ile durdur, Yavaş, 1–8 adımlar, R baştan. Sorun bildir: Gmail ya da Outlook taslağı, karekod.

Gösterimde her yongada bir bayt çizilir; gerçek yongada milyarlarca hücre vardır, metin bunu söyler. Simülasyon Türkçe harfleri UTF-8 ile 2 baytta saklar (Ş, ğ, ı).

Kaydetmek için: adresi açın, Ctrl+S ile bilgisayara ya da USB belleğe kaydedin. Dosya yaklaşık 2 MB.

### Hangi ortamlarda denendi

Laboratuvarda: Chromium ile 1280×720, 1366×625, 1280×600, 1024×768, 1920×1080, 390×844 ve 844×390. ETAP'taki eski Firefox sürümlerinde ve gerçek tahtada henüz denenmedi. 3B sahne için WebGL 2 gerekir; yoksa tarayıcıyı güncelleme notu çıkar.

Kullanılan kütüphaneler ve yazı tipi: three.js (MIT), qrcode-generator (MIT, Kazuhiko Arase), Nunito (SIL Open Font License 1.1).

## Konu isteği

Sınıfınızın konusunu, sınıfı ve öğrenme çıktısı kodunu yazın: herkeseegitimtek@gmail.com. Her hafta gelen isteklerden birini seçip atölyesini yapıyoruz.

## Eksik ya da yanlış

Bir atölyede kavram, terim ya da kazanım açısından eksik gördüğünüz yeri herkeseegitimtek@gmail.com adresine yazın. Düzeltip güncelliyoruz.

## Katkı verenler

Düzeltme öneren öğretmenler, izinleriyle, burada ve sürüm notunda yer alır.

## Nasıl yapıldı

Bu çalışmalarda takım arkadaşım Claude. Kurul (fen öğretmeni gözü, öğrenci gözü, QA) ve bağımsız doğrulayıcı incelemesinden geçti.

## Lisans

MIT. Herkese Eğitim · İdiye Ökten
