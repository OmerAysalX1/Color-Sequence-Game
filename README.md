# Color-Sequence-Game

# Color Sequence Game

Bu proje, oyuncunun rastgele yanan renkleri hafızasında tutarak doğru sırayla tekrar etmesini gerektiren bir **gömülü sistem hafıza oyunudur**.

## ✨ Özellikler
- Rastgele oluşturulan renk dizisi
- Oyuncunun doğru sırayı takip etmesi gerekiyor
- Giderek zorlaşan seviyeler
- LED göstergesi ve buton kontrolü
- LCD ekran ile geri bildirim
- Buzzer ile sesli uyarılar

## 💻 Kullanılan Donanımlar
- RGB LED
- Tek renkli LED
- Butonlar (Oyuncunun seçim yapması için)
- Raspberry Pi Pico WH
- Buzzer (Sesli geri bildirim için)
- Potansiyometre (Parlaklık ayarı için)
- 16x2 LCD (Oyun durumu ve yönlendirmeleri göstermek için)

## 🔧 Kullanılan Yazılım ve Teknolojiler
- **Python / MicroPython** (Raspberry Pi Pico için)
- **Wokwi** (Simülasyon ve test için)

## 🌐 Kurulum
1. **Gerekli kütüphaneleri yükleyin** (MicroPython için)
2. **Kodları Raspberry Pi Pico'ya yükleyin**
3. **Donanımı bağlantı şemasına göre bağlayın**
4. **Cihazı çalıştırarak oyunu oynayın**

## 🎮 Nasıl Oynanır?
1. Oyun rastgele bir LED yakarak başlar.
2. **Yeşil LED** yanarsa, oyuncunun sırasının geldiğini belirtir.
3. Oyuncu, LED sırasını doğru şekilde butonlara basarak tekrar etmelidir.
4. Doğru seçim yapıldığında, bir sonraki turda yeni bir renk eklenir.
5. Yanlış seçim yapılırsa "Wrong Button" uyarısı görünür ve oyun baştan başlar.

## 📸 Projeden Görseller
Aşağıda proje sırasında alınan bazı görselleri bulabilirsiniz:

![Oyun Ekranı](./IMG_0011.jpeg)
![Oyun Devam](./IMG_0013.jpeg)
![Sıra Sende](./IMG_0014.jpeg)
![Yanlış Buton](./wrong_button.jpeg)

## ✨ Demo
Oyunun çalıştığını gösteren bir video için [buraya tıklayın](./game_video.mp4).

## 💡 Katkıda Bulunma
Projeye katkıda bulunmak isterseniz, lütfen **pull request** göndermekten çekinmeyin!

## 📄 Lisans
Bu proje **MIT Lisansı** altında yayınlanmıştır.

