# Freelancer Web App

Express JS kullanılarak tasarlanmış bir websitesidir. Tek sayfa bir uygulama olmakla beraber, yönetici için gerekli alanları modal üzerinden tamamladık.

Uygulama geliştirilikren hazır bir tema kullanılmıştır. Start Bootstrap - [Freelancer v7.0.6](https://startbootstrap.com/theme/freelancer).

![Portfolies](portfolies.png)

## Kurulum

Uygulamayı forklayabilir veya dosyaları bilgisayarınıza indirebilirsiniz. Uygulamayı bilgisayarınızda bir klasöre indirdiğinizde.

- Komut satırını açın ve komut satırı üzerindenprojenizin olduğu dizine gidin.
- ```npm init``` komutu ile uygulamayı başlamak için hazırlayın.
- **.env** dosyasında **APP_MONGODB_DB_NAME=veri_tabani_adi**, **APP_MONGODB_FULL_URL=veritabani_tam_url** ve **APP_SESSION_SECRET_KEY=** alanlarını doldurun.
- ```node app``` komutu ile uygulamanızı çalıştırın.

**.env** dosyası

```
PORT=5000
APP_MONGODB_DB_NAME=db-freelancer
APP_MONGODB_FULL_URL=mongodb://localhost:27017
APP_SESSION_SECRET_KEY=EkdsOpaaufaaa222UfaaaUUP
```


APP_SESSION_SECRET_KEY ise rastgele oluşturulmuş bir stringdir.


## Kullanılan Teknolojiler

Uygulama Node JS temelli geliştirilmiştir. Kullanılan paketler aşağıda sıralanmaktadır.

- Express JS
- Bootstrap
- Mongodb
- express-session
- express-fileupload
- express-validator
- randomstring
- mongoose
- bcrypt
- dotenv
- ejs

## Ekran Görüntüleri

Uygulama ile ilgili bazı ekran görüntüleri.

![Home](home.png)

![Portfolies](portfolies.png)

![Portfolio](portfolies1.png)

![Add Portfolio](add.png)
