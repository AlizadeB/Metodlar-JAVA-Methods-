# Metodlar (JAVA Methods)

Metod müəyyən tapşırıq və ya əməliyyatı yerinə yetirmək üçün birlikdə qruplaşdırılmış kodlar toplusudur.

Metodun üstünlükləri :
-	Biz metodu adı vasitəsilə təkrar istifadə edə bilərik.
-	Metod kodu dəfələrlə yazmağın qarşısını alır. 
-	Asan dəyişdirilə bilən quruluşa malikdir.
-	Metod çağırdıqda istifadə edə bilərik.
### Java-da iki növ metod var:

-	Standart Kitabxana Metodları: Bunlar Java-da istifadə oluna bilən daxili metodlardır.
-	İstifadəçi tərəfindən müəyyən edilmiş Metodlar: Tələblərimizə əsasən öz metodumuzu yarada bilərik.

*Standart kitabxana metodlarına aid nümunələr* :

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/3d7429993b60c9700130370465473bdf.png)

Məsələn yuxarıdakı nümunədə cümlədəki simvolları sayan (cümlənin uzunluğunu hesablayan)
length() metodu, a^b-ni hesablayan Math sinfinə aid pow() metodu 
nümunə olaraq verilmişdir. Buna aid nümunələri göstərməklə bitməz 
bunun üçün yaxşı araşdırma etməlisiniz. Tətbiq və araşdırma bu 
metordları öyrənməkdə sizə kömək olacaq.

İstifadəçi tərəfindən yaradılan metodları isə metodların quruluşu 
başlığı altında nümunələrlə daha rahat öyrənəcəyik.

## Metodların quruluşu

Metodların quruluşunu bir struktur altında göstərmək çox çətindir. Bunun üçün bilməli olduğumuz iki ayrı quruluş var:
-	Geriyə dəyər qaytaran
-	Geriyə dəyər qaytarmayan

Bundan başqa da parametrin olub olmamasına görə ayırmaq olar. Məhz buna görə metodları dörd ayrı formada sadədən mürəkkəb quruluşa doğru öyrənək :
-	Geriyə dəyər qaytarmayan parametrsiz
-	Geriyə dəyər qaytarmayan parametrli
-	Geriyə dəyər qaytaran parametrsiz
-	Geriyə dəyər qaytaran parametrli

## Gerıyə dəyər qaytarmayan *parametrsiz* metodlar

Əgər metod geriyə dəyər qaytarmırsa onun tipi ***void***, yəni boş olur. 
Gördüyünüz kimi aşağıdakı nümunədə metoddan kənar iki müraciət dəyişkəni
 təyin olunub ki, bunlar da metodda daha sonra istifadə üçün nəzərdə tutulmuşdur.

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/38b6ba1655dbcb0a7c0912ad73a48da1.png)

## Gerıyə dəyər qaytarmayan *parametrli* metodlar

Bu metodun tək fərqi parametr qəbul etməsidir. Sahə hesablama zamanı 
parametrli metod daha məntiqə uyğundur. Çünki beləcə istifadəçi metodu 
çağırdıqda dəyərləri daxil etməsi məcbur olacaq. Metodları daha yaxşı 
anlamaq üçün hamısında eyni nümunə istifadə edilmişdir.

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/0be0741bbb82ea9724c8dd8ff6c16013.png)

Yuxardakı metodu Hendese sinfi içində yaratmış olduğumuzu düşünək və 
bunu başqa sinifdə çağırıb istifadəsinə baxaq:

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/affc1fa52559923d5b1e194f76a30c4c.png)

Əvvəlcə Hendese sinfinin obyekti yaradıldı daha sonra referans dəyişəni 
(***hendese***) vasitəsilə metod parametrlər daxil edilərək istifadə edildi.

## Gerıyə dəyər qaytaran *parametrsiz* metodlar

Bu metod növündə metodun artıq bir tipə malik olmasıdır. Burada daha 
bir yenilik məcburi olaraq istifadə olunan ***return*** açar sözüdür. Bu açar 
sözündən sonra gələn ifadə mütləq şəkildə metodun **verilən tipi ilə eyni** olmalıdır.

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/6307271843feb2fbf375f71973536442.png)

## Gerıyə dəyər qaytaran *parametrli* metodlar

Burda da tək fərq parametrlərin istifadəsidir. Amma bir məsələni unutmayın ki 
`parametrin tipi` `metodun tipi` ilə ***eyni olmaq məcburiyyətində deyil.***

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/fa192276d0aa90ea96f85adfb4a18255.png)

Gəlin bir neçə nümunə ilə metodların öyrənilməsini sadələşdirək.

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/278cd9251b52e16f1e4bf86a37142bcc.png)

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/048eef36ab5002dbcd8cd13673b53e84.png)

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/770e5a3819ae52ee90e4904bd0687dcd.png)

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/72430f8c760876b246a36f752af718e4.png)

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/fec2ff098e882dc4b698419952409aa2.png)

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/6d49ea8bec27e99c12396cb4a4b5b2f8.png)

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/c10aeb7953c94432b89e167ae44c484f.png)

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/351ac6473822095171371065bfd86c20.png)

## Statik metodlar

İndiyə kimi gördüyümüz metodlar müraciət metodları (***instance methods***) idi. 
Bu metodları istifadə etmək üçün sinfin obyektini çağırıb referans dəyişəni vasitəsilə çağırırdıq. 

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/0c1c2861af0485a14a67788487edf8f4.png)

Statik metodlarda bir başa sinif vasitəsilə metoda müraciət etmiş oluruq :

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/e7e86c75bbae13a33dd44a279d71a317.png)

Burada Math sinfi vasitəsilə bir başa müraciət edərək sqrt() 
parametrli metodunu istifadə etmiş olduq. İndisə istifadəçi 
tərəfindən əvvəlcə ***instance*** sonra isə ***static*** bir metod yazaq :

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/5336a50bbeabee85d17c64047ab9d656.png)

Birinci növbədə metodu yazdıq daha sonra isə metodu çağıraraq istifadə edək:

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/913f5acc4070dcfc0397c99c7d4ea336.png)

İndisə metodu statik metoda çevirib istifadə edək :

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/9dc6afa157c7808b152f22fec5932d2c.png)

Sadəcə metodun verilən tipi qarşısına static açar sözünü əlavə etməmiz kifayət edir. Daha sonra isə metodu bir başa sinfin obyektini yaratmadan istifadə edə bilirik :

![Uygulama Ekran Görüntüsü](https://i2.paste.pics/6a5d2298f71a79ac5efe68fd36789cea.png)

## İstinadlar

Bu yazı aşağıdaki mənbələrdən yararlanılaraq hazırlanmışdır:

- https://www.w3schools.com/java/java_methods.asp
- https://www.geeksforgeeks.org/methods-in-java/
- https://www.javatpoint.com/method-in-java
- https://www.programiz.com/java-programming/methods
- https://www.programiz.com/java-programming/constructors
- https://www.geeksforgeeks.org/constructors-in-java/ 
