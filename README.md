# python5.gun

Dekoratörler diğer fonksiyonların işlevselliğini(görevlerini) değiştiren, kodları kısaltan ve daha okunabilir hale getiren fonksiyonlardır. Önce kendi içindeki işlevleri yapar ve sonrasında kendinden sonra gelen fonksiyonu çağırarak onu execute(uygulama) eder. Kullanım şekilleri aşağıdadır.

pytest.approx(): İki veya ikiden fazla sayının sayı kümeleri yaklaşık olarak bazı farklılıklara eşitler.
pytest.fail(): Yürütülmekte olan test açıkça başarısız olursa, mesaj gösterir.
pytest.skip(): Gösterilen mesajla yürütme testini atlatır.
pytest.exit(): Test sürecinden çıkartır.
pytest.main(): İşlem içi test yürütmesi tamamlandığında çıkış kodunu döndürür
pytest.raises(): Bir kod bloğu çağrısının beklenen istisnayı ortaya çıkardığını veya bir hata istisnası oluşturduğunu ileri sürer.
pytest.mark.skip(): Bu dekoratör bir test fonksiyonunda belirlenen testi atlamak için kullanılır.
pytest.mark.timeout(): Bir testin belirli bir sürede tamamlanması gerektiğini belirlemek için kullanılır.
Farklı gösterimleri var;
@pytest.mark.skip: Testi atlar, test çalıştırılmaz.
@pytest.mark.skipif: Belirli bir koşula bağlı olan testi atlar.
@pytest.mark.parametrize: Birden fazla parametre vererek testi çalıştırmamızı sağlar.
@pytest.mark.xfail: Testin başarısız olmasını beklediğimizi belirtmek için kullanılır.
@pytest.mark.timeout: Testin belirli bir süre içinde tamamlanması gerektiğini belirtir.

