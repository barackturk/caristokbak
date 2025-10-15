 _                  _    _  _     ______                          _        
| |                | |  (_)| |    | ___ \                        | |       
| |      __ _  ___ | |_  _ | | __ | |_/ / _   _  _ __   __ _   __| |  __ _ 
| |     / _` |/ __|| __|| || |/ / | ___ \| | | || '__| / _` | / _` | / _` |
| |____| (_| |\__ \| |_ | ||   <  | |_/ /| |_| || |   | (_| || (_| || (_| |
\_____/ \__,_||___/ \__||_||_|\_\ \____/  \__,_||_|    \__,_| \__,_| \__,_|
                                                                           

çalışanları için ████████  BURAK TÜRK  ████████ tarafından hazırlanmıştır.


STOK & CARİ BAK V2.2

Bu program, stoklarınızı ve cari (müşteri/tedarikçi) hesaplarınızı kolayca takip etmeniz için geliştirilmiştir.
Aşağıda programın kullanımı ve özellikleri adım adım açıklanmıştır.

------------------------------------------------------------------------------

KULLANIM BAŞLANGICI
-------------------
1. Programı çalıştırmak için simgesine çift tıklayın.
2. Açılan ekranda kullanıcı adı ve şifrenizi girin.
   - Yönetici hesabı ile yeni kullanıcılar ekleyebilir ve şube ataması yapabilirsiniz.

------------------------------------------------------------------------------

GENEL ÖZELLİKLER
----------------
- Tüm şube ve depoların stok durumunu kolayca görebilir, filtreleyebilir ve arayabilirsiniz.
- Müşteri veya tedarikçi cari hesap hareketlerini listeleyebilir, ekstre alabilirsiniz.
- Teklif ve ekstreleri PDF olarak oluşturup kaydedebilirsiniz.
- Tüm rapor ve listeleri Excel dosyası olarak dışa aktarabilirsiniz.
- Çoklu şube desteği sayesinde birden fazla şubeyi tek ekrandan takip edebilirsiniz.
- Kullanıcı yönetimi ile, kim hangi şubeye erişecek kolayca belirlenebilir.
- Programdan çıkış yapmadan bağlantı ayarlarını değiştirebilirsiniz.
- Kapanmamış faturalar takibi ve raporlama.
- Otomatik sütun genişliği ayarlama ve akıllı sıralama.
- Gelişmiş filtreleme sistemi (tarih, şube, bölge, müşteri türü, ödeme yöntemi).
- Gerçek zamanlı arama ve filtreleme özellikleri.

------------------------------------------------------------------------------

KULLANICI VE ŞUBE YÖNETİMİ
--------------------------
- Bir kullanıcı birden fazla şubeye atanabilir.
- Kullanıcılar, sisteme giriş yaptığında atanmış oldukları tüm şubelerin verilerini görebilir.
- Yönetici (admin), tüm şubeleri görebilir ve düzenleyebilir.
- Her rapor (satış, tahsilat, stok) kullanıcıya özel olarak atanmış şubelerle sınırlı gelir.

Kullanıcı eklemek veya şube bilgisini değiştirmek için:
1. Yönetici olarak giriş yapın.
2. Üstteki menüden "Dosya" → "Kullanıcı Belirle" seçeneğine tıklayın.
3. "Ekle" ile yeni kullanıcı oluşturun, "Düzenle" ile mevcut kullanıcıyı güncelleyin.

------------------------------------------------------------------------------

RAPORLAR VE FİLTRELEME
----------------------
- Stok, satış ve tahsilat raporlarında şube filtresi kullanabilirsiniz.
- "Tüm Şubeler" seçeneği ile sadece size atanmış olan tüm şubelerin toplam verilerini görebilirsiniz.
- Belirli bir şubeyi seçerseniz sadece o şubenin verileri ekranda gösterilir.
- Admin tüm şubeleri, normal kullanıcı sadece atanmış şubelerini filtreleyebilir.
- Tahsilat Raporu ve Satış Raporu'nda çoklu şube seçimi yapabilirsiniz.
- "Tümünü Seç" ve "Seçimi Temizle" butonları ile kolayca şube seçimi yapabilirsiniz.
- Cari Ekstresi'nde Borç, Alacak, Bakiye ve Durum toplamları otomatik olarak hesaplanır ve gösterilir.
- Kapanmamış Faturalar sekmesinde detaylı filtreleme (tarih, şube, müşteri türü, ödeme yöntemi, ödeme planı).
- Otomatik sütun genişliği ayarlama ve akıllı sıralama sistemi.
- Gerçek zamanlı arama ve filtreleme özellikleri.

------------------------------------------------------------------------------

YENİ ÖZELLİKLER (V2.2)
----------------------
- **Gelişmiş Satış Raporu Özet Tablosu**:
  - "Verilen Hizmet" sütunu "İade Satış" olarak güncellendi.
  - İade faturaları ve irsaliyeleri ayrı bir sütunda gösteriliyor.
  - Satış toplamları iade işlemlerinden etkilenmiyor.
  - Daha net ve analiz edilebilir satış performansı raporları.
  
- **Optimize Edilmiş Satış Raporu Sütun Sıralaması**:
  - Tarih, Fiş No, Fiş Türü, CAİ, Hizmet Kodu, Hizmet Açıklaması
  - Miktar, Birim Fiyat, Toplam Tutar, İnd. Oranı, İnd.Br.Fiyat
  - Toplam İnd., Net Tutar, Ödeme Planı, Cari Kodu
  - Mantıklı gruplama ve kolay analiz için optimize edilmiş sıralama.

- **Kapanmamış Faturalar Sekmesi**: Açık faturaları takip etmek için yeni sekme.
  - Tarih aralığı, şube, müşteri türü, ödeme yöntemi ve ödeme planı filtreleri.
  - Otomatik sıralama (Kalan Vade'ye göre).
  - Excel export özelliği.
  
- **Gelişmiş Filtreleme Sistemi**:
  - Gerçek zamanlı arama (Cari Kod, Marka, Ürün).
  - Çoklu şube seçimi.
  - Bölge bazlı filtreleme.
  - Tarih aralığı filtreleri.
  
- **Akıllı Tablo Özellikleri**:
  - Otomatik sütun genişliği ayarlama.
  - Çift tıklama ile sütun genişliği optimizasyonu.
  - Gelişmiş sıralama sistemi (sayısal ve metin).
  - Tablo başlıklarına tıklayarak sıralama.
  
- **Kullanıcı Deneyimi İyileştirmeleri**:
  - Daha hızlı veri yükleme.
  - Gelişmiş hata yönetimi.
  - Kullanıcı dostu arayüz.
  - Otomatik kaydetme özellikleri.

------------------------------------------------------------------------------

DOSYA YAPISI HAKKINDA
---------------------
- "Stok & Cari Bak V2.2.exe" : Programı başlatan ana dosya
- "connection.json" : Bağlantı ve sunucu bilgileri burada tutulur
- "users.json" : Kullanıcı ve şube atama bilgileri burada tutulur
- ".ttf" : Yazı tipi (font) dosyaları
- ".png" : Görsel dosyalar

------------------------------------------------------------------------------

İPUÇLARI VE YARDIM
------------------
- Tablolardaki başlıklara tıklayarak sıralama yapabilirsiniz.
- Sütun ayırıcılarına çift tıklayarak otomatik genişlik ayarlayabilirsiniz.
- Filtreleri temizlemek için "Filtreleri Temizle" butonunu kullanabilirsiniz.
- Kapanmamış Faturalar sekmesinde "Kalan Vade" sütununa göre otomatik sıralama yapılır.
- Satış Raporu'nda iade işlemleri ayrı bir sütunda gösterilir ve satış toplamlarını etkilemez.
- "Yardım" menüsünden program hakkında detaylı bilgiye ulaşabilir ve sorun bildirebilirsiniz.


------------------------------------------------------------------------------

GÜVENLİK VE NOTLAR
------------------
- Şifrenizi kimseyle paylaşmayın ve güçlü bir parola seçin.
- Çıkış yapmak için "Oturumu Kapat" seçeneğini kullanın.
- Program ayarları ve son kullandığınız bilgiler otomatik olarak kaydedilir.
- Tüm kullanıcılar sadece kendi şubelerinin verilerini görebilir.
- Veritabanı bağlantı bilgileri güvenli şekilde saklanır.
- Kullanıcı yetkilendirme sistemi ile veri güvenliği sağlanır.

