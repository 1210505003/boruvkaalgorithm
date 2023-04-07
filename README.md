# boruvkaalgorithm
##**Nedir, Ne Amaçla Kullanılır?**## <br>
Boruvka algoritması Minimum yayılan ağaç algoritmaları arasında yer alır. <br>Bu algoritmalara “Açgözlü (Greedy) Algoritmaları da denir. Bu şekilde denmesinin sebebi en uygun sonuca ulaşmak için her adımda belirli bir strateji izlerler. <br>Her adımında, sonraki adımları düşünmeden sadece bulunduğu durumdaki en iyi seçeneğe yönlenir. <br> <br>
Boruvka algoritması bir graf algoritmasıdır. 1926 yılında Otokar Baruvka tarafından yayınlanmıştır. Moravia şehri için etkili bir elektrik dağıtım ağını amaçlamıştır. <br><br>
 Boruvka algoritması, bir ağırlıklı grafın minimum ağacını bulmak için kullanılır. <br> (Ağırlıklı graf, her bir kenarın bir ağırlık veya maliyet değerine sahip olduğu bir graf türüdür.) <br>Bu algoritma, grafın tüm düğümlerini tek tek ziyaret ederek, her düğüm için en küçük ağırlıklı kenarı seçer ve bu kenarın bağladığı diğer düğümü, düğümün bulunduğu ağacın bir parçası yapar. <br>Bu işlem, tüm düğümler ziyaret edilene ve tüm ağaçlar birleştirilene kadar tekrarlanır. <br>Paralel hesaplama için uygundur, her düğümün hesaplanabilecek ayrı bir alt düğümü vardır. <br> Az yoğunluklu grafiklerde iyi çalışır,yoğun grafiklerde performansı düşük olabilir. <br><br>
Fiberoptik kabloların döşenmesinde (telekominasyon),karayolu, havayolu gibi ulaşım ağlarında ,minimum maaliyetle enerji dağıtımında, tıbbı görüntüleme ve eğitim alanlarında da kullanılabilir.<br>
###Çalışma zamanı### <br>
m kenar sayısı olsun.Grafın bağlantılı olması durumunda ve tüm ağırlıkların farklı olması durumunda en iyi çalışma zamanıyla gerçekleşir.
Bu durumda,her bir düğümün sadece bir kenarı seçilecektir ve bu nedenle toplam işlem adedi m olacaktır. En iyi çalışma zamanı: O(m) <br>
n düğüm sayısı olsun. Ortalama çalışma zamanı: O(m log(n)) dir. Bu durum grafın rastgele olması durumunda gerçekleşir. <br>
eEn kötü çalışma zamanı grafın tüm düğümlerini içeren tam bir tam sayı ağırlıklı grafı ele aldığında gerçekleşir: O(m log(m)) <br>


###**çalışma şekli**### <br> 
<img src="https://github.com/1210505003/boruvkaalgorithm/blob/main/1.png" alt="1" width="500"> <br>
<img src="https://github.com/1210505003/boruvkaalgorithm/blob/main/2.png" alt="2" width="500"> <br>
<img src="https://github.com/1210505003/boruvkaalgorithm/blob/main/3.png" alt="3" width="500"> <br>
