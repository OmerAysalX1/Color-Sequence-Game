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

![Oyun Ekranı](./I![IMG_0014](https://github.com/user-attachments/assets/feda0e36-31eb-4b2f-b6c6-eb3c9c0c9369)
MG_0011.jpeg)
![Oyun Devam](./IMG_0013.![IMG_0012](https://github.com/user-attachments/assets/a58e6d53-0e69-45c2-ad52-81973d34f635)
jpeg)
![Sıra Sende](./IMG_0014.j![IMG_0011](https://github.com/user-attachments/assets/27145a9f-a4b3-4035-ad21-cd36e3a47ef1)
peg)
![Yanlış Buton](./wrong_button.j![IMG_0013](https://github.com/user-attachments/assets/e405b527-e882-40af-a2af-cb6d29de38db)
peg)

## ✨ Demo
Oyunun çalıştığını gösteren bir video için [buraya tıklayın](./game_video.mp4).

## 💡 Katkıda Bulunma
Projeye katkıda bulunmak isterseniz, lütfen **pull request** göndermekten çekinmeyin!

## 📄 Lisans
Bu proje **MIT Lisansı** altında yayınlanmıştır.

