# react-weather-istanbul
istanbulun hava durumunu gösterir

İstanbul Hava Durumu Uygulaması
Bu uygulama, OpenWeatherMap API kullanarak İstanbul'daki hava durumunu alır ve React ile arayüzünde gösterir.

Nasıl Kullanılır
İlk olarak projeyi klonlayın:
git clone https://github.com/kodilay/react-weather-istanbul.git

Proje klasörüne gidin:
cd repo-name

Gerekli paketleri yükleyin:

npm install

Uygulamayı başlatın:

npm start

Tarayıcınızda http://localhost:3000 adresine gidin ve İstanbul'daki hava durumunu görün!
API Anahtarı
Bu uygulama, OpenWeatherMap API'sini kullanarak hava durumu verilerini alır. Bu nedenle, bir API anahtarına ihtiyacınız var. Kendi anahtarınızı edinmek için buraya kaydolabilirsiniz.

Anahtarınızı alıp, src/App.js dosyasındaki <API_KEY> yerine ekleyin.

axios
  .get('https://api.openweathermap.org/data/2.5/weather?q=Istanbul&appid=<API_KEY>&units=metric')


Daha Fazla Bilgi
Bu uygulama, React ve axios kütüphanesi kullanılarak oluşturulmuştur. Daha fazla bilgi için, lütfen React belgelerine ve axios belgelerine başvurun.

Katkıda Bulunma
Bu proje açık kaynaklıdır ve her türlü katkıya açıktır. Lütfen katkıda bulunmak için bir pull talebi gönderin.
