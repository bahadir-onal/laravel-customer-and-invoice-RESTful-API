# Laravel API Projesi

Bu proje, Laravel ile geliştirilen bir API sunucusunu temsil etmektedir. API, müşteri ve fatura işlemlerini sorunsuz bir şekilde gerçekleştirmenizi sağlar. Aynı zamanda Sanctum kullanılarak API'nin güvenliği sağlanmaktadır, bu da yetkisiz erişimleri engeller ve veri güvenliğini korur.

## Özellikler

- RESTful API standartlarına uygun tasarlanmıştır.
- JSON formatında veri alışverişini destekler.
- Sanctum kimlik doğrulama mekanizmasıyla güvenlik sağlar.
- Veritabanı işlemleri, model-tablo ilişkileri, yönlendirme ve veri doğrulama gibi Laravel özelliklerinden yararlanır.

## Kurulum

1. Projeyi klonlayın: `https://github.com/bahadir-onal/laravel-customer-and-invoice-RESTful-API.git`
2. Proje dizinine gidin: `cd laravel-customer-and-invoice-RESTful-API`
3. Bağımlılıkları yükleyin: `composer install`
4. `.env` dosyasını oluşturun ve veritabanı ayarlarınızı yapın: `cp .env.example .env`
5. Uygulama anahtarını oluşturun: `php artisan key:generate`
6. Veritabanını oluşturun: `php artisan migrate`
7. Sunucuyu başlatın: `php artisan serve`

## İletişim

bahadironal3@gmail.com
