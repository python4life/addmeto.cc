# Кажется твиттер решил убить нас всех

Ребята из Твиттера очень давно мечтали удавить лишние генераторы запросов к API. Полтора года назад в правилах использования появились строчки о том, что не надо использовать API для повторения функциональности сайта twitter и официального клиента. Уже это напрягало. А теперь [твиттер обещает приступить к репрессиям](https://dev.twitter.com/blog/changes-coming-to-twitter-api).

![center](http://img-fotki.yandex.ru/get/6504/9320383.7/0_7ca9e_621c451b_orig)

Что же собственно они объявили? Начиная с Twitter API версии 1.1 которая будет единственной уже через полгода:

* будет необходима аутентификация для *каждого* запроса к API. Сейчас многие вызовы можно делать анонимно, например поиск или запрос профайла.
* вводятся новые правила по регулировке ограничений на количество вызовов. И они, ну, немножко драконовские.
* так же войдут в силу новые Правила Разработчика, которые прижмут всех, но особенно разработчиков альтернативных твиттер-клиентов.

Интересно тут буквально всё. Для начала - я согласен с первым пунктом, конечно доступ к каждому элементу API должен быть по ключу. Но дальше начинается треш, угар, содом и гоморра. Потому что ограничивать использование Twitter API не по количеству запросов, а по количеству выданных ключей - это **очень** странно. Ограничение в 100 тыс пользователей для сервиса на базе twitter API - это очень мало, даже я писал бOльшие проекты.

Дальше - еще унизительнее. Майкл Сиппей, директор по продукту, запросто классифицирует потребителей API твиттера, выписывая их в четыре квадрата. И на этой квадратичной схеме показывает полезность или бесполезность проектов. Например [klout](http://klout.com/bobuk) полезный, а твитбот (как и любой другой альтернативный клиент) - вредный, вредный, врееедныый!

Вот как прореагировали уважаемые мной разработчики и блоггеры на этот анонс:

* Джон Груббер: [Твиттер отдал разработчикам команду «УМРИ!»](http://daringfireball.net/linked/2012/08/16/twitter-drop-dead).
* Мэтью Панзарино из TNW: [Будущее твиттера только в официальных клиентах, привыкайте](http://thenextweb.com/twitter/2012/08/17/twitter-4/).
* Марко Армент: [Интерпретируя некоторые изменения в Твиттер API](http://www.marco.org/2012/08/16/twitter-api-changes). #*

И напоследок два твита, которые я зафейворитил в официальном твиттер клиенте, как раз по этому поводу

![center](http://img-fotki.yandex.ru/get/6505/9320383.7/0_7ca9f_a7026d6b_L)

Дорогие разработчики, нас всех опять кинули. Расходимся.

## Немного разных ссылок

* [Большое обозрение поиска в Windows8](www.bing.com/community/site_blogs/b/search/archive/2012/08/15/bingonwindows8.aspx). Это очень круто, если бы не win8 - я бы пользовался с удовольствием. 
* [Подробный обзор новой системы для публикации - Medium](http://www.niemanlab.org/2012/08/13-ways-of-looking-at-medium-the-new-bloggingsharingdiscovery-platform-from-ev-and-obvious/). Я не оценил. Т.е. да, красиво, но какого-то нового смысла я пока в ней не увидел.
* [Исходники HTML5 MMO игры, на Node.js](https://github.com/tlhunter/Cobalt-Calibur-3). Исходники лежат давно, но обновляются часто и хорошо выглядят. Даже можно поднять свою копию.
* [Интересное, что вы не знали о WebKit-инспекторе](http://blog.joocode.com/browsers/12-things-about-the-webkit-inspector-i-didnt-know/). Я в последнее время пользуюсь только им и только в Safari. Так же загляните в каменты, там тоже много пользы.
* В закладки: [Как настроить дуалбут с линуксом на твоем маке](http://lifehacker.com/5934942/how-to-dual-boot-linux-on-your-mac-and-take-back-your-powerhouse-apple-hardware). Понятно, что всё через rEFIt, но есть детали™.
* [На Raspberry Pi научились запускать b2g](http://www.geek.com/articles/chips/raspberry-pi-gets-a-firefox-os-port-20120816/), теперь от FirefoxOS будет польза и в умном доме.

*p.s. простите, что мало и не часто - с понедельника всё вернется. Болею.*