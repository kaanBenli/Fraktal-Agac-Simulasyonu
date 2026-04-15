Bu proje, matematiksel fraktal algoritmaları kullanılarak oluşturulmuş, etkileşimli ve mevsimsel geçişlere sahip bir **Canlı Ağaç Simülasyonu**dur. HTML5 Canvas ve JavaScript (Vanilla JS) kullanılarak geliştirilmiştir.

 Özellikler:

Dinamik Fraktallar: Her dal, Bézier kübik eğrileri kullanılarak matematiksel olarak hesaplanır ve rüzgarın yönüne göre organik bir şekilde esner.
Mevsimsel Döngü: Her 5 saniyede bir ağaç mevsim değiştirir:
     Bahar: Pembe çiçekler açar.
     Yaz: Canlı yeşil yapraklar ve meyveler oluşur.
     Sonbahar: Turuncu yapraklar dökülmeye başlar, rüzgar sesi artar ve toz partikülleri uçuşur.
     Kış: Yapraklar tamamen dökülür ve kar yağışı başlar.
Etkileşimli Kontrol Paneli:
    Derinlik: Ağacın dal karmaşıklığını ayarlar.
    Başlangıç Uzunluğu: Ağacın boyutunu belirler.
    Rüzgar Yoğunluğu: Salınım hızını ve fiziksel etkileri kontrol eder.
    Kamera Kontrolleri: Fare tekerleği ile yakınlaşma (Zoom) ve sürükleyerek hareket ettirme (Pan) özellikleri mevcuttur.
    Otomatik Odaklama: Kar yağışı başladığında kamera rastgele bir kar tanesini takip ederek sinematik bir görüntü oluşturur.

Kurulum ve Kullanım
Projeyi yerel bilgisayarınızda çalıştırmak için:
1. Bu depoyu indirin veya kopyalayın.
2. Klasör içindeki `index.html` dosyasını herhangi bir modern web tarayıcısı (Chrome, Firefox, Edge, Safari) ile açın.

Alternatif olarak, VS Code kullanıyorsanız `workspace.code-workspace` dosyasını açarak projeyi geliştirme ortamında hemen düzenlemeye başlayabilirsiniz.

Teknik Detaylar

Ağacın dalları aşağıdaki özyinelemeli (recursive) fonksiyon yapısıyla oluşturulmuştur:
Bézier Eğrileri: Dalların rüzgarda kırılmadan, yumuşak bir şekilde bükülmesi için kullanılmıştır.
Dinamik Partikül Sistemi: Yaprak dökümü, toz ve kar taneleri için birbirinden bağımsız çalışan fizik motoru simülasyonu eklenmiştir.


*Bu proje matematik ve sanatın birleşimiyle oluşturulmuştur.*
