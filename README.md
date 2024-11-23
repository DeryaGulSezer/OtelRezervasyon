Otel Rezervasyon Veri Analizi ve İptal Oranları:

Veri seti linki: https://www.kaggle.com/datasets/mojtaba142/hotel-booking

Bu proje, otel rezervasyon verileri üzerinde analiz yaparak iptal oranlarını anlamayı ve çeşitli faktörlerin iptallere etkisini incelemeyi amaçlamaktadır.
Python kullanılarak veri işleme, görselleştirme ve temel analizler gerçekleştirilmiştir.

Projenin İçerdikleri:
Eksik veri analizi ve doldurma işlemleri.
Otel türüne ve rezervasyon süresine göre iptal oranları analizi.
Ay bazında iptal oranlarının hesaplanması ve görselleştirilmesi.
Önceden rezervasyon süresi ile iptal ilişkisi görselleştirmesi.

Bu projede otel türüne göre iptal oranlarna bakıldığında, City Hotel iptal oranı %40 üzerinde görünüyor. Bu durum City Hotel rezervasyonlarının daha sık iptal edildiğini gösteriyor.
Resort Hotel iptal oranı ise yaklaşık %30 civarında. Bu durum iptal oranı buralarda daha az olduğunu ifade ediyor.
City Hotel iptal oranlarını azaltabilmek için yeni stratejiler belirlenebilir. 
Ayrıca otel türlerindeki bu farklar rezarvasyon iptal kuralları da etkili olabilir.

Rezervasyon sürelerini kategorilere ayırıp iptal oranına bakıldığında rezervasyon süresi uzadıkça iptal oranının arttığı görünüyor. Uzun süreli rezervasyonlar daha fazla iptal riski taşıyor.
Bu riski azaltmak için esnek rezervasyon politikaları gelişitirilebilir. (Erken rezervasyon iptali durumunda belirli bir ücret kesintisi gibi.)

Ay bazında iptal oranına bakıldığında, en yüksek iptal oranı Nisan ayında, en düşük iptal oranı da Kasım ayında görünüyor. İlkbahar ve yaz aylarında sonbahar ve kış aylarına göre iptal oranı genel olarak daha düşük.
İlkbahar ve yaz aylarında alternatif seyahat planları yapma olasılığı daha fazla olduğundan sonbahar ve kış aylarına göre iptaller daha fazla olabilir.
Cözüm olarak mevsimsel iptal eğilimlerine göre stratejiler geliştirmek gerekebilir.

Önceden rezervasyon süresi ile iptal ilişkisini gözlemlediğimde de İptal edilen ve iptal edilmeyen rezervasyonlar kısa rezervasyon sürelerinde yoğunlaşıyor.
En çok 0–100 gün arasında daha sık veri bulunuyor. Rezervasyon süresi 400 günün üzerine çıktığında hem iptal edilen hem de edilmeyen durumlarda veri sayısının azaldığı gözleniyor.
Çıkan grafikte net bir doğrusal veya belirgin bir eğilim gözlenmiyor. Bu, önceden rezervasyon süresinin doğrudan iptal üzerinde belirgin bir etkisinin olmayabileceğini gösteriyor.


