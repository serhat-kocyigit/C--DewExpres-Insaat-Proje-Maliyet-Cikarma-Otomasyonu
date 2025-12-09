
# 🏗️ İnşaat Proje ve Maliyet Takip Otomasyonu

## 🚀 Projeye Genel Bakış

Bu proje, inşaat sektöründeki projelerin **maliyet, teklif ve genel durum takibini** profesyonel düzeyde yönetmek için tasarlanmış güçlü bir **masaüstü otomasyon** çözümüdür.

Gelişmiş kullanıcı arayüzü bileşenleri ve kalıcı veritabanı altyapısı sayesinde, birden fazla projenin finansal ve operasyonel verilerini güvenilir ve düzenli bir şekilde saklamayı ve raporlamayı sağlar.

## ⚙️ Teknik Altyapı ve Mimari

Bu otomasyon sistemi, kurumsal yazılım geliştirme standartlarına uygun, güvenilir ve performanslı teknolojiler üzerine kurulmuştur.

### Temel Teknoloji Yığını

| Özellik | Teknoloji | Açıklama |
| :--- | :--- | :--- |
| **Yazılım Dili** | **C#** | Projenin ana geliştirme dilidir. |
| **Platform** | **.NET Framework (Windows Forms)** | Windows tabanlı, yerel performansı yüksek masaüstü uygulamasıdır. |
| **Kullanıcı Arayüzü (UI)** | **DevExpress UI Framework** | Modern görünüm, gelişmiş GridControl (tablo), Ribbon menü, filtreleme ve raporlama yetenekleri sağlar. |
| **Veritabanı** | **SQL Server / LocalDB (Yüksek Olasılık)** | Verilerin kalıcı, güvenli ve ilişkisel bir yapıda saklanmasını garanti eder. |

### Uygulama Mimarisi

Uygulama, veri yönetimi, iş mantığı ve sunum katmanlarını içeren tipik bir **Katmanlı Mimari (Layered Architecture)** üzerine inşa edilmiştir:

* **UI (Sunum) Katmanı:** DevExpress bileşenleri ve WinForms ile kullanıcı etkileşimini sağlar.
* **Business Logic (İş Mantığı) Katmanı:** Maliyet hesaplamaları, teklif oluşturma mantığı ve veriye dayalı iş kurallarını barındırır.
* **Data (Veri Erişim) Katmanı:** Veritabanı bağlantılarını (`Connection String`), CRUD (Oluşturma, Okuma, Güncelleme, Silme) işlemlerini yönetir.


## ✅ Ana İşlevler ve Modüller

Bu otomasyon, inşaat projelerinin ana takip ihtiyaçlarına odaklanmıştır:

1.  **Gelişmiş Maliyet Hesaplama:**
    * Malzeme birim fiyat, miktar ve toplam maliyet takibi.
    * İşçilik ve genel gider hesaplamaları.
    * Proje toplam maliyetinin otomatik olarak güncellenmesi.
2.  **Proje Yönetimi:**
    * Projelerin durum ve aşama takibi.
    * Proje geçmişinin kayıt altında tutulması.
3.  **Doküman & Teklif Yönetimi:**
    * Projelerle ilişkili belgelerin ve tekliflerin sisteme entegrasyonu.
    * SQL tabanlı kalıcı kayıt sistemi.
4.  **Raporlama:**
    * Oluşturulan tekliflerin ve maliyet tablolarının raporlanması (Muhtemelen DevExpress Reporting araçları ile).

## 🛠️ Kurulum ve Gereksinimler

Bu uygulamayı çalıştırmak için aşağıdaki bileşenlere ihtiyacınız vardır:

1.  **Microsoft .NET Framework:** Uygulamanın çalışacağı Windows ortamında kurulu olmalıdır.
2.  **SQL Veritabanı Altyapısı:** Uygulamanın kullanacağı veritabanının (çoğu zaman **SQL Server Express** veya **LocalDB**) kurulu ve erişilebilir olması gerekir.
3.  **DevExpress Lisansı:** Projeyi geliştirme ortamında derlemek ve düzenlemek için DevExpress lisansına sahip olmanız gerekebilir (kullanılan DevExpress sürümüne bağlı olarak).

> ⚠️ **Veritabanı Bağlantısı:** Veritabanı bağlantı dizisi (Connection String) genellikle `App.config` dosyasında bulunur. Uygulamayı ilk çalıştırdığınızda veritabanı bağlantısını kendi yerel SQL sunucunuza göre ayarlamanız gerekebilir.

## 🚀 Sonuç ve Potansiyel

Bu proje, bir "hobi projesinden" ziyade, **profesyonel UI ve kalıcı veri saklama** özellikleriyle donatılmış, ticari kullanıma potansiyel olarak uygun bir temel oluşturur.

**Geliştirmeye Açık Alanlar:**

* **Çok Kullanıcılı Erişim:** Şu an tek kullanıcılı varsayılmaktadır. Birden fazla kullanıcı, rol ve yetki sistemi eklenmesi.
* **Ağ Üzerinde Çalışma:** Uygulamanın bir sunucudaki merkezi bir SQL veritabanına bağlanacak şekilde yapılandırılması.

