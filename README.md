# Flarum VR Eklentisi

Bu Flarum eklentisi, forumunuzu gezmek için bir WebXR arayüzü sağlar.

## Özellikler

- **VR Modu Düğmesi**: VR deneyimini başlatmak için forum başlığına basit bir düğme ekler.
- **Sürükleyici Tartışma Listesi**: En son tartışmaları 3D uzayda etkileşimli paneller olarak görüntüler.
- **3D Avatar**: Kullanıcı avatarları, gönderilerinin yanında yüzleri profil fotoğraflarından alınan 3D figürler olarak gösterilir.
- **Tam Etkileşim**: VR ortamında yeni tartışmalar başlatın ve mevcut olanlara yanıt verin.
- **PC/Mobil Önizleme**: VR başlığı olmadan fare/klavye veya dokunmatik kontrollerle ortamı test edin.
- **Otomatik VR Algılama**: Uyumlu bir VR başlığı takıldığında tam sürükleyici moda otomatik olarak geçer.

## Kurulum

1. Sunucunuza SSH ile bağlanın ve Flarum kök dizininize gidin.
2. Eklentiyi Composer kullanarak yükleyin:
   ```bash
   composer require nckerll/flarum-vr
   ```
3. Flarum yönetici panelinize giriş yapın, "Eklentiler" sayfasına gidin ve "Flarum VR" eklentisini etkinleştirin.
4. Flarum önbelleğini temizleyin:
   ```bash
   php flarum cache:clear
   ```