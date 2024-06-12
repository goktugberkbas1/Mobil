Erciyes üniversitesi 
Bilgisayar Mühendisliği
Mobile Application Development
Dr. Öğr. Üyesi Fehim Köylü

1030520974 Göktuğ Berkbaş



Mobile Application Development Weather App Project

Hava Durumu Uygulaması

Bu Flutter projesi, hava durumu verilerini görsel olarak sunan bir mobil uygulamadır. Uygulama, çeşitli hava durumu bilgilerini almak için bir API kullanır ve bu bilgileri kullanıcı dostu bir arayüzde gösterir.

Başlarken

Projeyi bilgisayarınıza klonlayın veya ZIP dosyası olarak indirin.
Flutter projenizin ana dizininde terminali açın.
Terminalde flutter pub get komutunu çalıştırarak bağımlılıkları yükleyin.
Projeyi bir Flutter geliştirme ortamında çalıştırın.
Proje Yapısı ve İçeriği

lib/screens/: Uygulamanın ekranlarını içeren dosyaların bulunduğu klasör.

home.dart: Ana ekran, popüler kategorileri ve hava durumu tahminlerini gösterir.

login.dart: Kullanıcı girişi ekranı, kullanıcıların oturum açmalarını ve kaydolmalarını sağlar.

search.dart: Arama ekranı, kullanıcıların hava durumu bilgilerini aramasını sağlar.

splash.dart: Başlangıç ekranı, uygulama yüklenirken gösterilen ekran.

lib/consent/: Uygulamanın genel olarak kullanılan bileşenlerinin bulunduğu klasör.

appbar.dart: Uygulamanın üst çubuğunu oluşturan bileşen.

colors.dart: Kullanılan renk paletini içeren dosya.

navigation.dart: Uygulama içi gezinmeyi yöneten bileşen.

lib/services/: Uygulamanın veri işleme ve sunma hizmetlerini sağlayan dosyaların bulunduğu klasör.

notification_service.dart: Bildirim hizmetlerini yöneten dosya.

weather_cubit.dart: Hava durumu verilerini yöneten Cubit sınıfı.

weather_records.dart: Hava durumu kayıtlarını işleyen yardımcı sınıfların bulunduğu dosya.

lib/models/: Uygulama tarafından kullanılan veri modellerinin bulunduğu klasör.

condition_model.dart: Hava durumu koşullarını temsil eden model sınıfı.

current_model.dart: Mevcut hava durumu verilerini temsil eden model sınıfı.

day_model.dart: Günlük hava durumu verilerini temsil eden model sınıfı.

forecast_day_model.dart: Hava durumu tahminlerini temsil eden model sınıfı.

hour_model.dart: Saatlik hava durumu verilerini temsil eden model sınıfı.

location_model.dart: Konum bilgilerini temsil eden model sınıfı.

lib/utils/: Yardımcı işlevleri sağlayan dosyaların bulunduğu klasör.

chart_data_formatter.dart: Grafik verilerini biçimlendiren yardımcı sınıfların bulunduğu dosya.


Kullanılan Kütüphaneler

flutter_local_notifications: Bildirimler için yerel bildirimleri yönetmek için kullanılır.

freezed_annotation: Serileştirme işlemleri için kod üretimi sağlar.

fl_chart: Grafikler oluşturmak ve görselleştirmek için kullanılır.

Bu projenin amacı, Flutter ve çeşitli paketler kullanarak hava durumu verilerini almak ve göstermek için bir örnek oluşturmaktır. 

Uygulama, kullanıcıların hava durumu tahminlerini kolayca takip etmelerine ve günlük yaşamlarını planlamalarına yardımcı olmak için tasarlanmıştır.