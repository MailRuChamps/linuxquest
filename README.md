# [Linux Quest](https://linux.mail.ru)

Игра для любителей и знатоков операционной системы Linux. Создано и поддерживается Mail.ru Group

Для кого эта игра:

* Если ты увлекаешься системным администрированием или ты инженер по доступности сервисов.
* Если ты начинающий специалист или считаешь себя гуру.
* Если ты хочешь попробовать что-то новое для себя и изучить новую область знаний.

## Правила игры

Игра индивидуальная. Даже если хочешь поделиться чем-то интересным, держи при себе, иначе ты поможешь своим соперникам, но общение на темы чемпионата только приветствуется!

Игра состоит из трех этапов, в каждом из которых нужно будет решить по одному заданию. Можно начинать с любого этапа и в любой момент. Если ты приступил к игре во время второго или третьего этапа, то выполнять задания можно в любой последовательности.

Чтобы принять участие в игре, необходимо зарегистрироваться, чтобы получить доступ к личному кабинету. Регистрация возможна, пока идет игра.

Архивы с образами можно скачать заранее, но они запаролены. Пароли и текущее задание будут появляться в твоём личном кабинете в момент начала каждого этапа. На каждом этапе перед игроками будут ставиться задачи «починить сервер», каждая из которых содержит разный набор проблем и «граблей». Задачи будут появляться в порядке возрастания сложности.

В ходе решения каждой задачи нужно собрать ключи. Они находятся в стандартных конфигурациях, директориях или именах файлов. Ключи — это имена математиков, разработчиков и других известных людей, оказавших влияние на мир IT. Таких людей не очень много, и чтобы квест нельзя было пройти простым перебором имен, наши специалисты по придумыванию сложных паролей написали эти имена не самым простым образом.

Ищи необычные вещи в стандартных местах! 

## Как начисляются баллы и как строится рейтинг игроков

После начала первого этапа (28 марта в 12:00 по московскому времени) в твоём личном кабинете появится пароль для открытия архива с образом. Также пароль будет отправлен на тот почтовый ящик, который ты укажешь при регистрации.

В этот же момент начнётся обратный отсчет секунд. Как только ты вобьёшь в поле ввода все найденные ключи, этап будет считаться пройденным, а к твоему рейтингу будет добавлено то количество секунд, которое на тот момент высвечивалось в поле обратного отсчета.

Обратный отсчет для первого этапа остановится при достижении 50 000 секунд (баллов) — это неснижаемый остаток. С этого момента и вплоть до окончания квеста (10 апреля в 12.00 по московскому времени) те участники, которые введут в поле все нужные ключи, получат только по 50 000 баллов.

Таким образом, если ты отвлёкся на что-то более важное (например, реально упавший сервер), или подключился к игре позже остальных, то у тебя всё равно есть шанс в следующем этапе поднапрячься и обогнать тех, кто успел набрать больше баллов.

Для второго уровня, который начнётся 2 апреля, неснижаемый остаток равен 100 000 секунд (баллов). И опять же, если ты подключился к игре уже после начала третьего уровня, то сможешь сперва решить активное задание текущего этапа (ведь время неумолимо съедает количество баллов, которые можно успеть заработать), а затем уже решить задания и ввести ключи по первому и второму этапу. И тогда к твоему результату, полученному за правильное и быстрое решение задачи третьего этапа, будут прибавлены 50 тыс. очков за первый уровень и 100 тыс. очков за второй.

На каждом этапе квеста необходимо найти от 3 до 5 ключей. Эти ключи можно вводить в любой последовательности, и если введенный ключ будет верным, ты сразу об этом узнаешь. На каждую игру дается всего 10 попыток ввода, поэтому будь внимателен и вводи точно ту последовательность символов, которая была обнаружена тобой.

Победителем квеста будет тот, кто наберет больше всего баллов. Следить за рейтингом участников можно в режиме реального времени на странице рейтинга.

Рекомендуем заранее скачать образ и настроить машину, которую ты будешь использовать для игры, чтобы после начала не терять на это драгоценные секунды. Для этого заходи в личный кабинет и следуй инструкциям.

## Расписание квеста, 2019

Регистрация — 25 марта в 12:00

Первый этап — 28 марта в 12:00

Второй этап — 02 апреля в 12:00

Третий этап — 05 апреля в 12:00

10 апреля мы объявим победителей!

## Подготовка окружения

Мы понимаем, что вариантов решения всех наших задач много, как и вариантов подготовки. Ниже мы описали один из возможных вариантов подготовки к Игре:

Для участия потребуется любой современный — или не очень — компьютер, настольный либо ноутбук. В дальнейшем будем называть его «ПК». Минимальные требования диктуются минимальными требованиями для установки и запуска одной виртуальной машины в VirtualBox. Операционная система (ОС): Linux (Ubuntu, любая версия), Unix(MacOS), Windows. 2 Гб ОЗУ, из которых 1 Гб выделяется для образа.

VirtualBox. На ПК с официального сайта устанавливается VirtualBox под имеющуюся ОС. https://www.virtualbox.org/wiki/Downloads
Импорт образа. Далее в VirtualBox нужно импортировать предоставленную конфигурацию.
Сеть (опционально). Чтобы с хост-машины в виртуальную машину можно было выполнять сетевые операции, виртуальной машине необходим виртуальный сетевой адаптер, коих есть несколько типов. Самый простой вариант: указать использование одного сетевого адаптера типа «Виртуальный адаптер хоста». В виртуальной машине интерфейс настраивается через DHCP, обращения производятся по выданному адресу.
После игры

Мы поздравим победителей и опишем один из способов решения наших заданий.
