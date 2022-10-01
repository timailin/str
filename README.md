Жизнь выдающихся программистов. Джей Фриман (saurik)
====================================================

[Блог компании RUVDS.com](/ru/company/ruvds/blog/) [Программирование \*](/ru/hub/programming/)[Разработка под iOS \*](/ru/hub/ios_dev/)[Системное программирование \*](/ru/hub/system_programming/)[Разработка под Android \*](/ru/hub/android_dev/)

[

![](https://habrastorage.org/r/w780q1/webt/hg/8k/uq/hg8kuql4qliwd6g92dzylso86ky.jpeg)

](https://habr.com/ru/company/ruvds/blog/688716/)  
Прошлая серия про талантливую программистку [Джастин Танни](https://habr.com/ru/company/ruvds/blog/682150/) не оставила равнодушной хабрасообщество. Поэтому продолжаем заполнять нижние строчки хит-парада выдающихся программистов 21 века. Это особенные личности, которым карьера как будто не важна. В силу высокого IQ, врождённой любознательности и особого характера они не способны выполнять скучные, рядовые задания. Только интересные или важные. И только по своей воле, не по указанию сверху.  
  
Следующий герой — более публичный и известный персонаж, про него даже есть [статья в Википедии](https://en.wikipedia.org/wiki/Jay_Freeman). Гений реверс-инжиниринга Джей Фриман известен под ником _saurik_, а славу ему принёс каталог «запрещённых» приложений [Cydia](https://cydia.saurik.com/) (для взломанных айфонов).  
  

▍ Cydia
-------

  
Популярное в 2008–2009 годах приложение [Cydia](https://cydia.saurik.com/) — графическая оболочка для стандартного установщика пакетов [apt](https://tracker.debian.org/pkg/apt). Она устанавливается на любое устройство iOS после джейлбрейка. В комплекте идут ссылки на каталоги «альтернативного» программного обеспечения, в том числе запрещенного к распространению через App Store, и утилит Linux, как стандартных, так и допиленных под Darwin (опенсорсная эппловская ОС, на её базе работают macOS, iOS, watchOS и другие оболочки).  
  
Линуксовые программы работают под Darwin, потому что это то же самое семейство Unix-подобных и BSD-систем.  
  
Cydia позиционировалась как новая, свободная версия старого установщика пакетов [Installer.app](https://en.wikipedia.org/wiki/Installer.app), который вышел в 2007 году, потому что в первых версиях iPhone вообще не было штатного способа устанавливать сторонние программы, а сервис App Store отсутствовал в принципе.  
  
В общем, сначала появился [Installer.app](https://en.wikipedia.org/wiki/Installer.app), потом App Store, а потом Cydia.  
  
![](https://habrastorage.org/r/w780q1/webt/pv/_d/ka/pv_dkams2irtp46mi7kbhjjbe2s.jpeg)  
  
В 2009 году джейлбрейк айфонов и установка Cydia стали настоящей революцией — про это писали многие технические СМИ, и даже [издания национального уровня](https://www.wsj.com/articles/SB123629876097346481). В 2012 году состоялись [слушания по DMCA](https://www.copyright.gov/newsnet/2012/451.html), на которых Бюро по авторским правам США продлило мораторий на применение закона DMCA для частных лиц. Другими словами, юристы [признали право владельца телефона на джейлбрейк своего устройства](https://www.eff.org/cases/2012-dmca-rulemaking). Это его собственность, поэтому он имеет полное право взламывать его, если пожелает.  
  
Это было принципиальное решение, потому что корпорация Apple и другие правообладатели настаивала на обратном — что программное обеспечение и, следовательно, сам смартфон в каком-то смысле _принадлежит_ ей после продажи, а пользователь просто временно _пользуется_ этим программным обеспечением. И якобы Apple может диктовать, какой софт разрешено устанавливать на телефон, а какой нельзя. Притязания Apple были отвергнуты, что стало важным решением для того времени. Джей Фриман тоже присутствовал на тех слушаниях в Лос-Анджелесе и сделал фото с задних рядов:  
  
![](https://habrastorage.org/r/w780q1/webt/ap/3q/jw/ap3qjwvq77qlpnutpmhiz_ozxye.jpeg)  
  
В 2009 году некоторые инструменты для джейлбрейка iOS сразу шли в комплекте с Cydia. После широкой огласки этот фронтенд и каталог был установлен более чем на 30 млн взломанных устройств. Суточная аудитория в 2009 году [превышала 470 тыс. человек](https://www.wired.com/2009/08/cydia-app-store/).  
  
![](https://habrastorage.org/r/w780q1/webt/ht/ai/cn/htaicn4bospsvpny9hcrewz4ho4.jpeg)Возможно, Саурик сумел заработать на этом проекте какие-то деньги. По крайней мере, он зарегистрировал частную фирму [SaurikIT, LLC](https://www.saurikit.com/), запустил для каталога Cydia Store систему приёма платежей по PayPal и брал с платных приложений стандартную комиссию 30%. Через полгода в каталоге зарегистрировались сотни бесплатных и [15 платных](https://www.wired.com/2009/08/cydia-app-store/) приложений, которые удалось продать на общую сумму $220 тыс (например, [3G Unrestrictor](https://www.3gunrestrictor.com/)). Потом обороты начали расти. В следующие несколько лет Cydia Store известен как крупнейший каталог альтернативных приложений для iOS. Приём платежей работал [до декабря 2018 года](https://www.theverge.com/2018/12/16/18143422/cydia-disables-in-app-purchases-ios-jailbreak-store-apple-iphone).  
  
Конечно, Cydia — не первая программа Джея Фримана. Он долго к этому шёл. Ещё в школьно-студенческие годы парень начал с декомпилятора C# и других полухакерских инструментов.  
  

▍ Другие проекты
----------------

  

*   [Anakrino](https://web.archive.org/web/20050203180426/http://www.saurik.com/net/exemplar/) — декомпилятор C# для Microsoft .NET. Первая публикация в веб-архиве датируется [28 апреля 2001 года](https://web.archive.org/web/20010428135752/http://www.saurik.com/net/exemplar/), когда чикагский парнишка в возрасте 19 лет приехал грызть гранит науки на факультет компьютерных наук Калифорнийского университета в Санта-Барбаре. Вот фотография того времени, вероятно, из университетского общежития на 1 курсе ([источник](https://vimeo.com/126618332)):  
      
    ![](https://habrastorage.org/r/w780q1/webt/_f/x3/ux/_fx3uxrs1mjd3iawiliyi8yft4e.jpeg)  
      
    Джей говорит, что с тех пор резко изменил внешний вид и стиль одежды — возможно, университетский стиль жизни, а потом многочисленные выступления перед публикой оказали какое-то влияние.  
      
    Так или иначе, Anakrino стала первой программой, которую он выложил в открытый доступ. Как видим, он изначально выбрал сферу реверс-инжиниринга. Она впоследствии и привела его к известности через джейлбрейки iOS и Android. Однако эту конкретную программу он позже удалил с ftp, включая исходники.  
    
*   [Chora/SVN](https://svn.haxx.se/dev/archive-2002-06/1614.shtml) — веб-клиент для системы контроля версий Subversion, разработан в 2002 году в качестве альтернативы ViewSVN.
*   Cycorder — высокоскоростной (MJPEG) рекордер видео для iPhone (см. ниже список приложений и функций для Cydia).
*   [Cycript](http://www.cycript.org/) — мост с JavaScript на Objective-C, позволяющий разработчикам исследовать и изменять запущенные приложения на iOS или Mac OS X, используя гибрид синтаксиса Objective-C++ и JavaScript с помощью интерактивной консоли с подсветкой синтаксиса и автозавершением табуляции.  
      
    Инъекция в процессы:  
      
    
        bash# cycript -p SpringBoard
        cy#
    
      
    Кроме Darwin, приложение автономно работает на Android и Linux, предоставляя доступ к Java, но без инъекции в процессы.  
      
    Как можно понять из примеров кода, хакерский инструмент Cycript нужен для _изменения поведения приложений_, установленных на ваше устройство, то есть для взлома.  
      
    Например, некое приложение пытается залезть в `/etc/passwd`, чтобы проверить пароль. А мы вместо этого отправляем его за паролем в директорию `/var/passwd-fake`:  
      
    
        cy# fopen = dlsym(RTLD_DEFAULT, "fopen")
        (typedef void*)(0x7fff900c34ec)
    
      
    Презентация:  
      
    
      
    
*   [Cyrket](https://web.archive.org/web/20081218052235/http://www.cyrket.com/) — клиент Android Market для десктопных веб-браузеров. Идейный аналог Cydia, только для Android.  
    
*   [FQL/JDBC](https://web.archive.org/web/20090620102150/http://forum.developers.facebook.com/viewtopic.php?pid=9172) — драйвер JDBC для Facebook Query Language (FQL). Позволял производить FQL-запросы в стандартном SQL-стиле. Данные возвращаются по умолчанию в формате JSON. К сожалению, Facebook API старше 2.0 больше пе поддерживают FQL.
*   [ircWAB](https://web.archive.org/web/20080829211521/http://www.irclogs.com/irc-bin/login.irc?net=srks) — простой IRC-клиент на HTTP, работал в браузере, без использования Java и Flash
*   [iPhone Java](https://web.archive.org/web/20071212202601/http://iphone.fiveforty.net/wiki/index.php/IPhone_Java) — порт Java для iPhone (с коннекторами Objective-C). Смысл в том, что после джейлбрейка на устройстве iOS можно запустить компактную Java Virtual Machine и рабочее окружение. В частности, автору удалось запустить на своём телефоне [JamVM](https://web.archive.org/web/20071226091615/http://jamvm.sourceforge.net/) с определёнными изменениями.  
    
*   [Menes/C++](http://svn.saurik.com/repos/menes/trunk/) — высокоуровневая библиотека C++, которая используется в инсталляторе Cydia и других инструментах.
*   [Nmap+V](https://web.archive.org/web/*/ftp://ftp.saurik.com/pub/nmap/nmap%2BV) — оригинальный сканер портов Nmap со вспомогательными XML-скриптами для распознавания протоколов и ускорения сканирования. Когда автор `nmap` не успел ещё реализовать эту функциональность у себя, он [рекомендовал](https://nmap.org/presentations/OSDEM01/) нуждающимся использовать патч от Саурика.
*   [Orchid](https://www.orchid.com/) — децентрализованная платформа и рынок VPN (на блокчейне ERC-20, токен OXT). Джея пригласили техническим директором — и он всё сделал.
*   [s3fs](http://svn.saurik.com/repos/menes/trunk/s3fs/) — высокопроизводительная файловая система для S3 (на уровне ядра Linux)
*   [Cydia Substrate](http://www.cydiasubstrate.com/) — мощная платформа для изменения кода работающих приложений на лету (под iOS и Android), для работы требует рутования или джейлбрейка. С помощью этой платформы создавались моды (изменённые варианты) оригинальных приложений Apple для платформы Cydia. Сам Джей разработал и выпустил с помощью этого модификатора многочисленные версии программных расширений и функций iOS для операционной системы после джейлбрейка, в том числе:  
      
    
    *   [Apple File Conduit 2](https://www.redmondpie.com/afc2-for-ios-8-8.1-released-by-saurik-gives-full-file-system-access-over-usb/) (AFC2) — полный доступ к файловой системе iOS;  
        
    *   [Cycorder](http://www.imore.com/the-free-iphone-video-recorder-cycorder) — бесплатный видеорекордер, упоминался выше;  
        
    *   [CyDialer](http://blogs.wsj.com/digits/2009/12/14/app-watch-exploiting-the-iphone-lock-screen/) — доступ к экрану блокировки, например, для быстрых звонков;  
        
    *   [Cydget](http://blogs.wsj.com/digits/2009/12/14/app-watch-exploiting-the-iphone-lock-screen/) — виджеты для экрана блокировки;  
        
    *   [Cyntact](https://web.archive.org/web/20180202012532/https://www.imore.com/daily-tip-add-contact-pics-address-book-cyntact-jailbreak) — добавление картинок (фотографий) в адресную книгу iOS;  
        
    *   [Cyueue](https://lifehacker.com/cyueue-adds-quick-song-queuing-to-the-ios-music-app-5991880) — добавление во встроенный плеер кнопки «Играть следующую песню» до окончания текущей;  
        
    *   Five Icon Dock — док на пять иконок;  
        
    *   [Veency](https://cydia.saurik.com/package/veency/) — удалённое подключение к айфону по VNC ([видео](https://cache.saurik.com/veency.mov));  
        
    *   [WinterBoard](https://appadvice.com/appnn/2008/08/how-to-use-winterboard-summerboard-replacement-a-walkthrough) — фоновое приложение, которое скачивает и применяет любые темы оформления, включая анимированный фон, значок аккумулятора, разные слайдеры и проч.;  
        
    *   [Cydia Eraser](https://www.networkworld.com/article/2950156/new-un-jailbreaking-tool-cydia-impactor-for-ios-has-android-roots.html) (Cydia Impactor), чтобы скрывать на телефоне следы джейлбрейка, удалять личные данные, стирать Cydia и возвращать оригинальный номер версии iOS;  
        
    *   … и др.
    
      
    ![](https://habrastorage.org/r/w1560/webt/wa/5s/3n/wa5s3n4_vythudzgayuus8_5vbs.png)В 2013 году Саурик [взломал Google Glass](https://www.forbes.com/sites/andygreenberg/2013/04/26/google-glass-has-already-been-hacked-by-jailbreakers/) и выпустил Cydia Substrate для Android (справа — фото того времени).  
    
*   [Telesphoreo](https://web.archive.org/web/20110728083846/http://www.telesphoreo.org/) — дистрибутив Linux-программ для установки на iPhone или другой совместимый смартфон (его можно было установить вместе с фронтендом Cydia).
*   Quotes — приложение Facebook для трансляции постов друзей.

  

▍ Telesphoreo
-------------

  
Стоит пару слов сказать о закрытом проекте [Telesphoreo](https://web.archive.org/web/20110716010440/http://www.saurik.com/id/1), который ставил целью [превратить iPhone в полноценную рабочую станцию Linux](https://www.linuxinsider.com/story/android-schmandroid-linux-on-the-iphone-62209.html).  
  
В 2008 году после массового джейлбрейка айфонов это был не единственный проект подобной направленности. Можно вспомнить ещё [CoreOS — iPhoneUnix](https://web.archive.org/web/20090620091637/http://www.wickedpsyched.com/iphone/unixtools), который предлагал нормальные рабочие копии под iOS следующих инструментов: `chmod`, `chown`, `wget`, `ping` и др.  
  
Через интерфейс Cydia можно было установить многие другие стандартные утилиты, bash, coreutils, OpenSSH и др. Telesphoreo планировался как открытый дистрибутив, включающий и другие утилиты, в том числе netstat, passwd, screen, su, uptime, vim, чтобы все они нормально работали и не глючили на iPhone.  
  
Со временем авторы этих проектов свернули свою деятельность и удалили сайты.  
  

* * *

  
Джей Фриман называет себя «серой шляпой», то есть он действует на грани закона, не переступая черту. Входил в группу iPhone Dev Team, которая занималась разработкой [джейлбрейков iOS](https://en.wikipedia.org/wiki/IOS_jailbreaking). Вероятно, он причастен к разработке эксплоитов. Но использование готовых эксплоитов для установки на свой телефон любого программного обеспечения, а также видоизменение установленного на своём телефоне софта не нарушает американского законодательства. Также и _написание_ программного обеспечения не может являться нарушением закона [согласно Конституции США](https://en.wikipedia.org/wiki/Bernstein_v._United_States). Здесь тонкая грань, которую Саурик благоразумно старается не переходить, по крайней мере, публично. Хотя пришлось удалить из открытого доступа половину разработанных инструментов, но сам он на свободе.  

> **[Telegram-канал](https://bit.ly/3KZeaxv) и [уютный чат](https://bit.ly/3qoIOXs) для клиентов**

[![](https://habrastorage.org/r/w1560/webt/sz/7j/pf/sz7jpfj8i1pa6ocj-eia09dev4q.png)](http://ruvds.com/ru-rub?utm_source=habr&utm_medium=article&utm_campaign=alizar&utm_content=zhizn_vydayushhixsya_programmistov._dzhej_friman_(saurik))

Теги:

*   [Джей Фриман](/ru/search/?target_type=posts&order=relevance&q=%5B%D0%94%D0%B6%D0%B5%D0%B9%20%D0%A4%D1%80%D0%B8%D0%BC%D0%B0%D0%BD%5D)
*   [saurik](/ru/search/?target_type=posts&order=relevance&q=%5Bsaurik%5D)
*   [джейлбрейк iOS](/ru/search/?target_type=posts&order=relevance&q=%5B%D0%B4%D0%B6%D0%B5%D0%B9%D0%BB%D0%B1%D1%80%D0%B5%D0%B9%D0%BA%20iOS%5D)
*   [Linux на iOS](/ru/search/?target_type=posts&order=relevance&q=%5BLinux%20%D0%BD%D0%B0%20iOS%5D)
*   [s3fs](/ru/search/?target_type=posts&order=relevance&q=%5Bs3fs%5D)
*   [Cydia](/ru/search/?target_type=posts&order=relevance&q=%5BCydia%5D)
*   [Telesphoreo](/ru/search/?target_type=posts&order=relevance&q=%5BTelesphoreo%5D)
*   [CoreOS](/ru/search/?target_type=posts&order=relevance&q=%5BCoreOS%5D)
*   [iPhoneUnix](/ru/search/?target_type=posts&order=relevance&q=%5BiPhoneUnix%5D)
*   [ruvds\_статьи](/ru/search/?target_type=posts&order=relevance&q=%5Bruvds_%D1%81%D1%82%D0%B0%D1%82%D1%8C%D0%B8%5D)
