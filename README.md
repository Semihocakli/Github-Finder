# Github Finder

Github Finder, Python ve Flask kullanarak oluşturulmuş bir web uygulamasıdır. Bu uygulama, kullanıcıların Github hesaplarında arama yapmalarına ve istedikleri kullanıcının profiline erişmelerine olanak tanır.

## Proje Yapısı

1. Arayüz: Flask ile hazırlanmış bir web sayfası üzerinden kullanıcılara sunulan basit bir arayüz.
2. Backend: Github API ile etkileşim halinde olan Python kodu.

## Gereksinimler

1. Flask
    ```
    pip install flask
    ```
2. Requests modülü
    ```
    pip install requests
    ```

## Kurulum

1. Github API'ye bağlanmak için bir access token gerekiyor. Bu token'ı Github hesabınızın ayarlarından edinebilirsiniz. Edindikten sonra bu token'ı bir dosyaya kaydedin ve proje dosyasına yerleştirin.

2. Uygulamayı çalıştırmak için `flask run` komutunu kullanın. Bu komut, uygulamayı varsayılan olarak 5000 portunda çalıştıracaktır.

## Kullanım

1. Flask'ın template özelliği sayesinde, uygulamanın arayüzünü kolayca tasarlayabilirsiniz.

2. Github API'yi kullanarak, kullanıcının girdiği Github kullanıcı adını alın. Ardından bu kullanıcının profiline erişmek için API'ye istek gönderin.

3. API'den alınan verileri kullanarak, kullanıcının profil sayfasını tasarlayın ve kullanıcıya sunun.

Github Finder projesinin genel olarak çalışma şekli bu şekildedir. Flask ve Python kullanarak bu projeyi geliştirmek oldukça eğlenceli olacaktır. Uygulamanızı istediğiniz şekilde özelleştirebilir ve Github API'yi kullanarak farklı verileri alabilirsiniz. İyi kodlamalar!

---

![Link](https://raw.githubusercontent.com/Semihocakli/Github-Finder/main/images/1.png)

![Link](https://raw.githubusercontent.com/Semihocakli/Github-Finder/main/images/2.png)

![Link](https://raw.githubusercontent.com/Semihocakli/Github-Finder/main/images/3.png)

![Link](https://raw.githubusercontent.com/Semihocakli/Github-Finder/main/images/4.png)
