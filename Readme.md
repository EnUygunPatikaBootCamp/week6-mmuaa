# Araştırma :

### Lazy Loading
- Lazy Loading, sayfada yer alan bir ögenin ihtiyaç duyulmadığı takdirde çağrılmaması prensibi ile çalışır yani bir nesne örneğinin gerçekten ihtiyaç duyulacağı ana kadar alınmaması ve bekletilmesi amacıyla kullanılır. Bu yöntemde veriler sorguya bağlı olarak çekilir ve veri setinin içindeki tüm dataları yüklemek yerine kullanılacağı an tekrar sorgu atar ve veriyi çeker.

### Eager Loading
- Lazy Loading’in tam tersi yönde çalışır. Kullanacağımız nesneleri, nesnenin ihtiyaç anından çok önce yaratır ve bekletir. Eager loading Linq sorgusu çalıştırıldığında verilerin tamamını yükler ve hafızaya alır.

# Symfony Odev Açıklama :

```
composer require api 
``` 
ile ApiPlatform kurdum projeme ve bunu 
```
use ApiPlatform\Core\Annotation\ApiResource;
```
şeklinde kullandım.
