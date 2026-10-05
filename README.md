# 🧮 MATH WORLD – Keşfet, Oyna, Öğren! (Android APK)

İlkokul 1–4. sınıf matematik oyunu. İnternetsiz çalışır, ilerleme cihazda saklanır.

## APK nasıl alınır? (Bilgisayara kurulum gerekmez)
1. GitHub'da yeni bir depo (repository) oluşturun, örn. `math-world`.
2. Bu klasördeki **tüm dosyaları** (gizli `.github` klasörü dahil) depoya yükleyin.
   - Web arayüzünden yüklerken `.github/workflows/build-apk.yml` dosyasının da yüklendiğinden emin olun.
3. Deponun **Actions** sekmesine gidin. "Build MATH WORLD APK" kendiliğinden başlar
   (başlamazsa iş akışını seçip **Run workflow** düğmesine basın).
4. Yaklaşık 5–8 dakika sonra işlem yeşil ✔ olur. İşleme tıklayın, en altta
   **Artifacts → MathWorld-APK** dosyasını indirin.
5. ZIP'ten çıkan `app-debug.apk` dosyasını telefona/tablete atıp kurun
   (gerekirse "Bilinmeyen kaynaklardan yüklemeye izin ver").

## İsteğe bağlı: uygulama simgesi
Depoya 512×512 boyutunda `icon.png` eklerseniz APK simgesi olarak kullanılır.

## Uygulamayı güncellemek
`www/index.html` dosyasını yenisiyle değiştirip yükleyin; APK otomatik yeniden derlenir.

## Notlar
- Paket adı: `com.mathworld.kids`
- Android geri tuşu uygulama içinde bir önceki ekrana döner; ana ekranda uygulamayı kapatır.
- Bu "debug" APK kişisel kullanım ve test içindir. Google Play için imzalı "release" sürüm gerekir.
