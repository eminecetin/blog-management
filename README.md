# blog-management

Bu proje, kullanıcıların blog yazıları ekleyip yönetebileceği, arama ve sıralama yapabileceği bir React tabanlı blog uygulamasıdır. Kullanıcılar ayrıca sisteme giriş yapabilir, yeni bir kullanıcı oluşturabilir ve çıkış yapabilirler.

Özellikler
Kullanıcı Yönetimi: Kullanıcılar giriş yapabilir, kayıt olabilir ve çıkış yapabilir.
Blog Ekleme: Kullanıcılar giriş yaptıktan sonra yeni bir blog yazısı ekleyebilir.
Blog Listeleme: Tüm blog yazıları listelenir ve kullanıcılar istedikleri yazıyı görüntüleyebilir.
Blog Filtreleme: Kullanıcılar, blog başlıklarına göre arama yapabilir ve listeyi sıralayabilir.
Blog Güncelleme ve Silme: Blog yazıları güncellenebilir veya silinebilir.
Veri Saklama: Uygulama, blog verilerini localStorage'de saklar, bu sayede sayfa yenilendiğinde veriler korunur.
Kurulum
Projeyi yerel ortamda çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

Projeyi Klonlayın:

git clone https://github.com/username/blog-app.git
cd blog-app
Gerekli Paketleri Yükleyin:

npm install
Uygulamayı Başlatın:

npm start
Bu komut, projeyi yerel geliştirme sunucusunda başlatacaktır. Tarayıcınızda http://localhost:3000 adresine giderek uygulamayı görüntüleyebilirsiniz.

Proje Yapısı
src/components: Tüm bileşenler burada yer alır.
BlogList: Blogların listelendiği ve yeni blogların eklendiği bileşenler.
user: Kullanıcı işlemlerini (giriş yapma, kayıt olma ve çıkış yapma) içeren bileşenler.
src/data: Varsayılan blog verilerini içeren dosya (blogData.js).
src/App.jsx: Uygulamanın ana bileşeni. Tüm işlevselliğin birleştiği yer.
src/App.css: Genel stil dosyası.
Kullanım
Kayıt Olma ve Giriş Yapma: Navbar'daki "Kayıt Ol" veya "Giriş Yap" düğmeleri ile kullanıcı hesabı oluşturabilir veya mevcut bir kullanıcıyla giriş yapabilirsiniz.
Blog Ekleme: Giriş yaptıktan sonra yeni bir blog eklemek için "Yeni Blog Ekle" formunu doldurabilirsiniz.
Arama ve Sıralama: Blogları başlığa göre arayabilir, tarihe veya yazar adına göre sıralayabilirsiniz.
Blog Güncelleme ve Silme: Her blogun yanında bulunan düzenleme ve silme seçenekleri ile blogları güncelleyebilir veya silebilirsiniz.
Geliştirme
Uygulamada geliştirme yapmak isteyenler için bazı öneriler:

Kullanıcı Doğrulaması: Kullanıcı giriş işlemini daha güvenli hale getirmek için JWT veya benzeri bir kimlik doğrulama sistemi eklenebilir.
Sunucu Taraflı Veri Yönetimi: Blog verilerini localStorage yerine bir sunucu veya veritabanında saklamak için bir backend ekleyebilirsiniz.
Daha Fazla Filtreleme Seçeneği: Bloglara kategori veya etiket ekleyerek filtreleme seçeneklerini genişletebilirsiniz.
Gereksinimler
Node.js ve npm yüklü olmalıdır.
React 17 veya daha yeni bir sürüm.
Geliştirme ve test için modern bir tarayıcı (Chrome, Firefox, Safari, vb.)
Katkıda Bulunma
Bu projeyi forkladıktan sonra kendi dalınızda geliştirme yapabilirsiniz.
Değişikliklerinizi commit'leyin.
Bir pull request (PR) açarak projeye katkıda bulunabilirsiniz.
Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.
