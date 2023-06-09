# Akıllı Şebekelerde Enerji Hırsızlığı Tespiti



# Kullanılacak Kütüphaneler
- Numpy
- Matplotlib 
- Pandas
- Tensorflow
- Keras
- PyTorch

# Sistem Tanıtımı 
-	Bu projenin genel olarak araştırma tabanlı olması nedeniyle projede uygulamaya değil araştırma sonuçlarına odaklanılmıştır.
-	Proje boyunca yapılan araştırmanın sonucuna ulaşmak için projenin arayüzünde araştırılmak istenen veri setleri ve makine öğrenme yöntemi seçilir.
-	Önceden hesaplanan sonuçlar ile iki farklı veri setinden dolaylı iki farklı grafik oluşturulmuştur. Arayüz ekranında yapılan seçime göre bu grafiklerden biri ekrana yansıtılır. Bu grafik üzerinde, arayüzde seçilen makine öğrenmesi yönteminin sonucu diğer yöntemlere göre daha belirgin gözükecek şekilde grafikte yansıtılır. Burada amaç diğer yöntemlerle seçilen yöntemin karşılaştırılmasının yapılmasıdır.

# Sonuç
Bilgisayar Projesi I ve Bilgisayar Projesi II kapsamında yürütülen çalışmalar, Akıllı Şebekelerde Enerji Hırsızlığı Tespitini geliştirmek ve farklı yaklaşımlar bulmak amacıyla gerçekleştirilmiştir. Bu çalışmaların içinde SEAI veri seti üzerinde yapılan modelleleme çalışmaları ön plana çıkmaktadır. Literatür taraması ve deneyler sonucunda, RNN (Recurrent Neural Network) modelinin SEAI veri seti için en uygun model olduğu tespit edilmiştir. RNN modeli, hırsızlık tespitinde başarılı sonuçlar vermiş ve diğer modellere kıyasla daha iyi performans sergilemiştir. Ancak, çalışmalar sırasında karşılaştırma yapma amacıyla CNN (Convolutional Neural Network) üzerinde de çalışmalar yapılmıştır. Literatür taraması ve deneyler sonucunda, SEAI veri seti için CNN modelinin uygun bir seçenek olmadığı görülmüştür. Bu durum, CNN'in veri setinin özellikleriyle tam olarak uyumlu olmadığını göstermektedir. Bununla birlikte, çalışmaların bütünlüğünü sağlamak adına CNN modeli üzerinde de çalışmalar yapılmış ve elde edilen sonuçlar diğer modellere kıyasla daha düşük başarı göstermiştir. Ayrıca, RNN modelinin bir varyasyonu olan RNN-LSTM (Long Short-Term Memory) modeli de çalışmalar kapsamında uygulanmıştır. RNN-LSTM modeli, RNN modeline göre biraz daha geride kalmış ve daha düşük performans göstermiştir. Bu durum, LSTM mimarisinin SEAI veri seti üzerinde beklenen etkiyi tam olarak sağlayamadığını göstermektedir.
_Güncellenecektir._
