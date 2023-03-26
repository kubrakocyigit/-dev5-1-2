PyTest'deki decorator'lar, test fonksiyonlarının davranışını ve niteliklerini değiştiren işlevleri olan özel işaretleyicilerdir.
@pytest.fixture : Testlerde kullanılacak ortamları hazırlamak ve paylaşmak için kullanılır.
@pytest.mark.parametrize : Aynı test kodunun farklı parametrelerle çalıştırılmasını sağlar. Bu decorator ile, bir test fonksiyonu farklı parametrelerle defalarca çağrılabilir ve sonuçları karşılaştırılabilir.
@pytest.mark.skip : Bir testin belirli bir koşul altında çalıştırılmamasını sağlar. Örneğin, bir test sadece belirli bir işletim sistemi altında geçerliyse, diğer işletim sistemlerinde çalıştırılmaması için bu decorator kullanılabilir.
@pytest.mark.xfail : Bir testin bilinen bir hata nedeniyle başarısız olacağı durumlarda kullanılır. Bu decorator ile testin başarısız olacağı beklenir, ancak testin hala çalışması ve sonuçların kaydedilmesi sağlanır.
@pytest.mark.timeout : Bir testin belirli bir süre içinde çalışması gerektiğinde kullanılır. Bu decorator, testin belirtilen süre içinde tamamlanmadığı durumlarda testin sonlandırılmasını sağlar.
@pytest.mark.dependency : Testler arasında bağımlılıklar tanımlamak için kullanılır. Bu decorator ile, bir testin önceki bir testin başarılı bir şekilde tamamlanmasını beklemesi sağlanabilir.
@pytest.mark.usefixtures : Bir testin önceden tanımlanmış bir fixture'ı kullanmasını sağlar. Bu decorator, bir test fonksiyonu bir veya daha fazla fixture'ı parametre olarak almadan önce, önceden tanımlanmış bir fixture'ı kullanarak testi çalıştırır.
