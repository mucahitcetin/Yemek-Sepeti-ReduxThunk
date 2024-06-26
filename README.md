<h1> Yemek-Sepeti-ReduxThunk</h1>

Bu proje, JSON API sunucusu oluşturularak geliştirilmiş bir yemek sitesi deneyimini sunan bir React uygulamasını içerir. Proje Axios ile veri çekimi ve sunucu verilerine erişim sağlar. React-Redux, Redux-Thunk kullanılarak uygulama genelinde durum yönetimi ve asenkron işlemler ele alınır. Tailwind ile modern tasarım anlayışıyla kullanıcı arayüzü oluşturulurken, React Toastify kullanılarak kullanıcı etkileşimi artırılır ve bilgilendirme sağlanır.

<h2>Teknolojiler ve Kütüphaneler</h2>

- ReactJS: Kullanıcı dostu arayüz ve bileşen tabanlı yapı için tercih edildi.
- Axios: HTTP istekleri yapmak ve sunucu verilerine erişmek için kullanıldı.
- Json-Server: Geliştirme aşamasında kullanılarak, sahte bir JSON API sunucusu oluşturuldu. Gerçek bir sunucuya bağlanmadan veri denemeleri yapıldı.
- React-Redux: Uygulama genelinde durumu yönetmek ve bileşenler arasında veri akışını sağlamak için kullanıldı. Redux kullanarak tek bir depoda tüm uygulama durumu yönetildi.
- Redux-Thunk: Redux ile asenkron işlemleri yönetmek için kullanıldı. Özellikle Redux ile API çağrıları yaparken ve yan etkileri ele alırken kullanışlı oldu.
- React Toastify: Kullanıcıları bilgilendirmek ve etkileşimi artırmak için bildirimler sağlar.
- Tailwind: Hızlı ve özelleştirilebilir kullanıcı arayüzleri oluşturmak için kullanılan bir CSS çerçevesi olarak tercih edildi. Stil belirtmek için sınıfları kullanıldı ve daha az CSS yazmayı gerektirdi.
- React-Icons: React uygulamasında ikonları kullanmak için kullanıldı. Çeşitli ikon setlerini (FontAwesome, Material Icons vb.) entegre etmek için tercih edildi.

<h2>Proje İçeriği</h2>

Bu proje, kullanıcıların modern bir yemek deneyimi yaşamasını sağlayan bir React uygulamasını içerir. Ana sayfada restoranlar listelenir ve kullanıcılar bu restoranlara tıklayarak ilgili restoranın yemeklerini görüntüleyebilirler. Restoranın yemekleri bölümünde, kullanıcılar artı butonuna basarak istedikleri yemekleri sepete ekleyebilirler. Aynı şekilde, istedikleri kadar ekleme veya çıkarma yapabilirler. Sonra, sayfanın sağ üst köşesinde bulunan sepet ikonuna tıklayarak sepete gidebilirler. Sepet bölümünde, eklenen yemeklerin miktarı istenildiği kadar güncellenebilir. Bu şekilde, kullanıcılar kolayca yemek seçimi yapabilir ve sepetlerini yönetebilirler.

📱 Responsive Tasarım Proje, kullanıcıların farklı cihazlarda rahatça gezinebilmesi için responsive bir tasarım içerir. Mobil, tablet ve masaüstü cihazlarda sorunsuz bir kullanıcı deneyimi sunar.

<h2>Ekran Görüntüsü</h2>

![](ekran.gif)
