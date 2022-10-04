# GlobalAIHub

* UrbanSounds8K Verisi kullanarak iki farklı notebook hazırlandı

1. Preprocessing notebook içerisinde veri seti okunarak gri formata çevirme, yeniden boyutlandırma, normalize etme işlemleri gerçekleştirildi. Son kısmında ise veri listeye atanarak train/test/validation kümelerine ayrılarak kayıt edildi.
2. Model notebook içerisinde ise veri kümeleri okundu. Ardından Keras kullanılarak derin sinir ağ modeli oluşturuldu ve veriler üzerinde çalıştırıldı. Ardından farklı bir model daha oluşturularak aynı veriler üzerinde tekrar çalıştırıldı. Bu sayede iki farklı ağın performansı da karşılaştırılmış oldu. 
