# Fındık Muhasebe

**Fındık Muhasebe**, fındık tüccarlarının günlük operasyonlarını yönetmelerine yardımcı olmak amacıyla Flutter ile geliştirilmiş bir mobil uygulamadır. Uygulama; fındık fiyatlarını takip etme, envanter seviyelerini izleme ve müşteri hesaplarını yönetme gibi özellikler sunarak tüccarlar için uçtan uca bir deneyim sağlar.

## Özellikler
- **Anlık Fiyat Takibi**: Uygulama, internet üzerinden (Web Scraping ile) günlük değişen fındık fiyat verilerini çeker. Böylece tüccarlar güncel piyasa fiyatlarından anında haberdar olur.
- **Envanter Yönetimi**: Stoktaki fındık miktarını takip edebilir ve depo seviyelerini verimli bir şekilde yönetebilirsiniz.
- **Müşteri Hesap Yönetimi**: Borç ve alacak takibi dahil olmak üzere müşteri işlemlerini destekleyerek iş ilişkilerini yönetmeyi kolaylaştırır.
- **Hasat ve Gider Takibi**: Hasat miktarı, kalitesi ve gübre/işçilik gibi gider kalemlerini kayıt altında tutun.
- **Gelecek Özellik (Planlanan)**: Mağaza tabelasında fındık fiyatlarının dijital olarak gösterilmesi özelliği bir sonraki güncelleme için planlanmaktadır.

## Kullanılan Teknolojiler
- **Flutter** & **Dart**
- **MongoDB**
- **Web Scraping** (Fiyat verilerini çekmek için)

## Kurulum
1. Depoyu klonlayın:
   ```sh
   git clone https://github.com/tahabugracck/findik_muhasebe.git
   ```
2. Bağımlılıkları yükleyin:
   ```sh
   flutter pub get
   ```
3. Uygulamayı çalıştırın:
   ```sh
   flutter run
   ```

## Kullanım
1. Uygulamayı açtığınızda ana ekranda güncel fındık fiyatlarını görebilirsiniz.
2. "Envanter" sekmesinden stok giriş-çıkışlarını yapın.
3. "Müşteriler" bölümünden borç/alacak kayıtlarını güncelleyin.
4. "Giderler" kısmına lojistik ve işçilik gibi maliyetleri ekleyerek net kar analizi yapın.

## Not
Bu proje, öğrenme ve kişisel gelişim amacıyla geliştirilmiş bir **öğrenci projesidir**.

---
*Geliştirici: [blosny](https://github.com/blosny)*
