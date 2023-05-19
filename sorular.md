## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, çalışılan projelerin kontrolünün yapıldığı bir yazılımdır. Kaynak kodların değişimini sürümlerini kontrol edebilmemiz için kullanılır.
2. Git ile GitHub arasında ne fark var?
Git, projenin localde çalışıp sürüm kontrolü yapabilmesine olanak sağlar. Github ise cloud tabanlı bir platformdur. Uzaktan sunucuya projelerimizi yükleyebilir ve sürüm kontrollerini buradan sağlayabiliriz.
3. Neden bir branch oluşturuyoruz?
Projenin ana kaynağından ayrılarak farklı ve bağımsız bir şekilde değişiklikler yapabilmemiz için branch kullanıyoruz. Örnek olarak, bir proje üzerinde bir çok kişi/ekip projede değişiklik yapabilir ve değişiklikleri test edebilir. 
4. Pull Request'in amacı nedir?
Pull request ile projenin temeline yapılacak değişiklikleri sağlamak için bir nevi öneride bulunmuş oluruz. Bu sayede projede değişiklikler yapılabilir, geliştiriciler bu değişiklikleri inceleyebilir ve test edebilir.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout main kodu ile main branch'e geçebiliriz.
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
Git fetch uzak sunucuda ki değişiklikleri alır. Git merge tüm farklı alanlarda ki değişiklikleri birleştirmek için kullanılır. Git pull ise git fetch ve merge de bulunan tüm değişiklikleri alır ve yerel tarafta bu işlemlerin birleştirmesini yapar.

7. Merge conflict nedir?
Merge conflict farklı alanlarda yapılan değişikliklerin birleşirken çakışmasına denir. 

8. Merge conflict'i nasıl çözeriz?

Merge conflict i düzenlemek için çakışmayı gidermek gerekiyor. Git ile çakışmayı inceleyebilir ve çakışmaya neden olan kodları görebiliriz. Bununla birlikte dosyaları düzeltebiliriz.
