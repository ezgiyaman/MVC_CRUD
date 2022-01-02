# MVC NEDİR ?

MVC, birbirinden bağımsız üç katmanı esas alan bir "Mimarisel Desen(Architectural Pattern)"dir.

![images-e1541800937137](https://user-images.githubusercontent.com/90327328/147884484-8bcb2bdd-4d0b-4cea-9ac6-4dcf9e9adc2f.png)


# MODEL

İşlenecek olan veriyi temsil eden katmandır.Genellikle veri tabanı işlemlerinin yapıldığı katmandır.

# VİEW

İstek neticesinde elde edilen verileri görselleştirerek görsel çıktısını verecek katmandır.

# CONTROLLER

* Gelen requestleri karşılayacak olan ve requestin içeriğine göre gerekli model işlemlerini yönetecek katmandır.
* Algoritmaları, servisleri, veritabanını vs. çağırarak/çalıştırarak/sorgulayarak istenilen veriyi üretmekte ve ihtiyaç dahilinde üretilen veriyi View ile görseleştirmekten sorumludur.
* Controller gelen isteği her zaman karşılamaktadır.
* Model ile Controller konuşmaktadır.Çünkü Model ve View sayfası birbirinden soyutlanmaktadır.Bunu da Controller yönetmektedir.

