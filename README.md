# Домашнее задание к занятию «2.3. Инструменты тестирования для работы с документацией»

## Задание 1
Продолжаем работать над тестированием [анкеты](http://zayavka-na-kartu-3.sdew.ru/). 

## Что нужно сделать
* Протестируйте анкету с использованием тестовых сценариев (тест-кейсов) и техник тест-дизайна, изученных ранее.

* Заведите найденные дефекты, [используя шаблон](https://docs.google.com/spreadsheets/d/15k7gRQQihGYLhiCQw9iWmWzR5dm9VdBD2OU9dS19-bk/edit?usp=sharing).
Создайте копию файла и заполните его. Мы ожидаем от вас не менее, чем 3 функциональных бага, но чем больше вы найдёте, тем лучше.

Результат задания: ссылка на Google-таблицу или Яндекс с заведёнными дефектами. 

Любые вопросы по решению задач задавайте в чате учебной группы.


## Задание 2

Представьте, что вы, как обычно, приходите утром на работу и планируете продолжить тестирование. Однако, открыв под кофе почту и мессенджеры, вы находите письмо от приятеля-разработчика, который работает вместе с вами. «Привет, — пишет он. — Я вчера ушёл в отпуск и прямо перед уходом с работы поймал несколько ошибок — Errors в логе. Все они записались в лог-файл, я скачал его и приложил к письму. Будь другом, заведи, пожалуйста, баг-репорты на эти эрроры, чтобы после возвращения я сразу приступил к работе над ними. Там несколько типов эрроров, не вникай, что с ними да как, просто сгруппируй по типам, почисти дубликаты и оформи со скриншотами и цитатами из лог-файла».

В работе тестировщика не всегда известно, какие шаги приводят к ошибкам в логах, но такие проблемы всё равно надо чинить и репортить в системы баг-трекинга, чтобы разработчики могли ими заняться.

## Что нужно сделать
1. Скачайте [файл](https://teslvova.s3.us-east-2.amazonaws.com/error_file.log).
2. Для лучшей читабельности скопируйте все данные из файла и вставьте их в один из редакторов для работы с кодом.
3. Проанализируйте логи и найдите в них Error-сообщения — скорее всего, там будет несколько одинаковых.
4. Перейдите по [ссылке](https://docs.google.com/document/d/1TjcBgMmVtcfKdqr2FaHSxG9ZGNXdLaf1Cdz_qUrUZlA/edit?usp=sharing) и создайте свою Jira.
5. Создайте баг-репорт(ы) на основе вышеуказанных Error-сообщений. Если у вас есть идеи о том, с чем могут быть связаны ошибки — вы можете написать предположения в репортах. Но так как вы не знаете, какие действия вызывают эти события, вы можете не описывать шаги, а поделиться информацией о том, кто вам дал эти логи.

Результат задания: созданные баг-репорты на ресурсе atlassian.com в виде скриншотов, вставленных в файл Google Docs.


## Задание 3 `*` (необязательная задача)

## Что нужно сделать
Нам надо проверить, не может ли злоумышленник обрушить наш сайт. Что будет, если он обойдёт ограничения по длине поискового запроса и всё же введёт ну очень большую строку? Надо проверить.

1. Зайдите на https://www.mos.ru/search.
2. Запустите любой поисковый запрос и посмотрите, как отреагирует приложение.
3. Исследуйте поле поиска в консоли DevTools.
4. Введите очень длинный текст в строку поиска и посмотрите, не изменится ли реакция приложения при поиске, в том числе и в DevTools.
5. Если вы нашли баг, опишите его в нашей стандартной форме баг-репорта, которую мы использовали ранее. В качестве ожидаемого результата опишите то, как, по-вашему, должна работать эта форма, а в фактическом — расскажите, что видите на самом деле. 

6*. Если у вас есть идеи или размышления на тему того, баг ли это, как его можно исправить и может ли это вызвать реальные проблемы — напишите, что вы думаете. 

В этом задании наша основная задача — тренировка работы с DevTools.

# Решение:
[Задание 1](https://github.com/artmaxst/Homework/blob/main/2.3(1).pdf)

[Задание 2](https://github.com/artmaxst/Homework/blob/main/2.3(2).pdf)

[Задание 3 * ](https://github.com/artmaxst/Homework/blob/main/2.3(_).pdf)
