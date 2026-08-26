## Araç Kiralama ve Paylaşım Yönetim Sistemi (CarShare)

Araç Kiralama ve Paylaşım Yönetim Sistemi; bireysel ve kurumsal kullanıcıların araç kiralama, filo yönetimi, şehirler arası mesafe hesaplama ve kiralama süreçlerini modern bir masaüstü arayüzüyle takip etmesini sağlayan nesne yönelimli (OOP) bir uygulamadır.

### Kurulum ve Ortam Hazırlığı

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

* **Python 3.13 ve Geliştirme Ortamı:** Sisteminizde Python 3.13 yüklü olduğundan emin olun. Bilgisayarınızda yüklü değilse Microsoft Store üzerinden veya python.org adresinden indirebilirsiniz. (Kurulum esnasında "Add Python to PATH" seçeneğini işaretlemeyi unutmayın.)
* **IDE Seçimi:** Visual Studio veya VS Code içerisinde `Ctrl + Shift + P` kısayolu ile Komut Paletini açıp **Python: Select Interpreter** alanından Python   3.13 sürümünü seçin.
* **Gerekli Kütüphaneler (Terminal):** Proje grafiksel arayüzünü PyQt5 ile sunduğu için terminalden kütüphaneyi yükleyebilirsiniz:

pip install PyQt5

Not: Eğer sisteminizde PyQt5 kütüphanesi küresel olarak daha önceden kurulduysa ekstra bir yükleme yapmanıza gerek yoktur. Arayüz kodla inşa edildiği için pyqt5-tools vb. yardımcı paketlerin yüklenmesi zorunlu değildir.

### Uygulama Özellikleri ve Modüller

* **Nesne Yönelimli Mimari (OOP):** `Arac`, `Kullanici` ve `Kiralama` sınıfları sayesinde modüler, sürdürülebilir ve genişletilebilir bir yazılım altyapısı sunar.
* **Gelişmiş Araç Yönetimi:** Araçların marka, model, tip, yakıt türü, bulundukları şehir, kilometre bilgileri ve km/saat ücretleri üzerinden detaylı takibi ve güncellenmesi.
* **Kullanıcı ve Ehliyet Profilleri:** Sistem kullanıcılarının kayıt bilgileri, ehliyet numaraları, telefon numaraları ve kiralama geçmişlerinin saklanması.
* **Dinamik Kiralama ve Fiyatlandırma:** Başlangıç ve bitiş saatlerine göre otomatik süre hesabı, kilometre güncellemeleri ve toplam ücret hesaplama mantığı.
* **Lokasyon Bazlı Mesafe Hesaplama:** Şehirler arası mesafelerin sistemsel olarak hesaplanması ve rotaya uygun operasyonların yürütülmesi.
* **Modern PyQt5 Arayüzü:** Renk paletleri, tablo görünümleri, formlar ve etkileşimli bileşenlerle zenginleştirilmiş kullanıcı deneyimi.
* **Veritabanı Katmanı (SQLite):** Tüm araç, kullanıcı ve kiralama verilerinin güvenli bir şekilde saklanması ve kalıcı olarak yönetilmesi.
