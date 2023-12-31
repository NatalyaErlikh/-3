# *Подсказка по GIT*

# **Git — один из видов систем контроля версий (или СКВ). Такие системы записывают изменения в набор файлов, а позже позволяют вернуться к определенной версии.**

# **РЕПОЗИТОРИЙ** 
``` sh
Репозиторий — место, где хранятся и поддерживаются какие-либо данные.
```

## Изучаем начальные команды GIT

- ### Команда *git init*
``` sh
Эта команда создаёт в текущем каталоге новый подкаталог с именем.git, содержащий все необходимые файлы репозитория — структуру Git репозитория.
```
- ### Команда *git add*
```sh
Команда git add добавляет содержимое рабочего каталога в индекс для последующего коммита.
```
- ### Команда *git commit -m "massage"*
```sh
Включает новые изменения в последний созданный коммит
```
- ### Команда *git log*
```sh
Показывает историю коммитов.
```
- ### Команда *git log --oneline*
```sh
Выводит каждый коммит в одну строку
```
- ### Команда *git checkout*
```sh
Rоманда в системе контроля версий Git, позволяющая перемещаться между ветками, коммитами и состояниями файлов.
```
## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звездочкой (*) или знаком нижнего подчеркивания (_). Например *вот так* или _вот так_.

Чтобы выделить текст полужирным, необходимо обрамить его двойнми звездочками (**) или двойным знаком нижнего подчеркивания (__). Например **вот так** или __вот так__.
Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба эти способа. Например _текст может быть выделен курсивом и при этом быть **полужирным**_.

Если выделить все звездочками или нижним подчеркиванием, то система не запутается и также различит, что от неё хотят. Например *текст может быть обрамен только звездочками, но быть выделен курсивом и при этом быть **полужирным***

Или _текст может быть обрамен только нижним подчеркиванием, но быть выделен курсивом и при этом быть __полужирным___


## Работа с изображниями
Чтобы вставить изображение в текст, достаточно написать следующее:
![Привет, это картинка!](Planet9_3840x2160.jpg)
## Списки
Чтобы добавить ненумерованние списки, необходимо пункты выделить звездочкой (*) или знаком +. например, вот так:
* Элеиент 1
* Элеиент 2
* элемент 3
+ элемент 4

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать. Например, вот так:
1. Первый пункт
2. Ворой пункт
3. Третий пункт

# *Инструкция по работе с GITHUB*

Создать аккаунт на Github.com

Создать локальный репозиторий

"Подружить" ваш локальный и удаленный репозитории. Github при создании нового репозитория подскажет как это сделать.

Отправить (push) ваш локальный репозиторий в удаленный (на Github), в парвый раз необходимо будет авторизоваться на удаленном репозитории.

Провести изменения "с другого компьютера" 

Выкачать (pull) актуальное состояние из удаленного репозитория.

### *Описание нескольких основных команд*

#### Git clone - эта команда позволяет скопировать внешний репозиторий на наш ПК

#### Git pull - вначале забирает изменения из указанного удалённого репозитория, а затем пытается слить их с текущей веткой/

#### Git push -  используется для установления связи с удалённым репозиторием, вычисления локальных изменений отсутствующих в нём, и собственно их передачи в вышеупомянутый репозиторий/

## Как сделать pull request

Делаем форк (fork) интересующего нас репозитория

Делаем git clone для нашей версии этого репозитория

Создаем ветку с предлагаемыми изменениями

Производим все изменения только в этой ветке

Отправляем эти изменения на свой аккаунт (push)

В окне на Github появляется возможность отправить pull request.
