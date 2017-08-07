# AndroQuiz

# Amaç

1. Git - GitHub becerilerinin arttırılmasını sağlamak.
2. Activity'ler üzerindeki becerileri geliştirmek.
3. Fragment'lar üzerindeki becerileri geliştirmek.
4. Activity-Fragment, Fragment-Activity arasında veri taşıyabilmek.
5. Activity-Activity arası veri taşıyabilmek.
6. XML Attributes, String işlemler, TextWatcher, Bundle, Intent, Parcelable, Interface, Singleton Pattern, MemoryLeak hakkında bilgi sahibi olunmasını sağlamak.

# İsterler

1. Projeyi "Fork" ediniz.
2. Master branch'inden yeni bir branch oluşturunuz.
3. Branch ismine kendi adınızı ve soyadınızı veriniz. Örn. ("GökhanÖztürk)
4. Activity - Fragment ikilisini, @string, @color, @style, @dimen gibi resource dosyalarını kullanmayı ihmal etmeyiniz.

# Uygulama

1. Uygulama ilk açıldığında, ekranda "Kullanıcı Adı",  "Kullanıcı Şifresi" ve Giriş butonu yer alacaktır. Tasarımı sizin yaratıcılığınıza kalmıştır (:
2. Şifre girilecek olan Edittext'te, her karakter girişinden sonra, maskeleme (* * * * ) şeklinde gösterim yaptırılacaktır.
3. "Kullanıcı Adı" alanına sadece "Alfa-Numerik" karakter girişi yapılabilecek; Sayı ve ? * / gibi özel karakter girişleri engellenecektir. Kullanıcı buraya gireceği isimde boşluk karakteri ile başlayamayacaktır. (startwith methodunu araştırnız.)
4. "Kullanıcı Adı" EditText'ine "hint" olarak "Sadece alfa-numerik karakter giriniz." yazdırılacaktır ve bu Edittext alanına en fazla 20 karakter girişi yapılabilecektir.
5. Login butonunu ilk açılışta "inaktif" konuma alınız. 
6. "Kullanıcı Adı" ve "Kullanıcı Şifresi" alanlarına en az 1'er karakter girişi olmadan "Login Butonu"nu "aktif" etmeyiniz.
7. "Login Butonu"na basıldığında, "Kullanıcı Adı" bilgisi "Quiz Ekranına" taşınacaktır. Bundle ile putExtra yardımı ile taşıyınız.
8. "Quiz Ekranı"nın en tepesinde kullanıcının girmiş olduğu "Kullanıcı Adı" bulunacaktır.
9. Altında "Soru - 1" ifadesi yer alacaktır.
10. Bunun da altında ise "Quiz Sorusu" bulunacaktır.
11. Sorunun altında ise "4 adet yuvarlak buton ve cevap şıkları" bulunacaktır. Bu butonlardan herhangi biri seçildiğinde diğerlerindeki seçim kaldırılacaktır.
12. Bu 4 şıkın altında ise "Devam Butonu" yer alacaktır ve "inaktif" olacaktır.
13. Bu 4 şık'tan birini seçmeden "Devam Butonu" aktif olmayacaktır.
14. Kullanıcı "Devam Butonu" basarak, görsel olarak aynı ekrana sahip, 2. soru açılacaktır. Benzer şartlar bu 2. soru ekranı içinde aynıdır.
15. Toplamda 10 adet soru sorulacaktır ve her bir soru cevaplandığında bir sonraki soruya geçilirken, cevap "Singleton Class" üzerinde saklanacaktır. 
16. Onuncu soruya gelindiğinde "Devam Butonu"nun texti "Sonuç Butonu" olarak değiştirilecektir.
17. Sonuç butonuna basıldığında toplanan 10 sorunun cevabı Soru1 = A, Cevap1 = true | Soru2 = D, Cevap2 = false, gibi String ve boolean ikilemeler ile saklanacak ve bir sonraki "Sonuç Ekranına" gönderilecektir.
18. Saklamayı yaptığınız bu classta (view model) toplam 10 soru (String) 10 cevap (boolean) bulunacaktır ve gönderimi yaparken "Parcelable" yöntemini kullanmanız beklenmektedir.
19. Sonuç Ekranı"nda yine en tepede "Kullanıcı Adı" bulunacaktır.
20. "Kullanıcı Adı"nın altında Soru 1 = Doğru, Soru 2 = Doğru, Soru 3 = Yanlış şeklinde alt alta sıralama yapılacaktır.
21. Yanlış textleri kırmızı ve bold, Doğru textleri yeşil ve bold olacaktır. Soru 1 textleri ise siyah düz olacaktır.

22. Yazdığınzı kodları Push'layınız. Ve bu adres üzerindeki ana projeye Pull Request (PR) atınız. Pull Request'lerinizi atarken artık master'ı değil, sizin kendi isminizde açılmış olan ana repodaki branch'lere atınız.

23. Activity - Fragment , Fragment - Activity, Activity - Activity kaç farklı veri taşıma yolu vardır? Bu veri taşıma yollarının dezavantajları nelerdir? Bu veri taşıma yollarından en performanslı olanı hangisidir ve neden? Sorularının cevaplarını kendi projenizde README.md isimli dosyanızı oluşturarak içerisine yazınız.

# Not : Master branch'e atılan PR'lar kabul edilmeyecektir.

# Tüm isterleri yerine getirmeniz durumunda, Android Bootcamp 201, kurunu başarıyla tamamladınız demektir. Aksi halde, bu işi meslek olarak yapabilmeniz için çok daha fazla çalışmanız gerektiği gerçeğini kendinize lütfen hatırlatınız..
