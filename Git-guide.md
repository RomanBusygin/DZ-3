У меня появилась мысль, что в первых двух заданиях надо было таки писать инструкцию по Git'у, а не по Marcdown. =( Чтож, теперь всё заново.

Все приблуды Marcdown расписаны в прошлых двух заданиях, тут просто перечислю основные команды Git'а, опишу их действие и сделаю пару commit'ов.

**git init** - инициализация локального репозитория

**git status** - получение информации от git о текущем состоянии данного репозитория

**git add** - добавление файла в отслеживаемые git'ом

**git commit -m "message"** - создание commit'а и сообщения к нему

**git log** - вывод в терминал истории всех коммитов с их кодами

**git checkout "первые 4 символа кода commit'а"** - переход к какому-либо commit'у

**git branch** - вывод на экран всех веток в репозитории

**git branch "имя ветки"** - создание новой ветки

**git checkout "имя ветки"** - переход на какую-либо ветку

**git diff** - увидеть разницу между текущим состоянием файла и последним commit'ом

**git branch -d "имя ветки"** - удаление ветки (если в ней будет что-то, то будет запрос)

**git branch -D "имя ветки"** - удаление ветки без запроса

**git log --graph** - вывод истории commit'ов с графическим представлением распределения их по веткам.

**git merge "имя ветки"** - слияние в текущую ветку информации из "имя ветки"

## Github
**git clone "ссылка на внешний репозиторий"** - склонировать (скачать) внешний репозиторий на компьютер (локальный репозиторий)

**git pull** - скачать файлы с удаленного репозитория (связанного с нашим локальным) и слить их

**git push** - отправка наших файлов на удаленный связанный репозиторий