MSM EVENTS WEB SİTESİ
=====================

DOSYALAR
- index.html                 Sayfa yapısı ve içerikler
- style.css                  Tasarım, renkler, düzen, responsive/mobil uyum
- script.js                  Türkçe/İngilizce dil seçimi, mobil menü, animasyonlar, iletişim formu
- assets/msm-events-logo.png Yüklediğiniz MSM Events logosu

BİLGİSAYARDA ÇALIŞTIRMA
1. ZIP dosyasını indirin.
2. ZIP dosyasına sağ tıklayın ve "Tümünü ayıkla" seçeneğini seçin.
3. Açılan msm-events-web klasörüne girin.
4. index.html dosyasına çift tıklayın. Tarayıcınızda açılır.
5. Dosyaları düzenlemek için Visual Studio Code önerilir. Üç kod dosyası aynı klasörde kalmalı ve assets klasörünün yeri değişmemelidir.
6. Değişiklikleri kaydedip tarayıcıda Ctrl+R ile yenileyin.

ÇALIŞAN ÖZELLİKLER
- TR / EN dil seçici: sayfa metinlerini değiştirir.
- Masaüstü ve mobil gezinme menüsü.
- Sayfa içi bağlantılar, animasyonlu görünme efektleri.
- İletişim formu alan kontrolü ve e-posta taslağı oluşturma.
- Otomatik güncel yıl.

YAYIN ÖNCESİ ÖNEMLİ NOTLAR
- İletişim e-posta adresi msmeventsonline@gmail.com olarak ayarlanmıştır. Yayına almadan önce bu adresin doğru ve erişilebilir olduğunu kontrol edin.
- Form şu anda verileri bir sunucuya kaydetmez; kullanıcının cihazındaki varsayılan e-posta uygulamasını açar. Gerçek form gönderimi için sunucu, API veya form hizmeti eklenmelidir.
- Portfolyo görselleri temsili CSS illüstrasyonlarıdır. Gerçek etkinlik fotoğrafları ve doğrulanmış referanslar daha sonra eklenmelidir.
- Google Fonts bağlantısı çevrimiçi olduğunda özel yazı tiplerini yükler. Bağlantı olmazsa sistem yazı tipleri kullanılır.
- Logo dosyası projeye dahil edilmiştir. Logo görseliniz siyah zemin içerdiğinden koyu zemin üzerinde gösterilir.
- Bu paket statik bir ön yüz sitesidir; üyelik, yönetim paneli, veritabanı veya sunucu tabanlı form içermez.

YAYINA ALMA
Siteyi bir hosting hizmetine veya GitHub Pages / Netlify gibi statik site barındırma hizmetlerine yükleyebilirsiniz. Yüklerken index.html, style.css, script.js ve assets klasörünün birlikte aktarılması gerekir.


NETLIFY İLE KOLAY YAYINLAMA
1. https://app.netlify.com/drop adresini açın ve ücretsiz hesap oluşturun / giriş yapın.
2. ZIP dosyasını önce bilgisayarınızda bir klasöre ayıklayın.
3. İçindeki msm-events-web klasörünü değil, klasörün İÇERİĞİNİ (index.html, style.css, script.js, README.txt ve assets klasörü) Netlify'ın manuel dağıtım alanına sürükleyin. Arayüzde klasör yükleme seçeneği varsa msm-events-web klasörünü de seçebilirsiniz.
4. Yayınlama tamamlandığında Netlify size bir *.netlify.app adresi verir. Siteyi o bağlantıdan açıp test edin.
5. Netlify site ayarlarından site adını değiştirerek kullanılabilir bir alt alan adı seçebilirsiniz; seçtiğiniz adın boşta olması gerekir.
6. Kendi alan adınızı kullanmak isterseniz daha sonra Netlify site ayarlarından domain ekleyebilir, alan adınızı satın aldığınız yerde DNS kayıtlarını Netlify'ın gösterdiği şekilde düzenleyebilirsiniz.

Not: Yayınlamadan önce formu test edin. Form, msmeventsonline@gmail.com adresine önceden doldurulmuş e-posta taslağı açar; ziyaretçinin cihazında bir e-posta uygulaması ayarlı olmalıdır. Bu statik sitede mesajlar otomatik olarak sunucuya kaydedilmez.
