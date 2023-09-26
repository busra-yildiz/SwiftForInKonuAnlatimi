# SwiftForInKonuAnlatimi
Swift programlama dilinde for-in döngüsü, bir dizi, koleksiyon veya aralığı (range) üzerinde dönme işlemleri için kullanılır. Bu döngü, bir 
koleksiyonun veya dizinin her öğesini tek tek alır ve belirtilen işlemleri yapar. İşte for-in döngüsünün temel kullanımı:
for eleman in koleksiyon {
    // Her bir eleman için yapılacak işlemler
}
eleman, her döngü adımında koleksiyonun bir öğesini temsil eder ve bu öğeyi kullanarak istediğiniz işlemleri gerçekleştirebilirsiniz. İşte birkaç örnek:

Dizi Üzerinde for-in Döngüsü Kullanımı:
let sayilar = [1, 2, 3, 4, 5]

for sayi in sayilar {
    print(sayi)
}
Bu örnekte, sayilar dizisi üzerinde bir for-in döngüsü kullanarak her bir sayıyı ekrana yazdırıyoruz.

Aralık Üzerinde for-in Döngüsü Kullanımı:
for indeks in 1...5 {
    print(indeks)
}
Bu örnekte, 1...5 aralığı üzerinde bir for-in döngüsü kullanarak 1'den 5'e kadar olan sayıları ekrana yazdırıyoruz.

Karakter Dizisi Üzerinde for-in Döngüsü Kullanımı:
let metin = "Merhaba"

for harf in metin {
    print(harf)
}
Bu örnekte, bir karakter dizisi üzerinde bir for-in döngüsü kullanarak her bir karakteri ekrana yazdırıyoruz.

İndeks ve Değer Kullanarak for-in Döngüsü Kullanımı:

Eğer döngüde hem indeks hem de değer kullanmak isterseniz, enumerated() fonksiyonunu kullanabilirsiniz:
let meyveler = ["elma", "armut", "muz"]

for (indeks, meyve) in meyveler.enumerated() {
    print("İndeks \(indeks): \(meyve)")
}
Bu örnekte, enumerated() fonksiyonu, döngüdeki öğelerin hem indeksini hem de değerini almanıza olanak tanır.

for-in döngüsü, Swift'te sıkça kullanılan bir döngü türüdür ve koleksiyonlarla çalışırken özellikle kullanışlıdır. Döngü içinde yapmak 
istediğiniz işlemleri for-in döngüsünün içine yerleştirerek, koleksiyonunuzun veya dizinizin her öğesini işleyebilirsiniz.
