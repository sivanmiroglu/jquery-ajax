# Uzaktan veritabanına (url) üzerinden bağlanıp veri çekme 

# ajaxTable : 

https://northwind.vercel.app/api/categories bağlantısında bulunan  dataları tablo ekleyerek ekran da gösterdik.

# ajaxSample : 

https://northwind.vercel.app/api/categories bağlantısında bulunan  dataları liste halinde ekran da gösterdik.

# ajaxPost : 

Bir Js objesi oluştararak girmemiz gereken bilgileri yazdık. 
https://northwind.vercel.app/api/products adresinde  type:'POST', diyerek veri ekleyeceğimizi bildirdik.
Ve eklenen bilgileri kaydetmesini istedik. Daha sonra eklendiğini uyarı şeklinde bize geri dönmesi için alert komutu yazdık.

# ajax alternatifi olan ve async yapıdaki Fetch ile veri çekme :

https://northwind.vercel.app/api/products
fetch ile sunucuya bir get işlemi yaptım ve url adresimizde bulunan veriler geldi.

# Fetch Post : 

JSON.stringify javascript objemi json a çevirdi.
https://northwind.vercel.app/api/categories
 method: 'POST', diyerek uzak bağlantıdaki veri listemize ekleme yapacağımızı bildirdik.

# getjson ile veri çekme yöntemi : 

"https://northwind.vercel.app/api/categories bağlantıma gittim ve oradaki dataları foreach ile dönerek ekran da gösterdim.


# Linq Sorgulama dili ile elimde bulunan verileri istenilen kriterlere uygunn halde ekran da gösterdik.
